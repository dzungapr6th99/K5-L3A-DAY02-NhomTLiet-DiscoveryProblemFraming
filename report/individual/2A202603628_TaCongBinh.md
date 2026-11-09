# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Tạ Công Bình
- MSSV: 2A202603628
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: NhomTLiet
- Link repo nhóm: https://github.com/dzungapr6th99K5-L3A-Day02-NhomTLiet-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Áp dụng **Double Diamond — Discover** để tìm vấn đề ở nhiều bối cảnh sử dụng AI; dùng **Jobs-to-be-Done / Job Story** để mô tả tình huống, động cơ và kết quả mong muốn.

**Bản minh họa bằng tình huống giả lập:** Sáu tình huống và toàn bộ số liệu dưới đây do AI tạo để minh họa cách điền template. Đây chưa phải dấu hiệu thật, trải nghiệm cá nhân hoặc kết quả khảo sát/phỏng vấn. Cần thay bằng dữ liệu thực tế trước khi dùng làm bằng chứng trong bài nộp.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi tổng hợp tài liệu cho một báo cáo, tôi muốn kiểm tra các thông tin và tài liệu tham khảo có đúng nguồn không, để tránh đưa nội dung sai vào bài viết. | Sinh viên hoặc người làm báo cáo có sử dụng trợ lý AI để research. | Khi kiểm tra 5 tài liệu tham khảo được gợi ý cho một báo cáo, người dùng không tìm thấy 2 tài liệu và mất thêm khoảng 20 phút tìm nguồn thay thế. |
| 2 | Lặp lại | Khi tiếp tục một công việc ở cuộc trò chuyện mới, tôi muốn giữ được các yêu cầu và quyết định đã thống nhất, để không phải giải thích lại từ đầu hoặc sửa kết quả mâu thuẫn. | Người dùng trợ lý AI để làm việc với một project qua nhiều phiên. | Khi tiếp tục sửa project ở cuộc trò chuyện mới, người dùng phải gửi lại cấu trúc thư mục và 4 yêu cầu đã chốt, mất khoảng 10 phút chuẩn bị lại ngữ cảnh trước khi tiếp tục công việc. |
| 3 | Tốn thời gian | Khi tích hợp một đoạn code được gợi ý vào project Python, tôi muốn code tương thích với phiên bản thư viện đang cài, để chạy được chức năng mà không phải sửa lỗi tích hợp nhiều lần. | Người học lập trình hoặc lập trình viên dùng công cụ hỗ trợ viết code. | Đoạn code được gợi ý gọi thư viện theo cách không phù hợp phiên bản đang cài; người dùng phải gửi lại thông báo lỗi và sửa qua 3 lượt mới chạy được. |
| 4 | Lặp lại | Khi chuyển ảnh hóa đơn thành bảng dữ liệu, tôi muốn số tiền và ngày tháng được trích xuất đúng, để tổng hợp chi tiêu mà không phải kiểm tra và sửa từng dòng. | Người nhập liệu hóa đơn hoặc tổng hợp chi tiêu bằng công cụ AI. | Trong một lần chuyển 10 ảnh hóa đơn thành bảng, có 3 hóa đơn bị đọc sai số tiền hoặc ngày tháng; người dùng phải mở lại ảnh gốc để đối chiếu và sửa các dòng tương ứng. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi phân loại phản hồi khách hàng, tôi muốn các phản hồi có cùng nội dung được xếp nhóm nhất quán giữa các lần xử lý, để số liệu tổng hợp phản ánh đúng các vấn đề khách hàng gặp. | Nhân viên chăm sóc khách hàng hoặc người phân tích phản hồi bằng mô hình ngôn ngữ. | Khi chạy cùng yêu cầu phân loại trên cùng 20 phản hồi khách hàng hai lần, người dùng thấy 4 phản hồi bị đổi nhóm giữa hai lần chạy và phải đọc lại để xác định nhóm phù hợp. |
| 6 | Lặp lại | Khi lấy kết quả trả về để nhập vào chương trình, tôi muốn dữ liệu tuân thủ đúng cấu trúc JSON đã yêu cầu, để bước đọc dữ liệu chạy được mà không phải chỉnh sửa thủ công. | Lập trình viên tích hợp kết quả từ mô hình ngôn ngữ vào ứng dụng. | Trong 10 lần thử yêu cầu trả về JSON, có 3 lần kết quả kèm phần giải thích ngoài JSON, khiến bước đọc dữ liệu báo lỗi; người dùng phải loại phần chữ thừa hoặc yêu cầu tạo lại. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI hỗ trợ đề xuất sáu candidate problem, diễn đạt theo Job Story và tạo số liệu giả lập để minh họa cách mô tả dấu hiệu.
- Sáu candidate được đưa vào bản minh họa theo yêu cầu; chưa có quyết định cá nhân về ý giữ/bỏ sau khi đối chiếu trải nghiệm thật.
- Các số liệu giả lập không được dùng để khẳng định học viên hoặc người khác thực sự đã gặp vấn đề. Khi hoàn thiện báo cáo, thay bằng sự kiện có căn cứ và tự ghi lý do giữ/bỏ từng ý.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

