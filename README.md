# NexusTalk — Dịch vụ Chat Real-Time

Mục đích: Xây dựng một ứng dụng giao tiếp real-time (tương tự Discord) tập trung vào low-latency messaging và thiết kế modular.

---

## 1. Tech Stack (Core Dependencies)

- Backend: Java 21, Spring Boot 3+
- Real-time: Spring WebSocket (STOMP)
- Security: Spring Security, JWT
- Database: PostgreSQL, Spring Data JPA

---

## 2. Tính năng cốt lõi (Core Functionality)

- Authentication: Đăng ký / Đăng nhập, cấp phát JWT
- Server & Channels: Tạo và quản lý không gian trò chuyện (channels)
- Real-Time Messaging: Gửi/nhận tin nhắn tức thì qua WebSocket
- Quyền truy cập & bảo mật cho API REST và WS

---
