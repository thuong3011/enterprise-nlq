# Enterprise NLQ Backend

Backend NestJS chuyển câu hỏi ngôn ngữ tự nhiên thành truy vấn PostgreSQL an toàn, phân tích dữ liệu bằng Gemini, lưu lịch sử chat và tạo báo cáo.

Xem hướng dẫn tổng quan tại [README.md ở thư mục gốc](../README.md).

## Cài đặt

```bash
npm install
```

Tạo `.env` theo mẫu trong README gốc, sau đó khởi chạy:

```bash
npm run start:dev
```

API mặc định: `http://localhost:3000`

## Các lệnh

```bash
npm run build
npm run lint
npm test
npm run test:e2e
npm run test:cov
npm run start:prod
```
