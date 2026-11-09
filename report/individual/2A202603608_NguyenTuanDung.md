# Báo cáo cá nhân — 2A202603608_NguyenTuanDung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Tuấn Dũng
- MSSV: 2A202603608
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhóm T Liệt
- Link repo nhóm: https://github.com/dzungapr6th99/K5-L3A-Day02-NhomTLiet-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Cần đọc, tổng hợp nhiều thông tin | tôi từng vào 1 team, khoảng 10 người. dự án đã chạy 1,5 năm. là 1 đề tài hoàn toàn mới ngoài thị trường, không ai có kinh nghiệm thực tế với mảng này mà chỉ có thể dùng kinh nghiệm cá nhân. khi người mới vào lại, có khá nhiều bottleneck. muốn phản biện 1 chức năng nào đó, hỏi ra mới biết là lãnh đạo yêu cầu, hoặc một nguyên do ngoài khác. đồng thời hệ thống quá lớn và cũng rất nhiều chức năng, việc hỏi tại sao theo phương án này, đi hỏi PIC của chức năng đó cũng gây mất thời gian
|Người mới tiếp cận công việc, Người phụ trách training | Mất thời gian, không cải thiện được bottleneck mặc dù bàn nhiều lần|
| 2 |Lặp lại, Pain từ người khác |  bị miss thông tin khi trong 1 ngày có quá nhiều đầu việc phát sinh, 1 đầu việc bị pending từ hôm qua nhưng tự dưng hôm nay leader cần gấp, xử ly sự cố, ... leader cũng ra khá nhiều đầu việc cho các thành viên, đồng thời cũng phải feedback cho ceo. và hay bị vấn đề hỏi thông tin việc A nay xong chưa trong khi công việc này mới bị pending hôm qua
| toàn team, leader| |
| 3 |Tốn thời gian | một bottleneck cần cải thiện,  nhưng sau nhiều lần bàn đi bàn lại, làm đi làm lại, chức năng vẫn sai, vẫn phải làm lại. chỉ 1 thay đổi nhỏ cũng ảnh hưởng đến toàn hệ thống chức năng. vấn đề ở đây là hệ thống sai hay con người sai? khi không ai phản biện được hệ thống, nhưng liệu có phải vì theo hệ thống mà người làm không control được code mình viết ra không?
| toàn bộ team| |
| 4 | Lặp lại, Tốn thời gian | Khi quay lại một đầu việc sau khi phải chuyển sang xử lý sự cố, tôi muốn nắm lại mình đã làm đến đâu và bước tiếp theo là gì, để tiếp tục công việc mà không phải đọc lại toàn bộ thông tin từ đầu. | Lập trình viên phải chuyển đổi giữa nhiều đầu việc | Gợi ý từ AI, chưa xác nhận bằng trải nghiệm cá nhân. Cần bổ sung một lần bị gián đoạn thật, thời gian khôi phục ngữ cảnh và số lần xảy ra trong tuần. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị kiểm tra một bản sửa chức năng, tôi muốn xác định đúng phiên bản yêu cầu đã được thống nhất, để không kiểm tra theo tài liệu cũ hoặc bỏ sót thay đổi trong các đoạn chat. | Lập trình viên, người kiểm thử, người chốt yêu cầu | Gợi ý từ AI, chưa xác nhận bằng trải nghiệm cá nhân. Cần bổ sung một lần có yêu cầu khác nhau giữa tài liệu và chat, thời gian đối chiếu và hậu quả thực tế. |
| 6 | Lặp lại, Tốn thời gian | Khi cần chạy dự án trên máy mới, tôi muốn biết đúng phiên bản công cụ, biến môi trường và thứ tự khởi động các dịch vụ, để bắt đầu làm việc mà không phải hỏi từng người hoặc thử sai nhiều lần. | Lập trình viên mới, người hỗ trợ cài đặt môi trường | Tình huống do AI gợi ý, chưa kiểm chứng. Có thể đo thời gian từ lúc lấy mã nguồn đến khi chạy thành công và số lần phải nhờ đồng nghiệp hỗ trợ. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một báo lỗi chỉ có ảnh chụp màn hình hoặc mô tả ngắn, tôi muốn có đủ bước tái hiện, dữ liệu đầu vào và môi trường xảy ra lỗi, để xác định được vấn đề trước khi bắt đầu sửa. | Lập trình viên, người kiểm thử, người báo lỗi | Tình huống do AI gợi ý, chưa kiểm chứng. Có thể ghi nhận số lượt hỏi bổ sung và thời gian từ khi nhận báo lỗi đến khi tái hiện thành công. |
| 8 | Pain từ người khác, Tốn thời gian | Khi tiếp nhận ca trực xử lý sự cố từ đồng nghiệp, tôi muốn biết các cảnh báo chưa giải quyết, thao tác đã thử và việc cần theo dõi tiếp, để không kiểm tra lại từ đầu hoặc bỏ sót sự cố đang diễn ra. | Người trực vận hành, lập trình viên hỗ trợ, người bàn giao ca | Tình huống do AI gợi ý, chưa kiểm chứng. Có thể đo thời gian đọc lại thông tin bàn giao, số thao tác kiểm tra bị lặp và số việc chưa có người tiếp nhận. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý thêm ý #4 (khôi phục ngữ cảnh sau gián đoạn) và #5 (xác định phiên bản yêu cầu đã chốt), dựa trên bối cảnh làm việc của ba ý đầu. Hai ý này đang là candidate để cân nhắc, chưa xác nhận giữ lại. Chỉ giữ khi đối chiếu được với trải nghiệm thật và bổ sung dấu hiệu cụ thể.
- Khi chọn, cần phân biệt #4 với #2: #4 tập trung vào thời gian cá nhân khôi phục ngữ cảnh; #2 tập trung vào việc các bên không nắm cùng trạng thái và ưu tiên. Phân biệt #5 với #3: #5 tập trung vào việc xác định yêu cầu hiện hành; #3 hiện còn nhiều nguyên nhân làm lại cần tách rõ.
- AI bổ sung ba đề tài #6 (cài đặt môi trường dự án), #7 (thu thập thông tin tái hiện lỗi) và #8 (bàn giao ca xử lý sự cố). Giữ trong danh sách ý tưởng vì có đối tượng và quy trình cụ thể, khác nhau về thời điểm phát sinh; chưa coi là trải nghiệm thật hoặc vấn đề đã được kiểm chứng. Chưa loại ý nào trong ba gợi ý mới.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

