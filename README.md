# Dược Khang Landing Page

Website landing page cho công ty Dược Liệu Dược Khang, được xây dựng bằng Astro.

## Cấu trúc dự án

```
duockhanglandingpage/
├── astro-site/          # Dự án Astro (source code)
│   └── grubby-gamma/    # Dự án Astro đã được thiết lập
│       ├── src/
│       │   └── pages/   # Các trang .astro
│       ├── public/       # Assets tĩnh
│       └── dist/         # Build output
├── about/               # Trang giới thiệu (đã build)
├── blog/                # Trang blog (đã build)
├── contact/             # Trang liên hệ (đã build)
├── products/            # Trang sản phẩm (đã build)
├── faq/                 # Trang FAQ (đã build)
├── index.html           # Trang chủ (đã build)
├── style.css            # CSS styles
├── favicon.ico          # Favicon
└── README.md           # File này
```

## Các trang chính

- **index.html** - Trang chủ
- **about/** - Giới thiệu công ty
- **products/** - Danh sách sản phẩm
- **blog/** - Blog và bài viết
- **contact/** - Liên hệ
- **faq/** - Câu hỏi thường gặp

## Cách phát triển

### 1. Chỉnh sửa nội dung

Để chỉnh sửa nội dung, hãy sửa các file `.astro` trong thư mục `astro-site/grubby-gamma/src/pages/`:

```bash
cd astro-site/grubby-gamma
# Chỉnh sửa các file .astro trong src/pages/
```

### 2. Chạy development server

Để xem preview trong quá trình phát triển:

```bash
cd astro-site/grubby-gamma
npm run dev
```

Truy cập: http://localhost:4321

### 3. Build dự án

Sau khi chỉnh sửa, build lại dự án:

```bash
cd astro-site/grubby-gamma
npm run build
```

### 4. Copy files đã build

Copy các file đã build từ `dist/` lên thư mục gốc:

```bash
cp -r dist/* ../
```

### 5. Commit và push

```bash
git add .
git commit -m "Cập nhật nội dung"
git push origin main
```

## SEO Features

- Meta tags đầy đủ (title, description, keywords)
- Open Graph tags
- Twitter Card tags
- Schema.org JSON-LD
- Canonical URLs
- Robots meta tags
- Sitemap.xml

## Responsive Design

Website được thiết kế responsive, tương thích với:
- Desktop
- Tablet
- Mobile

## Deployment

Website được deploy trên GitHub Pages tại: https://duockhang.vn

## Công nghệ sử dụng

- **Astro** - Static Site Generator
- **HTML/CSS** - Markup và styling
- **JavaScript** - Tương tác (nếu cần)

## Liên hệ

- **Hotline:** 0913 069 855
- **Email:** duockhang1902@gmail.com
- **Địa chỉ:** 51 Nguyễn Văn Của, P. 13, Q. 8, TP. Hồ Chí Minh

## Trạng thái hiện tại

✅ Dự án Astro đã được thiết lập hoàn chỉnh
✅ Các trang chính đã được tạo và build thành công
✅ Development server đang chạy tại http://localhost:4321
✅ Tất cả các link navigation đã được cập nhật đúng định dạng
✅ SEO meta tags đã được thiết lập đầy đủ

## Công việc tiếp theo

- [ ] Thêm nội dung chi tiết cho các trang sản phẩm
- [ ] Tối ưu hóa hình ảnh và assets
- [ ] Thêm tính năng tìm kiếm
- [ ] Tích hợp analytics
- [ ] Thêm trang 404 tùy chỉnh 