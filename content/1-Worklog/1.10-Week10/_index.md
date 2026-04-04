---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


### Objectives:

* Complete the final model fine-tuning process, applying the Softmax function to optimize classification results.
* Export detailed scoring models (on a 5-point scale) to `.tflite` format for integration.

### Tasks:

| Day | Task                                                                                                                     | Start Date | Completion Date | Reference Material |
| --- | ------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ------------------ |
| 2   | - Configure the Softmax activation function in the output layer to calculate probability distribution for each level (lv_1, lv_2, lv_3) | 03/16/2026 | 03/16/2026      |                    |
| 3   | - Use probabilities from Softmax combined with Score mapping to calculate continuous scores on a 5-point scale and complete model training | 03/17/2026 | 03/17/2026      |                    |
| 4   | - Convert models from `.keras` format to TensorFlow Lite (`.tflite`) format                                               | 03/18/2026 | 03/18/2026      |                    |
| 5   | - Apply Quantization techniques to optimize and reduce `.tflite` file size without compromising accuracy                  | 03/19/2026 | 03/19/2026      |                    |
| 6   | - Test `.tflite` files to ensure accurate output scores ranging from 1.0 to 5.0                                          | 03/20/2026 | 03/20/2026      |                    |

### Results:

* Successfully integrated Softmax to output probability distributions and smoothly map to detailed 5-point scores.
* Successfully exported and optimized model files in `.tflite` format.
* Ensured lightweight, stable models capable of accurate scoring.
