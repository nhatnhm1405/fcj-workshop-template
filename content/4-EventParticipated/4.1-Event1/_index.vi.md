---
title: "Buildrathon Kickoff: Code the Future with CMC Global"
date: 2026-09-26
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

### Thông tin sự kiện

- **Ngày tổ chức:** 26/09/2026
- **Giờ bắt đầu công bố:** 09:00 (UTC+7)
- **Địa điểm:** Bitexco Financial Tower, TP.HCM
- **Vai trò:** Người tham dự
- **Trang sự kiện:** [Buildrathon Kickoff: Code the Future with CMC Global](https://luma.com/8fe9vvps)

### Tổng quan

Buổi kickoff giới thiệu chương trình Buildrathon, định hướng tham gia và kết nối kiến thức Cloud, AI với kinh nghiệm của các diễn giả. Bên cạnh phần giới thiệu chương trình, nội dung kỹ thuật đưa ra một ví dụ về cách tổ chức các thành phần của một ứng dụng AI.

### Diễn giả

| Diễn giả | Vai trò được giới thiệu | Nội dung |
| --- | --- | --- |
| Nguyễn Gia Hưng | Head of Solutions Architect, AWS Việt Nam và Campuchia | Giới thiệu chương trình, mục đích và định hướng Buildrathon. |
| Bùi Nhật Trường | Tech Lead, CMC Global | Chia sẻ kỹ thuật và ví dụ kiến trúc Slack bot ứng dụng AI. |

### Nội dung chính

#### Giới thiệu Buildrathon

Phần mở đầu trình bày bối cảnh của thử thách Buildrathon, những mục tiêu và kết quả chương trình hướng đến. Nội dung cũng đặt việc phát triển kỹ năng Cloud và AI trong bối cảnh đầu tư vào nhân lực, hạ tầng và kỹ năng tại Việt Nam.

#### Ví dụ kiến trúc Market Slack Bot

Phần chia sẻ kỹ thuật giới thiệu sơ đồ **Market Slack Bot**. Ví dụ giúp phân tích ứng dụng AI theo các thành phần và trách nhiệm:

| Thành phần | Vai trò được minh họa |
| --- | --- |
| Slack | Tiếp nhận lượt nhắc tên, tin nhắn trực tiếp và ngữ cảnh hội thoại. |
| Socket Mode / WebSocket | Kết nối Slack với luồng xử lý của bot. |
| Response gate | Kiểm soát phản hồi trước bước xử lý tiếp theo. |
| Claude Code | Thành phần xử lý với đầu ra được minh họa dưới dạng `print · JSON`. |
| `SOUL.md` và Memory | Cấu hình giọng điệu, phạm vi và ngữ cảnh hội thoại. |
| Bot schedule, internal API, cron và database | Xử lý tác vụ theo lịch, kết nối chức năng nội bộ và lưu thông tin liên quan. |

Khi xem một kiến trúc AI, cần chú ý cách yêu cầu đi vào hệ thống, cách phản hồi được kiểm soát, nơi lưu ngữ cảnh và cách tổ chức tác vụ định kỳ.

### Bài học rút ra

- Bắt đầu bằng mục tiêu và phạm vi của chương trình trước khi đi vào giải pháp kỹ thuật.
- Phân tách một ứng dụng AI thành các phần tiếp nhận yêu cầu, xử lý, quản lý ngữ cảnh và tác vụ theo lịch.
- Xem xét các thành phần phối hợp với nhau như thế nào thay vì chỉ tập trung vào mô hình AI.

### Định hướng áp dụng

Tôi có thể dùng ví dụ này làm cơ sở để tìm hiểu cách quản lý ngữ cảnh và tác vụ định kỳ trong một ứng dụng học tập. Đây là hướng nghiên cứu tiếp theo.

### Hình ảnh check-in

*[Sẽ bổ sung ảnh check-in cá nhân tại sự kiện.]*

### Tài liệu tham khảo

- [Trang sự kiện Buildrathon Kickoff](https://luma.com/8fe9vvps)
- [Bài ghi nhận sự kiện của thành viên cùng nhóm](https://nauppnouv.github.io/fcj-workshop-template/4-eventparticipated/4.1-event1/)