Ba card triển khai candidate 3, 1 và 2 của CP1. Dùng **Job Story** để mô tả nhu cầu; chọn lọc theo actor, quy trình, bottleneck, impact và khả năng kiểm chứng. Đây là bản nháp có AI hỗ trợ: card 1–2 là tình huống minh họa; card 3 dựa trên tình huống học viên mô tả nhưng chưa đo số liệu. Thứ hạng là đề xuất, không phải kết quả chấm điểm nhóm CP3.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Code được gợi ý không tương thích với project Python | Có actor và đầu ra rõ; có thể dùng log, phiên bản thư viện và kiểm tra chức năng để phân biệt lỗi và đo số lượt sửa. | Chưa có dữ liệu thực tế; cần phân biệt lỗi phiên bản thư viện, thiếu ngữ cảnh và lỗi logic. |
| 2 | Khó kiểm chứng tài liệu tham khảo được gợi ý | Có thể đối chiếu từng nguồn và đo công sức xác minh; có phương án tìm nguồn trực tiếp để so sánh. | Không tìm thấy nguồn chưa chứng minh nguồn không tồn tại; cần kiểm tra thông tin trích dẫn và phạm vi tìm kiếm. |
| 3 | Khó duy trì ngữ cảnh còn hiệu lực khi chat dài hoặc chuyển phiên | Yêu cầu, quyết định và phương án đã bỏ nằm xen kẽ; việc khôi phục ngữ cảnh có thể tốn công và token đầu vào. Có thể thử ghi chú bàn giao trước khi xây công cụ. | Chưa đo thời gian, token và số yêu cầu bị bỏ sót; chưa biết công sức cập nhật ghi chú có nhỏ hơn công sức giải thích lại không. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tích hợp một đoạn code được gợi ý vào project Python, tôi muốn code tương thích với phiên bản thư viện đang cài, để chạy được chức năng mà không phải sửa lỗi tích hợp nhiều lần. |
| Actor | Người học lập trình Python dùng trợ lý AI để bổ sung một chức năng có sử dụng thư viện bên ngoài vào project đang có. |
| Thời điểm / bối cảnh | Project đã có môi trường và phiên bản thư viện cụ thể. Người dùng nhận code gợi ý, tích hợp rồi chạy thử. Card mô tả tình huống giả lập, chưa có log hoặc lần thực hiện thực tế được cung cấp. |
| Quy trình hiện tại (3–7 bước) | Mô tả chức năng → nhận và tích hợp code → chạy thử → đọc lỗi, đối chiếu phiên bản và sửa lại → kiểm tra chức năng cùng phần liên quan. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 mất 20 phút và 3 lượt sửa do cách gọi thư viện không phù hợp phiên bản. Cần kiểm tra log để phân biệt lỗi tương thích với lỗi logic trước khi xác nhận đây là bottleneck thật. |
| Impact (nếu không giải thì sao) | Mất tổng cộng 40 phút cho một lần tích hợp chức năng; công việc bị gián đoạn khi phải sửa qua nhiều lượt. Có nguy cơ thay đổi phần đang chạy ổn nếu chỉ sửa theo lỗi mới mà không kiểm tra chức năng liên quan; rủi ro này chưa được đo. |
| Success metric (baseline → target) | Từ baseline giả lập 40 xuống không quá 25 phút/chức năng; số lượt sửa do lỗi tương thích từ 3 xuống không quá 1. Đo từ lúc mô tả yêu cầu đến khi chức năng vượt qua bộ kiểm tra xác định trước; ghi riêng loại lỗi và số lượt sửa. Điều kiện chất lượng: chức năng mới đúng yêu cầu và các kiểm tra chức năng liên quan vẫn đạt. Cần đo baseline thật trước khi kết luận cải thiện. |
| Phương án không dùng AI | Kiểm tra phiên bản Python và thư viện; đọc tài liệu đúng phiên bản; chạy ví dụ tối thiểu để xác nhận cách gọi API trước khi tích hợp. Ghi phiên bản phụ thuộc để người khác tái hiện môi trường. |
| Giả thuyết về AI (nếu có) | Cung cấp phiên bản môi trường, đoạn code liên quan và log lỗi có thể giúp gợi ý phù hợp hơn. Quy trình thử: chuẩn bị ngữ cảnh → AI đề xuất bản sửa nhỏ → người dùng duyệt → chạy kiểm tra. Không tự nâng phiên bản phụ thuộc hoặc sửa ngoài phạm vi; người dùng quyết định thay đổi và có thể quay lại bản trước. Hiệu quả giảm lỗi chưa được chứng minh. |
| Cảm nhận nhanh | Thử checklist môi trường và tài liệu đúng phiên bản trước. Nếu vẫn cần hỗ trợ sửa code, cân nhắc Workflow có bước kiểm tra của con người; chưa có lý do cần Agent. |

