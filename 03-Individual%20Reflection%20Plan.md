# 03 — Individual Reflection Plan cho nhóm 5 người

## Phân công tổng thể

| Thành viên | Vai trò chính | Nhiệm vụ chính | Output nên có |
|---|---|---|---|
| **Long** | Coordinator + Problem Statement Owner | Tổng hợp top 3 problems của cả nhóm, chấm điểm shortlist, viết Problem Statement v0/v1/final | Bảng cluster, bảng score, Problem Statement |
| **Ngọc Anh** | Workflow Owner | Vẽ current/future workflow cho bài toán deadline tracker, xác định bottleneck, before/after impact | Mermaid workflow, bảng before/after impact |
| **Việt Anh** | Research Owner | Tìm các tool/case có sẵn như Google Calendar, Todoist, Microsoft To Do, Zapier, Motion/Reclaim | Bảng research giải pháp, research takeaway |
| **Hoàng Anh** | Rule / Workflow / Agent Owner | Phân tích nên dùng Rule, Workflow hay Agent; lập luận vì sao chọn Workflow | Bảng Rule/Workflow/Agent, boundary, risk |
| **Ngô Anh** | Validation + Risk Owner | Làm quick validation, hỏi nhanh bạn bè/sinh viên, tổng hợp feedback, viết exit/rollback | Bảng validation, risk, fallback, final decision |

---

# Reflection cho Long

## Đóng góp của Long trong nhóm

| Hoạt động | Long đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra các problem liên quan đến quản lý thời gian, khóa luận, deadline và lịch học | Nhóm có thêm candidate từ trải nghiệm sinh viên thật |
| Group convergence | Tổng hợp top 3 problems của 5 thành viên | Nhóm có danh sách khoảng 15 candidates để phân cụm |
| Shortlist & score | Chấm điểm các chủ đề theo actor, workflow, pain, impact, lab feasibility, R/W/A và domain fit | Nhóm chọn được problem khả thi nhất: theo dõi & cập nhật deadline từ nhiều nguồn |
| Problem Statement | Viết Problem Statement v0/v1/final | Nhóm có bản mô tả problem rõ actor, workflow, bottleneck, impact, metric và boundary |
| Decision | Chốt scope nhỏ cho MVP | Nhóm tránh làm agent quá rộng và tập trung vào workflow có human review |

## Bảng dùng AI trong reflection của Long

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Scan | Nhờ AI phân nhóm top 3 problems của các file cá nhân | Giúp nhìn ra pattern chung giữa nhiều problem | Một số cluster ban đầu còn rộng như productivity chung chung | Thu hẹp về deadline tracker vì có workflow rõ |
| Shortlist | Nhờ AI tạo bảng chấm điểm | Giúp so sánh các candidate công bằng hơn | Điểm số chỉ là gợi ý, không thay thế quyết định nhóm | Điều chỉnh theo độ dễ research và phù hợp lab |
| Problem Statement | Nhờ AI viết lại problem statement theo mẫu | Giúp field đầy đủ và mạch lạc | AI có xu hướng làm scope lớn hơn, gần giống agent | Giữ boundary: không tự thêm deadline khi chưa xác nhận |
| Decision | Nhờ AI viết final decision và rollback | Giúp nghĩ ra risk và điều kiện dừng | Một số rollback hơi nghiêm ngặt | Chỉnh lại thành pilot nhỏ, dễ đo |

## Bài học của Long

Problem tốt không phải problem nghe “AI” nhất, mà là problem có actor, workflow, bottleneck và metric rõ. Việc chấm điểm giúp nhóm tránh chọn chủ đề quá rộng như AI tutor hoặc agent tự động toàn phần. Với bài deadline tracker, AI chỉ nên hỗ trợ bước trích xuất deadline, còn người dùng vẫn cần review trước khi lưu.

Nếu làm lại, tôi sẽ validate sớm hơn với nhiều sinh viên hơn để baseline thời gian 60–80 phút/tuần có bằng chứng mạnh hơn.

---

# Reflection cho Ngọc Anh

## Đóng góp của Ngọc Anh trong nhóm

| Hoạt động | Ngọc Anh đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra problem về theo dõi deadline từ Discord, Outlook, Zalo, cổng thông tin và ghi chú cá nhân | Problem này được nhóm chọn làm hướng chính |
| Workflow | Mô tả current state gồm mở nhiều nguồn, đọc thông báo, lọc deadline, ghi note, nhập calendar | Nhóm thấy rõ bottleneck nằm ở việc lọc và nhập deadline thủ công |
| Future workflow | Đề xuất workflow mới: paste/import text → AI extract → user review → export calendar/todo | Nhóm có before/after rõ ràng |
| Impact | Ước lượng thời gian trước/sau và số bước thủ công | Nhóm có metric để đánh giá MVP |
| Human boundary | Nhấn mạnh user phải review trước khi lưu deadline | Giảm rủi ro AI nhập sai lịch |