> Bản nháp phát triển từ ba vấn đề đầu ở CP1. Các thời gian và mục tiêu bên dưới là giả định để thiết kế cách đo, chưa phải số liệu thực tế.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Khó tra cứu lý do của quyết định thiết kế trong dự án | Gắn với trải nghiệm vào team khoảng 10 người, dự án đã chạy 1,5 năm; ảnh hưởng người mới và PIC. | Thông tin đã được ghi nhưng khó tìm, hay chưa được ghi lại? |
| 2 | Thành viên và leader không nắm cùng trạng thái, lý do pending và ưu tiên của task | Công việc phát sinh và sự cố làm việc cập nhật bị gián đoạn; có thể thử bảng task chung. | Nguyên nhân chính là thiếu cập nhật, thiếu đọc hay thay đổi ưu tiên? |
| 3 | Khó xác định phạm vi ảnh hưởng khi sửa chức năng | Thu hẹp tình trạng làm đi làm lại thành một bước có thể kiểm tra. | Bỏ sót phụ thuộc có phải nguyên nhân chính hay do yêu cầu và kiểm thử? |

### Problem Card #1 — Tra cứu căn cứ quyết định thiết kế

| Trường | Nội dung |
|---|---|
| Job Story | Khi tiếp nhận một chức năng có cách xử lý khó hiểu, tôi muốn biết căn cứ và ràng buộc của quyết định thiết kế, để đánh giá thay đổi mà không phải hỏi lại nhiều người hoặc tranh luận lại phương án cũ. |
| Actor | Lập trình viên mới vào dự án; PIC chức năng hỗ trợ giải thích. |
| Thời điểm / bối cảnh | Nhận task ở dự án đã chạy 1,5 năm, có nhiều chức năng và quyết định từ trước khi người mới tham gia. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc task/code; 2. Tìm tài liệu/chat; 3. Xác định PIC; 4. Hỏi và chờ giải thích; 5. Đối chiếu nguồn; 6. Ghi kết luận để tiếp tục. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 tìm căn cứ trong nhiều nguồn, giả định 25 phút/lần; thời gian chờ PIC ở bước 4 ghi riêng. |
| Impact (nếu không giải thì sao) | Người mới chậm bắt đầu task, PIC bị gián đoạn; nhóm có thể bàn lại phương án từng bị loại vì một ràng buộc chưa được biết. |
| Success metric (baseline → target) | Giả định bước tra cứu 25 → tối đa 10 phút/câu hỏi. Thử với 10 câu hỏi có nguồn xác nhận, mục tiêu ít nhất 8 câu tìm đúng căn cứ; đo riêng thời gian chờ PIC. |
| Phương án không dùng AI | Nhật ký quyết định theo chức năng, có lý do, ngày chốt, PIC và link nguồn; quy định người cập nhật. |
| Giả thuyết về AI (nếu có) | Hỗ trợ tìm và tổng hợp căn cứ từ nguồn được phép, luôn kèm nguồn; thiếu căn cứ thì báo thiếu và chuyển PIC xác nhận. |
| Cảm nhận nhanh | Chưa biết: thử mục lục và nhật ký quyết định trước khi quyết định cần AI. |

