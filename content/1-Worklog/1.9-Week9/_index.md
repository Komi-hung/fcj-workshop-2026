---

title: "Week 9 Worklog"
date: 2024-02-26
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
----------------------

### Week 9 Objectives:

* Continue refining the architecture and loss function to improve accuracy (metrics).
* Resolve all remaining issues in the model convergence process.

### Tasks Completed:

| Day | Task                                                                                                                              | Start Date | Completion Date | Reference Material |
| --- | --------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Review the Dual Channel + Spatial Attention (CBAM) block to check for potential data flow bottlenecks                           | 03/02/2026 | 03/02/2026      |                    |
| 3   | - Adjust weights of the Masked Focal Loss to force the model to focus more on hard samples                                        | 03/03/2026 | 03/03/2026      |                    |
| 4   | - Add additional Data Augmentation techniques (brightness, contrast) to the Custom train loop <br> - Prepare to retrain remaining models | 03/04/2026 | 03/04/2026      |                    |
| 5   | - Retrain `wrinkles_forehead_model.keras` and `wrinkles_mouth_model.keras` with the optimized architecture                        | 03/05/2026 | 03/05/2026      |                    |
| 6   | - Summarize and compare metrics (F1-score, Precision, Recall) of all 4 models after 2 weeks of fine-tuning                       | 03/06/2026 | 03/06/2026      |                    |

### Results:

* Evaluation metrics showed significant improvement compared to the initial faulty training.
* Most architectural issues have been resolved, but real-world prediction results are still not reliable enough (final model version not yet ready).