## Bảng dùng AI trong reflection của Ngọc Anh

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Workflow | Nhờ AI chuyển mô tả thành Mermaid | Nhanh hơn khi vẽ current/future workflow | AI đôi lúc gộp bước lọc deadline và nhập calendar | Tách lại để thấy bottleneck rõ hơn |
| Impact | Nhờ AI tạo bảng before/after impact | Có format rõ, dễ đưa vào file markdown | Một số metric chưa sát với sinh viên | Chỉnh lại metric theo thời gian/tuần và số deadline sót |
| Boundary | Nhờ AI gợi ý human review point | Giúp xác định điểm kiểm soát chất lượng | AI đôi khi muốn tự động sync calendar quá sớm | Giữ bước review bắt buộc |
| Fallback | Nhờ AI nghĩ fallback khi extract sai | Có nhiều phương án rollback | Một số fallback quá kỹ thuật | Chọn fallback đơn giản: sửa tay hoặc không lưu |

## Bài học của Ngọc Anh

Vẽ workflow giúp nhóm nhìn rõ AI nên nằm ở đâu. Nếu chỉ nói “AI quản lý deadline” thì scope rất rộng, nhưng khi vẽ từng bước, nhóm thấy phần tốn công nhất là đọc, lọc và chuẩn hóa deadline từ nhiều nguồn. Future state không cần thay thế Google Calendar mà chỉ cần biến text rời rạc thành deadline có cấu trúc.

Nếu làm lại, tôi sẽ đo thử thời gian thật của một tuần học để bảng before/after có dữ liệu đáng tin hơn.

---

# Reflection cho Việt Anh

## Đóng góp của Việt Anh trong nhóm

| Hoạt động | Việt Anh đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra các problem về kho note công nghệ, tìm lại câu trả lời Discord và setup lab | Nhóm có thêm các candidate liên quan đến search và học tập |
| Research | Tìm các giải pháp có sẵn như Google Calendar, Todoist, Microsoft To Do, Zapier, Motion, Reclaim | Nhóm hiểu thị trường đã giải quyết phần nào |
| Gap analysis | So sánh điểm mạnh và khoảng trống của các tool hiện có | Nhóm thấy khoảng trống nằm ở việc gom deadline từ nhiều nguồn text thô |
| Takeaway | Kết luận không nên build calendar app từ đầu | Nhóm tập trung vào AI Deadline Inbox |
| Source quality | Ưu tiên link chính thức của các tool | Bảng research đáng tin hơn |

## Bảng dùng AI trong reflection của Việt Anh

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Research | Nhờ AI gợi ý các tool tương tự | Gợi ý nhanh nhiều nhóm tool: calendar, todo, AI scheduling, automation | Có tool không trực tiếp giải quyết problem sinh viên | Chỉ giữ tool liên quan đến deadline/task/calendar |
| Gap analysis | Nhờ AI phân tích điểm mạnh/khoảng trống | Giúp thấy rõ “storage/scheduling” khác với “extraction” | Một số nhận xét ban đầu hơi chung | Viết lại theo hướng input rời rạc từ Discord/Zalo/LMS |
| Takeaway | Nhờ AI tóm tắt bài học cho nhóm | Có câu chốt tốt cho slide/report | AI có xu hướng nói “build agent” | Sửa thành workflow có review |
| Link/source | Nhờ AI gợi ý link chính thức | Tiết kiệm thời gian tìm nguồn | Cần kiểm lại link và claim | Chỉ dùng link tool chính thức, bỏ số liệu không verify |

## Bài học của Việt Anh

Research không phải để copy sản phẩm có sẵn, mà để hiểu phần nào đã có và phần nào còn trống. Các tool như Google Calendar, Todoist hay Reclaim mạnh ở lưu deadline và lên lịch, nhưng chưa giải quyết tốt việc đọc thông tin deadline rải rác từ Discord, Zalo, email hoặc LMS. Vì vậy, cơ hội của nhóm là làm lớp trung gian: từ scattered messages sang verified deadlines.

Nếu làm lại, tôi sẽ tìm thêm 1–2 case study về student planner hoặc LMS notification để research sát hơn với sinh viên.

---

# Reflection cho Hoàng Anh

## Đóng góp của Hoàng Anh trong nhóm

