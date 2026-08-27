# NEXORA Data Backup

Nhánh này chỉ chứa dữ liệu backup tự động từ VPS.
Không chứa code — xem nhánh `main` để xem code.

## Cấu trúc
- `storage/` — Toàn bộ file JSON dữ liệu (users, prompts, DNA, insights...)

## Tự động cập nhật
Cron job chạy 02:00 AM hàng ngày, commit và push lên đây.
