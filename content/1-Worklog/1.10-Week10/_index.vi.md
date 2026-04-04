---
title: "Worklog Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


### Mục tiêu:

* Hoàn tất quá trình tinh chỉnh mô hình lần cuối, áp dụng hàm Softmax để tối ưu kết quả phân loại.
* Xuất mô hình chấm điểm chi tiết (trên thang điểm 5) sang định dạng `.tflite` để chuẩn bị tích hợp.

### Công việc:

| Day | Task                                                                                                                     | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ------------------ |
| 2   | - Cấu hình hàm kích hoạt Softmax ở layer output để tính toán phân phối xác suất cho từng cấp độ (lv_1, lv_2, lv_3)       | 03/16/2026 | 03/16/2026      |                    |
| 3   | - Sử dụng xác suất từ Softmax kết hợp Score mapping để tính ra điểm liên tục trên thang điểm 5 và hoàn tất train model   | 03/17/2026 | 03/17/2026      |                    |
| 4   | - Thực hiện chuyển đổi các mô hình từ định dạng `.keras` sang định dạng TensorFlow Lite (`.tflite`)                      | 03/18/2026 | 03/18/2026      |                    |
| 5   | - Áp dụng kỹ thuật lượng tử hóa (Quantization) để tối ưu và giảm dung lượng file `.tflite` mà không làm giảm độ chính xác| 03/19/2026 | 03/19/2026      |                    |
| 6   | - Chạy thử nghiệm file `.tflite` để đảm bảo output trả về chính xác điểm số chi tiết từ mức 1.0 đến 5.0                  | 03/20/2026 | 03/20/2026      |                    |

### Kết quả:

* Tích hợp thành công Softmax để xuất ra phân phối xác suất và quy đổi mượt mà ra thang điểm 5 chi tiết.
* Xuất và tối ưu hóa thành công các file mô hình định dạng `.tflite`.
* Đảm bảo mô hình nhẹ, hoạt động ổn định và có khả năng chấm điểm chính xác.