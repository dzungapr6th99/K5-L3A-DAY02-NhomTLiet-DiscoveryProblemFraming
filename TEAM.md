# Team — Nhóm T Liệt

Thông tin thành viên được đối chiếu với sáu báo cáo trong `report/individual/`. Bảng phân công xác định trách nhiệm thực hiện và kiểm chéo từ lần cập nhật này; không được hiểu là toàn bộ đầu việc đã do người được giao hoàn thành trước đó. Phần đóng góp đã ghi nhận tách riêng theo nội dung báo cáo và lịch sử Git.

## Thông tin nhóm

- Tên nhóm: Nhóm T Liệt — `NhomTLiet`.
- Repo nhóm: https://github.com/dzungapr6th99/K5-L3A-Day02-NhomTLiet-DiscoveryProblemFraming
- Candidate problem nhóm chọn: Người bán đồ ăn trong group Chợ Vinhomes phải thường xuyên theo dõi và đọc bài để phát hiện nhu cầu mua, kể cả bài không nêu tên món, rồi đối chiếu khả năng phục vụ.
- Quyết định trong báo cáo: **Not Yet** đối với triển khai trực tiếp trên Facebook; chọn thiết kế **Workflow có người bán duyệt** để nghiên cứu và thử ngoại tuyến.
- Phạm vi hiện tại: discovery, framing và thiết kế đánh giá; không ghi nhận đã triển khai hệ thống, phỏng vấn hoặc chạy pilot.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Tuấn Dũng | 2A202603608 | Điều phối repo; so sánh candidate; kiến trúc can thiệp và AI Canvas | [dzungapr6th99](https://github.com/dzungapr6th99) |
| 2 | Khuất Tiến Minh | 2A202603616 | Gom cluster/OST; research giải pháp và phản biện mức cần thiết của AI | [Minhktm02](https://github.com/Minhktm02) |
| 3 | Trần Tuấn Đăng | 2A202603618 | Quy trình trước/sau; tiêu chí đánh giá và bộ eval | [TunDangg](https://github.com/TunDangg) |
| 4 | Tạ Công Bình | 2A202603628 | Biên tập báo cáo; Problem Statement; tổng hợp rủi ro và quyết định | [BinhTa2004](https://github.com/BinhTa2004) |
| 5 | Nguyễn Minh Thông | 2A202603637 | Làm rõ domain Chợ Vinhomes; shortlist; assumption map và tình huống sử dụng | [ToyzZone](https://github.com/ToyzZone) |
| 6 | Đỗ Hoàng Phúc | 2A202603652 | Nguồn dữ liệu và khả thi; mô hình baseline, công sức và chi phí | [Codeforlife-MagicWed](https://github.com/Codeforlife-MagicWed) |


## Phân công theo checkpoint

### Nguyên tắc chia việc

- Chia thành **12 gói việc**, mỗi người **2 gói chính + 2 gói hỗ trợ/kiểm chéo**.
- Mỗi người có một gói mức 3 và một gói mức 2, cộng hai lượt kiểm chéo mức 1: tổng **7 đơn vị khối lượng quy ước**. Đây là công cụ cân bằng phân công, không phải giờ đã làm, điểm thành tích hoặc tỷ lệ đóng góp thực tế.
- Người chính chịu trách nhiệm nội dung và đối chiếu nguồn; người hỗ trợ kiểm tính nhất quán, giả định và cách đo. Nội dung có sẵn được rà soát, không cần viết lại chỉ để tăng số lần sửa.
- Phần scan, reflection và tự khai đóng góp vẫn do từng thành viên tự thực hiện. AI hỗ trợ soạn/phản biện được ghi nhận, không gán sản phẩm AI thành công việc độc lập của người khác.

| Checkpoint / gói việc | Người chính | Người hỗ trợ | Sản phẩm / trách nhiệm kiểm tra | Mức |
|---|---|---|---|---:|
| A1 — CP3: shortlist và bảng pitch | Nguyễn Minh Thông | Tạ Công Bình | Mục 2.1: đúng actor, candidate và bottleneck; phân biệt câu hỏi chuẩn bị với câu hỏi đã được hỏi. | 2 |
| A2 — CP3: cluster và cây OST | Khuất Tiến Minh | Nguyễn Tuấn Dũng | Mục 2.2–2.3: tách knowledge công ty/ngữ cảnh cá nhân; outcome thống nhất, nhánh là pain thay vì tính năng. | 3 |
| A3 — CP3: điểm và lý do hội tụ | Nguyễn Tuấn Dũng | Đỗ Hoàng Phúc | Mục 2.4: cộng điểm đúng; giải thích lựa chọn và hai candidate không chọn mà không điều chỉnh điểm để khớp kết luận. | 2 |
| A4 — CP4: giả định và tình huống | Nguyễn Minh Thông | Trần Tuấn Đăng | Mục 3.1–3.2 và ghi chú phân tích: tách nhu cầu rõ/mở, giả định và bằng chứng; không ghi kết quả khảo sát không có. | 3 |
| A5 — CP4: research giải pháp | Khuất Tiến Minh | Đỗ Hoàng Phúc | Mục 3.3 và ghi chú research: đối chiếu nguồn sản phẩm, chức năng, khoảng trống; phân biệt claim nhà cung cấp với kết quả thử. | 2 |
| A6 — CP4: nguồn dữ liệu và khả thi | Đỗ Hoàng Phúc | Nguyễn Minh Thông | Phân tích cách nhận input, quyền dùng, độ bao phủ/độ trễ; chỉ rõ công cụ phân loại không tự cấp quyền đọc group. | 3 |
| A7 — CP5: quy trình trước/sau | Trần Tuấn Đăng | Tạ Công Bình | Mục 4.1–4.2: sơ đồ, actor/input/output, Rule/AI/con người, boundary và phương án quay về. | 3 |
| A8 — CP5: baseline và before/after | Đỗ Hoàng Phúc | Khuất Tiến Minh | Mục 4.3: phép tính 5 phút × 12 lượt = 60 phút/ngày; target 30 phút, không gộp chờ với thao tác hoặc bỏ công sức nhập/duyệt. | 2 |
| A9 — CP5: Problem Statement v0 | Tạ Công Bình | Nguyễn Tuấn Dũng | Mục 5: đủ 6 trường, problem không chứa giải pháp, baseline ghi ước lượng, target và cách đo rõ. | 3 |
| A10 — CP6: mức can thiệp và AI Canvas | Nguyễn Tuấn Dũng | Trần Tuấn Đăng | Mục 6: so sánh bốn mức, ma trận, Canvas và PAIR; chọn Workflow ở mức thiết kế, giữ No AI/Rule làm đối chứng. | 3 |
| A11 — CP6: v1 và eval | Trần Tuấn Đăng | Nguyễn Minh Thông | Mục 7: v0→v1 có lý do; 5 tiêu chí, 10 ca minh họa, cách tính metric và trường hợp không xác định. | 2 |
| A12 — CP6: quyết định và tích hợp báo cáo | Tạ Công Bình | Khuất Tiến Minh | Mục 8–10: bốn rủi ro, Not Yet, pilot/ngưỡng dừng, định hướng tương lai; link assets và thống nhất thuật ngữ. | 2 |

### Đối chiếu khối lượng

| Thành viên | Gói chính | Gói hỗ trợ/kiểm chéo | Khối lượng quy ước |
|---|---|---|---:|
| Nguyễn Tuấn Dũng | A3, A10 | A2, A9 | 7 |
| Khuất Tiến Minh | A2, A5 | A8, A12 | 7 |
| Trần Tuấn Đăng | A7, A11 | A4, A10 | 7 |
| Tạ Công Bình | A9, A12 | A1, A7 | 7 |
| Nguyễn Minh Thông | A1, A4 | A6, A11 | 7 |
| Đỗ Hoàng Phúc | A6, A8 | A3, A5 | 7 |

Phân công cân bằng về đầu ra và khối lượng dự kiến; không suy ra sáu người đã đóng góp ngang nhau trong quá khứ. Các mục cá nhân dưới đây ghi phần có căn cứ riêng, không xác nhận hoàn thành mới chỉ từ việc được giao.

## Cá nhân

Các mục này tổng hợp từ báo cáo hiện có. “Góc tự tổng kết” là gợi ý dựa trên phần việc, không phải lời reflection đã được từng thành viên xác nhận.

### NguyenTuanDung-2A202603608

**Phần việc phụ trách:** A3, A10; kiểm chéo A2, A9.

**Đóng góp cụ thể đã ghi nhận:** Có báo cáo cá nhân phân tích thông tin dự án phân tán, onboarding và lý do quyết định; nội dung này là một nguồn hình thành candidate knowledge công ty trong CP3. Repo chung thuộc tài khoản `dzungapr6th99`; không từ đó suy ra đã hoàn thành mọi phần tích hợp hoặc kiến trúc được giao ở trên.

**Bằng chứng:** [Báo cáo cá nhân](report/individual/2A202603608_NguyenTuanDung.md); [báo cáo nhóm](report/team/group_report.md), mục 2.1–2.2. Trách nhiệm A3/A10 được xác định ở bảng phân công, chưa dùng làm bằng chứng hoàn thành.

**Điều mình học được từ phần nhóm — góc tự tổng kết:** Phân biệt việc thông tin không tồn tại với việc khó tìm nguồn còn hiệu lực; lý do chọn mức AI phải gắn với quy trình thay vì tên công cụ.

### KhuatTienMinh-2A202603616

**Phần việc phụ trách:** A2, A5; kiểm chéo A8, A12.

**Đóng góp cụ thể đã ghi nhận:** Theo mục 4 báo cáo cá nhân, đã đề xuất gộp HR Inquiry Handling với vấn đề của Dũng thành cluster knowledge công ty; ghi câu hỏi về sự cần thiết của AI và khả năng lấy dữ liệu Facebook. Đây là tự khai của thành viên trong repo, không phải biên bản được xác minh độc lập.

**Bằng chứng:** [Báo cáo cá nhân](report/individual/2A202603616_KhuatTienMinh.md), mục 4; [báo cáo nhóm](report/team/group_report.md), mục 2.2. Commit `9a7966d` cập nhật báo cáo cá nhân; commit chứng minh có bản cập nhật, không tự chứng minh toàn bộ hoạt động thảo luận.

**Điều mình học được từ phần nhóm — góc tự tổng kết:** Gom các vấn đề cùng pattern nhưng giữ ranh giới quyền truy cập và chủ sở hữu; nghiên cứu đối thủ phải so đúng nhu cầu, không chỉ thấy sản phẩm tương tự rồi loại đề tài.

### TranTuanDang-2A202603618

**Phần việc phụ trách:** A7, A11; kiểm chéo A4, A10.

**Đóng góp cụ thể đã ghi nhận:** Có báo cáo CP1–CP2 về công việc lập trình, lỗi, đọc tài liệu/API và chuẩn bị báo cáo kỹ thuật. Đây là nguồn candidate cá nhân và căn cứ phân công phần quy trình/eval; mục tham gia nhóm của báo cáo chưa ghi đủ để xác nhận đã thực hiện A7/A11.

**Bằng chứng:** [Báo cáo cá nhân](report/individual/2A202603618_TranTuanDang.md); commit `7ace10e` — `docs: update cp1,cp2`. Phần được giao rà soát: báo cáo nhóm mục 4 và 7.

**Điều mình học được từ phần nhóm — góc tự tổng kết:** Sơ đồ phải thể hiện rõ bước nghẽn và điểm con người kiểm tra; eval cần đầu ra mong đợi và ngưỡng đạt trước khi thử hệ thống.

### TaCongBinh-2A202603628

**Phần việc phụ trách:** A9, A12; kiểm chéo A1, A7.

**Đóng góp cụ thể đã ghi nhận:** Chuẩn bị candidate ngữ cảnh, bổ sung chat dài/quyết định cũ-mới/token và yêu cầu đưa Card #3 vào shortlist; biên tập báo cáo nhóm với AI hỗ trợ theo đề tài Vinhomes. Đã yêu cầu phân biệt số liệu ước lượng với kết quả đo, bỏ đường dẫn tài liệu ngoài repo khỏi báo cáo và tách checklist nộp bài khỏi định hướng tương lai. Không khai đã phỏng vấn hoặc chạy pilot.

**Bằng chứng:** [Báo cáo cá nhân](report/individual/2A202603628_TaCongBinh.md), mục 3–5; [báo cáo nhóm](report/team/group_report.md); [ghi chú research](report/assets/cp4-research-notes.md); [ghi chú phân tích](report/assets/cp4-problem-analysis-notes.md). Commit `54d403d` — `Upload Team report`, commit `a5eee5f` — `Upload individual report`.

**Điều mình học được từ phần nhóm — góc tự tổng kết:** Chọn đề tài, chọn thiết kế và quyết định triển khai là ba việc khác nhau; phải tính tổng công sức cập nhật/nhập/duyệt thay vì chỉ nhìn tốc độ đầu ra AI.

### NguyenMinhThong-2A202603637

**Phần việc phụ trách:** A1, A4; kiểm chéo A6, A11.

**Đóng góp cụ thể đã ghi nhận:** Báo cáo cá nhân có candidate người bán phải trực group và Card #1 mô tả quy trình, bottleneck, phương án không dùng AI, metric và câu hỏi. Candidate này được chọn làm trọng tâm báo cáo nhóm. Không từ việc sở hữu candidate suy ra đã có phỏng vấn hoặc kiểm thử thực tế.

**Bằng chứng:** [Báo cáo cá nhân](report/individual/2A202603637_NguyenMinhThong.md), CP1 ý #5 và CP2 Card #1; [báo cáo nhóm](report/team/group_report.md), mục 1–3. Commit `cea5ca6` — `CP1, CP2: bang scan problem va top 3 Problem Card (Thong)`.

**Điều mình học được từ phần nhóm — góc tự tổng kết:** Nhu cầu không nêu tên món vẫn có thể là cơ hội; phát hiện được ý định chưa đồng nghĩa có thể phục vụ hoặc lấy được dữ liệu đủ sớm.

### DoHoangPhuc-2A202603652

**Phần việc phụ trách:** A6, A8; kiểm chéo A3, A5.

**Đóng góp cụ thể đã ghi nhận:** Có báo cáo CP1–CP2 về tổng hợp chi tiêu, nguyên liệu và đơn đồ ăn nhóm, thể hiện các luồng tổng hợp/đối chiếu dữ liệu. Đây là căn cứ phân công baseline và công sức vận hành; mục tham gia nhóm còn trống nên không khẳng định đã thực hiện phân tích nguồn vào của đề tài Vinhomes.

**Bằng chứng:** [Báo cáo cá nhân](report/individual/2A202603652_DoHoangPhuc.md); commit `f485752` — cập nhật báo cáo cá nhân CP1/CP2. Phần được giao rà soát: báo cáo nhóm mục 3.3, 4.3 và rủi ro Feasibility/Viability.

**Điều mình học được từ phần nhóm — góc tự tổng kết:** Phân biệt số đo, ước lượng và mục tiêu; công cụ lọc chỉ có ích khi giảm được tổng công sức và có nguồn dữ liệu phù hợp.
