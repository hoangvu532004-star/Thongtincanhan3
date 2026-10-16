# My Portfolio - Bài tập 36 GitHub Pages

## Cấu trúc thư mục
```
my-portfolio/
├── index.html      (Trang chủ)
├── about.html      (Giới thiệu)
├── contact.html    (Liên hệ)
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
    └── avatar.jpg  (Thay bằng ảnh cá nhân của bạn)
```

## Các bước deploy lên GitHub Pages
1. Đăng nhập GitHub → bấm **New repository** → đặt tên `my-portfolio` → Public → Create.
2. Upload toàn bộ file trong thư mục này lên repo (kéo-thả trên web, hoặc dùng git):
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<username>/my-portfolio.git
   git push -u origin main
   ```
3. Vào repo → **Settings** → **Pages** → Branch: `main` / `/root` → **Save**.
4. Chờ 1-2 phút → truy cập: `https://<username>.github.io/my-portfolio/`

## Lưu ý
- Thay "Nguyễn Văn A" bằng tên thật của bạn trong tất cả file `.html` và `js/script.js`.
- Thay `images/avatar.jpg` bằng ảnh cá nhân (giữ nguyên tên file).
- Cập nhật email / GitHub / Facebook trong `contact.html`.
