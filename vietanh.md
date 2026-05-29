# 01 — Individual Problem Scan

> Phần cá nhân: scan rộng ≥ 5 problems từ trải nghiệm thật, chọn top 3 và phác thảo workflow trước/sau.
> Mạch tư duy: **Problem-first, not AI-first** — quan sát pain → vẽ workflow → định lượng → mới nghĩ tới Rule / Workflow / Agent.

## Bảng scan (10 problems — vượt mức tối thiểu 5 để lấy bonus)

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI tốt hơn | Kho note công nghệ (framework/library/tin GitHub-FB) trong app note mobile phình to, không cấu trúc, không tìm theo ngữ nghĩa được → khi cần dùng lại rất khó tìm | Bản thân tôi; các bạn dev hay lưu note tản mạn | ⚠️ ~5–15 phút/lần tìm lại; phần lớn note không bao giờ dùng lại ("note chết") |
| 2 | Lặp lại / Pain người khác | Tìm lại quyết định/câu trả lời cũ của GV/TA trong Discord lớp đã trôi mất → phải hỏi lại câu đã có đáp án | SV trong lớp; TA (phải trả lời lại) |  ~10–15 phút/lần; nhiều SV cùng gặp; câu hỏi lặp trong kênh |
| 3 | Tốn thời gian | Tự setup môi trường (cài đặt, dependency, config) + debug lỗi trước mỗi buổi lab/dự án mới | SV làm lab; người mới onboard |  ~20–40 phút/buổi, đôi khi cả buổi; thời gian lab ngắn nên trễ nội dung chính |
| 4 | Tốn thời gian / AI tốt hơn | Tổng hợp tài liệu dài để học/ôn — bị chặn vì không tải được PDF để nạp vào NotebookLM | SV trước deadline |  tài liệu dài; mất thời gian đọc & tóm tắt thủ công; tool bị chặn input |
| 5 | Lặp lại | Mất tập trung khi học/làm sâu — chỉ ~30 phút là tâm trí phân tán sang việc khác | Bản thân tôi |  chu kỳ tập trung ~30 phút; nhiều lần/ngày; kéo dài thời gian hoàn thành |
| 6 | Tốn thời gian | Trì hoãn task phức tạp cần kiến thức rộng để hiểu vấn đề & xác định giải pháp | Bản thân tôi |  trì hoãn vài giờ→vài ngày trước khi bắt đầu task khó |
| 7 | Lặp lại / Pain người khác | App điểm danh phức tạp, hay lỗi | Cả lớp; người vận hành |  lỗi lặp mỗi buổi; tốn thời gian thao tác lại |
| 8 | AI tốt hơn | Lượng kiến thức nhiều, thời gian lab ngắn → khó biết học gì trước, ưu tiên ra sao | SV trong khóa |  cảm giác quá tải; không có lộ trình ưu tiên rõ |
| 9 | Pain từ người khác | Chênh lệch tốc độ tiếp thu trong lớp đa độ tuổi; lớp đông khó theo sát từng người | SV tiếp thu chậm hơn; GV/TA |  một số bạn bị bỏ lại; cần chia nhóm nhỏ |
| 10 | Lặp lại / Tốn thời gian | Theo dõi framework/library mới liên tục nhưng không có cách triage → lưu rồi quên, không bao giờ thử lại | Bản thân tôi |  lưu nhiều, dùng lại rất ít; bỏ lỡ công cụ hữu ích |

> Ghi chú phân loại: #5, #6 (tập trung, trì hoãn) là pain thật nhưng **khó vẽ workflow và khó đo + AI-fit mờ** → để trong scan cho đầy đủ, không đưa vào top 3. #7 (app điểm danh) bản chất là lỗi kỹ thuật/UX → **giải pháp non-AI (sửa app)** hợp hơn, không phải bài toán AI. #9 là vấn đề hệ thống/giáo vụ, quá rộng cho một buổi lab. #4 và #10 thực chất là biến thể của cùng cụm "tổng hợp & truy vấn tri thức" với #1.

### Vì sao phần scan này mạnh

- Scan rộng (10 > 5) **trước** khi hội tụ, dùng đủ 4 lăng kính.
- Mỗi problem có **actor** và **dấu hiệu thật**, không phải ý chung chung.
- Không bắt đầu bằng "làm chatbot/agent" — bắt đầu từ pain, workflow, bottleneck.
- Có ghi rõ **vì sao loại** một số problem (tập trung, app điểm danh, chênh lệch tiếp thu) → thể hiện tư duy sàng lọc, không gom bừa.
- Top 3 đa dạng về cấp độ giải pháp: 1 bài thiên Workflow, 1 bài impact rộng nhiều người, 1 bài là ví dụ "Rule không kém AI".

## Top 3 (chọn để pitch với nhóm)

Tiêu chí chọn: actor rõ · workflow vẽ được · bottleneck cụ thể · impact đo được · so sánh được Rule/Workflow/Agent · không quá rộng cho 1 buổi lab.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | **Kho note công nghệ khó truy vấn** ([card 1](./problem-card-1-tech-notes.md)) | Pain rất cá nhân & thật; workflow rõ; đo được bằng thời gian tìm lại + tỷ lệ note dùng lại; so sánh Rule/Workflow/Agent đầy đủ; khác biệt với ví dụ mẫu | "Note dùng lại được" định nghĩa & đo thế nào cho khách quan |
| 2 | **Tìm lại câu trả lời cũ trong Discord lớp** ([card 2](./problem-card-2-discord-search.md)) | Nhiều người cùng đau (impact rộng); baseline thời gian rõ; dễ validate nhanh với bạn cùng lớp | Quyền truy cập lịch sử Discord; trùng hướng với case TA trong bài giảng nên cần làm rõ góc nhìn riêng |
| 3 | **Setup môi trường lab mất thời gian** ([card 3](./problem-card-3-env-setup.md)) | Baseline & before/after rất rõ; là ví dụ tốt cho thông điệp "Rule không kém AI"; gắn trực tiếp với pain "thời gian lab ngắn" | Lỗi môi trường đa dạng theo máy/OS → khó chuẩn hóa hoàn toàn |

## Card tôi muốn pitch nhất

Vì sao:

```
Đây là pain tôi gặp thật mỗi tuần, có workflow rõ và đo được bằng thời gian tìm lại 
note + tỷ lệ note dùng lại. Nó cũng khác với ví dụ mẫu (weekly report) nên dễ thể hiện
"scan từ trải nghiệm thật", và so sánh được cả 3 mức Rule / Workflow / Agent.
```

Câu hỏi tôi muốn nhóm challenge:

```
- "Note được dùng lại" đo khách quan thế nào (đánh dấu note đã mở/dùng trong 1 tháng)?
- Chỉ cần chuẩn hóa format + tag + app search tốt (Rule) đã đủ chưa, có thật cần AI semantic search không?
```

## Files trong thư mục này

- `README.md` — file này (bảng scan + top 3 + card muốn pitch).
- `problem-card-1-tech-notes.md` — Problem Card #1 + workflow trước/sau.
- `problem-card-2-discord-search.md` — Problem Card #2 + workflow trước/sau.
- `problem-card-3-env-setup.md` — Problem Card #3 + workflow trước/sau.
