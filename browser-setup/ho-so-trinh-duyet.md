# Setup Môi trường Trình duyệt

## 1. Tách biệt Profile trình duyệt (Data Isolation)
Đừng bao giờ gom chung tài khoản cá nhân và công việc vào một chỗ để tránh nhầm session hoặc lộ cookie:
- **Profile 1 (Personal):** Dùng cá nhân, xem phim, lướt web riêng tư.
- **Profile 2 (`TechNova_Work`):** Chỉ đăng nhập Email cty, GitHub, Jira, Figma.

## 2. Sắp xếp Bookmark gọn gàng
Ghim sẵn 3 thư mục này trên thanh Bookmark để truy cập lẹ tay:

📁 01_Work_Dev/
  ├── GitHub TechNova
  ├── Jira / Trello
  └── Figma Workspace
📁 02_Onboarding_Docs/
  ├── Nội quy công ty
  └── Quy trình làm việc
📁 03_Tools/
  ├── Bitwarden Web
  └── ChatGPT / Claude

## 3. Các Extension nên cài

### Nhóm Dev
- **JSON Viewer:** Format lại dữ liệu JSON từ API cho dễ đọc.
- **React Developer Tools:** Soi component và state khi code React.

### Nhóm Công việc
- **Loom:** Quay nhanh video màn hình kèm giọng nói để gửi bug.
- **Grammarly:** Bắt lỗi chính tả tiếng Anh khi viết mail hay viết doc.

### Nhóm Bảo mật
- **Bitwarden:** Tự động điền mật khẩu từ kho lưu trữ.
- **uBlock Origin:** Chặn quảng cáo rác, lướt web mượt hơn.

> 🔒 **Mẹo nhỏ:** Nhớ chỉnh quyền **Site Access** của đống extension này về chế độ `On click` thôi nhé, đừng cho nó đọc dữ liệu mọi trang web bạn mở.

## 4. Mẹo dùng F12 DevTools
- **Inspect Element:** Soi thẻ HTML và thử chỉnh CSS trực tiếp trên web.
- **Network Tab:** Check xem API trả về status 200 hay 500 lỗi lòi mắt.
- **Hard Reload (`Ctrl + Shift + R`):** Xóa cache trình duyệt ngay lập tức nếu thấy code vừa sửa mà web không đổi.
