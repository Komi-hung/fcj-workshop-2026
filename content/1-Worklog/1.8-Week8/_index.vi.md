---
title: "Week 8 Worklog"
date: 2024-02-19
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
----------------------

### Mục tiêu tuần 8:

* Đánh giá kết quả train từ tuần trước và tiến hành tinh chỉnh (fine-tuning) mô hình.
* Sửa các lỗi phát sinh (overfitting/underfitting) và bắt đầu cải thiện các siêu tham số (hyperparameters).

### Công việc thực hiện:

| Day | Task                                                                                                             | Start Date | Completion Date | Reference Material |
| --- | ---------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Đánh giá biểu đồ Loss/Accuracy của 4 model đã train <br> - Phân tích các trường hợp mô hình dự đoán sai nhiều | 02/23/2026 | 02/23/2026      |                    |
| 3   | - Tiến hành gỡ lỗi Overfitting trên tập validation <br> - Điều chỉnh lại Learning Rate và Cosine Warmup Schedule | 02/24/2026 | 02/24/2026      |                    |
| 4   | - Thay đổi cấu hình Mixup Augmentation để xử lý tốt hơn sự mất cân bằng dữ liệu của các nhãn                   | 02/25/2026 | 02/25/2026      |                    |
| 5   | - Bắt đầu quá trình retrain lại **acne_model.keras** và **wrinkles_model.keras** với các thông số mới         | 02/26/2026 | 02/26/2026      |                    |
| 6   | - Ghi nhận kết quả retrain: Các chỉ số có thay đổi nhưng chưa đạt chuẩn yêu cầu <br> - Tạm dừng để phân tích thêm| 02/27/2026 | 02/27/2026      |                    |

### Kết quả:

* Xác định được các nguyên nhân chính gây ra sai số trong quá trình huấn luyện ban đầu.
* Đã thực hiện điều chỉnh nhiều thông số (learning rate, augmentation) nhưng mô hình vẫn chưa hội tụ tốt, chưa thể xuất ra model hoàn chỉnh để sử dụng.