# Vũ Trụ Chi Chủ - Bản cài

Repo này **chỉ chứa bản cài game** (không có mã nguồn), dùng cho tính năng **tự cập nhật** trong game.

- Mỗi phiên bản là một **Release** (tag `v<phiên bản>`), gồm:
  - `VTCT_pc_<phiên bản>.zip` — bản PC (Windows). Game tự tải, giải nén đè và mở lại.
  - `VTCT_<phiên bản>.apk` — bản Android. Game tự tải rồi mở trình cài đặt.
- Game đọc link tải từ `https://thanhdi.com/server/version.json`.
- Release đánh dấu **Pre-release** là bản thử nghiệm.

Quy trình phát hành: `GameClient_NEW/docs/TU_CAP_NHAT.md` (repo client).
