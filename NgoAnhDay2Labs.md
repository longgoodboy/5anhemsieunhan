# 01 — Individual Problem Scan

## Scan rộng

Dưới đây là bản scan 10 problems tập trung vào các lĩnh vực: phát triển phần mềm AI (xử lý âm thanh/nhận diện cảm xúc), quản lý dự án học tập (chu trình PDCA), kỹ năng học tiếng Anh (IELTS), và giao tiếp/quy chuẩn trong môi trường học thuật/làm việc.

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
| --- | --- | --- | --- | --- |
| 1 | Lặp lại | Viết báo cáo tiến độ tuần (Weekly Progress) cho bài báo khoa học dựa trên chu trình PDCA của nhóm 6-7 người. | Trưởng nhóm, Thành viên | Mất 60-90 phút mỗi cuối tuần để tổng hợp chat, file |
| 2 | Lặp lại | Format và chuẩn hóa tài liệu tham khảo (Citation/References) theo chuẩn APA/IEEE khi viết paper. | Thành viên viết bài | Mất 30 phút mỗi lần cập nhật danh mục tài liệu |
| 3 | Tốn thời gian | Đọc và tóm tắt các nghiên cứu nền tảng (Literature Review) về Wav2vec 2.0 và module nhận diện cảm xúc. | Sinh viên nghiên cứu | 45-60 phút cho mỗi paper tiếng Anh chuyên ngành |
| 4 | Tốn thời gian | Chuyển đổi dữ liệu nhãn âm thanh thô (raw audio labels) sang định dạng ma trận cấu trúc để huấn luyện mô hình. | Sinh viên xử lý AI | 30-40 phút viết script xử lý thủ công cho mỗi tập dữ liệu mới |
| 5 | AI có thể tốt hơn | Viết nhận xét, phản biện (Peer-review) nội dung học thuật cho các thành viên khác trong nhóm. | Người review | Nhận xét dễ bị chung chung, thiếu tính đóng góp sâu |
| 6 | AI có thể tốt hơn | Luyện viết IELTS Writing Task 2 nhưng không có feedback chi tiết về từ vựng học thuật và tính mạch lạc (Coherence). | Bản thân | Điểm viết dậm chân tại chỗ, không rõ lỗi sai cụ thể |
| 7 | Pain từ người khác | Thành viên trong nhóm nộp bài muộn hoặc sai format quy định của "Special Subject 1". | Trưởng nhóm | Phải nhắn tin nhắc nhở, sửa format thủ công 2-3 lần |
| 8 | Pain từ người khác | Khách hàng/Giảng viên thay đổi yêu cầu về các module chức năng (Capture, Emotion, Admin Dashboard). | Cả nhóm dự án | Phải sửa lại sơ đồ kiến trúc hệ thống và PRD từ đầu |
| 9 | Tốn thời gian | Tìm kiếm và tổng hợp các tiêu chuẩn ứng xử, văn hóa doanh nghiệp/học thuật phục vụ bài luận. | Bản thân | Mất nhiều thời gian lọc giữa các nguồn tài liệu rời rạc |
| 10 | Lặp lại | Viết email/tin nhắn cập nhật tiến độ hàng ngày (Daily Standup) bằng tiếng Anh chuyên ngành. | Bản thân, Thành viên | Mất 10-15 phút suy nghĩ từ vựng phù hợp |

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
| --- | --- | --- | --- |
| 1 | **Tổng hợp Weekly Progress Paper (PDCA)** | Workflow lặp lại rõ ràng, tốn thời gian của nhóm đông người (6-7 thành viên), có metric baseline tốt. | Cách định lượng "chất lượng insight" của báo cáo thế nào là đủ tốt. |
| 2 | Đọc & Tóm tắt Paper AI (Wav2vec 2.0) | Tần suất cao trong giai đoạn nghiên cứu, cản trở tốc độ làm dự án. | Khó đo lường độ chính xác của các thuật ngữ chuyên sâu về audio. |
| 3 | Sửa lỗi format/Nhắc nhở thành viên | Gây ức chế tâm lý, ảnh hưởng đến tiến độ chung của "Special Subject 1". | Phụ thuộc nhiều vào ý thức con người, khó tự động hóa hoàn toàn. |

## Problem Card #1 — Weekly Progress Report (Dự án Nghiên cứu AI)

**Problem 1 câu:** Mỗi tuần, trưởng nhóm mất hơn 80 phút để thu thập, phân loại và tổng hợp báo cáo tiến độ thủ công từ 6-7 thành viên (theo chu trình PDCA), dẫn đến việc báo cáo gửi giảng viên thường bị trễ hoặc thiếu các phân tích sâu về rủi ro kỹ thuật.

