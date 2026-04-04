---

title: "Week 9 Worklog"
date: 2024-02-26
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
----------------------

### Mục tiêu tuần 9:

* Tiếp tục đi sâu vào tinh chỉnh kiến trúc và hàm loss để cải thiện độ chính xác (metrics).
* Giải quyết triệt để các lỗi còn tồn đọng trong quá trình hội tụ của mô hình.

### Công việc thực hiện:

| Day | Task                                                                                                                              | Start Date | Completion Date | Reference Material |
| --- | --------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Rà soát lại khối Dual Channel + Spatial Attention (CBAM) xem có gây nghẽn (bottleneck) luồng dữ liệu không                      | 03/02/2026 | 03/02/2026      |                    |
| 3   | - Tinh chỉnh trọng số của Masked Focal Loss để ép mô hình tập trung hơn vào các điểm dữ liệu khó (hard samples)                   | 03/03/2026 | 03/03/2026      |                    |
| 4   | - Bổ sung thêm các kỹ thuật Data Augmentation (độ sáng, độ tương phản) vào Custom train loop <br> - Chuẩn bị retrain các model còn lại | 03/04/2026 | 03/04/2026      |                    |
| 5   | - Retrain `wrinkles_forehead_model.keras` và `wrinkles_mouth_model.keras` với kiến trúc được tối ưu lại                           | 03/05/2026 | 03/05/2026      |                    |
| 6   | - Tổng hợp và so sánh thông số (F1-score, Precision, Recall) của toàn bộ 4 mô hình sau 2 tuần tinh chỉnh                          | 03/06/2026 | 03/06/2026      |                    |

### Kết quả:

* Các chỉ số đánh giá (metrics) đã có sự cải thiện rõ rệt so với bản train lỗi đầu tiên.
* Đã giải quyết được phần lớn các lỗi kiến trúc, tuy nhiên kết quả dự đoán thực tế vẫn chưa đủ độ tin cậy an toàn (vẫn chưa cho ra được model phiên bản cuối cùng).