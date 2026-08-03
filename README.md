# VL Pzo Vjp - VLearn nhưng Pzo Vjp hơn
Các tính năng được thêm vào:
- Tạo quiz tương tác trực tiếp theo slide, nhóm slide, toàn bộ slide
- Tạo flashcard tương tác trực tiếp theo slide, nhóm slide, toàn bộ slide
- Tóm tắt theo slide đang hiển thị, nhóm slide, toàn bộ slide
- Tạo mindmap theo slide, nhóm slide, toàn bộ slide
- Lưu quiz, flashcard, mindmap để xem lại sau này
- Chia dữ liệu theo bài
- Tải xuống slide trực tiếp
- Tự parse dữ liệu slide
- Và còn nhiều tính năng khác

# Hướng dẫn cài đặt Userscript **VL Pzo Vjp** bằng Tampermonkey

Userscript **VL Pzo Vjp** được cài đặt thông qua tiện ích **Tampermonkey**. Hướng dẫn dưới đây áp dụng cho **Google Chrome** và **Mozilla Firefox**.

---

# Yêu cầu

* Google Chrome hoặc Mozilla Firefox phiên bản mới.
* Đã kết nối Internet.
* Quyền cài đặt tiện ích mở rộng trên trình duyệt.

Script cài đặt:

**[https://github.com/nayumiDEV/K4-hackathon-VipCyberLord-E403/raw/refs/heads/main/dist/vlpzovjp.user.js](https://github.com/nayumiDEV/VLPzoVjp/raw/refs/heads/main/dist/vlpzovjp.user.js)**

---

# Hướng dẫn trên Google Chrome

## Bước 1. Cài đặt Tampermonkey

1. Truy cập trang chính thức của Tampermonkey:

   https://www.tampermonkey.net/

2. Chọn **Chrome**.

3. Nhấn **Get from Store**.

4. Chọn **Thêm vào Chrome (Add to Chrome)**.

5. Xác nhận **Add extension** để hoàn tất cài đặt.

---

## Bước 2. Bật quyền User Scripts (nếu Chrome yêu cầu)

Trên các phiên bản Chrome mới (Chrome 138+), Tampermonkey cần được cấp quyền chạy Userscript.

1. Mở:

```
chrome://extensions
```

2. Chọn **Tampermonkey**.

3. Bật tùy chọn:

```
Allow User Scripts
```

Nếu trình duyệt của bạn chưa có tùy chọn này, hãy bật **Developer Mode** ở góc trên bên phải.

---

## Bước 3. Cài đặt VL Pzo Vjp

Sau khi Tampermonkey đã được cài đặt:

Mở đường dẫn:

[https://github.com/nayumiDEV/K4-hackathon-VipCyberLord-E403/raw/refs/heads/main/dist/vlpzovjp.user.js](https://github.com/nayumiDEV/VLPzoVjp/raw/refs/heads/main/dist/vlpzovjp.user.js)

Tampermonkey sẽ tự động mở cửa sổ cài đặt.

Chọn:

```
Install
```

Sau vài giây, script sẽ được thêm vào Tampermonkey.

---

## Bước 4. Kiểm tra

* Nhấn biểu tượng Tampermonkey trên thanh công cụ.
* Đảm bảo **VL Pzo Vjp** đang ở trạng thái **Enabled**.
* Nếu chưa, chỉ cần bật công tắc của script.

---

# Hướng dẫn trên Mozilla Firefox

## Bước 1. Cài đặt Tampermonkey

1. Truy cập:

https://www.tampermonkey.net/

2. Chọn **Firefox**.

3. Chọn **Add to Firefox**.

4. Chấp nhận các quyền được yêu cầu.

5. Nhấn **Add** để cài đặt.

---

## Bước 2. Cài đặt VL Pzo Vjp

Sau khi Tampermonkey đã được cài đặt:

Mở:

https://github.com/nayumiDEV/K4-hackathon-VipCyberLord-E403/raw/refs/heads/main/dist/vlpzovjp.user.js

Firefox sẽ chuyển sang Tampermonkey và hiển thị cửa sổ cài đặt.

Nhấn:

```
Install
```

Script sẽ được thêm vào danh sách Userscript của Tampermonkey.

---

## Bước 3. Kiểm tra

* Nhấn biểu tượng Tampermonkey.
* Kiểm tra **VL Pzo Vjp** đã được bật.
* Nếu chưa bật, chỉ cần gạt công tắc sang **Enabled**.

---

# Cập nhật script

Nếu tác giả phát hành phiên bản mới, Tampermonkey sẽ tự động kiểm tra và thông báo cập nhật (nếu script hỗ trợ cập nhật tự động).

Bạn cũng có thể cập nhật thủ công:

* Mở Tampermonkey Dashboard.
* Chọn **Utilities** hoặc **Check for Userscript Updates**.
* Cập nhật lên phiên bản mới nếu có.

---

# Gỡ cài đặt

1. Mở Tampermonkey Dashboard.
2. Chọn **VL Pzo Vjp**.
3. Nhấn **Delete** hoặc biểu tượng thùng rác.
4. Xác nhận xóa.

---

# Khắc phục sự cố

### Script không tự cài khi mở liên kết

* Kiểm tra Tampermonkey đã được cài đặt.
* Làm mới trang và mở lại liên kết script.
* Đảm bảo Tampermonkey đang được bật.

---

### Chrome báo không thể chạy Userscript

Hãy mở:

```
chrome://extensions
```

và bật:

* **Allow User Scripts**

hoặc

* **Developer Mode** (đối với một số phiên bản Chrome).

---

### Script đã cài nhưng không hoạt động

Kiểm tra:

* Script đang ở trạng thái **Enabled**.
* Làm mới trang web (F5 hoặc Ctrl + F5).
* Nếu vẫn không hoạt động, hãy thử tắt và bật lại script trong Tampermonkey.

---

## Liên kết cài đặt nhanh

**Tampermonkey**

https://www.tampermonkey.net/

**VL Pzo Vjp**

https://github.com/nayumiDEV/K4-hackathon-VipCyberLord-E403/raw/refs/heads/main/dist/vlpzovjp.user.js