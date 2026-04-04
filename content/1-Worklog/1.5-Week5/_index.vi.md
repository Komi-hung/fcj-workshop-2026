---
title: "Worklog Tuần 5"
date: 2026-02-02
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Hoàn thiện 100% bộ dữ liệu (dataset) chuẩn cho 3 hạng mục: ACNE, SKINTONE, WRINKLES.
* Tìm hiểu về Load Balancing và Auto Scaling trên AWS để tối ưu hệ thống.

### Công việc thực hiện trong tuần:

| Day | Task                                                                                                                                                             | Start Date | Completion Date | Reference Material                      |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | --------------------------------------- |
| 2   | - Hoàn tất thu thập và gán nhãn dữ liệu cho phần ACNE (theo 3 mức độ ) <br> - Tìm hiểu về Elastic Load Balancing (ELB)                                    | 02/02/2026 | 02/02/2026      |  |
| 3   | - Hoàn thiện bộ dataset về SKINTONE (Phân loại theo thang đo Fitzpatrick) <br> - Cấu hình Application Load Balancer                                               | 02/03/2026 | 02/03/2026      | |
| 4   | - Thu thập đủ số lượng ảnh cho phần WRINKLES (Nếp nhăn vùng mắt, trán) <br> - Tìm hiểu về Auto Scaling Group                                                     | 02/04/2026 | 02/04/2026      | |
| 5   | - Tiền xử lý dữ liệu cuối cùng (Augmentation, Normalization) cho toàn bộ dataset <br> - Cấu hình Auto Scaling dựa trên tải của CPU                               | 02/05/2026 | 02/05/2026      |  |
| 6   | - Đóng gói bộ Dataset Skin AI hoàn chỉnh và lưu trữ bản final trên S3 <br> - Test khả năng chịu tải và tự động mở rộng của hệ thống                              | 02/06/2026 | 02/06/2026      | |

### Kết quả đạt được:

* Hoàn thành bộ dữ liệu chuẩn (Dataset) cho model Skin AI Analytic với đầy đủ các nhãn Acne, Skintone và Wrinkles.
* Hiểu và thực hành triển khai hệ thống có khả năng chịu tải (High Availability) bằng Load Balancer và Auto Scaling.