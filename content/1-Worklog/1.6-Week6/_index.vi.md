---
title: "Worklog Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Thêm và quản lý dữ liệu hình ảnh mỹ phẩm từ Amazon S3 vào database thông qua Prisma Studio.
* Hiểu về CDN và tối ưu hiệu năng với CloudFront.

### Công việc thực hiện trong tuần:

| Day | Task                                                                                                                                                             | Start Date | Completion Date | Reference Material                      |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | --------------------------------------- |
| 2   | - Thiết lập Prisma schema cho dữ liệu mỹ phẩm (chứa field URL ảnh lưu từ S3) <br> - Tìm hiểu CloudFront <br> - Chi phí của Amazon CloudFront                     | 02/09/2026 | 02/09/2026      | |
| 3   | - Viết script/chuẩn bị file để trích xuất danh sách link ảnh mỹ phẩm từ S3 <br> - Tạo CloudFront Distribution                                                    | 02/10/2026 | 02/10/2026      ||
| 4   | - Tiến hành thêm dữ liệu (seed data) mỹ phẩm vào database bằng Prisma <br> - Kết nối CloudFront với S3 <br> +Tạo nhóm S3 <br> +Tải file index.html <br> +Cấu hình Amazon CloudFront <br> +Dọn dẹp tài nguyên | 02/11/2026 | 02/11/2026      |  |
| 5   | - Kiểm tra, chỉnh sửa dữ liệu hình ảnh mỹ phẩm trực tiếp trên giao diện Prisma Studio <br> - Kiểm tra cơ chế cache                                               | 02/12/2026 | 02/12/2026      | |
| 6   | - Hoàn tất việc cập nhật toàn bộ database mỹ phẩm, đảm bảo link ảnh hoạt động tốt <br> - Tối ưu hiệu năng hệ thống                                               | 02/13/2026 | 02/13/2026      |  |

### Kết quả đạt được:

* Đồng bộ và quản lý thành công dữ liệu hình ảnh sản phẩm mỹ phẩm từ S3 lên database bằng Prisma Studio.
* Triển khai CDN bằng CloudFront thành công.
* Cải thiện tốc độ tải nội dung.
* Hiểu cơ chế cache và phân phối nội dung.