Quy trình nháp hiện tại — giả định tổng 70 phút, gồm 20 phút chờ:

```text
[Đọc task/code: 10'] → [Tìm tài liệu/chat: 25'] ← BOTTLENECK
→ [Tìm PIC: 5'] → [Hỏi/chờ phản hồi: 20']
→ [Đối chiếu nguồn: 5'] → [Ghi kết luận: 5']
```

### Problem Card #2 — Đồng bộ trạng thái và ưu tiên task

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhiều việc phát sinh và một task đang pending, tôi muốn biết trạng thái, lý do chờ và ưu tiên mới nhất, để chọn đúng việc cần làm và báo cáo thống nhất với leader. |
| Actor | Thành viên thực hiện task và leader tổng hợp tiến độ. |
| Thời điểm / bối cảnh | Đầu ngày hoặc sau khi chuyển sang xử lý sự cố, thông tin nằm trong chat nhưng bảng công việc chưa cập nhật đầy đủ. |
| Quy trình hiện tại (3–7 bước) | 1. Xem bảng task; 2. Đọc lại chat; 3. Hỏi từng người để xác nhận trạng thái; 4. Leader chốt ưu tiên; 5. Cập nhật bảng và báo cáo. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 hỏi lại và ghép trạng thái, giả định 15 phút/lượt tổng hợp. |
| Impact (nếu không giải thì sao) | Mất thời gian báo cáo lại, gián đoạn thành viên và có nguy cơ làm sai thứ tự ưu tiên. |
| Success metric (baseline → target) | Giả định thời gian tổng hợp 35 → tối đa 15 phút/lượt; đo trong 5 ngày. Mục tiêu bổ sung: ít nhất 90% task pending ghi rõ lý do, người cần phản hồi và thời điểm kiểm tra lại. |
| Phương án không dùng AI | Bảng task chung có trạng thái, lý do pending, ưu tiên, người phụ trách và lần cập nhật cuối; thống nhất cập nhật khi có thay đổi. |
| Giả thuyết về AI (nếu có) | Soạn bản tóm tắt từ cập nhật đã xác nhận, đánh dấu thông tin mâu thuẫn để người phụ trách kiểm tra; leader vẫn chốt ưu tiên. |
| Cảm nhận nhanh | Workflow: chuẩn hóa cập nhật và nhắc thông tin thiếu trước khi thêm AI. |

Quy trình nháp hiện tại — giả định tổng 35 phút/lượt:

```text
[Xem bảng task: 5'] → [Đọc chat: 5']
→ [Hỏi và ghép trạng thái: 15'] ← BOTTLENECK
→ [Leader chốt ưu tiên: 5'] → [Cập nhật và báo cáo: 5']
```

### Problem Card #3 — Xác định phạm vi ảnh hưởng khi sửa chức năng

