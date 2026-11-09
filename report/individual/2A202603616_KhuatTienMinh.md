# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Khuất Tiến Minh
- MSSV: 2A202603616
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: NhomTLiet
- Link repo nhóm: https://github.com/dzungapr6th99/K5-L3A-Day02-NhomTLiet-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi chuẩn bị đăng ký nghỉ phép, tôi muốn biết chính xác số ngày phép còn lại để chủ động lên kế hoạch | Nhân viên | Nhân viên cần phải truy cập hệ thống hoặc hỏi HR để xác  nhận trước khi đăng ký |
| 2 | Lặp  | Khi gửi yêu cầu nghỉ phép, tôi muốn theo dõi trạng thái phê duyệt để biết yêu cầu được xử lý hay chưa? | Nhân viên | Phải kiểm tra lại hệ thống hoặc liên hệ quản lý/HR để hỏi trạng thái |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi không hiểu quy định nghỉ phép hoặc chế độ công ty, tôi muốn tìm được thông tin chính xác ở một nơi để thực hiện đúng quy trình | Nhân  | Phải tìm kiếm và đọc nhiều tài liệu hoặc hỏi HR để hiểu quy định |
| 4 | Pain từ người khác | Khi phát hiện dữ liệu chấm công không chính xác, tôi muốn được hướng dẫn điều chỉnh để đảm bảo ngày công được ghi nhận đúng | Nhân viên, HR | Sai lệch dữ liệu có thể khiến nhân viên phải liên hệ HR để xác minh |
| 5 | Tốn thời gian | Khi chuẩn bị chốt công cuối tháng, tôi muốn nhanh chóng phát hiện các bản ghi thiếu hoặc bất thường để xử lý trước kỳ tính lương | HR | HR phải kiểm tra và đối chiếu dữ liệu chấm công của nhiều nhân viên. |
| 6 | Lặp lại | Khi nhận nhiều câu hỏi giống nhau từ nhân viên, tôi muốn có nguồn thông tin thống nhất để giảm thời gian trả lời thủ công | HR | Các câu hỏi về nghỉ phép, chấm công và chính sách có thể được gửi lặp lại |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi cần sắp xếp nhân sự trong nhóm, tôi muốn xem tổng hợp lịch nghỉ của các thành viên để chủ động phân bổ công việc | Manager, nhân viên | Quản lý phải kiểm tra lịch nghỉ của nhiều thành viên trước khi phân công. |
| 8 | Cần đọc, tổng hợp nhiều thông tin | Khi cần đánh giá tình hình nhân sự, tôi muốn xem báo cáo tổng hợp để đưa ra quyết định nhanh chóng và chính xác | Manager, HR | Phải tổng hợp dữ liệu từ nhiều nguồn trước khi lập báo cáo |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | HR mất thời gian trả lời câu hỏi lặp lại | Tần suất có thể cao, ảnh hưởng trực tiếp đến hiệu suất HR và trải nghiệm nhân viên | Số câu hỏi lặp lại mỗi ngày và thời gian HR xử lý |
| 2 | HR mất thời gian kiểm tra dữ liệu chấm công | Có quy trình nghiệp vụ rõ ràng, nhiều dữ liệu cần đối chiếu, sai sót có thể ảnh hưởng đến tính lương | Tỷ lệ dữ liệu bất thường và thời gian kiểm tra thực tế |
| 3 | Nhân viên khó tra cứu ngày phép còn lại | Nhu cầu phổ biến, ảnh hưởng đến nhiều nhân viên, dễ kiểm chứng và đo lường | Hệ thống hiện tại có cung cấp thông tin chính xác, dễ truy cập hay chưa |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhân viên liên tục hỏi các câu hỏi nghiệp vụ giống nhau, tôi muốn có nguồn thông tin thống nhất để giảm thời gian trả lời thủ công, để tôi có thể tập trung vào các công việc nhân sự quan trọng hơn. |
| Actor | Nhân viên HR; nhân viên công ty là người gửi câu hỏi. |
| Thời điểm / bối cảnh | Trong giờ làm việc, khi nhân viên cần tìm hiểu quy định nghỉ phép, chấm công, lương hoặc chính sách công ty. |
| Quy trình hiện tại (3–7 bước) | 1. Nhân viên phát sinh thắc mắc. 2. Nhắn tin hoặc liên hệ HR. 3. HR tiếp nhận câu hỏi. 4. HR tìm kiếm tài liệu hoặc kiểm tra thông tin. 5. HR trả lời nhân viên. 6. Nhân viên hỏi thêm nếu chưa hiểu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4–5: HR phải tìm kiếm thông tin và soạn câu trả lời. Thời gian: chưa đo, cần khảo sát. |
| Impact (nếu không giải thì sao) | HR bị gián đoạn công việc, mất thời gian xử lý câu hỏi lặp lại, nhân viên phải chờ phản hồi. |
| Success metric (baseline → target) | Baseline: cần đo số câu hỏi và thời gian xử lý. Target đề xuất: giảm 30–50% thời gian xử lý câu hỏi lặp lại. |
| Phương án không dùng AI | Xây dựng FAQ, tài liệu hướng dẫn và phân loại câu hỏi theo chủ đề. |
| Giả thuyết về AI (nếu có) | AI có thể hiểu câu hỏi bằng ngôn ngữ tự nhiên và tìm câu trả lời từ tài liệu, quy định nội bộ. |
| Cảm nhận nhanh | 	Chưa biết → có thể phù hợp với AI Agent kết hợp RAG, nhưng cần kiểm soát nguồn thông tin và quyền truy cập. |

