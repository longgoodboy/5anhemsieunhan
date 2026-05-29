
# 01 — Individual Problem Scan

## Scan rộng (từ file Excel)

| #  | Lăng kính     | Problem                                            | Ai đang đau?        | Dấu hiệu thật            |
| -- | ------------- | -------------------------------------------------- | ------------------- | ------------------------ |
| 1  | Quy trình     | Quyết định và feedback từ cấp trên không nhất quán | Thành viên cấp dưới | Task bị revise nhiều lần |
| 2  | Công bằng     | Có dấu hiệu thiên vị giới tính trong đánh giá      | Sinh viên nữ        | Ý kiến bị bỏ qua         |
| 3  | Tốn thời gian | Đi đường dài đi học                                | Sinh viên ở xa      | 70 phút/lượt             |
| 4  | Hiệu suất     | Thành viên trì hoãn công việc                      | Nhóm                | Task trễ deadline        |
| 5  | Hiệu suất     | Thiếu ngủ ảnh hưởng năng lượng                     | Cá nhân/team        | Ngủ 5 tiếng/ngày         |
| 6  | (từ Excel)    | ...                                                | ...                 | ...                      |
| 7  | ...           | ...                                                | ...                 | ...                      |
| 8  | ...           | ...                                                | ...                 | ...                      |
| 9  | ...           | ...                                                | ...                 | ...                      |
| 10 | ...           | ...                                                | ...                 | ...                      |

👉 Nhận xét:

* Bạn đã có **problem thật + dấu hiệu rõ** (rất tốt)
* Có nhiều loại: **cá nhân, nhóm, hệ thống**

---

## 🎯 Top 3 Problems

| Rank | Problem                              | Vì sao chọn                 | Chưa chắc                  |
| ---- | ------------------------------------ | --------------------------- | -------------------------- |
| 1    | Feedback không nhất quán từ cấp trên | Workflow rõ + lặp lại nhiều | Có đủ data để đo chưa      |
| 2    | Thành viên trì hoãn công việc        | Impact trực tiếp team       | Có giải bằng AI được không |
| 3    | Đi học mất nhiều thời gian           | Rất tốn thời gian           | Khó áp dụng AI             |

---

# 🧠 Problem Card #1 (CHỌN CHÍNH)

## Problem (1 câu)

Feedback và quyết định từ cấp trên không nhất quán, khiến task bị sửa nhiều lần và tốn thời gian.

## Actor

* Sinh viên / thành viên nhóm / cấp dưới

## Context

* Khi làm assignment / task nhóm
* Sau khi nộp → nhận feedback → sửa → lại bị đổi ý

## Current Workflow

```text
1. Làm task theo yêu cầu ban đầu
2. Nộp cho cấp trên
3. Nhận feedback
4. Sửa lại
5. Nộp lại
6. Nhận feedback mới (khác trước)
7. Lặp lại nhiều lần
```

## Bottleneck

👉 Feedback không rõ ràng / thay đổi liên tục

## Impact

* Mất thời gian sửa đi sửa lại
* Gây frustration cho người làm
* Giảm hiệu suất team

## Success Metric

* Giảm số lần revise (ví dụ: từ 3-4 lần → 1-2 lần)
* Giảm thời gian hoàn thành task

## Non-AI Solution

* Checklist yêu cầu rõ ràng
* Template feedback

👉 Nhưng:

* Vẫn phụ thuộc vào con người → không ổn định

## AI Hypothesis

👉 AI có thể:

* Chuẩn hóa yêu cầu
* Tóm tắt feedback rõ ràng
* So sánh feedback cũ vs mới

## Quick gut

👉 **Workflow**

---

## Current vs Future Workflow

### CURRENT (≈ nhiều vòng lặp)

```text
[Task]
→ [Submit]
→ [Feedback unclear]
→ [Revise]
→ [Feedback changed]
→ [Revise again]
```

---

### FUTURE (có AI)

```text
[Task]
→ [Submit]
→ [AI chuẩn hóa feedback]
→ [AI highlight inconsistency]
→ [User revise 1 lần]
→ [Submit]
```

---

# 02 — Group Problem Statement

## 🎯 Chọn Problem

👉 Nhóm nên chọn:

**“Feedback không nhất quán gây rework nhiều lần”**

### Vì sao:

* Có workflow rõ
* Có pain thật
* Có thể áp dụng AI
* Có thể đo được

---

## 🔍 Insight quan trọng

```text
Pain không nằm ở việc "có feedback",
mà là feedback không rõ và không nhất quán.
```

---

## Problem Statement v1

| Field          | Nội dung                                           |
| -------------- | -------------------------------------------------- |
| Actor          | Sinh viên / thành viên nhóm                        |
| Workflow       | Làm task → nhận feedback → sửa → feedback thay đổi |
| Bottleneck     | Feedback không rõ và không nhất quán               |
| Impact         | Tốn thời gian, giảm hiệu suất                      |
| Success Metric | Giảm số lần revise                                 |
| Boundary       | AI không quyết định thay người                     |

---

# 🤖 Rule / Workflow / Agent

| Mức      | Giải pháp                 | Đánh giá    |
| -------- | ------------------------- | ----------- |
| Rule     | Checklist yêu cầu         | Không đủ    |
| Workflow | AI chuẩn hóa feedback     | ✅ Phù hợp   |
| Agent    | AI tự quyết định sửa task | ❌ Quá risky |

👉 **Chọn: Workflow**

---

## Final Solution

```text
Workflow:

1. User nhận feedback
2. Input vào AI
3. AI:
   - Tóm tắt feedback
   - Chuẩn hóa yêu cầu
   - So sánh với feedback cũ
4. User revise 1 lần
```

---

# 📊 Before vs After

| Metric     | Trước   | Sau     |
| ---------- | ------- | ------- |
| Số lần sửa | 3-4 lần | 1-2 lần |
| Thời gian  | Cao     | Giảm    |
| Clarity    | Thấp    | Cao     |

---

# 03 — Reflection (bạn có thể dùng luôn)

## Tôi đã đóng góp

* Phân tích problem từ thực tế (Excel)
* Xác định pain chính là “feedback inconsistency”
* Xây workflow before/after

## Dùng AI như thế nào

| Phase             | Dùng AI            |
| ----------------- | ------------------ |
| Scan              | Gợi ý thêm problem |
| Workflow          | Vẽ flow            |
| Problem Statement | refine wording     |

## Bài học

* Problem tốt = có workflow + metric
* Không phải cái gì cũng cần Agent
* Workflow thường là mức hợp lý nhất

---

