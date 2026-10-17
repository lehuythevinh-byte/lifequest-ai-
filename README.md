# LIFEQUEST AI V11.6 — Clean UI & Beautiful Minimap

Bản cập nhật V11.6 của LIFEQUEST AI, đóng gói để triển khai bằng GitHub Pages trên repository hiện có:

- Repo: https://github.com/lehuythevinh-byte/lifequest-ai-
- Website khi đã bật Pages: https://lehuythevinh-byte.github.io/lifequest-ai-/

## Mã nguồn

- `index.html`: toàn bộ HTML, CSS và JavaScript của phiên bản V11.6; đổi tên từ file HTML bạn cung cấp, không thay đổi nội dung.
- `.gitignore`: tránh đưa nhầm file cấu hình riêng và bản chứa khóa bí mật lên GitHub.
- `.nojekyll`: không bật xử lý Jekyll mặc định cho GitHub Pages.

## Cập nhật qua Git Bash (không cần `git init` lại)

1. Giải nén ZIP.
2. Sao chép `index.html` và `README.md` vào thư mục repo Git đã dùng để push V11.4 (ghi đè các file cũ).
3. Mở Git Bash trong thư mục repo, chạy:

```bash
git status
git add index.html README.md
git commit -m "Update LIFEQUEST AI to V11.6"
git push origin main
```

Nếu Git báo "nothing to commit", hãy kiểm tra bạn đã thay `index.html` đúng thư mục có `.git` chưa.

## GitHub Pages

Tại Settings > Pages, chọn Deploy from a branch; branch `main`, folder `/ (root)`.
Nếu Pages đã bật từ V11.4, bản cập nhật `main` sẽ kích hoạt triển khai lại.

## Bảo mật & AI

- Trong bản nguồn này, cấu hình `GEMINI_API_KEY` rỗng; không nhúng khóa Gemini vào HTML công khai.
- GitHub Pages chỉ phục vụ nội dung tĩnh. Để dùng Gemini an toàn, cần endpoint server-side / serverless riêng, hoặc thiết lập phía người dùng với hiểu rõ rủi ro lộ key.
- Phaser tải qua Internet/CDN; mở trang cần kết nối mạng.
- Nếu API key đã từng xuất hiện trong repo/public HTML, hãy thu hồi và đổi key.

Nguồn: `LIFEQUEST_AI_V11_6_CLEAN_UI_BEAUTIFUL_MINIMAP(1).html`.
