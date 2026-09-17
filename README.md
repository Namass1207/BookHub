# BOOKHUB - Ứng dụng quản lý cửa hàng sách

BOOKHUB là dự án website mô phỏng **quản lý cửa hàng sách**, được xây dựng bằng HTML, CSS và JavaScript.

Dự án tập trung vào giao diện và các chức năng phía frontend. Dữ liệu được lưu trữ bằng `localStorage` để mô phỏng hoạt động của hệ thống mà **không sử dụng backend hoặc database**.

## Công nghệ sử dụng

- HTML5
- CSS3
- JavaScript
- localStorage
- Git / GitHub

## Cấu trúc dự án

```text
BOOKHUB/
│
├── index.html
│
├── customer/
│   ├── login.html
│   ├── register.html
│   ├── profile.html
│   ├── products.html
│   ├── product-detail.html
│   ├── cart.html
│   ├── checkout.html
│   └── orders.html
│
├── admin/
│   ├── login.html
│   ├── dashboard.html
│   ├── customers.html
│   ├── categories.html
│   ├── products.html
│   ├── imports.html
│   ├── prices.html
│   ├── orders.html
│   └── inventory.html
│
├── css/
│   ├── style.css
│   ├── customer.css
│   └── admin.css
│
├── js/
│   ├── main.js
│   ├── auth.js
│   ├── storage.js
│   ├── products.js
│   ├── product-detail.js
│   ├── cart.js
│   ├── checkout.js
│   ├── orders.js
│   └── admin/
│       ├── dashboard.js
│       ├── customers.js
│       ├── categories.js
│       ├── products.js
│       ├── imports.js
│       ├── prices.js
│       ├── orders.js
│       └── inventory.js
│
├── data/
│   ├── books.js
│   ├── categories.js
│   └── users.js
│
├── images/
│   ├── logo/
│   ├── books/
│   └── banners/
│
└── README.md
```

## Chức năng chính

### Khách hàng

- Đăng ký tài khoản
- Đăng nhập / đăng xuất
- Xem và cập nhật thông tin cá nhân
- Xem danh sách sách
- Xem chi tiết sách
- Tìm kiếm sách
- Lọc sách theo danh mục
- Thêm sách vào giỏ hàng
- Tăng / giảm số lượng sản phẩm
- Xóa sản phẩm khỏi giỏ hàng
- Tính tổng tiền
- Thanh toán và tạo đơn hàng
- Xem lịch sử đơn hàng

### Quản trị viên

- Đăng nhập trang quản trị
- Xem dashboard
- Quản lý khách hàng
- Quản lý danh mục sách
- Quản lý sách
- Quản lý nhập sách
- Quản lý giá
- Quản lý đơn hàng
- Quản lý tồn kho

## Lưu trữ dữ liệu

Dự án không sử dụng MySQL, MongoDB hoặc database/server backend.

Dữ liệu demo được xử lý bằng JavaScript và lưu trong trình duyệt thông qua:

```javascript
localStorage
```

Cách này phù hợp với mục đích **demo/prototype frontend** của dự án. Dữ liệu `localStorage` chỉ tồn tại trên trình duyệt và thiết bị đang sử dụng.

## Cách chạy dự án

### Cách 1: Mở trực tiếp

Mở file:

```text
index.html
```

bằng trình duyệt.

### Cách 2: Sử dụng VS Code

Có thể sử dụng extension **Live Server** trong Visual Studio Code.

1. Mở thư mục `BOOKHUB` bằng VS Code.
2. Mở file `index.html`.
3. Chọn **Open with Live Server**.
4. Website sẽ được chạy trên trình duyệt.

## Lưu ý

Đây là dự án frontend mô phỏng hệ thống quản lý cửa hàng sách.

- Không có server backend.
- Không có database thật.
- Không nên sử dụng dữ liệu cá nhân hoặc mật khẩu thật.
- Dữ liệu đăng nhập, giỏ hàng và đơn hàng chỉ phục vụ mục đích demo.
- Khi xóa dữ liệu trình duyệt, dữ liệu `localStorage` của website có thể bị mất.

## Mục tiêu dự án

Dự án nhằm xây dựng một website mô phỏng quy trình hoạt động của cửa hàng sách, bao gồm hai nhóm người dùng:

- **Khách hàng:** tìm kiếm, xem sách, thêm vào giỏ hàng và đặt hàng.
- **Quản trị viên:** quản lý khách hàng, sách, danh mục, giá, nhập hàng, đơn hàng và tồn kho.

---

**BOOKHUB — Bookstore Management System**
