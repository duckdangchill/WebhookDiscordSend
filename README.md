# Discord Cloud Relay 🚀

Trang web tĩnh gọn nhẹ dùng để gửi văn bản, liên kết từ máy ảo / VPS Cloud về Discord qua Webhook.

---

### ✨ Tính năng
* **Lưu Webhook tự động:** Nhập link Webhook Discord một lần, trình duyệt tự lưu vào `localStorage`. Khi cần đổi chỉ cần bấm nút `Đổi / Xóa`.
* **Định dạng theo thiết bị:**
  * 📱 **Điện thoại:** Bọc dạng `` `văn bản` `` (tiện bấm giữ copy trên app Discord mobile).
  * 💻 **Máy tính:** Bọc dạng ```` ```văn bản``` ```` (sẵn nút copy 1-click trên Discord desktop).
* **Tiện ích:** Nút xóa văn bản nhanh, tự động xóa sạch khung nhập sau khi gửi thành công.
* **Giao diện Tactile Dark / Soft Neumorphism:** Tông xám than cao cấp, trầm dịu mắt, không dùng màu neon loè loẹt, tương thích tốt trên cả trình duyệt máy tính lẫn cloud VPS.

---

### 🌐 Cách đưa lên GitHub Pages (3 bước)

1. **Đẩy mã nguồn lên GitHub:**
   ```bash
   git init
   git add .
   git commit -m "feat: initial discord cloud relay"
   git branch -M main
   git remote add origin https://github.com/<tai-khoan-cua-ban>/<ten-repo>.git
   git push -u origin main
   ```

2. **Bật GitHub Pages:**
   * Vào repository trên GitHub -> chọn **Settings**.
   * Chọn mục **Pages** ở thanh menu bên trái.
   * Tại phần **Build and deployment** -> **Branch**: chọn `main` và thư mục `/(root)` -> bấm **Save**.

3. **Sử dụng:**
   * Sau khoảng 1 phút, GitHub sẽ cấp cho bạn một đường dẫn dạng:
     `https://<tai-khoan-cua-ban>.github.io/<ten-repo>/`
   * Mở link này trên trình duyệt của máy Cloud/VPS, dán Webhook Discord vào một lần duy nhất và bắt đầu gửi văn bản về máy thật.
