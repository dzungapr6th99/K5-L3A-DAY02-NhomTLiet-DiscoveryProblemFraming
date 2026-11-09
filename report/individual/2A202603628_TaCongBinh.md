# Báo cáo cá nhân — 2A202603628_TaCongBinh

> Báo cáo có AI hỗ trợ biên tập và phản biện từ các vấn đề học viên xác nhận đã gặp. Các mốc thời gian do AI đề xuất cho mô hình mô tả được ghi rõ là ước lượng thiết kế, không phải số đo thực tế.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Tạ Công Bình
- MSSV: 2A202603628
- Email trường (không bắt buộc, repo có thể để public): 26ai.binhtc@vinuni.edu.vn
- Tên nhóm: NhomTLiet
- Link repo nhóm: https://github.com/dzungapr6th99/K5-L3A-Day02-NhomTLiet-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

Áp dụng **Double Diamond — Discover** để tìm vấn đề ở nhiều bối cảnh sử dụng AI; dùng **Jobs-to-be-Done / Job Story** để mô tả tình huống, động cơ và kết quả mong muốn.

**Cơ sở trải nghiệm:** Tôi xác nhận đã gặp cả sáu vấn đề dưới đây khi sử dụng AI. AI hỗ trợ sắp xếp và diễn đạt theo Job Story; riêng vấn đề ngữ cảnh được tôi mô tả thêm về chat dài, yêu cầu cũ/mới và chi phí đọc lại lịch sử. Việc xác nhận vấn đề không đồng nghĩa xác nhận các con số do AI từng đưa ra. Vì chưa có bản ghi định lượng, bảng CP1 chỉ ghi dấu hiệu tôi xác nhận đã gặp; thời gian trong các card CP2 là ước lượng thiết kế để mô tả quy trình.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi tổng hợp tài liệu cho một báo cáo, tôi muốn kiểm tra các thông tin và tài liệu tham khảo có đúng nguồn không, để tránh đưa nội dung sai vào bài viết. | Tôi khi research và viết báo cáo có sử dụng trợ lý AI. | Tôi từng không tìm thấy tài liệu được gợi ý, phải tìm lại và đối chiếu nguồn trước khi sử dụng. Chưa ghi lại số tài liệu, số lần và thời gian xử lý. |
| 2 | Lặp lại · Cần đọc, tổng hợp nhiều thông tin | Khi tiếp tục một project trong cuộc trò chuyện dài hoặc chuyển sang phiên mới, tôi muốn xác định đúng yêu cầu và quyết định còn hiệu lực, để không phải giải thích lại toàn bộ hay làm theo thông tin đã cũ. | Tôi khi dùng trợ lý AI làm project qua nhiều lượt và nhiều phiên. | Tôi gặp việc ngữ cảnh bị bỏ sót trong chat dài; khi chuyển phiên phải lọc lịch sử lẫn quyết định cũ/mới, còn đưa toàn bộ vào thì tốn token. Tôi đã mô tả trực tiếp tình huống này trong cuộc trò chuyện làm báo cáo; chưa đo thời gian/token. |
| 3 | Tốn thời gian | Khi tích hợp một đoạn code được gợi ý vào project Python, tôi muốn code tương thích với phiên bản thư viện đang cài, để chạy được chức năng mà không phải sửa lỗi tích hợp nhiều lần. | Tôi khi học lập trình và tích hợp code vào project Python. | Tôi từng nhận code có cách gọi thư viện không phù hợp môi trường đang dùng, phải gửi lại lỗi và sửa qua nhiều lượt trước khi chạy được. Chưa có thống kê số lượt và thời gian. |
| 4 | Lặp lại | Khi chuyển ảnh hóa đơn thành bảng dữ liệu, tôi muốn số tiền và ngày tháng được trích xuất đúng, để tổng hợp chi tiêu mà không phải kiểm tra và sửa từng dòng. | Tôi khi trích xuất thông tin hóa đơn bằng AI. | Tôi từng thấy kết quả đọc sai số tiền hoặc ngày tháng, phải mở ảnh gốc để đối chiếu và sửa dòng tương ứng. Chưa thống kê số ảnh, số trường sai hoặc thời gian sửa. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi phân loại phản hồi khách hàng, tôi muốn các phản hồi có cùng nội dung được xếp nhóm nhất quán giữa các lần xử lý, để số liệu tổng hợp phản ánh đúng các vấn đề khách hàng gặp. | Tôi khi dùng mô hình ngôn ngữ phân loại phản hồi. | Tôi từng thấy cùng nội dung bị đổi nhóm giữa các lần xử lý, phải đọc lại để quyết định nhóm phù hợp. Chưa lưu bộ kết quả để tính tỷ lệ thay đổi nhãn. |
| 6 | Lặp lại | Khi lấy kết quả trả về để nhập vào chương trình, tôi muốn dữ liệu tuân thủ đúng cấu trúc JSON đã yêu cầu, để bước đọc dữ liệu chạy được mà không phải chỉnh sửa thủ công. | Tôi khi đưa kết quả mô hình ngôn ngữ vào chương trình. | Tôi từng nhận thêm phần giải thích ngoài JSON khiến bước đọc dữ liệu báo lỗi, phải bỏ phần chữ thừa hoặc yêu cầu tạo lại. Chưa ghi số lần lỗi trên tổng số lần chạy. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI hỗ trợ gợi nhớ và diễn đạt danh sách sáu vấn đề theo Job Story. Tôi xác nhận các vấn đề đều đã gặp và giữ lại vì phù hợp trải nghiệm sử dụng AI của mình.
- Tôi bổ sung bối cảnh cho candidate 2 và chọn phát triển thành Card #3 muốn pitch nhất: ngữ cảnh có thể bị bỏ sót ngay trong chat dài, lịch sử lẫn quyết định cũ/mới và đọc lại toàn bộ tốn token.
- Tôi bỏ cách diễn đạt coi toàn bộ vấn đề là tình huống dựng. Các số đếm minh họa AI từng đưa ra không được coi là lịch sử thực tế; dấu hiệu CP1 được viết lại định tính, còn thời gian CP2 tách riêng là ước lượng thiết kế.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

