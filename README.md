# zcloner-config

Tệp cấu hình công khai cho ứng dụng zCloner: thời hạn bản dùng thử, phiên bản mới nhất, thông báo.

`zcloner.json` được ký bằng khóa Ed25519 của zCloner Team; ứng dụng chỉ nhận tệp có chữ ký hợp lệ. Sửa tay tệp này sẽ làm chữ ký không còn hợp lệ.

Không chỉnh sửa trực tiếp: sửa `config/zcloner.config.json` trong mã nguồn zCloner, chạy `npm run sign-config`, rồi chép `config/zcloner.json` vào đây.