Quy trình nháp hiện tại:

```text
THỜI GIAN MINH HỌA GIẢ LẬP — CHƯA ĐO THỰC TẾ

[1. Mô tả chức năng: 5 phút]
→ [2. Nhận và tích hợp code: 5 phút]
→ [3. Chạy thử: 5 phút]
→ [4. Đọc lỗi, đối chiếu phiên bản và sửa lại: 20 phút] ← BOTTLENECK
→ [5. Kiểm tra chức năng và phần liên quan: 5 phút]

Tổng minh họa: 40 phút/chức năng.
Bước 4 bao gồm các lượt sửa và chạy lại trong tình huống minh họa.
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi tổng hợp tài liệu cho một báo cáo, tôi muốn kiểm tra thông tin và tài liệu tham khảo có đúng nguồn và đúng ngữ cảnh không, để tránh đưa nội dung chưa được xác minh vào bài viết. |
| Actor | Sinh viên sử dụng trợ lý AI để tìm tài liệu phục vụ một báo cáo học tập. |
| Thời điểm / bối cảnh | Sau khi nhận danh sách tài liệu gợi ý, trước khi đưa thông tin và trích dẫn vào báo cáo. Card dùng tình huống giả lập gồm 5 tài liệu, trong đó 2 tài liệu chưa tìm thấy; chưa có bộ nguồn thực tế để đối chiếu. |
| Quy trình hiện tại (3–7 bước) | Nhận danh sách tài liệu → tìm và mở từng nguồn → đối chiếu nội dung với nhận định → tìm nguồn thay thế nếu chưa xác minh được → ghi trích dẫn và quyết định sử dụng. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước tìm nguồn thay thế mất 20 phút vì 2/5 tài liệu chưa tìm thấy. Cần kiểm tra lại tiêu đề, tác giả, năm và phạm vi tìm kiếm trước khi kết luận nguồn sai hoặc không tồn tại. |
| Impact (nếu không giải thì sao) | Tổng thời gian xác minh và hoàn thiện danh sách là 45 phút. Nếu bỏ qua đối chiếu, có nguy cơ trích dẫn một nguồn không hỗ trợ nhận định; chưa có bằng chứng người dùng đã nộp báo cáo sai. |
| Success metric (baseline → target) | Từ baseline giả lập 45 xuống không quá 30 phút/bộ 5 nguồn. Đo từ lúc nhận danh sách đến khi hoàn tất kiểm tra và ghi trích dẫn. Mọi nguồn được sử dụng phải truy cập, đọc và đối chiếu được với nhận định; nguồn chưa xác minh không đưa vào báo cáo. So sánh các bộ nguồn có mức độ khó tương đương và ghi số nguồn cần thay, tránh chỉ đo tốc độ tìm kiếm. |
| Phương án không dùng AI | Tìm trực tiếp trên kho học thuật hoặc website chính thức. Lập bảng gồm nhận định, tên nguồn, tác giả/năm, đường dẫn và đoạn hỗ trợ; kiểm tra trước khi viết nội dung dựa trên nguồn đó. |
| Giả thuyết về AI (nếu có) | Có thể hỗ trợ tổng hợp từ tập tài liệu người dùng đã xác minh và chỉ rõ đoạn nguồn cho từng nhận định. Người dùng kiểm tra cả sự tồn tại của nguồn và việc nguồn có thực sự hỗ trợ kết luận. Không xem một đường dẫn mở được là bằng chứng nội dung đúng; chưa biết hỗ trợ này có giảm tổng công sức không. |
| Cảm nhận nhanh | **No AI** cho khâu xác minh và quyết định dùng nguồn. Nếu cần tổng hợp nhiều tài liệu đã kiểm tra, có thể cân nhắc Workflow hỗ trợ đọc/tóm tắt; chưa chốt mức cho toàn bộ quy trình. |

Quy trình nháp hiện tại:

```text
THỜI GIAN MINH HỌA GIẢ LẬP — CHƯA ĐO THỰC TẾ

