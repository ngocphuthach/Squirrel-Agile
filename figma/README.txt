# Squirrel Banking App

## 1. Giới thiệu dự án

**Squirrel Banking App** là một ứng dụng web mô phỏng hệ thống quản lý tài khoản ngân hàng cá nhân. Dự án được xây dựng nhằm phục vụ bài thực hành môn Công nghệ phần mềm, tập trung vào quy trình phát triển phần mềm theo mô hình Agile/Scrum, quản lý công việc bằng Jira, thiết kế giao diện bằng Figma và quản lý mã nguồn bằng Git/GitHub.

Ứng dụng cho phép người dùng thực hiện các thao tác cơ bản như đăng ký, đăng nhập, xem thông tin tài khoản, xem số dư, xem lịch sử giao dịch, thêm giao dịch và xóa giao dịch.

---

## 2. Mục tiêu dự án

Dự án được thực hiện với các mục tiêu chính:

- Hiểu cách mô tả nhu cầu của một dự án phần mềm.
- Biết cách xây dựng Product Backlog và Sprint Backlog.
- Biết cách tạo và quản lý Issue trong Jira.
- Biết cách làm việc nhóm bằng Git và GitHub.
- Biết cách tạo branch, commit, push và pull request.
- Thiết kế giao diện hệ thống bằng Figma.
- Xây dựng cấu trúc ban đầu cho ứng dụng web ngân hàng cá nhân.

---

## 3. Chức năng chính

Các chức năng chính của hệ thống gồm:

### Đăng nhập

Người dùng có thể đăng nhập vào hệ thống bằng email và mật khẩu.

### Đăng ký

Người dùng có thể tạo tài khoản mới bằng cách nhập các thông tin cần thiết.

### Xem thông tin tài khoản

Người dùng có thể xem thông tin tài khoản cá nhân, bao gồm:

- Tên chủ tài khoản
- Số tài khoản
- Trạng thái tài khoản
- Số dư hiện tại

### Xem lịch sử giao dịch

Người dùng có thể xem danh sách các giao dịch đã thực hiện.

### Thêm giao dịch

Người dùng có thể thêm giao dịch mới, bao gồm:

- Tên giao dịch
- Số tiền
- Loại giao dịch: thu nhập hoặc chi tiêu
- Ghi chú giao dịch

### Xóa giao dịch

Người dùng có thể xóa giao dịch đã tạo trước đó.

### Bảo mật

Hệ thống dự kiến tích hợp các cơ chế bảo mật như:

- Xác thực người dùng
- Mã hóa mật khẩu
- Quản lý phiên đăng nhập
- Bảo vệ dữ liệu cá nhân

---

## 4. Công nghệ sử dụng

Dự án sử dụng các công nghệ và công cụ sau:

| Công nghệ / Công cụ | Mục đích |
|---|---|
| HTML | Xây dựng cấu trúc giao diện |
| CSS | Thiết kế giao diện người dùng |
| JavaScript | Xử lý tương tác phía client |
| Node.js | Nền tảng chạy JavaScript phía server |
| Express.js | Xây dựng API back-end |
| MongoDB | Lưu trữ dữ liệu trong phiên bản nâng cấp |
| Figma | Thiết kế giao diện |
| Jira | Quản lý dự án Agile/Scrum |
| Git | Quản lý phiên bản mã nguồn |
| GitHub | Lưu trữ repository và làm việc nhóm |

---

## 5. Thành viên nhóm

| Nickname | Vai trò / Công việc |
|---|---|
| Arcanine | Quản lý dự án, tạo repository, xử lý một số chức năng chính |
| Basculin | Thiết kế giao diện, tạo thư mục solution, xây dựng file index.html |
| Cascoon | Hỗ trợ giao diện, xử lý JavaScript và merge nhánh |

---

## 6. Product Backlog

| ID | Nội dung |
|---|---|
| PBI1 | Xây dựng chức năng đăng nhập và đăng ký |
| PBI2 | Xây dựng trang tổng quan Dashboard |
| PBI3 | Xây dựng chức năng thêm và xóa giao dịch |
| PBI4 | Tích hợp bảo mật cho hệ thống |

---

## 7. Sprint Backlog

| Sprint | Nội dung |
|---|---|
| Sprint 1 | Xây dựng giao diện đăng nhập và đăng ký |
| Sprint 2 | Xây dựng trang tổng quan hiển thị thông tin tài khoản và số dư |
| Sprint 3 | Xây dựng chức năng thêm và xóa giao dịch |
| Sprint 4 | Tối ưu bảo mật, thiết kế cơ sở dữ liệu và kiểm thử |

---

## 8. Cấu trúc thư mục dự án

```text
Squirrel-Agile/
│
├── figma/
│   └── figma-Basculin.svg
│
├── solution/
│   └── index.html
│
├── api/
│   └── server.js
│
├── README.md
│
└── .git/