Quy trình nháp hiện tại:

```
Nhân viên có thắc mắc
        ↓
Liên hệ HR
        ↓
HR tiếp nhận câu hỏi
        ↓
Tìm kiếm tài liệu / kiểm tra quy định
        ↓
Soạn câu trả lời
        ↓
Gửi phản hồi cho nhân viên
        ↓
Nhân viên hỏi thêm (nếu chưa rõ)

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị chốt công cuối tháng, tôi muốn nhanh chóng phát hiện các bản ghi chấm công thiếu hoặc bất thường để xử lý trước kỳ tính lương, để đảm bảo dữ liệu ngày công chính xác. |
| Actor | Nhân viên HR phụ trách chấm công. |
| Thời điểm / bối cảnh | Cuối ngày hoặc cuối tháng, đặc biệt trước thời điểm tổng hợp công và tính lương. |
| Quy trình hiện tại (3–7 bước) | 1. HR truy xuất dữ liệu chấm công. 2. Tổng hợp dữ liệu theo nhân viên. 3. Kiểm tra ngày thiếu giờ vào/ra. 4. Kiểm tra dữ liệu bất thường. 5. Liên hệ nhân viên hoặc quản lý xác minh. 6. Điều chỉnh dữ liệu nếu cần. 7. Chốt dữ liệu chấm công. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: HR phải rà soát nhiều bản ghi và xác minh từng trường hợp. Thời gian: chưa đo, cần khảo sát. |
| Impact (nếu không giải thì sao) | Tốn thời gian đối soát, có nguy cơ bỏ sót sai sót, ảnh hưởng đến quá trình tính lương |
| Success metric (baseline → target) | Baseline: thời gian kiểm tra và số lỗi phát hiện hiện tại chưa đo. Target đề xuất: giảm 30% thời gian rà soát thủ công, không làm giảm tỷ lệ phát hiện lỗi. |
| Phương án không dùng AI | Sử dụng các quy tắc kiểm tra tự động: thiếu giờ vào/ra, trùng bản ghi, giờ công vượt giới hạn. |
| Giả thuyết về AI (nếu có) | AI có thể phân tích dữ liệu lịch sử để nhận diện những mẫu chấm công bất thường khó phát hiện bằng quy tắc cố định. |
| Cảm nhận nhanh | Rule / Workflow trước; chỉ cân nhắc AI khi xuất hiện những mẫu bất thường phức tạp. |

Quy trình nháp hiện tại:

```
HR truy xuất dữ liệu chấm công
        ↓
Tổng hợp dữ liệu theo nhân viên
        ↓
Kiểm tra bản ghi thiếu hoặc bất thường
        ↓
Phát hiện trường hợp cần xác minh
        ↓
Liên hệ nhân viên / quản lý
        ↓
Điều chỉnh dữ liệu
        ↓
