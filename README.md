# AutoPost Pro — Releases

Đây là **kênh phát hành ứng dụng Windows chính thức** của AutoPost Pro. Repository này **chỉ chứa các bản phát hành EXE, thông tin phiên bản và checksum**, không chứa mã nguồn hay cấu hình của người dùng.

- **Tải ứng dụng:** [GitHub Releases](https://github.com/Hadeverl4/AutoPost-Pro-Releases/releases)
- **Cập nhật Beta:** [update/beta.json](./update/beta.json) (chỉ chuyển sang `published: true` sau khi EXE đã được xác minh và phát hành)
- **Phiên bản hiện tại:** Chưa có EXE nào được phát hành công khai.

## Cách cập nhật

Khi có bản mới, AutoPost Pro Beta có thể kiểm tra manifest qua HTTPS theo yêu cầu của người dùng, thông báo phiên bản và mở **trang Release chính thức** để tải. Ứng dụng **không tự tải/chạy/ghi đè EXE** mà không có sự đồng ý. Các bản mới sẽ ghi changelog và SHA-256 để người dùng kiểm tra file.

## Chính sách an toàn

- Không đăng `.env`, API key, mật khẩu, cookie, profile trình duyệt, video hay Excel chứa dữ liệu cá nhân.
- Không phát hành file trước khi kiểm thử frozen EXE trên Windows và xác minh SHA-256.
- Không yêu cầu người dùng chạy PowerShell tải script từ nguồn lạ.
- Không cấp quyền công khai cho repository mã nguồn Private chỉ để phân phối binary.
- Microsoft Defender/SmartScreen có thể cảnh báo với binary chưa có chữ ký số. Hãy kiểm tra nguồn và checksum trước khi chạy.

## Developer

© AutoPost Pro · FONQ II — [GitHub releases](https://github.com/Hadeverl4/AutoPost-Pro-Releases/releases).