| Trường | Nội dung |
|---|---|
| Job Story | Khi sửa một quy tắc dùng chung, tôi muốn xác định các chức năng phụ thuộc và trường hợp cần kiểm tra, để tránh sửa đúng một nơi nhưng gây lỗi ở nơi khác. |
| Actor | Lập trình viên, người review và người kiểm thử. |
| Thời điểm / bối cảnh | Trước khi thay đổi hàm hoặc quy tắc được nhiều chức năng sử dụng; cần kiểm chứng nguyên nhân làm lại bằng một thay đổi cụ thể. |
| Quy trình hiện tại (3–7 bước) | 1. Xác nhận yêu cầu; 2. Rà nơi sử dụng và phạm vi test; 3. Hỏi PIC module; 4. Sửa code; 5. Kiểm thử hồi quy; 6. Review và quay lại bước 2 nếu phát hiện bỏ sót. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 rà các phụ thuộc và ca kiểm thử, giả định 40 phút/lần; chưa có bằng chứng đây là nguyên nhân chính trong mọi lần làm lại. |
| Impact (nếu không giải thì sao) | Có nguy cơ lỗi hồi quy, tăng số vòng sửa và chậm bàn giao. |
| Success metric (baseline → target) | Giả định thời gian rà ảnh hưởng 40 → tối đa 20 phút/thay đổi. Đo trên 5 thay đổi tương đương, đồng thời yêu cầu số lỗi hồi quy do bỏ sót phụ thuộc không tăng. |
| Phương án không dùng AI | Find References, sơ đồ phụ thuộc, checklist tác động và bộ test hồi quy; người review xác nhận phạm vi. |
| Giả thuyết về AI (nếu có) | Gợi ý nơi bị ảnh hưởng và ca kiểm thử từ code/tài liệu được cung cấp, kèm đường dẫn để kiểm tra; không mặc định danh sách gợi ý là đầy đủ. |
| Cảm nhận nhanh | Workflow: chuẩn hóa bước phân tích tác động và kiểm thử trước; AI là giả thuyết hỗ trợ cần đánh giá. |

Quy trình nháp hiện tại — giả định tổng 135 phút/vòng đầu:

```text
[Xác nhận yêu cầu: 10'] → [Rà phụ thuộc/test: 40'] ← BOTTLENECK
→ [Hỏi PIC: 10'] → [Sửa code: 30']
→ [Test hồi quy: 30'] → [Review: 15']
Nếu bỏ sót ảnh hưởng: quay lại bước rà phụ thuộc, ghi riêng thời gian làm lại.
```

### Card muốn pitch nhất

- Card số: #1 — Tra cứu căn cứ quyết định thiết kế.
- Vì sao: Gần trải nghiệm đã mô tả ở CP1, có thể thu hẹp vào một nhóm chức năng và so sánh với nhật ký quyết định không dùng AI.
- Câu hỏi muốn nhóm phản biện: Thông tin khó tìm hay chưa từng được ghi? Ai cập nhật và xác nhận căn cứ? Mục lục cùng tìm kiếm thông thường đã đủ chưa?

### AI đã phản biện card thế nào

Đây là phản biện và chỉnh sửa trong bản nháp AI hỗ trợ; mức đồng ý cần người viết xác nhận theo tình huống thật.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 gộp học hệ thống, tìm PIC và tìm lý do thiết kế. | Chờ xác nhận | Thu hẹp vào căn cứ quyết định; tách tra cứu và chờ phản hồi. |
| Công cụ tìm kiếm không khôi phục được lý do chưa được ghi lại. | Chờ xác nhận | Thêm nhật ký quyết định và yêu cầu báo thiếu nguồn. |
| Card #2 chưa rõ trạng thái thiếu hay ưu tiên thay đổi. | Chờ xác nhận | Tách trạng thái, lý do chờ và ưu tiên; leader chốt ưu tiên. |
| Card #3 chưa chứng minh nguyên nhân làm đi làm lại. | Chờ xác nhận | Chỉ chọn bỏ sót phụ thuộc làm giả thuyết kiểm chứng; thêm điều kiện lỗi hồi quy không tăng. |
| Chưa có số đo thực tế cho ba card. | Chờ xác nhận | Gắn nhãn giả định cho thời gian, thêm cách đo và phương án không AI. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

