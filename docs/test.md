---
title: Quản trị module Trắc nghiệm
---

## Các thiết lập ban đầu

> Đây là quá trình xây dựng các dữ liệu ban đầu, phục vụ cho các tính năng khác của hệ thống. Do đó, bạn không được bỏ qua các thiết lập theo các hướng dẫn trong phần này.

### Xóa dữ liệu mẫu

Dữ liệu mẫu là dữ liệu được AZtest nhập sẵn sau khi khởi tạo website, nhằm mục đích giúp người quản trị có cái nhìn tổng quan về website của mình. Bạn cần xóa các dữ liệu này trước khi bắt đầu xây dựng nội dung website.

Để xóa dữ liệu mẫu, thực hiện theo các bước sau đây:

> Hành động này sẽ xóa hết tất cả dữ liệu của module **Trắc nghiệm**, bạn không thể khôi phục lại dữ liệu sau khi đã xóa. Việc này chỉ phù hợp với website mới, cần xóa dữ liệu demo.

- [Đăng nhập khu vực quản trị website](/start/#ang-nhap-khu-vuc-quan-tri)
- Truy cập **Quản lý modules** (menu ngang)
- Trong bảng danh sách module, tìm đến dòng có tên module là **test** (hình) 

![](./images/test/xoa-du-lieu-mau.png)  

- Click nút **Cài lại** ở cuối dòng này. Hệ thống sẽ hiển thị hộp thoại nhỏ để xác nhận thêm một lần nữa, click **Thực hiện** để đồng ý xóa.

### Thiết lập chủ đề

**Chủ đề** là đơn vị giúp phân loại đề thi trong hệ thống AZtest. Qua chủ đề, chúng ta có thể thiết lập các thuộc tính (cấu hình) riêng cho các đề thi nằm cùng một chủ đề. 

Bạn cần tạo ít nhất 01 chủ đề trước khi thực hiện các bước tiếp theo.

Xem [Quản lý chủ đề](/test/#quan-ly-chu-e)

### Thiết lập xếp loại

Xếp loại là hình thức đánh giá kết quả thi dựa vào điểm thi. Xếp loại có thể dễ dàng cấu hình theo ý của người quản trị.

Xem [Quản lý xếp loại](/test/#quan-ly-xep-loai)

## Quản lý chủ đề

Truy cập **Trắc nghiệm / Chủ đề** (menu dọc)

![](./images/test/truy-cap-quan-ly-chu-de.png)

Trên danh sách chủ đề, bạn có thể:

- Click vào Tiêu đề để truy cập đến danh sách chủ đề con
- **Hiển thị trang chủ:** Cấu hình cho phép Hiển thị / Không hiển thị chủ đề (và các đề thi thuộc chủ đề) lên trang chủ của website.
- **Số liên kết:** Quy định số đề thi cùng chủ đề được gợi ý khi xem một đề thi bất kỳ
- **Phương án hiển thị:** Quy định giao diện hiển thị đề thi khi xem chủ đề
- **Thống kê điểm cao:** Quy định giao diện hiển thị đề thi khi xem chủ đề

### Thêm chủ đề

Tại khu vực thêm chủ đề, nhập đầy đủ thông tin bắt buộc (trường có dấu sao):

- **Tiêu đề (1):** Nhập tên cho chủ đề. Ví dụ: Đề thi toán, đề thi lý, đề thi hóa,...
- **Liên kết tĩnh (2):** Phần này sẽ tự động tạo sau khi nhập xong Tiêu đề, bạn có thể sửa lại hoặc không (không được để trống)
- **Thuộc chủ đề (3):** Chọn chủ đề trực thuộc (Bạn có thể thêm chủ đề con của một chủ đề bằng cách chọn chủ đề trực thuộc)
- **Title tag (4):**  (SEO) Nhập thẻ tiêu đề, 
- **Mô tả (5):** Mô tả ngắn gọn về chủ đề.
- **Hình ảnh (6):** Chọn hình ảnh minh họa cho chủ đề. 
- **Từ khóa (8):** Nhập từ khóa tìm kiếm cho chủ đề.

![](./images/test/them-chu-de-1.png)

Sau khi nhập thông tin, nhấn nút **Cập nhật** để tiến hành thêm. Nếu thêm thành công, chủ đề mới sẽ xuất hiện trong danh sách chủ đề.

### Sửa chủ đề

- Tại danh sách các chủ đề, click nút **Sửa** ở cuối dòng
- Hành động sửa cũng như hành động [Thêm chủ đề](/test/#them-chu-e)

### Xóa chủ đề

- Tại danh sách các chủ đề, click nút **Xóa** ở cuối dòng
- Xóa chủ đề cha, cũng đồng thời xóa chủ đề con của nó
- Xóa chủ đề sẽ xóa hết các dữ liệu thuộc chủ đề đó (Đề thi, lịch sử thi,...). Bạn cần chuyển dữ liệu cần thiết sang chủ đề khác trước khi quyết định xóa một chủ đề

## Quản lý xếp loại