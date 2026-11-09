# CP4 — Ghi chú research giải pháp và ràng buộc

- Ngày tổng hợp: 09/11/2026.
- Đề tài: hỗ trợ người bán đồ ăn phát hiện nhu cầu trong group Chợ Vinhomes, kể cả bài không nêu tên món.
- Phương pháp: đọc nguồn công khai với AI hỗ trợ, tổng hợp từ research đã thực hiện trong phiên làm báo cáo. Không đăng ký hoặc kiểm thử sản phẩm.
- Báo cáo liên quan: [mục 3.3 — Research](../team/group_report.md#33-research-giải-pháp-đã-có).

## 1. Câu hỏi nghiên cứu

1. Có cách đơn giản nào giảm công sức đọc group trước khi cần AI?
2. Sản phẩm hiện có chỉ khớp từ khóa hay đã nhận diện ý định mua?
3. Có thể mặc định nhận bài mới từ tích hợp Facebook Groups cũ không?
4. Công cụ có sẵn giải quyết được bước nào và còn giới hạn gì?

## 2. Ghi chú theo nguồn

| Nguồn đã đọc | Nội dung nguồn hỗ trợ | Diễn giải cho đề tài | Điều không được suy ra |
|---|---|---|---|
| [Groups Watcher — Chrome listing](https://chromewebstore.google.com/detail/groups-watcher/haclmflikcbameonpfkeomjpfaokombf), [FAQ](https://www.groupswatcher.com/extension-faq), [website](https://www.groupswatcher.com/) | Listing mô tả tiện ích theo dõi group; FAQ thông báo extension deprecated và cảnh báo rủi ro tài khoản; website quảng bá dịch vụ có AI intent score. | Đã có sản phẩm quảng bá lọc ý định, nên không định nghĩa khoảng trống là “chưa ai dùng AI”. Phải phân biệt extension với dịch vụ hiện tại. | Không coi claim của nhà cung cấp là bằng chứng chất lượng tiếng Việt, quyền dùng dữ liệu hoặc bảo đảm an toàn tuyệt đối. |
| [GrabFood Merchant](https://www.grab.com/vn/merchant/food/) | Mô tả tạo cửa hàng, menu và phí dịch vụ theo hợp đồng. | Đây là kênh mua từ gian hàng, khác việc người mua đăng nhu cầu tự do trong group. | Không dùng một tỷ lệ phí chung 20–30% cho GrabFood, ShopeeFood và beFood khi chưa xác minh từng nền tảng. |
| [Vinhomes Resident — App Store](https://apps.apple.com/vn/app/vinhomes-resident/id6450522818) | Mô tả tiện ích, hóa đơn và dịch vụ cư dân. | Phạm vi được giới thiệu chưa trực tiếp chứng minh đã giải quyết bài toán tìm người bán từ bài hỏi mua. | Không kết luận app hoàn toàn không có chợ/đặt món hoặc là nguyên nhân cư dân lập group chỉ từ mô tả công khai. |
| [Google Forms — quản lý phản hồi](https://support.google.com/docs/answer/139706?hl=en) | Có thể xem phản hồi trong Sheets và bật email báo phản hồi mới. | Phương án nhận nhu cầu có cấu trúc, giảm yêu cầu hiểu văn bản tự do nếu người mua chấp nhận dùng form. | Form không tự đọc group; thông báo phản hồi chưa phải phân phối đúng người bán theo món. |
| [n8n — Text Classifier](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.text-classifier.md) | Phân loại input theo category định nghĩa; có lựa chọn đưa ca không khớp rõ sang nhánh Other. | Có thể dùng cho bước nhận diện nhu cầu trong Workflow và chuyển ca chưa rõ sang người duyệt. | Node phân loại không cấp quyền đọc Facebook hoặc chứng minh độ chính xác trên dữ liệu của đề tài. |
| [Zapier — Facebook Groups app removal](https://help.zapier.com/hc/en-us/articles/23970212345357-App-update-Facebook-Groups-app-removal) | Nhà cung cấp thông báo tích hợp Facebook Groups dừng từ 22/04/2024. | Không xây thiết kế dựa trên giả định trigger Facebook Groups cũ còn hoạt động. | Việc một tích hợp dừng không chứng minh mọi nguồn dữ liệu khác đều bất khả thi hoặc đều được phép. |
| [Buffer — Facebook Group Posts](https://buffer.com/resources/scheduling-facebook-group-posts-with-buffer/) | Mô tả notification publishing, người dùng hoàn tất việc đăng bài sau thông báo. | Tham khảo pattern hỗ trợ trước, con người thực hiện hành động cuối cùng. | Đây không phải sản phẩm phát hiện nhu cầu mua hoặc bằng chứng có quyền đọc luồng bài group. |

## 3. Phương án chưa xác minh trực tiếp

Thông báo tất cả bài, quy ước hashtag và Keyword Alerts là các phương án được nêu trong Problem Card. Chưa kiểm tra giao diện hoặc quyền tính năng ở group thật; không gộp thông báo chung với cảnh báo cá nhân theo từ khóa, không mặc định người bán thường có quyền admin/mod.

Trang thông báo gốc của Meta trả lỗi giới hạn truy cập trong lần kiểm tra. Thông tin về dịch vụ Zapier/Buffer được ghi theo thông báo trực tiếp của các nhà cung cấp đó, không ghi đã xác minh nội dung trang Meta.

## 4. Kết luận research

- Tách hai bài toán: nhận dữ liệu được phép và nhận diện nhu cầu trong nội dung đã nhận.
- Không mặc định phải tự xây; công cụ sẵn có là phương án so sánh về chất lượng, công sức và chi phí.
- So sánh Workflow với No AI và Rule mở rộng, không chỉ so với hai từ khóa tên món.
- Người bán vẫn kiểm thông tin, tồn kho, phạm vi giao và tự phản hồi; research công cụ không thay cho bằng chứng người dùng hoặc kết quả pilot.