| Hoạt động | Hoàng Anh đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra các problem về AI learning material finder, AI tutor 24/7 và gym plan cá nhân hóa | Nhóm có thêm candidate về personalization |
| Challenge | Hỏi nhóm liệu deadline tracker có cần agent tự đọc Discord/Zalo không | Nhóm nhận ra scope agent quá rộng và có rủi ro permission |
| Rule / Workflow / Agent | Lập bảng so sánh Rule, Workflow, Agent | Nhóm thống nhất chọn Workflow |
| Boundary | Xác định AI không được tự thêm deadline nếu user chưa xác nhận | Nhóm có boundary rõ ràng |
| Risk | Phân tích hallucination, sai ngày giờ, hiểu sai ngữ cảnh | Nhóm có kế hoạch review và rollback |

## Bảng dùng AI trong reflection của Hoàng Anh

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| R/W/A | Nhờ AI so sánh Rule, Workflow và Agent | Giúp chia rõ mức độ tự động hóa | AI ban đầu có xu hướng chọn Agent vì nghe mạnh hơn | Chỉnh lại: MVP chỉ cần Workflow |
| Risk | Nhờ AI liệt kê rủi ro khi extract deadline | Gợi ý các lỗi như hallucination, sai ngày, bỏ sót yêu cầu phụ | Một số risk quá chung | Gắn risk với ví dụ cụ thể như “thứ sáu tuần này” |
| Boundary | Nhờ AI viết boundary | Giúp câu chữ rõ ràng | AI viết hơi dài và trùng ý | Rút gọn thành không tự lưu, không bịa, không thay user quyết định |
| Decision | Nhờ AI phản biện việc chọn Agent | Giúp nhóm có lý do không chọn Agent | AI chưa biết constraint lab của nhóm | Thêm lý do: permission, privacy, demo khó |

## Bài học của Hoàng Anh

Agent không phải lúc nào cũng là lựa chọn tốt nhất. Với bài này, workflow đã đủ vì đường đi khá tuyến tính: user đưa input, hệ thống trích xuất, user review, rồi mới export. Rule vẫn hữu ích cho bước tách block và xuất file, AI hữu ích ở bước hiểu ngôn ngữ tự nhiên, còn human review là điểm kiểm soát chất lượng.

Nếu làm lại, tôi sẽ đưa thêm ví dụ cụ thể về khi nào rule fail, ví dụ deadline viết mơ hồ như “trước buổi lab sau”.

---

# Reflection cho Ngô Anh

## Đóng góp của Ngô Anh trong nhóm

| Hoạt động | Ngô Anh đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Đưa ra các problem về feedback không nhất quán, thành viên trì hoãn và đi học mất thời gian | Nhóm có thêm góc nhìn về workflow nhóm và logistics |
| Validation | Hỏi nhanh bạn bè/sinh viên về việc theo dõi deadline từ nhiều nguồn | Nhóm có tín hiệu xác nhận pain thật |
| Challenge | Hỏi liệu một số người chỉ cần template/calendar chứ không cần AI không | Nhóm thêm non-AI alternative |
| Fallback | Đề xuất fallback khi AI extract sai hoặc không chắc chắn | Nhóm có exit/rollback rõ ràng |
| Final decision | Góp ý chốt pilot nhỏ thay vì build full app | Nhóm có scope vừa sức trong lab |

## Bảng dùng AI trong reflection của Ngô Anh

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Validation | Nhờ AI tạo câu hỏi phỏng vấn nhanh | Giúp hỏi đúng vào workflow và pain | Một số câu hỏi hơi dài, giống survey chính thức | Rút gọn thành câu hỏi dễ hỏi bạn bè |
| Challenge | Nhờ AI phản biện problem deadline tracker | Giúp thấy trường hợp chỉ cần calendar/template | AI đôi lúc phản biện quá rộng | Giữ lại phản biện liên quan đến MVP |
| Fallback | Nhờ AI viết exit/rollback condition | Có điều kiện dừng rõ | Một số điều kiện quá nghiêm ngặt | Chỉnh thành sửa hơn 50% deadline trong 2 tuần thì rollback |
| Final decision | Nhờ AI tổng hợp decision rationale | Câu chữ rõ, dễ đưa vào file | Có đoạn hơi giống quảng cáo sản phẩm | Sửa thành lập luận ngắn gọn theo tiêu chí bài học |

## Bài học của Ngô Anh

Validation giúp nhóm không bị cuốn vào ý tưởng AI quá sớm. Có người thật sự mất thời gian theo dõi deadline, nhưng cũng có người chỉ cần template hoặc calendar tốt hơn. Vì vậy, nhóm cần giữ MVP nhỏ: paste/import text, AI extract deadline, user review, export. Nếu AI không giúp giảm thời gian hoặc phải sửa quá nhiều, nhóm nên rollback về checklist/template.

Nếu làm lại, tôi sẽ hỏi nhiều sinh viên ở nhiều lớp khác nhau để xem nguồn deadline phổ biến nhất là Discord, Zalo, email hay LMS.
