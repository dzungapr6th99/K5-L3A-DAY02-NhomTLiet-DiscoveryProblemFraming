# CP4 — Ghi chú phân tích tình huống người bán đồ ăn

- Ngày tổng hợp: 09/11/2026.
- Cơ sở: mô tả trong Problem Card và phân tích của [báo cáo nhóm](../team/group_report.md).
- Loại tài liệu: ghi chú phân tích định tính, có AI hỗ trợ; không phải biên bản quan sát, phỏng vấn hoặc kết quả survey.

## 1. Bối cảnh và người dùng

Người bán đồ ăn nhà làm nhận cơ hội từ bài cư dân hỏi mua trong group Chợ Vinhomes. Người bán vừa chuẩn bị/giao món vừa theo dõi group. Bài hỏi mua có thể gọi đúng tên món hoặc chỉ nêu đang đói, muốn đồ nóng, cần cơm cho gia đình.

Phạm vi phân tích là phát hiện cơ hội và đánh giá khả năng phục vụ. Việc phản hồi, trao đổi giá, xác nhận tồn kho và chốt đơn thuộc người bán. Không mặc định mọi người dùng group gặp cùng mức độ pain.

## 2. Chuỗi hành vi và giả thuyết pain

| Bước | Hành vi được mô tả | Giả thuyết khó khăn |
|---:|---|---|
| 1 | Mở group và lướt bài mới | Lặp nhiều lượt, chia sự chú ý khi đang nấu/giao. |
| 2 | Đọc bài và đối chiếu món/khu vực/giờ | Bài không nêu món khó phát hiện bằng Rule tên món hẹp; thiếu chi tiết cần hỏi thêm. |
| 3 | Tự bình luận hoặc nhắn tin | Phải kiểm món còn bán và khả năng giao, không thể tự hứa theo nội dung mô hình tạo. |
| 4 | Chờ khách so sánh và trả lời | Phát hiện sớm không bảo đảm có đơn; giá và điều kiện giao vẫn ảnh hưởng. |
| 5 | Chốt qua Messenger và hẹn giao | Cần người bán xác nhận thông tin giao dịch cuối cùng. |

Bottleneck của mô hình nằm ở bước 1–2. Đây là giả thuyết phân tích, chưa phải kết quả đo thao tác người bán thật.

## 3. Các câu minh họa và cách diễn giải

| Câu minh họa, không phải bài thu thập từ group | Tín hiệu nhu cầu | Thông tin không được tự thêm |
|---|---|---|
| Đói quá, giờ này có ai ship gì ko | Nhu cầu ăn uống mở | Không tự gán món hoặc địa chỉ giao. |
| Có ai bán gì nóng nóng ko ạ | Muốn đồ ăn nóng | Không tự khẳng định muốn bún bò hoặc người bán còn hàng. |
| Tìm bún bò ship tòa S2, 2 tô ạ | Rõ món, số lượng, điểm giao được nêu | Không mặc định S2 thuộc phạm vi giao và có thể phục vụ ngay. |
| Tối nay lười nấu, nhà 3 người cần cơm tối | Nhu cầu cơm và thời điểm tối | Không mặc định muốn cơm tấm hoặc chấp nhận suất ăn cụ thể. |

Rule chỉ khớp chính xác “bún bò” hoặc “cơm tấm” nhận được 1/4 câu trên. Đây là minh họa giới hạn của một Rule hẹp, không phải recall thực tế hay kết quả so sánh AI.

## 4. Mô hình baseline để thiết kế

| Đại lượng | Giá trị dùng trong báo cáo | Trạng thái |
|---|---|---|
| Mở/lướt | 2 phút/lượt | Ước lượng thiết kế do AI hỗ trợ đề xuất, không phải số đo. |
| Đọc/lọc/đối chiếu | 3 phút/lượt | Ước lượng thiết kế, không phải lời người bán xác nhận. |
| Tần suất | 12 lượt/ngày | Giả định làm việc, không phải thống kê hành vi. |
| Baseline B | (2 + 3) × 12 = 60 phút/ngày | Kết quả tính từ các giả định trên. |
| Target C | Không quá 30 phút/ngày | Mục tiêu giảm 50%, chưa đạt thực nghiệm. |

C gồm cả nhập dữ liệu, duyệt, sửa và phần theo dõi thủ công còn lại; tính cả công sức hỗ trợ. Thời gian chờ khách không cộng như công sức thao tác. Số đơn từ group/ngày là điều kiện chất lượng khi so sánh, chưa có baseline số đơn được thu thập.

## 5. Cách giải thích và khả năng phản bác

- Hướng thiết kế: nhận diện nhu cầu rõ/mở trước, sau đó người bán đối chiếu khả năng phục vụ; nhu cầu mở không đồng nghĩa đơn chắc chắn phù hợp.
- Nếu thông báo/hashtag/Rule mở rộng đã đủ, không cần tăng mức can thiệp AI.
- Nếu ít bài phù hợp, giá/tồn kho/giao hàng mới là nguyên nhân chính, lợi ích lọc có thể thấp.
- Nếu nhập và duyệt gợi ý tốn hơn tự đọc, giải pháp chuyển gánh nặng thay vì tiết kiệm.
- Nếu luồng dữ liệu thiếu/chậm, kết quả phân loại ngoại tuyến không chứng minh khả năng phát hiện nhu cầu kịp thời.

Kết luận phân tích: Workflow có người duyệt là hướng thiết kế; Not Yet cho triển khai trực tiếp. Ghi chú này không bổ sung dữ liệu thực nghiệm mới so với báo cáo nhóm.
