# 🎬 FilmResource — Kho Tài Nguyên Làm Phim

Mẫu website tĩnh miễn phí, phù hợp để đăng lên GitHub Pages.

## Cấu trúc

- `index.html` — giao diện chính
- `style.css` — giao diện
- `script.js` — tìm kiếm và lọc danh mục
- `downloads/` — đặt các file ZIP/PNG/MP3/project thật của bạn vào đây

## Thêm tài nguyên

Trong `index.html`, sao chép một thẻ `<article class="resource-card">...</article>` rồi sửa:
- tên tài nguyên
- mô tả
- loại file
- số lượng file
- đường dẫn trong `href`

Ví dụ:
`href="downloads/my-pack.zip"`

## Đưa website lên GitHub Pages

1. Tạo repository trên GitHub.
2. Upload toàn bộ file/thư mục này.
3. Vào Settings → Pages.
4. Chọn Deploy from branch → `main` → `/ (root)`.
5. Lưu lại và mở địa chỉ GitHub Pages được cung cấp.
