# LIFEQUEST AI V11.4 — Random Distinct Houses

Game học tiếng Anh, kỹ năng sống với thế giới 2D, NPC, nhiệm vụ, tương tác và chế độ AI tùy cấu hình.

## Chạy trên GitHub Pages

1. Đăng nhập GitHub và tạo repository mới (repository của bạn `lehuythevinh-byte/lifequest-ai-`).
2. Tải nội dung trong ZIP này lên **thư mục gốc** của repository: `index.html`, `README.md`, `.nojekyll` và `.gitignore`. **Đừng tải cả ZIP lên** nếu muốn chạy GitHub Pages.
3. Tại repository, mở **Settings > Pages**.
4. Ở **Build and deployment > Source**, chọn **Deploy from a branch**.
5. Chọn branch `main`, folder `/ (root)` và **Save**.
6. Khi GitHub Pages triển khai xong, website có dạng `https://lehuythevinh-byte.github.io/lifequest-ai-/`.

## Lưu ý bảo mật Gemini

- File `index.html` trong gói này đã bỏ Gemini API key được nhúng sẵn.
- Nếu key cũ từng được chia sẻ hay xuất hiện trong HTML, hãy **thu hồi / đổi key trên Google AI Studio hoặc Google Cloud**. Không đưa key thật vào GitHub, kể cả repository riêng tư nếu bạn có thể tránh được.
- GitHub Pages chỉ lưu website tĩnh, không chạy được endpoint `/api/gemini` phía máy chủ. Các chức năng offline vẫn có thể hoạt động; để dùng Gemini AI an toàn trên web công khai, triển khai backend/serverless proxy có bảo vệ riêng.
- Phaser được tải từ CDN nên trò chơi cần Internet.

## Điều khiển

Dùng WASD hoặc phím mũi tên để di chuyển, **E** để tương tác, **G** để mở menu, **K** để mở cấu hình AI.

## Nguồn

Đóng gói từ `LIFEQUEST_AI_V11_4_RANDOM_DISTINCT_HOUSES.html`. Phần mã của trò chơi được giữ nguyên, ngoại trừ việc xóa API key nhúng khỏi cấu hình.

## Repository chính xác

- GitHub: https://github.com/lehuythevinh-byte/lifequest-ai-
- Trang GitHub Pages (khi đã bật): https://lehuythevinh-byte.github.io/lifequest-ai-/
- Cấu hình Pages: https://github.com/lehuythevinh-byte/lifequest-ai-/settings/pages

> Lưu ý: Dấu gạch nối `-` cuối `lifequest-ai-` là một phần tên repository.