Ba card triển khai candidate 3, 1 và 2 của CP1, đều là vấn đề tôi xác nhận đã gặp. Dùng **Job Story** để mô tả nhu cầu và phân tích actor, quy trình, bottleneck, impact. AI hỗ trợ biên tập và phản biện; thời gian từng bước là ước lượng thiết kế, chưa được bấm giờ. Bảng top 3 là phần cá nhân, không phải điểm nhóm CP3.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Code được gợi ý không tương thích với project Python | Tôi đã gặp lỗi khi tích hợp; có thể dùng log, phiên bản thư viện và kiểm tra chức năng để phân biệt nguyên nhân. | Chưa thống kê định lượng; cần phân biệt lỗi phiên bản, thiếu ngữ cảnh và lỗi logic. |
| 2 | Khó kiểm chứng tài liệu tham khảo được gợi ý | Có thể đối chiếu từng nguồn và đo công sức xác minh; có phương án tìm nguồn trực tiếp để so sánh. | Không tìm thấy nguồn chưa chứng minh nguồn không tồn tại; cần kiểm tra thông tin trích dẫn và phạm vi tìm kiếm. |
| 3 | Khó duy trì ngữ cảnh còn hiệu lực khi chat dài hoặc chuyển phiên | Yêu cầu, quyết định và phương án đã bỏ nằm xen kẽ; việc khôi phục ngữ cảnh có thể tốn công và token đầu vào. Có thể thử ghi chú bàn giao trước khi xây công cụ. | Chưa đo thời gian, token và số yêu cầu bị bỏ sót; chưa biết công sức cập nhật ghi chú có nhỏ hơn công sức giải thích lại không. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tích hợp một đoạn code được gợi ý vào project Python, tôi muốn code tương thích với phiên bản thư viện đang cài, để chạy được chức năng mà không phải sửa lỗi tích hợp nhiều lần. |
| Actor | Người học lập trình Python dùng trợ lý AI để bổ sung một chức năng có sử dụng thư viện bên ngoài vào project đang có. |
| Thời điểm / bối cảnh | Khi tôi tích hợp code được gợi ý vào project Python có môi trường và phiên bản thư viện cụ thể, rồi chạy thử và gặp lỗi. Đây là vấn đề tôi xác nhận đã gặp; chưa đính kèm log hoặc số liệu bấm giờ. |
| Quy trình hiện tại (3–7 bước) | Mô tả chức năng → nhận và tích hợp code → chạy thử → đọc lỗi, đối chiếu phiên bản và sửa lại → kiểm tra chức năng cùng phần liên quan. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: đọc lỗi, đối chiếu phiên bản và sửa qua nhiều lượt. Thời gian 20 phút là ước lượng thiết kế trong sơ đồ, chưa đo. Cần phân loại lỗi để không quy mọi lỗi logic hoặc thiếu ngữ cảnh thành lỗi tương thích. |
| Impact (nếu không giải thì sao) | Công việc bị gián đoạn và phải sửa lại trước khi tích hợp được chức năng. Tổng 40 phút trong sơ đồ là ước lượng thiết kế; không phải thời gian thực tế đã xác nhận. Sửa theo lỗi mới mà không kiểm tra phần liên quan có thể tạo lỗi khác. |
| Success metric (baseline → target) | Từ baseline ước lượng thiết kế 40 xuống không quá 25 phút/chức năng; số lượt sửa do lỗi tương thích từ 3 xuống không quá 1. Đo từ lúc mô tả yêu cầu đến khi chức năng vượt qua bộ kiểm tra xác định trước; ghi riêng loại lỗi và số lượt sửa. Điều kiện chất lượng: chức năng mới đúng yêu cầu và các kiểm tra chức năng liên quan vẫn đạt. Cần đo baseline thật trước khi kết luận cải thiện. |
| Phương án không dùng AI | Kiểm tra phiên bản Python và thư viện; đọc tài liệu đúng phiên bản; chạy ví dụ tối thiểu để xác nhận cách gọi API trước khi tích hợp. Ghi phiên bản phụ thuộc để người khác tái hiện môi trường. |
| Giả thuyết về AI (nếu có) | Cung cấp phiên bản môi trường, đoạn code liên quan và log lỗi có thể giúp gợi ý phù hợp hơn. Quy trình thử: chuẩn bị ngữ cảnh → AI đề xuất bản sửa nhỏ → người dùng duyệt → chạy kiểm tra. Không tự nâng phiên bản phụ thuộc hoặc sửa ngoài phạm vi; người dùng quyết định thay đổi và có thể quay lại bản trước. Hiệu quả giảm lỗi chưa được chứng minh. |
| Cảm nhận nhanh | **Chưa biết.** Thử checklist môi trường và tài liệu đúng phiên bản trước. Nếu vẫn cần hỗ trợ sửa code, cân nhắc Workflow có bước kiểm tra của con người; chưa có lý do cần Agent. |