> Hai đóng góp phản biện đã được tôi cung cấp: đề xuất phân loại ngữ nghĩa bằng Encoder + kNN và chỉ ra từ khóa như “gà” có thể gây hiểu sai ngữ cảnh. Những mục còn lại được hệ thống hóa từ CP1 và bài nhóm để tôi đối chiếu; không phải biên bản xác nhận mọi hoạt động đã diễn ra.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Đề tài cá nhân của tôi là khó tìm thông tin và lý do quyết định trong dự án; Card #1 là hướng muốn pitch. | Bài nhóm ghi nhận đề tài này cùng đề tài HR của Khuất Tiến Minh trong cluster Knowledge công ty; chưa có chi tiết xác nhận buổi pitch cá nhân. |
| Phản biện bài của bạn khác | Tôi phản biện cách lọc bằng tìm text: từ “gà” không phải lúc nào cũng chỉ món ăn. Tôi đề xuất thử phân loại ngữ nghĩa bằng Encoder kết hợp kNN thay vì mặc định dùng LLM. | Bổ sung góc nhìn cần đánh giá cả báo nhầm do đa nghĩa và bỏ sót nhu cầu không nêu món; đây là đề xuất của tôi, chưa phải kết quả nhóm đã thử hoặc chốt. |
| Nhận phản biện | Chưa có câu hỏi cụ thể từ thành viên khác được ghi nhận trong thông tin tôi cung cấp. | Bản nháp nêu các điểm cần tự kiểm: dữ liệu gán nhãn, ngưỡng phân loại, trường hợp không rõ và cách so sánh; không gán các câu hỏi này cho người khác. |
| Gom cluster / cây OST | Đề tài tra cứu kiến thức dự án của tôi được gộp vào cluster B cùng câu hỏi chính sách HR lặp lại. | Pattern chung là khó tìm thông tin có nguồn và còn hiệu lực, phụ thuộc người nắm kiến thức; bài nhóm tiếp tục đào sâu cluster người bán đồ ăn. |
| Chọn candidate problem | Theo bài nhóm, candidate được chọn là người bán đồ ăn phải trực group Chợ Vinhomes để phát hiện nhu cầu. | Tôi tập trung phản biện bước nhận diện nhu cầu trong đề tài này; không coi việc chọn candidate là quyết định triển khai. |
| Kiểm chứng / research | Tôi nêu giả thuyết kỹ thuật cần kiểm tra: phân loại theo ngữ cảnh có thể xử lý những ca từ khóa đa nghĩa. Chưa có kết quả training, đánh giá hoặc phỏng vấn cá nhân được cung cấp. | Đề xuất thêm mẫu có từ khóa nhưng không có nhu cầu mua đồ ăn, mẫu nhu cầu mở và mẫu thiếu ngữ cảnh vào bộ đánh giá. |
| Quy trình nhóm | Phản biện của tôi tập trung vào bước đọc/lọc nội dung, trước khi đối chiếu món, khu vực và thời gian phục vụ. | Bộ phân loại chỉ hỗ trợ nhận diện trên nội dung đã nhận; nguồn dữ liệu, tồn kho và quyết định phản hồi vẫn cần xử lý riêng. |
| Problem Statement | Từ phản biện, nhu cầu cần mô tả là phát hiện đúng bài có ý định tìm đồ ăn phù hợp, kể cả không nêu tên món. | Không định nghĩa thành “tìm bài có từ gà” hoặc “xây chatbot”; bài có từ khóa chưa đồng nghĩa cơ hội bán hàng. |
| Mức can thiệp AI | Tôi đề xuất thử Encoder tạo biểu diễn ngữ nghĩa và kNN phân loại theo mẫu đã gán nhãn, so sánh với Rule và phương án LLM trên cùng input. | Đây là lựa chọn cho bước phân loại trong Workflow có người duyệt; chưa khẳng định tốt hơn LLM, chưa có kết quả thực nghiệm. |
| Quyết định | Bài nhóm chốt Not Yet cho triển khai trực tiếp trên Facebook và nghiên cứu tiếp Workflow có người duyệt. | Đề xuất của tôi là một nhánh đánh giá ngoại tuyến; không thay thế điều kiện về nguồn dữ liệu, quyền sử dụng và hiệu quả thực tế. |

