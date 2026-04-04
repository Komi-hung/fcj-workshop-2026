---

title: "Week 8 Worklog"
date: 2024-02-19
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
----------------------

### Week 8 Objectives:

* Evaluate training results from the previous week and perform model fine-tuning.
* Fix arising issues (overfitting/underfitting) and begin improving hyperparameters.

### Tasks Completed:

| Day | Task                                                                                                             | Start Date | Completion Date | Reference Material |
| --- | ---------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Evaluate Loss/Accuracy charts of the 4 trained models <br> - Analyze cases with high prediction errors         | 02/23/2026 | 02/23/2026      |                    |
| 3   | - Debug overfitting on the validation set <br> - Adjust Learning Rate and Cosine Warmup Schedule                 | 02/24/2026 | 02/24/2026      |                    |
| 4   | - Modify Mixup Augmentation configuration to better handle label imbalance                                      | 02/25/2026 | 02/25/2026      |                    |
| 5   | - Begin retraining `acne_model.keras` and `wrinkles_eyes_model.keras` with new parameters                       | 02/26/2026 | 02/26/2026      |                    |
| 6   | - Record retraining results: Metrics improved but did not meet requirements <br> - Pause for further analysis    | 02/27/2026 | 02/27/2026      |                    |

### Results:

* Identified key causes of errors during the initial training process.
* Adjusted multiple parameters (learning rate, augmentation), but the models have not yet converged well enough to produce a finalized model for use.
