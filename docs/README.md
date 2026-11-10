# TechNova Onboarding Kit

Chào mừng bạn đã gia nhập TechNova! Tài liệu này được tổng hợp như một cuốn cẩm nang bỏ túi giúp bạn tự setup xong không gian làm việc, nắm chắc nguyên tắc bảo mật và biết cách tự xử lý các lỗi vặt ngay trong ngày đầu tiên đi làm.

## Khởi động nhanh (Quick Start)

Mở Git Bash lên và chạy lần lượt mấy lệnh này để kéo code về máy:

## Clone kho lưu trữ về máy
git clone https://github.com/technova/technova-onboarding-kit.git

## Di chuyển vào thư mục dự án
cd technova-onboarding-kit

## Tạo file cấu hình môi trường từ bản mẫu
cp security/.env.example .env

## Việc cần làm ngay hôm nay

- [ ] Cài Google Drive for Desktop để bật đồng bộ file ngầm (Hybrid Workflow).
- [ ] Tách riêng 2 Profile trình duyệt (`Personal` cho cá nhân, `TechNova_Work` cho công việc).
- [ ] Cài Bitwarden, bật 2FA bằng App cho GitHub và mail công ty.
- [ ] Tạo file `.env` cá nhân và kiểm tra kỹ `.gitignore` xem đã giấu file chưa.
- [ ] Đọc qua mẫu báo lỗi để sau này có gặp bug tự gỡ hoặc gửi ticket cho IT cho nhanh.

## Danh sách tài khoản cơ bản

| Dịch vụ | Tài khoản mẫu | Quyền hạn | Mục đích dùng |
| :--- | :--- | :--- | :--- |
| Google Workspace | `ten.nv@technova.io` | User | Viết doc, lưu trữ tài liệu |
| GitHub Org | `username-cua-ban` | Member | Push code, tạo Pull Request |
| Bitwarden | `ten.nv@technova.io` | Premium | Lưu pass, API keys, secrets |
| Lark / Slack | `ten.nv@technova.io` | Member | Kênh chat trao đổi nội bộ |
