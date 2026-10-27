---
title: "Worklog Tuần 1"
date: 2026-09-14
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

Trong tuần đầu tiên (14/09/2026–18/09/2026), tôi bắt đầu tìm hiểu nền tảng điện toán đám mây và các khái niệm cơ bản của AWS. Nội dung học gồm hạ tầng toàn cầu, cách tương tác với AWS, quản lý chi phí và thực hành với EC2, Amazon Bedrock và AWS Lambda.

### Mục tiêu tuần 1

- Hiểu điện toán đám mây, cách sử dụng tài nguyên linh hoạt và mô hình thanh toán theo mức sử dụng.
- Phân biệt Region, Availability Zone, Edge Location và các cách tương tác với AWS qua Console, CLI và SDK.
- Tìm hiểu quản lý quyền và bảo vệ thông tin xác thực khi sử dụng tài nguyên AWS.
- Làm quen với AWS Budgets, AWS Support và AWS Well-Architected Framework.
- Thực hành khởi tạo EC2, dùng Bedrock Playground và xây dựng ứng dụng web đơn giản bằng Lambda.

### Nhật ký công việc theo ngày

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Tìm hiểu các khái niệm cơ bản về điện toán đám mây, lợi ích của AWS và định hướng học tập trong chương trình. Ghi chú về tính linh hoạt và cách trả phí theo mức sử dụng. | 14/09/2026 | 14/09/2026 | [Module 01-01](https://www.youtube.com/watch?v=HxYZAK1coOI), [01-02](https://www.youtube.com/watch?v=IK59Zdd1poE), [01-03](https://www.youtube.com/watch?v=HSzrWGqo3ME); [First Cloud Journey](https://cloudjourney.awsstudygroup.com/) |
| 3 | Tìm hiểu hạ tầng toàn cầu của AWS: Region, Availability Zone và Edge Location. Phân biệt AWS Management Console, AWS CLI và SDK; làm quen với tối ưu chi phí và AWS Well-Architected. | 15/09/2026 | 15/09/2026 | [Module 01-04](https://www.youtube.com/watch?v=pjr5a-HYAjI), [01-05](https://www.youtube.com/watch?v=2PQYqH_HkXw), [01-06](https://www.youtube.com/watch?v=IY61YlmXQe8), [01-07](https://www.youtube.com/watch?v=Hku7exDBURo); [AWS Global Infrastructure](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/global-infrastructure.html) |
| 4 | Thực hành tạo EC2 instance với Amazon Linux 2023 và `t3.micro`; thiết lập key pair, mạng và security group, kết nối bằng EC2 Instance Connect, chạy một số lệnh Linux rồi terminate instance. Đồng thời tìm hiểu AWS Budgets, ngân sách chi phí và các ngưỡng cảnh báo actual/forecast. | 16/09/2026 | 16/09/2026 | [Activity 01: Amazon EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html); [Activity 02: AWS Budgets](https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html); [FCJ Lab07](https://000007.awsstudygroup.com/) |
| 5 | Thực hành Amazon Bedrock Playground với Amazon Nova 2 Lite: nhập prompt và quan sát response, số token cùng latency. Tạo Lambda function từ HTTP blueprint, mở Function URL và kiểm tra trang “Hello from AWS Lambda!”. | 17/09/2026 | 17/09/2026 | [Amazon Bedrock Playground](https://docs.aws.amazon.com/bedrock/latest/userguide/playgrounds.html); [AWS Lambda Function URLs](https://docs.aws.amazon.com/lambda/latest/dg/lambda-urls.html); [AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html) |
| 6 | Tìm hiểu các kênh và loại yêu cầu hỗ trợ AWS, thông tin cần chuẩn bị khi mô tả sự cố và cách dùng sáu trụ cột Well-Architected để xem xét một kiến trúc. | 18/09/2026 | 18/09/2026 | [Lab09-01](https://www.youtube.com/watch?v=4FDcK0_kbfY), [09-02](https://www.youtube.com/watch?v=BAEh-_RzmNg), [09-03](https://www.youtube.com/watch?v=haafDPugAnE), [09-04](https://www.youtube.com/watch?v=ThJBaQ3DEBs); [FCJ Lab09](https://000009.awsstudygroup.com/); [Well-Architected pillars](https://docs.aws.amazon.com/wellarchitected/latest/framework/the-pillars-of-the-framework.html) |

### Kết quả đạt được

- Tổng hợp được các khái niệm nền tảng về cloud và những thành phần chính trong hạ tầng toàn cầu của AWS.
- Phân biệt vai trò của Console, CLI và SDK trong việc tương tác với dịch vụ AWS.
- Kết nối và kiểm tra EC2 instance, sau đó terminate instance; tìm hiểu vai trò của key pair và security group.
- Hiểu mục đích của AWS Budgets và AWS Support, đồng thời làm quen với sáu trụ cột của AWS Well-Architected Framework.
- Nhận được response từ Amazon Bedrock Playground và kiểm tra trang HTML được trả về qua Lambda Function URL.

### Bài học rút ra

- Lựa chọn Region và dịch vụ cần gắn với yêu cầu thực tế về độ trễ, khả năng sẵn sàng, dữ liệu và chi phí.
- Private key cần được lưu an toàn; quy tắc SSH trong security group nên giới hạn theo nguồn truy cập cần thiết.
- Khi dùng Lambda Function URL không xác thực, endpoint có thể được gọi công khai; cần xem xét quyền truy cập và dọn tài nguyên sau khi thử nghiệm.
- AWS Budgets giúp theo dõi và cảnh báo chi phí; cảnh báo không đồng nghĩa với việc chi tiêu tự động bị chặn.
- Khi cần hỗ trợ, mô tả rõ triệu chứng, thời điểm và phạm vi ảnh hưởng giúp việc trao đổi về sự cố hiệu quả hơn.

### Bước tiếp theo

Tiếp tục tìm hiểu VPC và networking trong Tuần 2; tìm hiểu thêm cách tích hợp Bedrock và Lambda vào ứng dụng.
