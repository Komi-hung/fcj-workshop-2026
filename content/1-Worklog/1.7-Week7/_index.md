---

title: "Week 7 Worklog"
date: 2024-02-12
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
----------------------

### Week 7 Objectives:

* Sequentially train 4 independent classification models for Skin AI Analytic.
* Build and optimize model architecture based on EfficientNetB3.

### Tasks Completed:

| Day | Task                                                                                                                                         | Start Date | Completion Date | Reference Material |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Set up EfficientNetB3 backbone (300x300, frozen ImageNet weights) <br> - Train model `acne_model.keras` (3-class Acne severity)            | 02/16/2026 | 02/16/2026      |                    |
| 3   | - Integrate Dual Channel + Spatial Attention (CBAM) <br> - Train model `wrinkles_eyes_model.keras` (Eye wrinkle severity)                    | 02/17/2026 | 02/17/2026      |                    |
| 4   | - Configure Masked Focal Loss and Mixup Augmentation to handle imbalance <br> - Train model `wrinkles_forehead_model.keras`                  | 02/18/2026 | 02/18/2026      |                    |
| 5   | - Set up Cosine LR Warmup Schedule and Custom train loop <br> - Train model `wrinkles_mouth_model.keras` (Mouth wrinkle severity)            | 02/19/2026 | 02/19/2026      |                    |
| 6   | - Set up Score mapping (lv_1 -> 1.0 \\ lv_2 -> 2.5 \\ lv_3 -> 5.0) <br> - Configure Per-model config and Safe Phase 1 / Phase 2 rollback | 02/20/2026 | 02/20/2026      |                    |

### Results:

* Completed training 4 independent classifier models for acne and wrinkle regions (eyes, forehead, mouth).
* Successfully applied advanced architectural techniques such as CBAM, Masked Focal Loss, and Mixup.
* Standardized severity score mapping for skin conditions.