[1. Nhận danh sách tài liệu: 3 phút]
→ [2. Tìm và mở từng nguồn: 10 phút]
→ [3. Đối chiếu nội dung với nhận định: 10 phút]
→ [4. Tìm nguồn thay thế: 20 phút] ← BOTTLENECK
→ [5. Ghi trích dẫn và quyết định sử dụng: 2 phút]

Tổng minh họa: 45 phút/bộ 5 nguồn.
Bước 4 bao gồm kiểm tra nguồn thay thế trước khi sử dụng.
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tiếp tục một project trong cuộc trò chuyện đã dài hoặc chuyển sang phiên mới, tôi muốn xác định đúng yêu cầu, quyết định và trạng thái hiện tại, để tiếp tục công việc mà không phải giải thích lại toàn bộ hoặc làm theo thông tin đã hết hiệu lực. |
| Actor | Người dùng trợ lý AI hỗ trợ một project kéo dài qua nhiều lượt trao đổi và nhiều phiên làm việc. |
| Thời điểm / bối cảnh | Trong quá trình làm project, yêu cầu được bổ sung hoặc thay đổi, một số phương án bị loại và một số quyết định được chốt. Khi chat dài, trợ lý có thể bỏ sót yêu cầu hoặc dùng lại quyết định cũ. Khi chuyển phiên, lịch sử còn lẫn thông tin đúng, thông tin đã thay đổi và các trao đổi không còn cần thiết. Đây là tình huống học viên mô tả, chưa có thống kê thực nghiệm. |
| Quy trình hiện tại (3–7 bước) | Nhận thấy cần khôi phục ngữ cảnh → mở lịch sử trao đổi → tìm yêu cầu và quyết định → phân biệt thông tin còn hiệu lực với phương án đã bỏ → tổng hợp và cung cấp lại ngữ cảnh → kiểm tra phản hồi, bổ sung nếu còn thiếu. Phương án khác đang cân nhắc là đưa lại toàn bộ lịch sử, nhưng có thể tăng token đầu vào và vẫn giữ nhiều thông tin gây nhiễu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Tìm và tổng hợp trạng thái hiện tại từ lịch sử nhiều thay đổi: phải xác định yêu cầu nào còn hiệu lực, quyết định nào thay thế quyết định cũ và việc gì đang dang dở. |
| Impact (nếu không giải thì sao) | Có thể phải nhắc lại yêu cầu, nhận đầu ra theo phương án đã bỏ và sửa lại công việc. Đưa toàn bộ lịch sử vào phiên mới có thể tăng token đầu vào và thời gian xử lý; chưa có số token hoặc chi phí đo được. |
| Success metric (baseline → target) | Thời gian khôi phục ngữ cảnh từ baseline giả lập 10 phút xuống không quá 3 phút/lần. Đo từ lúc bắt đầu khôi phục đến khi kiểm tra phản hồi xác nhận đúng các yêu cầu còn hiệu lực. So sánh token của bản bàn giao với toàn bộ lịch sử trên cùng công cụ đếm token; mục tiêu bản bàn giao ít token hơn nhưng không bỏ sót yêu cầu/quyết định quan trọng trong checklist người dùng duyệt. Ghi riêng thời gian cập nhật bản bàn giao để đánh giá tổng công sức, không chỉ thời gian đầu phiên. Cần đo baseline thật trước khi kết luận cải thiện. |
| Phương án không dùng AI | Duy trì ghi chú bàn giao theo template: mục tiêu, trạng thái hiện tại, yêu cầu còn hiệu lực, quyết định đã chốt, phương án đã bỏ và lý do, việc tiếp theo, câu hỏi còn mở. Người dùng tự cập nhật khi có thay đổi quan trọng, ghi phiên bản hoặc thời điểm cập nhật; dùng bản này để nhắc lại trong chat hiện tại hoặc chuyển sang phiên mới. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ đề xuất cập nhật bản bàn giao từ những thay đổi kể từ lần cập nhật trước. Người dùng đối chiếu lịch sử, duyệt các yêu cầu/quyết định và lưu bản mới. Quy trình dự kiến: có thay đổi → đề xuất cập nhật → người dùng duyệt → lưu → cung cấp lại khi cần. AI không tự chốt quyết định thay người dùng, không tự loại yêu cầu quan trọng và không ghi đè bản đã duyệt khi chưa được xác nhận. Bản tóm tắt cũng có thể bỏ sót hoặc giữ thông tin cũ, nên cần kiểm tra. |
| Cảm nhận nhanh | **No AI trước:** thử ghi chú bàn giao thủ công. Nếu việc cập nhật vẫn tốn công, cân nhắc **Workflow** với AI soạn cập nhật và người dùng duyệt. Chưa cần Agent vì các bước bàn giao có thể xác định trước; chưa đủ bằng chứng để chốt mức can thiệp. |