Quy trình nháp hiện tại:

```text
THỜI GIAN ƯỚC LƯỢNG THIẾT KẾ — CHƯA ĐO THỰC TẾ

[1. Mô tả chức năng: 5 phút]
→ [2. Nhận và tích hợp code: 5 phút]
→ [3. Chạy thử: 5 phút]
→ [4. Đọc lỗi, đối chiếu phiên bản và sửa lại: 20 phút] ← BOTTLENECK
→ [5. Kiểm tra chức năng và phần liên quan: 5 phút]

Tổng ước lượng thiết kế: 40 phút/chức năng.
Bước 4 bao gồm các lượt sửa và chạy lại trong mô hình thời gian ước lượng.
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi tổng hợp tài liệu cho một báo cáo, tôi muốn kiểm tra thông tin và tài liệu tham khảo có đúng nguồn và đúng ngữ cảnh không, để tránh đưa nội dung chưa được xác minh vào bài viết. |
| Actor | Sinh viên sử dụng trợ lý AI để tìm tài liệu phục vụ một báo cáo học tập. |
| Thời điểm / bối cảnh | Sau khi tôi nhận danh sách tài liệu gợi ý, trước khi dùng thông tin và trích dẫn vào báo cáo. Tôi đã gặp việc không tìm thấy nguồn và phải kiểm tra lại; chưa lưu bộ nguồn để thống kê tỷ lệ. |
| Quy trình hiện tại (3–7 bước) | Nhận danh sách tài liệu → tìm và mở từng nguồn → đối chiếu nội dung với nhận định → tìm nguồn thay thế nếu chưa xác minh được → ghi trích dẫn và quyết định sử dụng. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước tìm nguồn thay thế khi chưa xác minh được tài liệu, ước lượng thiết kế 20 phút. Kiểm tra lại tiêu đề, tác giả, năm và phạm vi tìm kiếm trước khi kết luận nguồn sai hoặc không tồn tại. |
| Impact (nếu không giải thì sao) | Phải tìm lại và kiểm tra nguồn trước khi viết, ảnh hưởng tiến độ báo cáo. Tổng 45 phút là ước lượng thiết kế; không khẳng định tôi đã nộp báo cáo sai hoặc mất đúng thời gian này. |
| Success metric (baseline → target) | Từ baseline ước lượng thiết kế 45 xuống không quá 30 phút/bộ 5 nguồn. Đo từ lúc nhận danh sách đến khi hoàn tất kiểm tra và ghi trích dẫn. Mọi nguồn được sử dụng phải truy cập, đọc và đối chiếu được với nhận định; nguồn chưa xác minh không đưa vào báo cáo. So sánh các bộ nguồn có mức độ khó tương đương và ghi số nguồn cần thay, tránh chỉ đo tốc độ tìm kiếm. |
| Phương án không dùng AI | Tìm trực tiếp trên kho học thuật hoặc website chính thức. Lập bảng gồm nhận định, tên nguồn, tác giả/năm, đường dẫn và đoạn hỗ trợ; kiểm tra trước khi viết nội dung dựa trên nguồn đó. |
| Giả thuyết về AI (nếu có) | Có thể hỗ trợ tổng hợp từ tập tài liệu người dùng đã xác minh và chỉ rõ đoạn nguồn cho từng nhận định. Người dùng kiểm tra cả sự tồn tại của nguồn và việc nguồn có thực sự hỗ trợ kết luận. Không xem một đường dẫn mở được là bằng chứng nội dung đúng; chưa biết hỗ trợ này có giảm tổng công sức không. |
| Cảm nhận nhanh | **No AI** cho khâu xác minh và quyết định dùng nguồn. Nếu cần tổng hợp nhiều tài liệu đã kiểm tra, có thể cân nhắc Workflow hỗ trợ đọc/tóm tắt; chưa chốt mức cho toàn bộ quy trình. |

Quy trình nháp hiện tại:

```text
THỜI GIAN ƯỚC LƯỢNG THIẾT KẾ — CHƯA ĐO THỰC TẾ