Chốt công cuối tháng

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | 	Khi chuẩn bị đăng ký nghỉ phép, tôi muốn biết chính xác số ngày phép còn lại để chủ động lên kế hoạch nghỉ mà không cần liên hệ HR. |
| Actor | Nhân viên công ty |
| Thời điểm / bối cảnh | Khi có nhu cầu nghỉ phép, lên kế hoạch cá nhân hoặc kiểm tra quyền lợi nghỉ phép. |
| Quy trình hiện tại (3–7 bước) | 1. Nhân viên phát sinh nhu cầu nghỉ. 2. Truy cập hệ thống hoặc liên hệ HR. 3. Tìm thông tin số ngày phép. 4. Kiểm tra lịch sử nghỉ phép. 5. Đối chiếu số ngày phép đã sử dụng. 6. Liên hệ HR nếu thông tin chưa rõ. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: Nhân viên phải tìm kiếm và tự đối chiếu thông tin. Thời gian: chưa đo. |
| Impact (nếu không giải thì sao) | Mất thời gian tra cứu, phụ thuộc vào HR, khó chủ động lên kế hoạch nghỉ. |
| Success metric (baseline → target) | Baseline: cần đo thời gian tra cứu và tỷ lệ nhân viên phải hỏi HR. Target đề xuất: 90% nhân viên tự tra cứu được số ngày phép mà không cần hỗ trợ. |
| Phương án không dùng AI | Hiển thị số ngày phép còn lại, đã sử dụng và lịch sử nghỉ phép trên trang cá nhân. |
| Giả thuyết về AI (nếu có) | AI có thể giải thích cách tính ngày phép và trả lời câu hỏi liên quan dựa trên chính sách công ty. |
| Cảm nhận nhanh | No AI / Rule: dữ liệu ngày phép có cấu trúc và công thức tính rõ ràng, không cần AI để truy xuất con số. |

Quy trình nháp hiện tại:

```
Nhân viên có nhu cầu nghỉ phép
        ↓
Truy cập hệ thống / liên hệ HR
        ↓
Tìm thông tin ngày phép
        ↓
Kiểm tra lịch sử nghỉ phép
        ↓
Đối chiếu số ngày đã sử dụng
        ↓
Liên hệ HR nếu chưa rõ
        ↓
Xác định số ngày phép còn lại

```

### Card muốn pitch nhất

- Card số: #1 – Repetitive HR Inquiry Handling.
- Vì sao: Đây là vấn đề có khả năng xuất hiện thường xuyên, ảnh hưởng đến cả HR và nhân viên. Có thể đo lường thời gian xử lý, số lượng câu hỏi lặp lại và tỷ lệ giải quyết thành công. Đồng thời, có thể so sánh giải pháp FAQ truyền thống với giải pháp ứng dụng AI.
- Câu hỏi muốn nhóm phản biện:
1.Vấn đề này có đủ nghiêm trọng để cần xây dựng một sản phẩm AI riêng không?
2.Nếu chỉ sử dụng FAQ hoặc tài liệu hướng dẫn thì có giải quyết được phần lớn vấn đề không?
3.AI có thể trả lời chính xác các câu hỏi liên quan đến chính sách nội bộ không?
4.Làm thế nào để tránh AI đưa ra thông tin sai về lương, nghỉ phép hoặc quyền lợi nhân viên?
5.Có nên xây dựng AI Agent hay chỉ cần chatbot RAG kết hợp tài liệu nội bộ?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa có số liệu chứng minh HR thực sự mất nhiều thời gian trả lời câu hỏi lặp lại. | Có | Bổ sung yêu cầu khảo sát số câu hỏi mỗi ngày và thời gian xử lý trung bình. |
| Vấn đề có thể giải quyết bằng FAQ hoặc tài liệu hướng dẫn mà không cần AI. |Có |	Bổ sung phương án không dùng AI để làm baseline so sánh.
Phạm vi câu hỏi quá rộng, bao gồm lương, nghỉ phép, chấm công và chính sách. |Có | Ưu tiên các câu hỏi thường gặp, có tài liệu nội bộ rõ ràng.
| Chưa có cơ chế đảm bảo độ chính xác của câu trả lời AI. |Có | Bổ sung giả thuyết RAG dựa trên tài liệu nội bộ và cơ chế chuyển câu hỏi khó cho HR.
| Target giảm 30–50% thời gian xử lý chưa có căn cứ thực nghiệm. |Có| Giữ đây là mục tiêu giả định, cần đo baseline trước khi xác nhận.
| Chưa xác định trường hợp nào cần AI, trường hợp nào chỉ cần Rule hoặc Workflow.|Có| Phân loại câu hỏi đơn giản theo FAQ, câu hỏi cần tổng hợp thông tin theo RAG, trường hợp nhạy cảm chuyển HR.
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
