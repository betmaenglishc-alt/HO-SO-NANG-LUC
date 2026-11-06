# BETMA ENGLISH – Landing page hồ sơ năng lực

Trang tĩnh (HTML/CSS/JS thuần), không cần cài đặt hay build.

## Cấu trúc

```
index.html                        Trang chính
assets/images/                    Toàn bộ ảnh dùng trong trang (anh-01.jpg ...)
BETMA-ENGLISH-ho-so-nang-luc.pdf  Bản PDF của trang
.nojekyll                         Báo GitHub Pages phục vụ file nguyên trạng
```

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub (ví dụ `betma-english`).
2. Tải lên **toàn bộ nội dung** của thư mục này, giữ nguyên thư mục `assets/images`.
3. Vào **Settings → Pages**, ở mục *Build and deployment* chọn *Deploy from a branch*, nhánh `main`, thư mục `/ (root)`, rồi lưu.
4. Sau ít phút, trang chạy tại `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

Muốn dùng tên miền riêng, thêm tên miền ở mục *Custom domain* trong cùng trang Settings → Pages.

## Chỉnh sửa

- Đổi ảnh: thay file cùng tên trong `assets/images/` (cạnh dài khoảng 900–1500px, định dạng JPG).
- Đổi chữ, số liệu: sửa trực tiếp trong `index.html`.
- Phông Be Vietnam Pro tải từ Google Fonts, cần có internet khi xem.