[1. Nhận danh sách tài liệu: 3 phút]
→ [2. Tìm và mở từng nguồn: 10 phút]
→ [3. Đối chiếu nội dung với nhận định: 10 phút]
→ [4. Tìm nguồn thay thế: 20 phút] ← BOTTLENECK
→ [5. Ghi trích dẫn và quyết định sử dụng: 2 phút]

Tổng ước lượng thiết kế: 45 phút/bộ 5 nguồn.
Bước 4 bao gồm kiểm tra nguồn thay thế trước khi sử dụng.
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tiếp tục một project trong cuộc trò chuyện đã dài hoặc chuyển sang phiên mới, tôi muốn xác định đúng yêu cầu, quyết định và trạng thái hiện tại, để tiếp tục công việc mà không phải giải thích lại toàn bộ hoặc làm theo thông tin đã hết hiệu lực. |
| Actor | Người dùng trợ lý AI hỗ trợ một project kéo dài qua nhiều lượt trao đổi và nhiều phiên làm việc. |
| Thời điểm / bối cảnh | Trong quá trình làm project, yêu cầu được bổ sung hoặc thay đổi, một số phương án bị loại và một số quyết định được chốt. Khi chat dài, trợ lý có thể bỏ sót yêu cầu hoặc dùng lại quyết định cũ. Khi chuyển phiên, lịch sử còn lẫn thông tin đúng, thông tin đã thay đổi và các trao đổi không còn cần thiết. Đây là tình huống học viên mô tả, chưa có thống kê thực nghiệm. |
| Quy trình hiện tại (3–7 bước) | Nhận thấy cần khôi phục ngữ cảnh → mở lịch sử trao đổi → tìm yêu cầu và quyết định → phân biệt thông tin còn hiệu lực với phương án đã bỏ → tổng hợp và cung cấp lại ngữ cảnh → kiểm tra phản hồi, bổ sung nếu còn thiếu. Phương án khác đang cân nhắc là đưa lại toàn bộ lịch sử, nhưng có thể tăng token đầu vào và vẫn giữ nhiều thông tin gây nhiễu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–5: tìm và tổng hợp trạng thái hiện tại từ lịch sử nhiều thay đổi, phân biệt yêu cầu còn hiệu lực, quyết định đã bị thay thế và việc dang dở. Tổng **7 phút theo sơ đồ ước lượng thiết kế**, chưa phải thời gian đo thực tế. |
| Impact (nếu không giải thì sao) | Có thể phải nhắc lại yêu cầu, nhận đầu ra theo phương án đã bỏ và sửa lại công việc. Đưa toàn bộ lịch sử vào phiên mới có thể tăng token đầu vào và thời gian xử lý; chưa có số token hoặc chi phí đo được. |
| Success metric (baseline → target) | Thời gian khôi phục ngữ cảnh từ baseline ước lượng thiết kế 10 phút xuống không quá 3 phút/lần. Đo từ lúc bắt đầu khôi phục đến khi kiểm tra phản hồi xác nhận đúng các yêu cầu còn hiệu lực. So sánh token của bản bàn giao với toàn bộ lịch sử trên cùng công cụ đếm token; mục tiêu bản bàn giao ít token hơn nhưng không bỏ sót yêu cầu/quyết định quan trọng trong checklist người dùng duyệt. Ghi riêng thời gian cập nhật bản bàn giao để đánh giá tổng công sức, không chỉ thời gian đầu phiên. Cần đo baseline thật trước khi kết luận cải thiện. |
| Phương án không dùng AI | Duy trì ghi chú bàn giao theo template: mục tiêu, trạng thái hiện tại, yêu cầu còn hiệu lực, quyết định đã chốt, phương án đã bỏ và lý do, việc tiếp theo, câu hỏi còn mở. Người dùng tự cập nhật khi có thay đổi quan trọng, ghi phiên bản hoặc thời điểm cập nhật; dùng bản này để nhắc lại trong chat hiện tại hoặc chuyển sang phiên mới. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ đề xuất cập nhật bản bàn giao từ những thay đổi kể từ lần cập nhật trước. Người dùng đối chiếu lịch sử, duyệt các yêu cầu/quyết định và lưu bản mới. Quy trình dự kiến: có thay đổi → đề xuất cập nhật → người dùng duyệt → lưu → cung cấp lại khi cần. AI không tự chốt quyết định thay người dùng, không tự loại yêu cầu quan trọng và không ghi đè bản đã duyệt khi chưa được xác nhận. Bản tóm tắt cũng có thể bỏ sót hoặc giữ thông tin cũ, nên cần kiểm tra. |
| Cảm nhận nhanh | **No AI trước:** thử ghi chú bàn giao thủ công. Nếu việc cập nhật vẫn tốn công, cân nhắc **Workflow** với AI soạn cập nhật và người dùng duyệt. Chưa cần Agent vì các bước bàn giao có thể xác định trước; chưa đủ bằng chứng để chốt mức can thiệp. |

