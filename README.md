## Demo web ebook tác phẩm Việt Nam

Trang web tĩnh đơn giản để đọc ebook các tác phẩm Việt Nam, có:

- **Mục lục** bên trái, chuyển nhanh giữa các chương.
- **Tìm kiếm** theo từ khoá trong toàn bộ nội dung (tiêu đề, tóm tắt, đoạn văn).
- **Gợi ý clip minh hoạ** cho những đoạn khó hình dung, mở dạng pop-up video.
- **Giao diện** nhẹ, dễ dùng, màu sắc trung tính nhưng tương phản rõ.

### Cách chạy

- Cách 1: Mở trực tiếp file `index.html` bằng trình duyệt (Chrome, Edge, Firefox...).
- Cách 2 (khuyến nghị hơn): dùng một web server tĩnh, ví dụ:

```bash
cd BWDEMO
npx serve .
```

Sau đó mở địa chỉ được in ra (thường là `http://localhost:3000`).

### Cách mở rộng

- Thêm chương mới: chỉnh trong `script.js`, mảng `book.chapters`.
- Thêm sách mới: có thể nhân bản cấu trúc `book`, sau đó thêm UI chọn sách.
- Thay link video demo bằng clip thật của bạn trong trường `url` của `mediaHints`.

