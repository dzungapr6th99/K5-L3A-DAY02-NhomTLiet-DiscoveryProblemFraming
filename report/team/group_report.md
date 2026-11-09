# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm T Liệt
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Người bán đồ ăn trong group Facebook Chợ Vinhomes phải thường xuyên trực và lướt group để phát hiện kịp bài tìm món phù hợp với món mình bán.
- Quyết định cuối: Chưa chốt Go / Not Yet / No-Go; lựa chọn đề tài ở CP3 chưa thay thế việc kiểm chứng và đánh giá ở CP4–CP6.

---

## 2. Hội tụ nhóm (CP3)

Theo kết quả lựa chọn do nhóm cung cấp, shortlist gồm 3 đề tài bên dưới; đề tài được chọn để đào sâu là người bán đồ ăn phải trực group Chợ Vinhomes. Đề tài knowledge công ty được gộp từ vấn đề tổng hợp/tra cứu thông tin của Nguyễn Tuấn Dũng và câu hỏi HR lặp lại của Khuất Tiến Minh. Đề tài thứ ba là ý #3 của CP1 của Trần Tuấn Đăng: chuẩn bị báo cáo kỹ thuật sau khi hoàn thành task code hoặc module AI (được phát triển thành Card #2 ở CP2).

Phần này tổng hợp từ báo cáo cá nhân và quyết định nhóm đã cung cấp, không phải biên bản đầy đủ các lượt pitch. Các điểm số và lý do so sánh bên dưới là bản nháp đề xuất để nhóm xác nhận; chưa có dữ liệu phỏng vấn hay nhật ký câu hỏi phản biện thực tế.

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Minh Thông — Card #1 | Khi cư dân đăng bài tìm món trong group Chợ Vinhomes, người bán muốn phát hiện kịp bài phù hợp, để có thể phản hồi mà không phải lướt group liên tục. | Người bán đồ ăn trong group; cần xác định khu Vinhomes và loại món cụ thể. | Theo dõi group và đọc các bài để tìm nhu cầu phù hợp; thời gian thực tế chưa đo. | Chưa có ghi chép câu hỏi và người hỏi; nhóm bổ sung sau buổi pitch. |
| 2 | Nguyễn Tuấn Dũng + Khuất Tiến Minh — gộp thành đề tài knowledge công ty | Khi cần hiểu quyết định dự án hoặc quy định nội bộ, nhân viên muốn tìm được thông tin có căn cứ và còn hiệu lực, để làm đúng việc mà không phải hỏi lại PIC hoặc HR nhiều lần. | Nhân viên, người mới, PIC và HR. | Tìm thông tin rải rác, xác minh nguồn và chờ người phụ trách giải thích; chưa có số đo chung. | Chưa có ghi chép câu hỏi và người hỏi; nhóm bổ sung sau buổi pitch. |
| 3 | Trần Tuấn Đăng — CP1 ý #3, CP2 Card #2 | Khi hoàn thành một task code hoặc module AI, tôi muốn có sẵn khung báo cáo kỹ thuật (annotated Markdown), để điền ngay kết quả mà không mất công nghĩ cách trình bày. | Học viên, sinh viên, lập trình viên; mentor/giảng viên là người đọc. | Tổng hợp log, trình bày code và giải thích logic; CP1 nêu 45–60 phút/báo cáo, Card #2 xác định phần viết giải thích khoảng 30 phút. Đây là số liệu trong báo cáo cá nhân, chưa kiểm chứng ở CP4. | Chưa có ghi chép câu hỏi và người hỏi; nhóm bổ sung sau buổi pitch. |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Phát hiện nhu cầu mua món | Người bán đồ ăn phải trực group Chợ Vinhomes — Nguyễn Minh Thông. | Nhu cầu phù hợp xuất hiện giữa nhiều bài đăng; người bán phải liên tục theo dõi để phát hiện kịp. |
| B — Knowledge công ty | Tra cứu/tổng hợp thông tin và lý do quyết định dự án — Nguyễn Tuấn Dũng; HR trả lời câu hỏi chính sách lặp lại — Khuất Tiến Minh. | Nhân viên khó tìm được thông tin có nguồn, còn hiệu lực; phụ thuộc vào người đang nắm kiến thức để giải thích lại. |
| C — Báo cáo kỹ thuật | Chuẩn bị báo cáo sau khi hoàn thành task code hoặc module AI — Trần Tuấn Đăng, CP1 ý #3 / CP2 Card #2. | Phải gom kết quả thực thi, log và code rồi tổ chức thành báo cáo có phần giải thích logic rõ ràng. |

**Ranh giới đề tài B:** Gộp nhu cầu tra cứu kiến thức và chính sách nội bộ. Không gộp nghiệp vụ kiểm tra chấm công, tính phép, tính lương hoặc phê duyệt nhân sự vào cùng phạm vi. Kiến thức kỹ thuật và chính sách HR vẫn cần chủ sở hữu, nguồn và quyền truy cập riêng.

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian người bán phải trực group Chợ Vinhomes
         mà vẫn phát hiện kịp các bài tìm món phù hợp.
         Baseline, target và cách đo cụ thể: cần bổ sung sau CP4.