Quy trình nháp hiện tại:

```text
THỜI GIAN ƯỚC LƯỢNG THIẾT KẾ — CHƯA ĐO THỰC TẾ

[1. Nhận thấy cần khôi phục ngữ cảnh: 1 phút]
→ [2. Mở lịch sử trao đổi: 1 phút]
→ [3. Tìm yêu cầu và quyết định: 3 phút]              ┐
→ [4. Phân biệt thông tin còn hiệu lực/đã bỏ: 2 phút] ├─ BOTTLENECK: 7 phút
→ [5. Tổng hợp và cung cấp lại ngữ cảnh: 2 phút]      ┘
→ [6. Kiểm tra phản hồi, bổ sung nếu thiếu: 1 phút]

Tổng ước lượng thiết kế: 10 phút/lần khôi phục ngữ cảnh.
Token đầu vào, số lần nhắc lại và thời gian sửa phát sinh: chưa đo.
```

### Card muốn pitch nhất

- Card số: **3 — Khó duy trì ngữ cảnh còn hiệu lực khi chat dài hoặc chuyển phiên** (theo hướng học viên đang chuẩn bị trình bày; chưa phải lựa chọn chung của nhóm).
- Vì sao: Học viên đã mô tả rõ tình huống chat dài, yêu cầu thay đổi, quyết định cũ/mới lẫn nhau và công sức cung cấp lại lịch sử. Phạm vi có thể thu hẹp vào khôi phục trạng thái một project; thử ghi chú bàn giao trước khi xây công cụ. Các metric thời gian và token vẫn cần đo.
- Câu hỏi muốn nhóm phản biện: Ghi chú bàn giao có thực sự giảm tổng công sức cập nhật và khôi phục ngữ cảnh không? Làm sao phát hiện thông tin đã hết hiệu lực hoặc quyết định quan trọng bị bỏ sót khi rút gọn lịch sử?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Vấn đề đã gặp là trải nghiệm thật, nhưng baseline chưa đo chưa đủ để kết luận mức độ và hiệu quả giải pháp. | **Đồng ý.** Tôi phân biệt việc đã gặp vấn đề với việc đã có số đo. | Xác nhận sáu vấn đề là trải nghiệm của tôi; bỏ số đếm chưa xác nhận ở CP1 và tách baseline ước lượng khỏi target/cách đo trong CP2. |
| Card 1: lỗi tích hợp có thể do logic hoặc thiếu ngữ cảnh, không chỉ do phiên bản thư viện. | **Đồng ý.** Không quy tất cả lỗi cho thư viện. | Phân biệt nguyên nhân theo log; metric số lượt sửa chỉ tính lỗi tương thích và thêm kiểm tra chức năng liên quan. |
| Card 2: không tìm thấy nguồn chưa chứng minh nguồn không tồn tại; mở được link chưa chứng minh nhận định đúng. | **Đồng ý.** Phải kiểm tra cả thông tin trích dẫn và nội dung. | Dùng “chưa tìm thấy/chưa xác minh”; đối chiếu nguồn với nhận định thay vì chỉ kiểm tra link. |
| Card 3: chỉ đo đầu phiên có thể bỏ qua công sức cập nhật ghi chú cuối phiên. | **Đồng ý.** Cần tính tổng công sức bàn giao. | Bổ sung đo riêng cập nhật và khôi phục ngữ cảnh, tránh tiết kiệm đầu phiên nhưng tốn hơn ở cuối phiên. |
| Card 3: giảm token vẫn có thể bỏ sót yêu cầu hoặc giữ quyết định cũ. | **Đồng ý.** Giữ đúng ngữ cảnh quan trọng hơn chỉ rút ngắn nội dung. | Thêm trạng thái còn hiệu lực/phương án đã bỏ, checklist yêu cầu và người dùng duyệt trước khi lưu. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Phần dưới ghi nhận công việc chuẩn bị và biên tập tôi đã thực hiện với AI trong phiên làm báo cáo. Câu hỏi chuẩn bị không được ghi thành câu hỏi đã hỏi trong buổi nhóm; phản biện từ AI được phân biệt với phản biện từ thành viên.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Tôi chuẩn bị Card #3 về duy trì ngữ cảnh khi chat dài hoặc chuyển phiên, bổ sung việc lịch sử lẫn quyết định cũ/mới và đọc lại toàn bộ tốn token; nhờ hỗ trợ diễn đạt để trình bày. | Card #3 của tôi được đưa vào shortlist thứ ba ở mục 2.1 báo cáo nhóm thay đề tài báo cáo kỹ thuật. Đây là phần chuẩn bị và đưa nội dung vào báo cáo, không xác nhận một buổi pitch đã diễn ra. |
| Phản biện bài của bạn khác | Tôi nhờ hỗ trợ chuẩn bị câu hỏi cho các candidate. Với Chợ Vinhomes: thông báo/hashtag đã đủ chưa, bài không nêu món có bị bỏ sót không, lấy nội dung bằng đường nào? Với knowledge công ty: ai cập nhật và xử lý nguồn mâu thuẫn? | Các câu hỏi được đặt trong bảng CP3 như câu hỏi chuẩn bị, không gán tên người hỏi hoặc ghi đã hỏi trực tiếp khi chưa có biên bản. |
| Nhận phản biện | Tôi nhận phản biện từ AI: ghi chú bàn giao có tốn công cập nhật không, giảm token có làm mất yêu cầu quan trọng không; tôi đã xác nhận đồng ý với cả năm phản biện CP2. | Card #3 bổ sung đo tổng công sức cập nhật/khôi phục, phân biệt quyết định còn hiệu lực với phương án đã bỏ và giữ bước người dùng duyệt. Không ghi đây là phản biện đã nhận từ bạn cùng nhóm. |
| Gom cluster / cây OST | Tôi yêu cầu thay candidate thứ ba bằng bài ngữ cảnh của mình; bản cập nhật có AI hỗ trợ đồng bộ cluster C và phần so sánh, giữ cây OST tập trung vào đề tài Vinhomes. | Cluster C mô tả pain duy trì ngữ cảnh, khác kho kiến thức công ty ở cluster B; không đưa giải pháp ghi chú bàn giao vào làm tên opportunity. |
| Chọn candidate problem | Tôi đề nghị Card #3 của mình xuất hiện trong shortlist, đồng thời yêu cầu hoàn thiện báo cáo chung theo đề tài Chợ Vinhomes và tài liệu định hướng đã cung cấp. | Bài ngữ cảnh là candidate so sánh; đề tài chung vẫn là người bán đồ ăn theo dõi group. Không đồng nhất card tôi muốn pitch với đề tài nhóm đã chọn. |
| Kiểm chứng / research | Tôi cung cấp tài liệu định hướng, yêu cầu AI đối chiếu giải pháp hiện có và biên tập phần nhận định định tính; tôi không thực hiện survey hoặc phỏng vấn trong quá trình làm báo cáo này. | Báo cáo có research công cụ kèm nguồn, phân biệt claim nhà cung cấp với kết quả thử nghiệm. Phần trải nghiệm chỉ là nhận định định tính, không ghi số người đã hỏi hoặc lời phỏng vấn không tồn tại. |
| Quy trình nhóm | Tôi yêu cầu hoàn thiện theo Problem Card người bán đồ ăn, sử dụng thời gian ước lượng cho quy trình trước/sau. AI hỗ trợ vẽ sơ đồ và đồng bộ bottleneck. | Báo cáo xác định bước mở/lướt và đọc/lọc là bottleneck của mô hình: 5 phút/lượt × 12 lượt/ngày = 60 phút/ngày, mục tiêu 30 phút/ngày. Đây là ước lượng thiết kế, chưa phải hiệu quả đo được. |
| Problem Statement | Tôi nhờ AI hoàn thiện CP5–CP6 theo mẫu và giữ đúng trọng tâm nhu cầu ăn uống không nêu tên món; yêu cầu phần cuối chỉ trình bày định hướng phát triển. | v0/v1 có actor, quy trình, bottleneck, impact, metric và boundary; v1 bổ sung chất lượng phân loại, độ bao phủ, độ trễ và người duyệt. Không ghi nhiệm vụ hoàn thiện bài vào mục hướng phát triển. |
| Mức can thiệp AI | Tôi nhờ hỗ trợ phân tích các mức và hoàn thiện phần thiết kế cho trường hợp chưa thực thi. | Báo cáo chọn Workflow có người duyệt ở mức thiết kế, giữ No AI/Rule làm đối chứng; không đề xuất Agent hoặc tự động bình luận/chốt đơn. Hiệu quả vượt đối chứng vẫn là điều cần đánh giá khi thử. |
| Quyết định | Tôi yêu cầu làm rõ ý nghĩa việc chọn candidate và quyết định triển khai, sau đó hoàn thiện phần kết luận cùng các điều kiện thử/dừng. | Báo cáo phân biệt chọn đề tài để nghiên cứu với triển khai trực tiếp; kết luận Not Yet cho Facebook trực tiếp và nêu hướng thử ngoại tuyến, không tuyên bố hệ thống đã chạy thành công. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi mở, hỗ trợ rà lại các vấn đề tôi đã gặp khi sử dụng AI và diễn đạt thành Job Story. | Giúp sắp xếp trải nghiệm thành 6 candidate theo các lăng kính, làm rõ tình huống, nhu cầu và kết quả mong muốn; phân biệt vấn đề với giải pháp. | Ban đầu gợi ý chưa sát bối cảnh sử dụng AI của tôi; có lúc dùng việc chỉnh báo cáo/tìm file thay cho vấn đề cần phân tích và mô tả các vấn đề như tình huống dựng, chưa phản ánh đúng trải nghiệm tôi xác nhận. | Tôi yêu cầu tập trung vào bối cảnh AI và xác nhận cả 6 vấn đề đều đã gặp. Tôi bổ sung chi tiết về chat dài, quyết định cũ/mới và công sức đọc lại lịch sử; giữ cách diễn đạt phù hợp trải nghiệm và bỏ những mô tả lệch bối cảnh. |
| CP2 Problem Card | Nhờ AI hỗ trợ triển khai 3 card, vẽ quy trình hiện tại và phản biện metric, phương án không dùng AI. | Làm rõ actor, bước nghẽn và cách đo; bổ sung chi phí cập nhật ghi chú, chất lượng ngữ cảnh và token đầu vào cho Card #3. | Bản đầu Card #3 chỉ tập trung chuyển phiên, chưa bao quát việc bỏ sót ngữ cảnh ngay trong chat dài. Ban đầu AI mô tả cả vấn đề như tình huống dựng, trong khi tôi xác nhận đã gặp; thời gian từng bước vẫn chỉ là ước lượng thiết kế, chưa chứng minh mức giảm kỳ vọng. | Đã yêu cầu bổ sung tình huống chat dài bị quên ngữ cảnh, khó tổng hợp lịch sử và tốn token khi đọc lại toàn bộ. Card #3 và candidate CP1 tương ứng đã được đồng bộ. Tôi đã xác nhận cả sáu vấn đề là trải nghiệm của mình và đồng ý với cả năm phản biện; báo cáo tách việc đã gặp vấn đề khỏi số liệu chưa đo. |
| CP4 Research | Nhờ AI tìm nguồn công khai về các phương án theo dõi nhu cầu, đọc tài liệu và đối chiếu với tài liệu định hướng tôi cung cấp. | Tổng hợp Google Forms, n8n, Groups Watcher, GrabFood, Vinhomes Resident và giới hạn tích hợp group; có link cho các claim công cụ. | Bản phân tích ban đầu chưa bám đầy đủ danh sách và trọng tâm tài liệu tôi đưa; thông tin về sản phẩm có thể thay đổi, không thể chỉ dùng mô tả cũ hoặc coi quảng cáo là kết quả kiểm thử. | Tôi gửi tài liệu định hướng và yêu cầu làm lại theo đó. Bản research được đối chiếu nguồn hiện tại, bỏ khẳng định phí chung chưa xác minh và phân biệt nghiên cứu công cụ với kiểm chứng người dùng; không ghi là tôi đã tự thử các sản phẩm. |
| CP5 Quy trình | Nhờ AI diễn đạt quy trình hiện tại/tương lai thành sơ đồ và bổ sung mô hình thời gian. | Tách bước lướt/đọc, phản hồi, chờ và chốt đơn; chỉ rõ Rule, AI, người duyệt và cách quay về thủ công. | Bản đầu dùng các biến thời gian chưa có giá trị và metric chưa bám mục tiêu giảm một nửa; dễ nhầm thời gian chờ khách với công sức thao tác. | Tôi yêu cầu dùng thời gian ước lượng và bám tài liệu định hướng. AI xây mô hình 60 → 30 phút/ngày; báo cáo ghi rõ là ước lượng thiết kế, tách chờ khỏi thao tác và tính cả công sức nhập/duyệt. |
| CP5–6 Problem Statement | Nhờ AI biên tập v0/v1 theo template và phản biện metric, boundary khi giải pháp chưa thực thi. | Liên kết pain → bottleneck → mục tiêu; v1 có điểm can thiệp, người kiểm tra và tiêu chí phân biệt đạt/không đạt. | AI từng đưa nhiều ghi chú về việc còn phải hoàn thiện báo cáo vào phần cuối; mục tiêu thiết kế và kết quả thực tế cũng cần phân biệt rõ. | Tôi yêu cầu bỏ đường dẫn file ngoài repo, bỏ checklist nộp bài khỏi mục hướng phát triển và chỉ giữ định hướng tương lai. Các số mục tiêu được trình bày như thiết kế, không viết thành kết quả đã đạt. |
| CP6 Mức can thiệp / quyết định | Nhờ AI so sánh No AI/Rule/Workflow/Agent, làm rõ Not Yet và hoàn thiện bốn rủi ro, ngưỡng dừng. | Tách chọn kiến trúc khỏi cho phép triển khai; có phương án đơn giản làm đối chứng và giữ người bán tự phản hồi. | Cách ghi “quyết định đề xuất” ban đầu khiến tôi cần hỏi rõ quan hệ giữa chọn bài toán, chọn giải pháp và triển khai; nguồn dữ liệu đầu vào cũng có thể bị xem nhẹ nếu chỉ chú ý khả năng phân loại. | Tôi hỏi lại ý nghĩa hai quyết định và yêu cầu chốt CP5–CP6 ở mức thiết kế. Báo cáo chọn Workflow có người duyệt, Not Yet cho triển khai trực tiếp và nêu điều kiện về nguồn vào, tổng công sức, chất lượng cùng ngưỡng dừng. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật, tối thiểu 200 từ cho các câu 6.1–6.6; câu 6.7 được chấm riêng. **Không dùng AI để viết thay.**