### Làm rõ đề xuất Encoder + kNN

Đây là thiết kế đề xuất để thử, chưa phải mô hình đã huấn luyện hoặc triển khai:

1. Chuẩn bị nội dung được phép sử dụng và giảm thông tin cá nhân; người hiểu nghiệp vụ gán nhãn: có nhu cầu mua đồ ăn, không có nhu cầu, hoặc chưa đủ ngữ cảnh.
2. Giữ riêng tập đánh giá, tránh để bài trùng hoặc gần trùng xuất hiện ở cả hai phía. Encoder chuyển nội dung đủ ngữ cảnh thành vector; kNN tham chiếu các mẫu đã gán nhãn trong tập phát triển.
3. Trước mắt thử Encoder có sẵn, chưa mặc định fine-tune. Với phương án này, bước xây kNN chủ yếu là lưu vector và nhãn tham chiếu; fine-tune Encoder là một thử nghiệm khác nếu có đủ dữ liệu và lý do.
4. Chọn k, cách đo tương đồng và ngưỡng từ chối trên tập phát triển. Ca ít tương đồng hoặc các láng giềng bất đồng được đưa sang người duyệt, không tự coi điểm tương đồng là xác suất đúng đã được kiểm định.
5. So sánh Rule mở rộng, Encoder + kNN và LLM trên cùng tập giữ lại: precision, recall, thời gian, chi phí và công sức sửa. Chưa có số liệu để kết luận phương án nào thắng.

Ví dụ do tôi/AI diễn đạt để minh họa lập luận, không phải bài thu thập từ group:

| Nội dung minh họa | Điều cần phân biệt |
|---|---|
| Có ai bán cơm gà giao trưa nay không? | Có nhu cầu mua món rõ ràng. |
| Mình chơi game này còn gà quá. | Có từ “gà” nhưng không nói về món ăn. |
| Nhà mình có gà cảnh cần tìm người nhận nuôi. | Nhắc tới con gà nhưng không phải nhu cầu mua đồ ăn chế biến. |
| Tối nay lười nấu, có ai giao đồ nóng không? | Có nhu cầu ăn uống mở dù không chứa tên món cụ thể. |
| Gà hôm qua ngon quá. | Nói về món ăn nhưng chưa thể suy ra đang muốn mua. |

Các ví dụ cho thấy cần kiểm tra cả nghĩa của từ và ý định của câu. Chúng không chứng minh Encoder + kNN hoặc LLM chắc chắn xử lý đúng; cả hai đều phải được đánh giá trên dữ liệu phù hợp.

---

## 5. Dùng AI

> Bảng này ghi việc AI hỗ trợ soạn bản nháp hiện tại. Không suy ra tôi đã dùng công cụ, phỏng vấn hoặc chạy thử mô hình ở các buổi trước.

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Mở rộng từ ba tình huống công việc đã mô tả sang các ý #4–#8. | Viết Job Story, tách actor và gợi ý cách đo. | Ý tưởng mới chưa phải trải nghiệm đã được xác nhận. | Giữ nhãn gợi ý AI và chưa kiểm chứng; ba ý đầu là cơ sở bối cảnh. |
| CP2 Problem Card | Cấu trúc ba ý đầu thành card và phản biện phạm vi, bottleneck, metric. | Tách bước tra cứu, chờ phản hồi, cập nhật trạng thái và rà ảnh hưởng. | Thời gian minh họa không có dữ liệu thực tế. | Ghi rõ giả định, thêm cách đo và phương án không AI để đối chiếu. |
| CP4 Research | Nhờ AI đọc bài nhóm và ghi chú research trong repo để hệ thống hóa điều đã có. | Phân biệt phân tích tình huống, research công cụ và kiểm chứng người dùng. | Không thể dùng ví dụ dựng làm dữ liệu đánh giá hoặc coi đọc tài liệu là phỏng vấn. | Ghi chưa có kết quả thử Encoder + kNN; không nhận research của cả nhóm thành nghiên cứu cá nhân đã tự thực hiện. |
| CP5 Quy trình | Nhờ AI diễn đạt vị trí bước phân loại trong Workflow. | Tách nhận dữ liệu, nhận diện nhu cầu, đối chiếu khả năng phục vụ và duyệt. | Dễ bỏ qua công sức nhập dữ liệu hoặc coi phân loại đúng là đã bán được hàng. | Đo tổng công sức và giữ người bán xác nhận trước phản hồi. |
| CP5–6 Problem Statement | Nhờ AI đối chiếu phản biện của tôi với framing trong bài nhóm. | Làm rõ từ khóa món ăn khác với ý định mua. | Dễ biến tên công nghệ thành tên vấn đề. | Giữ nhu cầu phát hiện cơ hội làm trọng tâm; công nghệ là phương án kiểm tra. |
| CP6 Mức can thiệp / quyết định | Hệ thống hóa đề xuất Encoder + kNN do tôi cung cấp và các điều kiện so sánh. | Làm rõ dữ liệu nhãn, tập giữ lại, ca không rõ và quyền duyệt. | Chưa có cơ sở nói Encoder + kNN chắc chắn rẻ hơn hoặc tốt hơn LLM. | Đề xuất đánh giá cùng input, giữ Not Yet và chọn mức đơn giản nhất đạt tiêu chí. |
| CP7 Reflection | AI hỗ trợ biên tập bản nháp dựa trên hai phản biện tôi đã cung cấp và tài liệu nhóm. | Liên kết lập luận với chuỗi problem → metric → boundary → quyết định. | AI không biết những gì tôi chưa kể, không thể xác nhận cảm xúc hoặc sự kiện cá nhân. | Các phần thiếu trải nghiệm cụ thể được ghi rõ để tôi bổ sung; cần tự rà lại trước khi nộp. |

