FIT90 PWA - CÀI ĐẶT TRÊN IPHONE

1. Giải nén và upload NGUYÊN nội dung thư mục fit90_pwa lên HTTPS hosting tĩnh (Cloudflare Pages, GitHub Pages, S3 + CloudFront).
2. Đảm bảo index.html, sw.js, manifest.webmanifest và thư mục icons cùng cấp như trong ZIP.
3. Mở URL HTTPS bằng Safari trên iPhone, chờ ứng dụng tải thành công ít nhất một lần.
4. Chia sẻ (Share) → Add to Home Screen (Thêm vào Màn hình chính) → Add. Sau đó mở bằng icon Fit90.
5. Để kiểm tra offline: mở một lần khi có mạng → bật chế độ máy bay → mở icon Fit90. Video YouTube cần có mạng.
6. Dữ liệu lưu local trên từng trình duyệt/app và không tự đồng bộ. Xuất JSON trong mục Thống kê để sao lưu, nhập JSON để chuyển dữ liệu.
7. Nếu đang dùng HTML file:// hoặc origin khác, dữ liệu KHÔNG tự chuyển sang PWA: xuất JSON từ bản cũ và nhập ở bản mới.
8. Không chạy PWA đầy đủ từ file://; service worker cần HTTPS (hoặc localhost để thử nghiệm trên máy tính).

Không sử dụng dịch vụ backend hoặc database. Không có nội dung/video YouTube được đưa vào gói offline.
