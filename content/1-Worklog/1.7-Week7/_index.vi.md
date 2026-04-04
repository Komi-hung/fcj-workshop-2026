--------------
title: "Week 7 Worklog"
date: 2024-02-12
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
----------------------

### Mục tiêu tuần 7:

* Tiến hành huấn luyện (train) tuần tự 4 mô hình phân loại độc lập cho Skin AI Analytic.
* Xây dựng và tối ưu kiến trúc mô hình dựa trên EfficientNetB3.

### Công việc thực hiện:

| Day | Task                                                                                                                                         | Start Date | Completion Date | Reference Material |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Thiết lập EfficientNetB3 backbone (300x300, frozen ImageNet weights) <br> - Train model `acne_model.keras` (3-class Acne severity)         | 02/16/2026 | 02/16/2026      |                    |
| 3   | - Tích hợp Dual Channel + Spatial Attention (CBAM) <br> - Train model `wrinkles_eyes_model.keras` (Eye wrinkle severity)                     | 02/17/2026 | 02/17/2026      |                    |
| 4   | - Cấu hình Masked Focal Loss và Mixup Augmentation xử lý mất cân bằng <br> - Train model `wrinkles_forehead_model.keras`                     | 02/18/2026 | 02/18/2026      |                    |
| 5   | - Thiết lập Cosine LR Warmup Schedule và Custom train loop <br> - Train model `wrinkles_mouth_model.keras` (Mouth wrinkle severity)          | 02/19/2026 | 02/19/2026      |                    |
| 6   | - Thiết lập Score mapping (lv_1 -> 1.0 \| lv_2 -> 2.5 \| lv_3 -> 5.0) <br> - Cấu hình Per-model config và Safe Phase 1 / Phase 2 rollback | 02/20/2026 | 02/20/2026      |                    |

### Kết quả:

* Hoàn thành huấn luyện 4 model classifier độc lập cho mụn và các vùng nếp nhăn (mắt, trán, miệng).
* Áp dụng thành công các kỹ thuật kiến trúc nâng cao như CBAM, Masked Focal Loss và Mixup.
* Chuẩn hóa được thang điểm đánh giá mức độ nghiêm trọng (Score mapping) cho các tình trạng da.