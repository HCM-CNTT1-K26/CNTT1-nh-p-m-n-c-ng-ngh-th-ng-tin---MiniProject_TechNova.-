# Không gian Đám mây & Quy tắc Phân quyền

## 1. Làm việc theo mô hình Hybrid (Local vs Cloud)
- **Local:** Cứ lưu file và thao tác trực tiếp trên ổ cứng máy cho nhanh, khỏi sợ độ trễ mạng làm giật lag.
- **Auto Sync:** Bật Google Drive for Desktop để nó ngầm đồng bộ file lên mây. Lỡ máy tính hỏng thì dữ liệu vẫn nằm an toàn trên cloud.

## 2. Cách đặt tên thư mục 5 trụ cột (`kebab-case`)
Toàn bộ viết thường, không dấu tiếng Việt, không khoảng trắng, nối các từ bằng dấu gạch ngang (`-`):

technova-root/
├── 01-projects/        # Code và tài liệu dự án đang chạy
├── 02-operations/      # Quy trình nội bộ, tài liệu vận hành
├── 03-resources/       # Asset thiết kế, template dùng chung
├── 04-archives/        # Dự án cũ đã xong, cất kho
└── 05-personal/        # Thư mục nháp cá nhân

## 3. Nguyên tắc chia sẻ file (Tránh share bừa bãi)

| Ai được xem? | Quyền hạn | Phạm vi áp dụng |
| :--- | :--- | :--- |
| Chính chủ | **Editor** | Thư mục cá nhân `05-personal/` |
| Anh em cùng team | **Editor** | Thư mục dự án chung `01-projects/` |
| Intern phòng khác | **Commenter** | Chỉ đọc và gõ comment góp ý |
| Khách ngoài cty | **Viewer** (Restricted) | Chỉ cấp quyền qua email cụ thể |

> ⚠️ **Cấm kỵ:** Tuyệt đối không bật chế độ *"Anyone with the link"* đi kèm quyền **Editor** cho bất kỳ tài liệu nào.

## 4. Văn hóa nhắn tin nhóm
- **Reply in Thread:** Thảo luận việc gì thì bám vào đúng message đó mà reply, đừng nhảy ra ngoài làm trôi tin nhắn chung.
- **Tag đúng người:** Cần ai thì gọi tên người đó (`@`). Đừng có hở ra là tag `@all` hay `@channel` lúc nửa đêm.
- **Vào thẳng vấn đề:** Bỏ thói quen nhắn "Hi anh" rồi ngồi đợi. Cứ phang thẳng Context + Vấn đề trong một tin nhắn duy nhất.
