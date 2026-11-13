# Ôn tập Lý luận GDTC

Website tĩnh (1 file `index.html`): tổng hợp kiến thức 7 bài, luyện trắc nghiệm 158 câu có trích nguồn, xem lại toàn bộ slide.

## Deploy lên Vercel

**Cách 1: kéo thả (nhanh nhất)**
1. Vào https://vercel.com/new rồi chọn "Deploy" bằng cách kéo thả thư mục `gdtc-vercel`.
2. Framework Preset: **Other**. Để trống Build Command và Output Directory.

**Cách 2: Vercel CLI**
```bash
npm i -g vercel
cd gdtc-vercel
vercel --prod
```

**Cách 3: GitHub**
Đẩy thư mục này lên một repo, vào Vercel chọn "Import Project" và chọn repo đó (Framework: Other).

Lưu ý: `index.html` nặng khoảng 14 MB vì đã nhúng sẵn ảnh slide, nằm trong giới hạn của Vercel cho file tĩnh.
