# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Tuấn Đăng    
- MSSV: 2A202603618
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: TLiet
- Link repo nhóm: https://github.com/dzungapr6th99/K5-L3A-Day02-NhomTLiet-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu một project web mới, tôi muốn cấu hình sẵn các chuẩn (ESLint, Prettier, Strict TS, Conventional Commits), để không phải setup tay từng bước mất thời gian | Dev | 40-60 phút cho mỗi lần khởi tạo project mới để config không bị lỗi conflict |
| 2 | Lặp lại | Khi huấn luyện mô hình PyTorch mới, tôi muốn tự động load và tiền xử lý dataset chuẩn (như SMS Spam), để tập trung ngay vào tinh chỉnh kiến trúc model | AI Trainee | Mất 20-30 phút mỗi lab chỉ để viết lại script load, clean text và vectorize dữ liệu |
| 3 | Tốn thời gian | Khi hoàn thành một task code hoặc module AI, tôi muốn có sẵn khung báo cáo kỹ thuật (annotated Markdown), để điền ngay kết quả mà không mất công nghĩ cách trình bày | Học viên, Sinh viên, Dev | Mất 45-60 phút để tổng hợp log, format code, chụp ảnh và viết giải thích logic cho báo cáo |
| 4 | Tốn thời gian | Khi build project Vue 3 / NestJS bị lỗi strict type, tôi muốn xác định nhanh vị trí và nguyên nhân Type mismatch, để fix bug nhanh hơn thay vì mò mẫm đọc log dài | Dev | Trung bình 15-20 phút mò mẫm stack trace mỗi khi Terminal báo đỏ do lỗi Type |
| 5 | Cần đọc, tổng hợp | Khi tích hợp một thư viện hoặc API mới (ví dụ vào CRM), tôi muốn nắm nhanh các endpoint và payload quan trọng, để code ngay thay vì đọc docs hàng chục trang | Lập trình viên | Đọc tài liệu và test thử Postman thường chiếm 1-2 tiếng trước khi viết dòng code thật đầu tiên |
| 6 | Cần đọc, tổng hợp | Khi cần hoàn thiện chứng chỉ tiếng Anh xét tốt nghiệp, tôi muốn tổng hợp các yêu cầu, lịch thi và tài liệu ôn ở một chỗ, để lên lộ trình học không bị sót | Sinh viên năm cuối | Mất nhiều buổi tối lướt group trường và web khoa để nhặt nhạnh thông tin |
| 7 | Pain từ người khác | Khi push code lên repo chung, tôi muốn đảm bảo commit message và style code đúng chuẩn, để không bị mentor hoặc reviewer yêu cầu sửa vặt | Dev, Mentor | Mentor nhắc nhở sửa format/commit message 2-3 lần/tuần (đếm Mentor nhắc nhở sửa format/commit message 2-3 lần/tuần) |
| 8 | Lặp lại | Khi tới giờ train team Valorant hoặc Đá bóng, tôi muốn biết nhanh lịch rảnh của cả đội, để chốt giờ chốt sân mà không phải lội tin nhắn hỏi từng người | Đội trưởng, Team member | Mất 15-20 phút chat qua lại trong group, thi thoảng trễ giờ do chốt muộn |
| 9 | Tốn thời gian | Khi chuẩn bị bài dạy kèm Toán/Anh cho học sinh lớp 12, tôi muốn tổng hợp các câu hỏi tương tự từ nhiều đề thi cũ, để tạo đề luyện tập sát sườn | Gia sư, Học sinh | Mất khoảng 1.5 tiếng mỗi tuần để cắt ghép, gõ lại công thức và viết đáp án chi tiết |
| 10 | Pain từ người khác | Khi bàn giao API cho team Front-end, tôi muốn API có sẵn tài liệu (Swagger/Postman collection) rõ ràng, để Front-end không nhắn tin hỏi lại cách truyền params | Back-end dev, Front-end dev | Front-end ping hỏi cách dùng API 3-4 lần cho mỗi module mới |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý và giữ lại ý 9 và 10. Đây là các pain point rất thực tế, có quy trình rõ ràng (cắt ghép đề, viết docs), tốn thời gian thật và đo đạc được. Có thể so sánh được với các giải pháp No AI / Rule

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tài liệu API cho Front-end (#10) | Quy trình lặp lại rất đều đặn (mỗi khi xong 1 API). Impact thấy rõ (giảm tin nhắn ping hỏi qua lại, tránh block việc của Front-end) | Có thể bài toán này dùng "Rule" (thư viện tự sinh Swagger) là đủ, chưa chắc đã cần đến AI |
| 2 | Viết báo cáo kỹ thuật (#3) | Tốn thời gian nhất ở đoạn "dịch" code thành văn xuôi (narrative). Đủ độ phức tạp và mơ hồ để áp dụng AI Workflow | Khó định lượng tiêu chí đánh giá "chất lượng văn phong" của bản nháp |
| 3 | Chốt lịch train team Valorant hoặc Đá bóng (#8) | Pain point thực tế, đời thường, nhiều người gặp. Quy trình dễ mô tả | Bị phụ thuộc vào sự hợp tác của các thành viên (có chịu rep tin nhắn hay không) |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bàn giao API cho team Front-end, tôi muốn có sẵn tài liệu rõ ràng, để Front-end không nhắn tin hỏi lại cách truyền params/payload |
| Actor | Backend Dev, Front-end Dev |
| Thời điểm / bối cảnh | Sau khi code và test xong API trên máy local, chuẩn bị push code lên nhánh chung |
| Quy trình hiện tại (3–7 bước) | 1. Code API (30') · 2. Test bằng Postman (5') · 3. Viết docs trên file Markdown/Notion mô tả request/response (20') · 4. Báo cho FE (1') · 5. FE ping hỏi lại vì docs thiếu case lỗi (5-10') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Tự gõ lại định dạng JSON request/response và viết mô tả các trường, mất khoảng 20 phút/API |
| Impact (nếu không giải thì sao) | Mất thời gian context-switching của cả hai bên; Front-end bị block tiến độ nếu Backend chưa kịp trả lời tin nhắn |
| Success metric (baseline → target) | Thời gian viết docs giảm từ 20 phút xuống dưới 5 phút. Số lần FE nhắn tin hỏi lại về API đó = 0 |
| Phương án không dùng AI | Dùng thư viện Rule-based để tự sinh tài liệu từ code |
| Giả thuyết về AI (nếu có) | AI đọc file Controller/DTO và tự sinh tài liệu Markdown kèm theo các ví dụ (business context) tự nhiên mà Swagger thường thiếu |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text 
HIỆN TẠI — 30 phút cho khâu docs + support

[1 Code xong API] → [2 Test Postman: 5'] → [3 Viết docs thủ công: 20'] ← BOTTLENECK
→ [4 Báo Front-end: 1'] → [5 Support FE hỏi lại do thiếu case: 5-10']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi hoàn thành một module code (hoặc lab AI), tôi muốn có sẵn khung báo cáo giải thích logic, để nộp tiến độ không mất công nghĩ cách trình bày |
| Actor | Dev, Học viên AI (Trainee), Mentor/Giảng viên (người đọc) |
| Thời điểm / bối cảnh | Cuối ngày làm việc hoặc sau khi train xong model, cần nộp file báo cáo Markdown lên hệ thống |
| Quy trình hiện tại (3–7 bước) | 1. Chạy code lấy log/metric (5') · 2. Chụp ảnh màn hình (5') · 3. Tạo file MD (2') · 4. Dán code/số liệu thô (5') · 5. Viết narrative giải thích logic (30') · 6. Format lại (bold, code block) (10') · 7. Nộp bài (3') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5: Viết văn xuôi (narrative) để giải thích thuật toán từ code thô, mất 30 phút vì hay bị "bí từ" |
| Impact (nếu không giải thì sao) | Chiếm 60 phút mỗi lần làm báo cáo. Gây tâm lý lười, trì hoãn nộp bài, hoặc viết quá sơ sài khiến mentor bắt làm lại |
| Success metric (baseline → target) | Tổng thời gian viết báo cáo giảm từ 60 phút xuống dưới 20 phút |
| Phương án không dùng AI | Dùng Template Markdown cố định có điền sẵn placeholder |
| Giả thuyết về AI (nếu có) | Đưa source code và log vào AI → AI sinh nháp cấu trúc Markdown và viết text giải thích luồng logic → Học viên review, bổ sung và chốt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 60 phút

[1 Lấy log/metric: 5'] → [2 Chụp output: 5'] → [3 Tạo file MD: 2']
→ [4 Dán code/số liệu thô: 5'] → [5 Viết narrative giải thích: 30'] ← BOTTLENECK
→ [6 Review & Format đẹp: 10'] → [7 Gửi: 3']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tới giờ train, tôi muốn biết nhanh lịch rảnh của cả đội, để chốt giờ chốt sân mà không phải lội tin nhắn hỏi từng người |
| Actor | Đội trưởng, các thành viên team |
| Thời điểm / bối cảnh | Trưa hoặc chiều trước buổi tối dự định train/đá bóng |
| Quy trình hiện tại (3–7 bước) | 1. Nhắn hỏi "Tối ai rảnh?" (1') · 2. Chờ mọi người rep lác đác (vài tiếng) · 3. Lội đọc chat tìm giờ giao nhau (10') · 4. Thông báo giờ chốt (2') · 5. Điều chỉnh chốt lại nếu cấn lịch (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3: Lội đọc tin nhắn rời rạc để đối chiếu giờ rảnh của 4-5 người, mất khoảng 10 phút |
| Impact (nếu không giải thì sao) | Dễ chốt lịch muộn, sát giờ, gây cấn lịch hoặc thiếu người, tạo cảm giác mệt mỏi cho người tổ chức |
| Success metric (baseline → target) | Thời gian tổng hợp lịch rảnh giảm từ 10 phút xuống 1 phút |
| Phương án không dùng AI | Tạo Poll trên Discord, Google Form định kỳ |
| Giả thuyết về AI (nếu có) | Dùng Bot Discord đọc các câu trả lời tự do (vd: "em rảnh sau 9h", "nay t bận") và tự động recommend giờ phù hợp nhất |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Phụ thuộc tin nhắn

[1 Nhắn hỏi rảnh không: 1'] → [2 Chờ mọi người rep: 1-2 tiếng] 
→ [3 Lội chat tổng hợp giờ chung: 10'] ← BOTTLENECK
→ [4 Thông báo chốt: 2'] → [5 Chốt lại do có thay đổi: 5']
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Đây là vấn đề cực kỳ nhức nhối và xảy ra hàng ngày trong bất kỳ team làm product/outsource nào. Giải quyết được bài toán này không chỉ tiết kiệm thời gian gõ phím của Backend mà còn loại bỏ hoàn toàn việc context-switching (đang code phải dừng lại trả lời tin nhắn) và giảm thời gian chết (blocker) của Front-end. Baseline đo lường cực kỳ dễ vì team code API mới liên tục
- Câu hỏi muốn nhóm phản biện: 
    1. Bài toán này nếu cài thư viện như Swagger (phương án Rule) là đã tự động sinh được cấu trúc rồi, vậy nhét AI vào có đang bị "giết gà dùng dao mổ trâu" (overkill) không?
    2. Nếu đoạn code Backend đặt tên biến (variable) quá tối nghĩa (ví dụ: status = 1), AI có thể tự suy diễn sai business logic (bịa ra 1 = Active, nhưng thực tế 1 = Pending). Làm sao kiểm soát được rủi ro AI dịch sai context này?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chỉ cần dùng thư viện tự sinh docs là đủ giải quyết phần định dạng, không cần đến AI | Đồng ý một phần | Xác định lại ranh giới: Sẽ dùng Rule (Swagger) để sinh cấu trúc Type/JSON. AI chỉ can thiệp để viết thêm phần "Ví dụ thực tế" và giải thích các case lỗi (400, 404) - những thứ mà Rule không tự nghĩ ra được |
| Metric "Số lần Front-end ping hỏi lại = 0" là quá tuyệt đối, phi thực tế và đôi khi FE hỏi vì lý do khác (không phải do docs thiếu) | Đồng ý hoàn toàn | Điều chỉnh lại metric cho thực tế hơn: "Giảm thời gian viết/hoàn thiện docs từ 20 phút xuống dưới 5 phút" và "Số lần FE ping hỏi lại về payload/params tối đa 1 lần/API" |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