Quy trình nháp hiện tại:

```text
THỜI GIAN MINH HỌA GIẢ LẬP — CHƯA ĐO THỰC TẾ

[1. Nhận thấy cần khôi phục ngữ cảnh: 1 phút]
→ [2. Mở lịch sử trao đổi: 1 phút]
→ [3. Tìm yêu cầu và quyết định: 3 phút]              ┐
→ [4. Phân biệt thông tin còn hiệu lực/đã bỏ: 2 phút] ├─ BOTTLENECK: 7 phút
→ [5. Tổng hợp và cung cấp lại ngữ cảnh: 2 phút]      ┘
→ [6. Kiểm tra phản hồi, bổ sung nếu thiếu: 1 phút]

Tổng minh họa: 10 phút/lần khôi phục ngữ cảnh.
Token đầu vào, số lần nhắc lại và thời gian sửa phát sinh: chưa đo.
```

### Card muốn pitch nhất

- Card số: **3 — Khó duy trì ngữ cảnh còn hiệu lực khi chat dài hoặc chuyển phiên** (theo hướng học viên đang chuẩn bị trình bày; chưa phải lựa chọn chung của nhóm).
- Vì sao: Học viên đã mô tả rõ tình huống chat dài, yêu cầu thay đổi, quyết định cũ/mới lẫn nhau và công sức cung cấp lại lịch sử. Phạm vi có thể thu hẹp vào khôi phục trạng thái một project; thử ghi chú bàn giao trước khi xây công cụ. Các metric thời gian và token vẫn cần đo.
- Câu hỏi muốn nhóm phản biện: Ghi chú bàn giao có thực sự giảm tổng công sức cập nhật và khôi phục ngữ cảnh không? Làm sao phát hiện thông tin đã hết hiệu lực hoặc quyết định quan trọng bị bỏ sót khi rút gọn lịch sử?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Cả ba card đang dùng baseline giả lập, chưa đủ để khẳng định mức độ pain hoặc hiệu quả giải pháp. | Chờ học viên tự đánh giá. | Bản nháp đã tách số liệu minh họa khỏi mục tiêu thử nghiệm và ghi cách đo. Chưa thay thế bằng số liệu thật. |
| Card 1: lỗi sau khi tích hợp có thể do logic hoặc thiếu ngữ cảnh, không chỉ do phiên bản thư viện. | Chờ học viên tự đánh giá. | Bản nháp yêu cầu phân loại lỗi theo log và chỉ tính lượt sửa do tương thích vào metric tương ứng; thêm điều kiện kiểm tra chức năng liên quan. |
| Card 2: không tìm thấy tài liệu chưa chứng minh tài liệu không tồn tại; một link mở được cũng chưa chứng minh nhận định đúng. | Chờ học viên tự đánh giá. | Bản nháp dùng cách diễn đạt “chưa tìm thấy/chưa xác minh”; yêu cầu kiểm tra thông tin trích dẫn và đối chiếu nội dung nguồn với nhận định. |
| Card 3: chỉ giảm thời gian đầu phiên có thể che mất công sức cập nhật ghi chú ở cuối phiên. | Chờ học viên tự đánh giá. | Bản nháp bổ sung đo riêng công sức cập nhật và khôi phục ngữ cảnh để đánh giá tổng công sức. |
| Card 3: tóm tắt ngắn hơn có thể bỏ sót yêu cầu hoặc giữ quyết định cũ, dù giảm token đầu vào. | Chờ học viên tự đánh giá. | Bản nháp thêm yêu cầu ghi rõ thông tin còn hiệu lực, phương án đã bỏ, kiểm tra bằng checklist và người dùng duyệt trước khi lưu. |

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
