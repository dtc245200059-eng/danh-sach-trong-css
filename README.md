# [Thực hành] Danh sách trong CSS

Dự án bài thực hành luyện tập sử dụng các thuộc tính CSS để định kiểu cho danh sách HTML (`<ul>`, `<ol>`, `<li>`).

## 📌 Mục tiêu bài thực hành
- Sử dụng `list-style-type` để thay đổi kiểu đánh dấu danh sách (hình vuông `square`, số La Mã viết hoa `upper-roman`).
- Sử dụng `list-style-image` để tạo dấu đánh dấu bằng hình ảnh tùy chỉnh (`url('star-icon.png')`).
- Sử dụng `list-style-position` để thay đổi vị trí của dấu đánh dấu (`outside` vs `inside`).
- Sử dụng thuộc tính rút gọn `list-style` kết hợp đồng thời kiểu, vị trí và hình ảnh.
- Thay đổi màu sắc và khoảng cách của danh sách bằng `background-color`, `color`, `padding`, `margin`.
- Hoàn thành bài tập tổng hợp: "Lộ trình học lập trình Web".

---

## 🛠 Cấu trúc thư mục dự án
- `index.html`: Cấu trúc ngữ nghĩa HTML5 chứa đầy đủ 8 phần bài tập theo yêu cầu.
- `style.css`: File định kiểu CSS độc lập, liên kết qua thẻ `<link rel="stylesheet" href="style.css">`.
- `star-icon.png`: Ảnh icon tùy chỉnh sắc nét dùng cho `list-style-image`.
- `bullet-icon.png`: Ảnh icon kim cương dùng cho thuộc tính rút gọn `list-style`.
- `README.md`: Hướng dẫn và mô tả bài thực hành.

---

## 📋 Tóm tắt các mục thực hành
| Phần | Nội dung | Thẻ & Thuộc tính CSS áp dụng |
| :---: | :--- | :--- |
| **1** | Chuẩn bị | Tạo `index.html`, `style.css`, liên kết `<link>` |
| **2** | Đổi kiểu danh sách không thứ tự | `<ul>`, `list-style-type: square;` |
| **3** | Đổi kiểu danh sách có thứ tự | `<ol>`, `list-style-type: upper-roman;` |
| **4** | Dấu đánh dấu bằng hình ảnh | `<ul>`, `list-style-image: url('star-icon.png');` |
| **5** | Vị trí dấu đánh dấu | `list-style-position: outside;` & `inside;` |
| **6** | Thuộc tính rút gọn | `list-style: square inside url('bullet-icon.png');` |
| **7** | Màu sắc & Khoảng cách | `background-color`, `color`, `padding`, `margin` |
| **8** | Bài tập tổng hợp | Kết hợp toàn diện cho "Lộ trình học lập trình Web" |

---

## 🌟 Điểm nổi bật
- **Giao diện hiện đại**: Phông chữ Plus Jakarta Sans từ Google Fonts, thẻ hiển thị thuộc tính CSS code-tag rõ ràng.
- **Minh họa trực quan**: Hộp so sánh đối chiếu giữa `outside` và `inside` giúp dễ dàng quan sát sự khác biệt khi render.
- **Tương thích cao**: Ảnh icon định dạng PNG trong suốt, tối ưu responsive trên mọi kích thước màn hình.
