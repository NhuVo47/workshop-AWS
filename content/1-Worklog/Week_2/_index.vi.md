---
title: "Worklog Tuần 2"
weight: 2
chapter: false
pre: " <b> 1.2 </b> "
---

### Mục tiêu

- Tìm hiểu kiến trúc serverless trên AWS và mô hình triển khai hệ thống.
- Nghiên cứu các dịch vụ AWS được sử dụng trong dự án.
- Hiểu quy trình xử lý ảnh tự động trên nền tảng AWS.
- Tìm hiểu cơ chế phân quyền và quản lý tài nguyên trên AWS.
- Chuẩn bị kiến thức phục vụ cho quá trình phát triển và tích hợp hệ thống.

---

### Công việc thực hiện

| Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| ---------- | ------------ | --------------- | ------------------ |
| Tìm hiểu Amazon S3 và mô hình Object Storage | 29/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/s3 |
| Tìm hiểu Amazon DynamoDB và mô hình cơ sở dữ liệu NoSQL | 30/06/2026 | 01/07/2026 | https://docs.aws.amazon.com/dynamodb |
| Tìm hiểu AWS Lambda và mô hình Serverless | 01/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/lambda |
| Tìm hiểu Amazon CloudWatch và cơ chế giám sát hệ thống | 02/07/2026 | 02/07/2026 | https://docs.aws.amazon.com/AmazonCloudWatch |
| Tìm hiểu AWS IAM và cơ chế phân quyền giữa các dịch vụ | 02/07/2026 | 03/07/2026 | https://docs.aws.amazon.com/iam |
| Phân tích kiến trúc và quy trình xử lý của hệ thống Image Optimization | 03/07/2026 | 03/07/2026 | |
| Tìm hiểu cách các dịch vụ AWS tích hợp và trao đổi dữ liệu trong hệ thống | 03/07/2026 | 03/07/2026 | |
| Nghiên cứu các dịch vụ AWS phù hợp với AWS Free Tier | 03/07/2026 | 03/07/2026 | |

---

### Kết quả nhận được

- Hiểu được vai trò của các dịch vụ AWS trong hệ thống xử lý ảnh tự động:

  - **Amazon S3**
    - Lưu trữ ảnh đầu vào và ảnh sau khi xử lý dưới dạng object.
    - Quản lý dữ liệu thông qua bucket và object.

  - **AWS Lambda**
    - Thực thi xử lý ảnh theo mô hình serverless.
    - Tự động được kích hoạt khi có sự kiện từ Amazon S3.

  - **Amazon DynamoDB**
    - Hiểu cơ chế lưu trữ dữ liệu NoSQL.
    - Nắm được cách sử dụng DynamoDB để lưu trữ thông tin của hệ thống.

  - **Amazon CloudWatch**
    - Theo dõi log và trạng thái hoạt động của các dịch vụ AWS.
    - Hỗ trợ giám sát và kiểm tra lỗi trong quá trình thực thi.

  - **AWS IAM**
    - Hiểu cơ chế quản lý người dùng, vai trò (Role) và chính sách (Policy).
    - Nắm được nguyên tắc phân quyền giữa các dịch vụ AWS.

- Hiểu được kiến trúc tổng thể của hệ thống xử lý ảnh tự động trên AWS và quy trình phối hợp giữa các dịch vụ.

- Nắm được mô hình triển khai ứng dụng theo kiến trúc serverless, giúp giảm chi phí vận hành và dễ dàng mở rộng khi hệ thống phát triển.

- Hiểu được tiêu chí lựa chọn dịch vụ AWS phù hợp với AWS Free Tier để tối ưu chi phí trong quá trình phát triển và thử nghiệm.