├── Opportunity A: Bài tìm món phù hợp nằm lẫn giữa nhiều bài không liên quan.
├── Opportunity B: Người bán khó nắm được bài mới khi đang chuẩn bị hoặc giao đồ ăn.
└── Opportunity C: Người bán phải đọc nội dung và đối chiếu với món mình đang bán.
```

Các nhánh trên là giả định cần kiểm chứng ở CP4; cây chỉ tập trung vào đề tài đã chọn, không trộn ba nhóm người dùng khác nhau vào một outcome.

Ví dụ cần loại khỏi tầng opportunity nếu xuất hiện khi thảo luận (chưa có biên bản xác nhận nhóm đã nêu các ý này): “bot quét group”, “chatbot bán hàng”, “tự động bình luận chào hàng”. Đây là phương án giải quyết, chưa phải nhu cầu hoặc pain.

### 2.4. Chấm điểm shortlist (1–5)

**Điểm đề xuất, chưa phải điểm nhóm đã thống nhất.** Thang điểm 1 = yếu/chưa rõ, 5 = mạnh/rõ. “Pain có bằng chứng” hiện chấm thận trọng theo nội dung báo cáo cá nhân; chưa đề tài nào được xem là đã kiểm chứng với người dùng ở CP4.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1. Người bán đồ ăn trực group Chợ Vinhomes | 4 | 4 | 2 | 4 | 4 | 4 | 3 | 25 |
| 2. Tra cứu knowledge công ty, gồm kiến thức dự án và chính sách HR | 3 | 3 | 2 | 3 | 2 | 4 | 4 | 21 |
| 3. Chuẩn bị báo cáo kỹ thuật sau task code/module AI | 4 | 5 | 3 | 4 | 4 | 4 | 4 | 28 |

**Căn cứ cho điểm đề xuất:**

- Đề tài 1 có người dùng và hoạt động chính tương đối rõ; có thể đo thời gian trực group và độ trễ phát hiện bài. Điểm bằng chứng còn thấp vì báo cáo cá nhân chưa có người bán xác nhận, chưa có số liệu thật; quyền tiếp cận group và khả năng lấy dữ liệu chưa được kiểm tra.
- Đề tài 2 gần trải nghiệm công việc của Dũng và Minh, tuy nhiên, trên thị trường đã có nhiều bên, nhiều công ty đã áp dụng, thậm chí là bán sản phẩm.
- Đề tài 3 là một đề tài rất hay, khi làm ổn sẽ là 1 impact lớn, tuy nhiên về giới hạn công nghệ và kinh nghiệm hiện tại của team vẫn đang chưa đủ khả năng để bàn luận hướng đào sâu về mặt công nghệ.

**Candidate được chọn:** Đề tài 1 — Người bán đồ ăn phải trực group Chợ Vinhomes, theo quyết định nhóm đã cung cấp.

**Vì sao chọn:** Nhóm xác định đây là đề tài khả thi nhất để tiếp tục đào sâu. Lý do chi tiết đề xuất để nhóm xác nhận: có thể giới hạn nghiệp vụ, tệp khác hàng, một nhóm món và một khung giờ bán; hoạt động phát hiện nhu cầu có thể quan sát và đo được. Trước khi chốt hướng giải quyết, phải kiểm chứng người bán thực sự tốn thời gian hoặc bỏ lỡ bài phù hợp, và nhóm có cách tiếp cận dữ liệu được phép.

Trong bảng điểm đề xuất, đề tài 3 đang cao hơn đề tài 1 vì báo cáo cá nhân mô tả quy trình và thời gian rõ hơn. Nhóm giữ lựa chọn đề tài 1 theo quyết định đã cung cấp; cần bổ sung căn cứ thực tế cho việc ưu tiên này sau thảo luận, không điều chỉnh điểm chỉ để khớp lựa chọn.

**Vì sao không chọn các candidate còn lại ở vòng này — lý do đề xuất để nhóm xác nhận:**

- **Knowledge công ty:** Phạm vi sau khi gộp còn rộng; cần tách quyền truy cập, xác định chủ sở hữu và tình trạng cập nhật của từng nguồn. Có thể quay lại nếu thu hẹp được vào một loại câu hỏi và có tài liệu thực tế để kiểm chứng. Ngoài ra trên thị trường, Odoo hay Jira cũng đều đã có chức năng này
- **Báo cáo kỹ thuật:** Cần phân biệt thời gian định dạng với thời gian tự hiểu và giải thích code; template có thể xử lý phần cấu trúc nhưng chưa rõ giảm được bao nhiêu thời gian. Nếu dùng AI soạn nháp, phải kiểm tra độ chính xác và quy định cho phép dùng AI của từng loại báo cáo. Đây vẫn là candidate khả thi, chưa có căn cứ kết luận kém hơn đề tài 1 về mọi tiêu chí.

**Xử lý bất đồng (nếu có):** Chưa có thông tin về bất đồng hoặc cách nhóm xử lý; nhóm bổ sung theo thảo luận thực tế.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
