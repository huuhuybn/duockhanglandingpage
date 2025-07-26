# Dược Khang Landing Page

Website landing page cho công ty Dược Liệu Dược Khang, được xây dựng bằng Astro.

## Cấu trúc dự án

```
duockhanglandingpage/
├── astro-site/          # Dự án Astro (source code)
│   ├── src/
│   │   └── pages/       # Các trang .astro
│   ├── public/          # Assets tĩnh
│   └── dist/            # Build output
├── *.html               # Các file HTML đã build
├── style.css            # CSS styles
├── favicon.ico          # Favicon
└── README.md           # File này
```

## Các trang chính

- **index.html** - Trang chủ
- **about.html** - Giới thiệu công ty
- **products.html** - Danh sách sản phẩm
- **blog.html** - Blog và bài viết
- **contact.html** - Liên hệ
- **faq.html** - Câu hỏi thường gặp

## Cách phát triển

### 1. Chỉnh sửa nội dung

Để chỉnh sửa nội dung, hãy sửa các file `.astro` trong thư mục `astro-site/src/pages/`:

```bash
cd astro-site
# Chỉnh sửa các file .astro trong src/pages/
```

### 2. Build dự án

Sau khi chỉnh sửa, build lại dự án:

```bash
cd astro-site
npm run build
```

### 3. Copy files đã build

Copy các file đã build từ `dist/` lên thư mục gốc:

```bash
cp dist/*.html ../
cp dist/style.css ../
```

### 4. Commit và push

```bash
git add .
git commit -m "Cập nhật nội dung"
git push origin main
```

## Chạy development server

Để xem preview trong quá trình phát triển:

```bash
cd astro-site
npm run dev
```

Truy cập: http://localhost:4321

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