**Nguồn biên tập:** Bản nháp có AI hỗ trợ từ lịch sử trao đổi, không phải reflection tự viết độc lập.

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Qua đọc các candidate, tôi hiểu cần xác định rõ người dùng và bước nghẽn. Bài ngữ cảnh của tôi khác bài knowledge công ty dù đều liên quan thông tin. Đây là nhận xét từ báo cáo, không phải buổi nghe pitch trực tiếp.

**6.2. Nhóm có lúc nào bị "solution-first" không? Nhận ra và xử lý thế nào?**

Khi chuẩn bị, tôi nhận ra dễ nghĩ ngay đến bot hoặc tóm tắt. Tôi yêu cầu làm rõ chat dài bị mất ngữ cảnh và nhu cầu mua không nêu món, rồi mới xem xét giải pháp và phương án không dùng AI.

**6.3. Tôi có đổi ý sau khi bị phản biện không?**

Tôi đồng ý với phản biện của AI rằng ghi chú bàn giao phải tính cả công sức cập nhật cuối phiên. Tôi bổ sung cách đo tổng công sức và kiểm tra yêu cầu bị bỏ sót, thay vì chỉ quan tâm thời gian đầu phiên và token.

**6.4. Kết quả research có làm tôi bất ngờ không?**

Từ research có AI hỗ trợ, tôi thấy hiểu đúng nội dung chưa đủ nếu không nhận được bài kịp thời và phù hợp quyền sử dụng. Công cụ sẵn có cũng cần được so sánh trước khi tự xây. Tôi chưa thực hiện phỏng vấn hoặc thử sản phẩm.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là phân biệt trải nghiệm thật, baseline ước lượng và kết quả đã đo. Tôi đã hỏi lại ý nghĩa Not Yet để hiểu rằng chọn vấn đề nghiên cứu chưa đồng nghĩa được triển khai. Mục tiêu 60 xuống 30 phút/ngày vẫn là kỳ vọng.

