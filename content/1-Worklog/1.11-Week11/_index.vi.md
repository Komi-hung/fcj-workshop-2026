---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

* Tích hợp mô hình phân tích da (Skin AI Analytic) chạy trực tiếp trên nền tảng web (Client-side), không qua API.
* Triển khai (deploy) website lên AWS Amplify, tối ưu hiệu năng và kiểm thử toàn bộ chức năng.

### Công việc thực hiện:

| Day | Task                                                                                                                                            | Start Date | Completion Date | Reference Material |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Rà soát lại kiến trúc hệ thống, chuyển đổi luồng xử lý AI sang Frontend. <br> - Khởi tạo dự án và cấu hình môi trường AWS Amplify.            | 03/16/2026 | 03/16/2026      |                    |
| 3   | - Cấu hình và load trực tiếp file mô hình `.tflite` vào trình duyệt web.                                                                        | 03/17/2026 | 03/17/2026      |                    |
| 4   | - Viết script tiền xử lý ảnh và đưa vào model chấm điểm ngay trên trình duyệt mà không cần gọi API backend.                                     | 03/18/2026 | 03/18/2026      |                    |
| 5   | - Kiểm thử chức năng phân tích trực tiếp local, đảm bảo tuyệt đối không có dữ liệu hình ảnh nào bị đẩy ra ngoài hay lưu trữ.                    | 03/19/2026 | 03/19/2026      |                    |
| 6   | - Tiến hành triển khai (deploy) ứng dụng web lên AWS Amplify. <br> - Kiểm thử trên môi trường Amplify, fix bug và xử lý các trường hợp biên.    | 03/20/2026 | 03/20/2026      |                    |
| 7   | - Test hiệu năng xử lý của web app trên Amplify từ nhiều thiết bị (PC, Mobile). <br> - Kiểm tra luồng CI/CD tự động và chuẩn bị bản demo.       | 03/21/2026 | 03/21/2026      |                    |

### Kết quả đạt được:

* Tích hợp thành công AI chạy trực tiếp trên trình duyệt, đảm bảo quyền riêng tư dữ liệu tuyệt đối (không lưu ảnh).
* Triển khai website thành công, hoạt động mượt mà và bảo mật trên nền tảng AWS Amplify.
* Giảm tải hoàn toàn cho server backend, tận dụng tốt khả năng tự động hóa triển khai (CI/CD) của Amplify.
* Hoàn thiện phiên bản web app cuối cùng để chuẩn bị demo.