**Actor:** Trưởng nhóm sinh viên (hoặc thành viên phụ trách điều phối) môn Special Subject 1.

**Thời điểm / bối cảnh:** Tối Chủ nhật hàng tuần, trước buổi họp sync đầu tuần với Giảng viên/Mentor.

**Current workflow:**

```text
1. Nhắc nhở thành viên nộp update qua chat nhóm (Slack/Zalo).
2. Thu thập dữ liệu từ Sheet tiến độ và các file draft của từng module (Capture, Emotion, Dashboard).
3. Phân loại thông tin theo 4 bước PDCA (Plan - Do - Check - Act).
4. Viết phần Narrative: Nhận định tiến độ, highlight các rủi ro kỹ thuật (ví dụ: lỗi xử lý nhiễu âm thanh, model overfit).
5. Định dạng lại văn bản theo template chuẩn học thuật.
6. Gửi báo cáo qua Email/LMS cho Giảng viên.

```

**Bottleneck:** Bước 4 — Biến các dòng cập nhật ngắn, rời rạc của các thành viên (ví dụ: "đang làm module emotion", "fix xong bug dashboard") thành một đoạn đánh giá narrative có cấu trúc, chỉ ra được **Risk** và **Next Action** cụ thể. Bước này mất khoảng 30 phút và dễ bị thiếu sót thông tin.

**Impact:** Mất 80-90 phút/tuần của trưởng nhóm. Báo cáo chất lượng thấp khiến giảng viên khó theo dõi tiến độ thực tế, nhóm không nhận được feedback đúng hướng.

**Success metric:** Giảm tổng thời gian tổng hợp xuống dưới **25 phút/tuần**. Đảm bảo 100% báo cáo chỉ ra được ít nhất 1 Risk kỹ thuật chính xác và Next Action tương ứng cho tuần tới.

**Non-AI alternative:** Tạo một Google Form bắt buộc điền đúng cấu trúc PDCA. Cách này giảm công sức phân loại nhưng không giải quyết được việc *tổng hợp mối liên hệ* giữa các module (ví dụ: Module Capture chậm sẽ ảnh hưởng trực tiếp đến Module Emotion).

**AI hypothesis:** AI hỗ trợ đọc các dữ liệu thô từ các module, kết nối ngữ cảnh để draft phần narrative (Đánh giá, Rủi ro, Giải pháp). Con người đóng vai trò kiểm chứng kỹ thuật.

**Quick gut:** Workflow.

---

# 02 — Group Problem Statement

## Group convergence (Hội tụ nhóm)

Nhóm thảo luận và gom các bài toán cá nhân vào 4 cụm lớn:

| Cluster | Candidate examples | Pattern chung |
| --- | --- | --- |
| **Báo cáo / Tổng hợp** | **Weekly Progress Paper (PDCA)**, Báo cáo lab, Biên bản họp nhóm | Gom thông tin từ nhiều nguồn/thành viên để tạo ra một văn bản tổng hợp có giá trị đánh giá. |
| Tìm kiếm / Tra cứu | Tra cứu tài liệu thuật toán, Tìm tài liệu tham khảo cũ | Tìm kiếm thông tin chính xác trong kho lưu trữ. |
| Đánh giá / Phản biện | Đọc thử PRD, Review code module AI, Check lỗi ngữ pháp | So sánh một bản nháp với một bộ tiêu chuẩn có sẵn. |

## Shortlist và score

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Weekly Progress (PDCA)** | 5 | 5 | 5 | 5 | 5 | 5 | 5 | **35** |
| Đọc & Tóm tắt Paper AI | 4 | 4 | 4 | 4 | 5 | 4 | 4 | 29 |
| Review code module | 4 | 3 | 3 | 4 | 4 | 4 | 4 | 26 |

**Nhóm chọn:** Weekly Progress Report (Theo chu trình PDCA cho dự án AI nhóm).

## Research giải pháp (Kết quả nghiên cứu)

* **Notion AI / Google Docs AI:** Tóm tắt văn bản tốt nhưng không tự động kết nối dữ liệu từ nhiều file/nguồn rời rạc của các thành viên nếu không gom chung vào một chỗ.
* **Z मिळा / Slack Reminders (Rule):** Chỉ giải quyết được bước nhắc nhở nộp bài đúng hạn, không giúp ích cho việc viết nội dung.
* **Pattern tối ưu phát hiện được:** Dùng một quy trình **Workflow** cố định: Gom data thô $\rightarrow$ Dùng Prompt cấu trúc hóa theo 4 bước PDCA $\rightarrow$ AI sinh bản nháp Narrative $\rightarrow$ Trưởng nhóm bổ sung/kiểm định chuyên môn.

