---
title: "Nhật ký công việc"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

**Trong trang này**, nhật ký công việc (worklog) sẽ tổng hợp lại toàn bộ hành trình xây dựng hệ thống website thương mại điện tử kết hợp AI phân tích da (Skin AI Analytic) và triển khai hạ tầng trên nền tảng đám mây AWS. Chương trình được hoàn thành trong vòng **12 tuần**. Trong các tuần đó, công việc bao gồm từ việc thu thập dữ liệu, thiết lập hạ tầng AWS cơ bản (S3, VPC, EC2), quản lý database (Prisma), cho đến huấn luyện, tinh chỉnh mô hình Deep Learning (EfficientNetB3) và cuối cùng là deploy toàn bộ hệ thống lên AWS Amplify.

Thông thường và cũng là tiêu chuẩn, một worklog được thực hiện trong khoảng 3 tháng (trong suốt thời gian thực tập) với nội dung các tuần như sau:

**Tuần 1:** [Làm quen với AWS và các dịch vụ cơ bản trong AWS](1.1-week1/)

**Tuần 2:** [Tìm hiểu Amazon S3, thực hành tạo Bucket, quản lý Object và phân quyền truy cập](1.2-week2/)

**Tuần 3:** [Thu thập, xử lý và xây dựng cấu trúc lưu trữ dữ liệu hình ảnh mỹ phẩm trên Amazon S3](1.3-week3/)

**Tuần 4:** [Tìm kiếm 50% dataset cho mô hình Skin AI và xây dựng hạ tầng mạng (VPC, EC2, NAT Gateway)](1.4-week4/)

**Tuần 5:** [Hoàn thiện 100% dataset (Acne, Skintone, Wrinkles) và tìm hiểu Load Balancing, Auto Scaling](1.5-week5/)

**Tuần 6:** [Đồng bộ ảnh mỹ phẩm từ S3 vào database bằng Prisma Studio và triển khai CDN CloudFront](1.6-week6/)

**Tuần 7:** [Thiết lập kiến trúc EfficientNetB3 và huấn luyện tuần tự 4 mô hình phân loại tình trạng da](1.7-week7/)

**Tuần 8:** [Phân tích đánh giá, gỡ lỗi Overfitting và tinh chỉnh siêu tham số (Hyperparameters) cho mô hình](1.8-week8/)

**Tuần 9:** [Tối ưu kiến trúc mạng (CBAM) và hàm loss (Masked Focal Loss) để cải thiện độ chính xác](1.9-week9/)

**Tuần 10:** [Tích hợp Softmax chấm thang điểm 5, xuất và lượng tử hóa mô hình sang định dạng .tflite](1.10-week10/)

**Tuần 11:** [Tích hợp mô hình AI chạy trực tiếp trên trình duyệt (Client-side) và Deploy lên AWS Amplify](1.11-week11/)

**Tuần 12:** [Kiểm thử tổng thể hệ thống, hoàn thiện tài liệu báo cáo và chuẩn bị thuyết trình Demo dự án](1.12-week12/)