---

## 6. Reflection (CP7)

> Bản nháp có AI hỗ trợ biên tập theo yêu cầu, dựa trên thông tin tôi đã cung cấp. Cần tự đối chiếu và diễn đạt lại bằng trải nghiệm thật trước khi nộp; đặc biệt không coi những mục còn thiếu sự kiện cá nhân là đã được xác nhận.

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua việc đối chiếu các đề tài trong bài nhóm, tôi thấy cùng là khó xử lý thông tin nhưng mỗi bài toán có nhu cầu khác nhau. Knowledge công ty cần thông tin có căn cứ và còn hiệu lực; người bán đồ ăn lại cần phát hiện nhu cầu kịp thời và biết mình có phục vụ được không. Tôi rút ra rằng phải làm rõ người dùng cần ra quyết định gì sau khi nhận thông tin, rồi mới chọn cách hỗ trợ. Đây là nhận xét từ nội dung bài nhóm; chi tiết về buổi nghe pitch cần tôi tự bổ sung nếu có.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Điểm tôi phản biện là không nên mặc định bài toán phân loại nội dung phải dùng LLM. Tôi đề xuất thử Encoder kết hợp kNN để phân loại theo ngữ nghĩa. Tuy nhiên, đề xuất này cũng chỉ có ý nghĩa sau khi xác định đúng nhãn cần phân loại, dữ liệu đầu vào và lỗi nào gây hại cho người bán. Bài nhóm giữ bước so sánh No AI, Rule và Workflow, đồng thời chưa cho triển khai trực tiếp. Tôi chưa có thông tin để khẳng định nhóm đã thử hoặc thống nhất chọn phương án Encoder + kNN.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi chưa cung cấp một tình huống cụ thể mình nhận phản biện rồi đổi ý, nên chưa thể ghi một câu chuyện như đã xảy ra. Quan điểm tôi đã nêu là cần thử phân loại ngữ nghĩa và kiểm tra hạn chế của lọc text. Điều tôi cần tự xem lại là không được từ việc chỉ ra lỗi của từ khóa mà kết luận ngay phương án mình đề xuất tốt hơn. Nếu Rule mở rộng đạt tiêu chí với ít công sức hơn, tôi cần chấp nhận phương án đó. Phần sự kiện thật về người phản biện, câu hỏi và thay đổi quan điểm cần tôi bổ sung.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Chưa có kết quả phỏng vấn, survey hoặc thử mô hình cá nhân được cung cấp để tôi mô tả cảm giác bất ngờ. Từ bài nhóm, điều cần lưu ý là phân loại được nội dung và nhận được nội dung đúng lúc là hai vấn đề khác nhau. Một phương án đạt chất lượng trên dữ liệu ngoại tuyến vẫn chưa chứng minh đã giảm công sức trực group. Tôi cần kiểm tra nguồn dữ liệu, độ trễ và công sức nhập, duyệt trước khi kết luận giải pháp có ích. Đây là điều rút ra từ tài liệu, không phải kết quả khảo sát do tôi thực hiện.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Trong lập luận của tôi, điểm khó là mô tả đúng ý định của người mua thay vì chỉ liệt kê các từ xuất hiện. Từ “gà” có thể nói về món ăn, con vật hoặc cách nói mình chơi kém; ngay cả khi nói về món ăn cũng chưa chắc đang muốn mua. Vì vậy, vấn đề cần giải quyết là giúp người bán phát hiện bài có nhu cầu phù hợp, kể cả nhu cầu mở, rồi đối chiếu khả năng phục vụ. Nếu viết thành “tìm bài chứa tên món” thì phạm vi quá hẹp; nếu viết thành “dùng LLM bán hàng” thì đã nhảy sang giải pháp.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ đề xuất xây bộ mẫu và cách chấm trước khi tranh luận mô hình. Bộ mẫu cần có bài hỏi mua rõ, nhu cầu không nêu món, từ đa nghĩa, bài chỉ nhận xét món và ca thiếu ngữ cảnh. Sau đó so sánh Rule mở rộng, Encoder + kNN và LLM trên cùng tập giữ lại. Tôi sẽ phản biện kỹ việc chỉ dùng vài ví dụ thuận lợi để kết luận, việc bỏ qua cảnh báo nhầm và việc không tính công sức người bán duyệt. Tôi cũng sẽ tách đề xuất kỹ thuật của mình khỏi quyết định triển khai, vì chọn được bộ phân loại vẫn chưa giải quyết nguồn dữ liệu và quyền sử dụng.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bản nháp 7 câu để tự kiểm tra hiểu bài, chưa thay cho phần tự giải thích không nhìn tài liệu:

