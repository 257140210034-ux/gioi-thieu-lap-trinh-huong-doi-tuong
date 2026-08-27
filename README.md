# GIỚI THIỆU VỀ LẬP TRÌNH HƯỚNG ĐỐI TƯỢNG

## 1. Thành viên nhóm

| STT | Họ và tên | Vai trò | Nội dung phụ trách | Branch |
|---|---|---|---|---|
| 1 | Nguyễn Đàm Hương Giang | Leader | Phương pháp tiếp cận hướng đối tượng | main |
| 2 | Đàm Thị Lan Anh | Thành viên | Phân tích và thiết kế hướng đối tượng – Phần 1 | branch-lananh |
| 3 | Trần Bảo Chi | Thành viên | Phân tích và thiết kế hướng đối tượng – Phần 2 | branch-baochi |
| 4 | Phạm Lê Nhật Minh | Thành viên | Các khái niệm cơ bản – Phần 1 | branch-nhatminh |
| 5 | Nguyễn Ngọc Bảo Trang | Thành viên | Các khái niệm cơ bản – Phần 2 | branch-baotrang |

## 2. Nội dung

### 2.1. Phương pháp tiếp cận hướng đối tượng

#### 2.1.1. Phương pháp lập trình hướng đối tượng

- Khắc phục những hạn chế của lập trình hướng cấu trúc.
- Đóng gói dữ liệu.
- Cho phép sử dụng lại mã nguồn.

#### 2.1.2. Phương pháp phân tích và thiết kế hướng đối tượng

Quá trình phân tích và thiết kế hướng đối tượng gồm:

1. Mô tả bài toán.
2. Đặc tả yêu cầu.
3. Trích chọn đối tượng.
4. Mô hình hóa lớp đối tượng.
5. Thiết kế tổng quan.
6. Thiết kế chi tiết.

### 2.2. Các khái niệm cơ bản

#### 2.2.1. Đối tượng

Đối tượng là các thực thể trong hệ thống hoạt động khi chương trình đang chạy.

Một đối tượng được xác định bằng ba yếu tố:

- Định danh.
- Trạng thái.
- Hoạt động của đối tượng.

#### 2.2.2. Lớp đối tượng

Lớp là một khái niệm trừu tượng, dùng để chỉ một tập hợp các đối tượng có mặt trong hệ thống.

Đối tượng là một thể hiện cụ thể của lớp, là một thực thể tồn tại trong hệ thống.

#### 2.2.3. Trừu tượng hóa đối tượng theo chức năng

Là quá trình mô hình hóa phương thức của lớp dựa trên các hành động của các đối tượng.

Các bước tiến hành:

- Tập hợp tất cả các hành động có thể có của các đối tượng.
- Nhóm các đối tượng có các hoạt động tương tự nhau.
- Mỗi nhóm đối tượng đề xuất một lớp tương ứng.
- Các hành động chung của nhóm đối tượng sẽ cấu thành các phương thức của lớp tương ứng.

#### 2.2.4. Trừu tượng hóa đối tượng theo dữ liệu

Là quá trình mô hình hóa các thuộc tính của lớp dựa trên các thuộc tính của các đối tượng tương ứng.

### 2.3. Các tính chất cơ bản

#### 2.3.1. Kế thừa

- Cho phép lớp dẫn xuất sử dụng các thuộc tính và phương thức của lớp cơ sở.
- Giúp tránh việc cài đặt trùng lặp mã nguồn.
- Khi cần thay đổi dữ liệu của các lớp, có thể chỉ cần thay đổi một lần ở lớp cơ sở.

#### 2.3.2. Đóng gói

- Cho phép che dấu sự cài đặt chi tiết bên trong của phương thức.
- Cho phép che dấu dữ liệu bên trong của đối tượng.
- Hạn chế tối đa việc sửa lại mã chương trình.

#### 2.3.3. Đa hình

- Cho phép các lớp định nghĩa các phương thức trùng nhau.
- Khi gọi các phương thức trùng tên, dựa vào đối tượng đang gọi mà chương trình sẽ thực hiện phương thức của lớp tương ứng.

## 3. Phân công chi tiết

### Nguyễn Đàm Hương Giang – Leader
- Quản lý Repository.
- Tạo và cập nhật README.md.
- Phụ trách phương pháp tiếp cận hướng đối tượng.

### Đàm Thị Lan Anh
- Mô tả bài toán.
- Đặc tả yêu cầu.
- Trích chọn đối tượng.

### Trần Bảo Chi
- Mô hình hóa lớp đối tượng.
- Thiết kế tổng quan.
- Thiết kế chi tiết.

### Phạm Lê Nhật Minh
- Đối tượng.
- Lớp đối tượng.
- Trừu tượng hóa đối tượng theo chức năng.
- Trừu tượng hóa đối tượng theo dữ liệu.

### Nguyễn Ngọc Bảo Trang
- Khái niệm kế thừa.
- Khái niệm đóng gói.
- Khái niệm đa hình.