**6.6. Nếu làm lại, tôi sẽ đổi gì?**

Tôi sẽ xác định phạm vi và ghi thời gian sớm hơn, bám template ngay từ đầu. Tôi muốn phản biện kỹ nguồn dữ liệu, tổng công sức nhập/duyệt và khả năng dùng cách đơn giản, tránh chỉ chú ý tính năng AI hoặc tốc độ xử lý.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định*.

Người bán trong group Chợ Vinhomes phải liên tục đọc bài để tìm nhu cầu ăn uống. Quy trình gồm mở group, lọc nhu cầu, phản hồi, chờ khách và chốt đơn. Bottleneck là lặp việc mở/lướt và đọc bài khi đang nấu hoặc giao. Baseline thiết kế ước lượng 60 phút/ngày, mục tiêu 30 phút/ngày và số đơn không giảm; chưa có kết quả đo. AI chỉ xử lý dữ liệu được phép, không tự nhắn tin, bình luận hoặc chốt đơn. Thiết kế chọn Workflow có người bán duyệt, so sánh với No AI/Rule. Quyết định là Not Yet cho triển khai trực tiếp, ưu tiên đánh giá nguồn dữ liệu và thử ngoại tuyến.

---

## 7. Tài liệu tham khảo

- [Worksheet CP1–CP2: cách scan, viết card và phản biện](../../docs/01-worksheet.md).
- [Framework của lab: Double Diamond, Job Story và phân biệt mức can thiệp](../../docs/03-international-frameworks.md).
- [Rubric: dấu hiệu thật, 3 card, thời gian và bottleneck](../../RUBRIC.md).
- Nguồn tình huống cá nhân: tôi xác nhận đã gặp cả sáu vấn đề trong phiên hỗ trợ báo cáo; riêng Card #3 được tôi mô tả chi tiết về chat dài và chuyển phiên. Chưa có bộ dữ liệu định lượng để xác nhận tần suất, thời gian hoặc chi phí.
