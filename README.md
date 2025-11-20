# 🍜 Phở Restaurant - Website Giới thiệu và Thực đơn
<div align="center">

<div align="center">

![Repo Size](https://img.shields.io/github/repo-size/TranDucLong040904/Project_PHP_Laravel?style=flat-square&label=Size&color=orange)
![Last Commit](https://img.shields.io/github/last-commit/TranDucLong040904/Project_PHP_Laravel?style=flat-square&label=Last%20Commit&color=blue)
![Commit Activity](https://img.shields.io/github/commit-activity/y/TranDucLong040904/Project_PHP_Laravel?style=flat-square&label=Commits/Year&color=red)
![Stars](https://img.shields.io/github/stars/TranDucLong040904/Project_PHP_Laravel?style=flat-square&color=yellow)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg?style=flat-square)](https://github.com/TranDucLong040904)

</div>

</div>

## Giới thiệu chung

**Phở Restaurant** là một **mini project web tĩnh** được thiết kế để giới thiệu tổng quan về món **Phở**—món ăn truyền thống nổi tiếng của Việt Nam. Trang web bao gồm các phần về lịch sử, cách chế biến, các biến thể vùng miền (Phở Hà Nội, Phở Nam Định), và một trang thực đơn đơn giản.

Dự án này là một bài tập thực hành về **Front-end cơ bản**, tập trung vào kỹ năng thiết kế giao diện **một trang (One-Page Layout)**, sử dụng hiệu quả **HTML5** và thư viện **Bootstrap**.

---

## 👨‍💻 Về Tác Giả

Dự án được phát triển và duy trì bởi:

| Avatar | Thông tin | Liên hệ |
| :---: | :--- | :--- |
| <img src="public\images\github_circle.png" width="80" height="80" style="border-radius:50%; object-fit:cover;"/> | **Trần Đức Long** | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/TranDucLong040904)<br>[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:22010139@st.phenikaa-uni.edu.vn) |

---

## ✨ Tính năng nổi bật

* **📱 Thiết kế Responsive:** Sử dụng Bootstrap để đảm bảo giao diện hiển thị tốt trên nhiều kích thước màn hình.
* **🌐 Giao diện một trang (One-Page Layout):** Thanh điều hướng cho phép di chuyển mượt mà đến các phần khác nhau trong cùng một trang (`#section1` đến `#section6`).
* **🌗 Chế độ Sáng/Tối (Light/Dark Mode):** Nút chuyển đổi giao diện sử dụng thuộc tính `data-bs-theme` của Bootstrap (thực hiện bằng JavaScript).
* **🛒 Form Giỏ hàng/Đặt hàng:** Trang `user.html` mô phỏng giao diện nhập thông tin người dùng và thanh toán (Checkout Form) theo phong cách W3Schools.
* **🖼️ Hiệu ứng trực quan:**
    * Sử dụng hình ảnh hấp dẫn về Phở và các thành phần.
    * Hiệu ứng **ảnh xoay tròn** (CSS `animation: spin`) trong phần Giới thiệu.

---

## 🛠️ Công nghệ sử dụng

| Công nghệ | Mô tả |
| :--- | :--- |
| **HTML5** | Cung cấp cấu trúc nội dung chính của trang web. |
| **CSS3** | Tùy chỉnh kiểu dáng, màu sắc và tạo hiệu ứng (ví dụ: hiệu ứng xoay). |
| **Bootstrap 5** | Thư viện CSS/JS chính giúp xây dựng layout, hệ thống lưới (`row`/`col`), và đảm bảo tính Responsive. |
| **JavaScript (Vanilla JS)** | Xử lý các tương tác cơ bản (chuyển đổi sáng/tối, tăng/giảm số lượng sản phẩm trong modal). |

---

## 📂 Cấu trúc Mã nguồn (Code Tree)

Dự án được tổ chức theo cấu trúc thư mục tiêu chuẩn cho dự án Web Front-end:

```text

│   index.html          # Trang chủ: Giới thiệu Phở, Lịch sử, Chế biến, Thực đơn, Địa chỉ (One-Page)
│   README.md           # File này
│   user.html           # Trang Giỏ hàng/Checkout Form
│
└───static
    ├───css
    │   ├── bootstrap.css   # File Bootstrap (được tùy chỉnh nếu có)
    │   └── style.css       # File CSS tùy chỉnh (chứa các style đặc thù, hiệu ứng xoay)
    │
    ├───images          # Ảnh minh họa món ăn, logo, và các biến thể Phở
    │   └── ... (.png, .jpg)
    │
    └───js
        ├── bootstrap.js    # File JavaScript của Bootstrap
        └── main.js         # File JavaScript tùy chỉnh (chứa logic chuyển đổi mode, tăng/giảm số lượng)
```
---

## 🚀 Hướng dẫn Cài đặt & Chạy Project
Do đây là một dự án web tĩnh, việc cài đặt và chạy rất đơn giản:

1. Clone repository về máy tính của bạn.

```
Bash

git clone https://github.com/TranDucLong040904/Pho_Restaurant.git
```
2. Mở thư mục vừa clone.

3. Mở file index.html bằng bất kỳ trình duyệt web hiện đại nào (Chrome, Firefox, Edge...).

4. Để kiểm tra trang Giỏ hàng, mở file user.html.

## 📝 Nội dung Chính của Website
Nội dung trang web được chia thành các phần chính:

#section1: Trang Chủ / Phở (Giới thiệu chung về Phở).

#section2: Tin Tức / Lịch Sử Hình Thành (Nguồn gốc tại Hà Nội/Nam Định).

#section3: Chế Biến (Tập trung vào công đoạn nấu nước dùng).

#section4: Biến Tấu (So sánh Phở Hà Nội và Phở bò Nam Định).

#section5: Thực Đơn (Hiển thị các món: Tái Lăn, Nạm/Gầu, Đặc Biệt).

#section6: Địa Chỉ (Nhúng bản đồ Google Maps).

## 📜 Giấy phép (License)
Dự án này được cung cấp miễn phí sử dụng cho mục đích học tập và tham khảo cá nhân trong quá trình học tập môn học.
