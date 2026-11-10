# Sổ tay Tự gỡ lỗi (Troubleshooting)

## 1. Mẹo tìm kiếm Google chuẩn bài
- `site:stackoverflow.com "đoạn lỗi của bạn"`: Ép Google chỉ tìm kiếm trên StackOverflow.
- `"React 18" "useContext"`: Đặt trong ngoặc kép để tìm kiếm chính xác từng từ khóa.
- `git commit -amend -push`: Dùng dấu trừ `-` để loại bỏ các kết quả rác không liên quan.

## 2. Cách đọc StackOverflow & GitHub Issues
- **StackOverflow:** Tìm đọc các câu trả lời có tích xanh (Accepted Answer) hoặc nhiều upvote. Tránh đọc mấy bài viết từ 5-7 năm trước vì công nghệ thay đổi nhiều rồi.
- **GitHub Issues:** Vào tab **Closed**, gõ từ khóa lỗi vào xem người ta fix bằng cách nào, thường sẽ có phần workaround khá hữu ích.

## 3. Cách ném Prompt cho AI gỡ lỗi

[NGỮ CẢNH]: Đang chạy Node.js v18 trên Windows 11, gõ lệnh npm run dev.
[LỖI NGUYÊN VĂN]: Error: Cannot find module 'express' at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
[YÊU CẦU]: Giải thích ngắn gọn lý do bị lỗi và hướng dẫn các lệnh cần gõ để sửa dứt điểm.

## 4. Mẫu báo lỗi (Bug Report) khi nhờ IT hỗ trợ

1. CONTEXT (Môi trường đang dùng):
- OS: Windows 11 Home
- Môi trường: Node.js v18.16.0 / Chrome Profile TechNova_Work
- Thao tác: Gõ lệnh npm install để kéo thư viện dự án.

2. EXPECTED RESULT (Mong muốn nhận được):
- Cài xong các gói phụ thuộc mượt mà không lỗi lầm.

3. ACTUAL RESULT (Thực tế xảy ra):
- Lệnh bị đứng ngang và văng ra mã lỗi ERESOLVE.

4. LOGS & SCREENSHOTS (Chi tiết lỗi):
- Dán log nguyên văn: [Paste log lỗi vào đây]
- Ảnh chụp màn hình: [Đính kèm link ảnh nếu có]
