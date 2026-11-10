# Checklist An toàn Thông tin

## 1. Quản lý pass bằng Bitwarden
- [ ] Bật tính năng tạo mật khẩu ngẫu nhiên từ **16 - 32 ký tự** (có đủ chữ hoa, thường, số, ký tự đặc biệt).
- [ ] Quy tắc sống còn: **1 tài khoản dùng 1 mật khẩu riêng**. Không dùng chung pass cho nhiều nơi.
- [ ] Cấm tuyệt đối việc lưu pass ra file Notepad hay dán giấy note lên màn hình.

## 2. Bật xác thực 2 bước (2FA / TOTP)
- [ ] Cài App Authenticator (Google Authenticator hoặc Bitwarden) để nhận mã cho GitHub và mail cty.
- [ ] Tránh dùng SMS OTP vì rất dễ dính trò đổi sim trộm (SIM swapping).
- [ ] Lưu lại đống **Backup Codes** vào phần ghi chú bảo mật trong Bitwarden.

## 3. Nhận biết lừa đảo & Quy tắc 5 KHÔNG

### Chiêu trò hay gặp
- **Phishing:** Mail giả mạo sếp hoặc IT bắt click vào link lạ để đổi pass.
- **Typosquatting:** Tên miền nhái kiểu `techn0va.io` nhìn qua tưởng thật.
- **Phần mềm Crack:** Tải app lậu về máy dễ dính mã độc tống tiền (Ransomware).

### Quy tắc 5 KHÔNG
1. **KHÔNG** dùng chung mật khẩu cá nhân cho tài khoản công ty.
2. **KHÔNG** bấm bừa vào link lạ hoặc file đính kèm từ người không quen.
3. **KHÔNG** cắm USB không rõ nguồn gốc vào máy tính làm việc.
4. **KHÔNG** tải phần mềm crack, lậu về máy công ty.
5. **KHÔNG** đưa mã OTP hay pass cho bất kỳ ai, kể cả anh em IT.

## 4. Giấu kỹ Secrets (.env & .gitignore)
- Tuyệt đối không gõ trực tiếp API Key hay pass database vào mã nguồn.
- Điền ngay tên file `.env` vào trong `.gitignore` trước khi gõ lệnh `git commit` đầu tiên.