## Workflow before/after

```text
CURRENT STATE — 80 phút
[1 Nhắc thành viên: 10'] 
→ [2 Gom số liệu/file thô: 15'] 
→ [3 Phân loại theo PDCA: 15'] 
→ [4 Viết Narrative (Highlight/Risk): 30'] <-- BOTTLENECK
→ [5 Format & Gửi: 10']

FUTURE STATE — 20 phút
[1 Rule/Template tự động nhắc & thu thập: 5'] 
→ [2 AI phân loại và cấu trúc thông tin: 2'] 
→ [3 AI draft Narrative (Insight/Risk): 3'] 
→ [4 Trưởng nhóm Review & Chỉnh sửa kỹ thuật: 8'] <-- HUMAN BOUNDARY
→ [5 Gửi báo cáo: 2']

```

## Problem Statement v1

* **Actor:** Trưởng nhóm/Thành viên điều phối dự án nghiên cứu AI (6-7 người).
* **Workflow:** Nhắc nhở $\rightarrow$ Thu thập data thô từ các module $\rightarrow$ Phân loại PDCA $\rightarrow$ Viết narrative (Insight/Risk) $\rightarrow$ Review $\rightarrow$ Gửi.
* **Bottleneck:** Viết nhận định tổng quan và phát hiện rủi ro từ dữ liệu thô của các module (mất 30 phút, dễ bỏ sót lỗi kỹ thuật).
* **Success Metric:** Thời gian hoàn thành < 25 phút; Giảng viên không đánh giá báo cáo là "chung chung/thiếu thực tế".
* **Boundary:** AI không tự ý gửi báo cáo khi chưa có người duyệt; không tự bịa ra tiến độ (hallucination) của các module chưa nộp bài.
* **Mức chọn:** **Workflow**. Vì tiến độ đi theo các bước tuyến tính, cần sự kết hợp giữa tự động hóa thu thập (Rule) và xử lý ngôn ngữ/ngữ cảnh (AI).

---

# 03 — Individual Reflection (Phản ánh cá nhân)

## Đóng góp của bạn trong nhóm

* **Đóng góp ý tưởng:** Đưa bài toán thực tế từ dự án "Special Subject 1" và chu trình PDCA vào buổi thảo luận, giúp nhóm có một domain cụ thể, thực tế để giải quyết.
* **Xây dựng Workflow:** Trực tiếp phác thảo cấu trúc các module (Voice Capture, Emotion Detection, Admin Dashboard) để làm dữ liệu đầu vào (Input data) cho bài toán ví dụ của nhóm, giúp prompt của nhóm sát với thực tế hơn.
* **Phản biện (Challenge):** Thuyết phục nhóm hạ cấp độ giải pháp từ "Agent" (tự động phân tích và chat với thành viên) xuống "Workflow" (AI draft + Human review) để kiểm soát rủi ro AI tự bịa tiến độ kỹ thuật.

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
| --- | --- | --- | --- | --- |
| **Problem Scan** | Gợi ý các problem thực tế xoay quanh vai trò sinh viên ngành IT làm dự án. | Gợi ý tốt các vấn đề về định dạng tài liệu học thuật và viết standup chuyên ngành. | Một số gợi ý quá chung chung như "quản lý thời gian học tập". | Loại bỏ các ý mơ hồ, giữ lại các ý có workflow đo đạc được thời gian. |
| **Workflow State** | Chuyển đổi mô tả luồng công việc thành định dạng text trực quan. | Tiết kiệm thời gian căn chỉnh các mũi tên biểu đồ. | AI gộp chung bước "phân loại dữ liệu" và "viết narrative" làm một. | Tách đôi hai bước này vì bước viết narrative mới là bottleneck thực sự. |

## Bài học rút ra

1. **Problem-driven, không phải Technology-driven:** Một bài toán tốt cần bắt đầu từ một nỗi đau có thật (mất thời gian viết báo cáo PDCA hàng tuần), có số liệu chứng minh (80 phút), chứ không phải cố tìm cách ứng dụng AI cho "ngầu".
2. **Điểm chặn con người (Human Boundary) là bắt buộc:** Đối với các báo cáo học thuật hoặc dự án kỹ thuật, AI rất dễ sinh ra các câu từ mượt mà nhưng rỗng tuếch (hallucination). Người trưởng nhóm bắt buộc phải giữ vai trò review kỹ thuật ở bước cuối cùng.
3. **Sự kết hợp giữa Rule và AI:** Không nhất thiết bước nào cũng cần AI. Bước nhắc nhở và gom file dùng template/rule là đủ; hãy để dành "năng lượng" của AI cho bước xử lý ngữ cảnh và viết bản nháp narrative.