Người bán đồ ăn trong group Chợ Vinhomes phải thường xuyên đọc bài để phát hiện kịp nhu cầu phù hợp, kể cả khi người mua không nêu tên món. Quy trình là nhận bài, đọc hiểu nhu cầu, đối chiếu món và khả năng giao, rồi người bán tự phản hồi và chốt đơn. Bài nhóm dùng baseline thiết kế 60 phút/ngày và mục tiêu tối đa 30 phút/ngày, đồng thời theo dõi số đơn, precision và recall; đây chưa phải kết quả đã đo. Boundary là chỉ xử lý dữ liệu được phép, không tự đoán tồn kho hoặc tự nhắn tin, bình luận và chốt đơn. Hướng thiết kế là Workflow có người duyệt, còn Encoder + kNN là phương án tôi đề xuất để thử cho bước phân loại bên cạnh Rule và LLM. Lý do cần xét ngữ cảnh là từ như “gà” có thể không chỉ món ăn, và bài không chứa tên món vẫn có thể có nhu cầu ăn uống. Quyết định hiện tại là Not Yet cho triển khai trực tiếp, cần kiểm chứng nguồn dữ liệu, nhu cầu và chất lượng trước khi chọn phương án đủ dùng.

---

## 7. Tài liệu tham khảo

- [Báo cáo nhóm](../team/group_report.md): candidate, cluster, quy trình, metric, boundary và quyết định Not Yet.
- [Ghi chú research CP4 của nhóm](../assets/cp4-research-notes.md): tổng hợp nguồn và giới hạn của research công cụ; không nhận là nguồn tôi đã tự kiểm tra.
- [Ghi chú phân tích tình huống CP4](../assets/cp4-problem-analysis-notes.md): ví dụ minh họa, baseline giả định và cách đo tổng công sức.
- [Worksheet](../../docs/01-worksheet.md) và [Rules](../../RULES.md): cấu trúc bài và quy định khai báo sử dụng AI.
- Nguồn đóng góp cá nhân: phản biện về từ khóa đa nghĩa “gà” và đề xuất Encoder + kNN do Nguyễn Tuấn Dũng cung cấp khi bổ sung báo cáo; chưa có biên bản thử nghiệm mô hình kèm theo.
