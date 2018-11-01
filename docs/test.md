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

- Truy cập **Trắc nghiệm / Quản lý xếp loại** (menu dọc)
- Mặc định, AZtest cấu hình sẵn 05 mốc xếp loại phổ biến, bạn có thể thay đổi các giá trị phù hợp với yêu cầu.

![](./images/test/quan-ly-xep-loai.png)

## Quản lý đề thi

> Để bắt đầu tạo một đề thi mới, bạn hãy chắc chắn đã đọc và thực hiện xong các yêu cầu tại [Các thiết lập ban đầu](/test/#cac-thiet-lap-ban-au)

Truy cập **Trắc nghiệm (1) / Đề thi (2)** (menu dọc)

![](./images/test/quan-ly-de-thi.png)

### Tạo đề thi mới

Trên giao diện **Quản lý đề thi**, click **Thêm đề thi (3)**

![](./images/test/them-de-thi.png)

> Cần nhập đầy đủ các trường có gắn dấu sao (*) ở cuối trước khi nhấn **Cập nhật**

Giải thích các trường thông tin:

- **Tên gọi đề thi (1):**  Nhập tên đề thi. Ví dụ: Đề thi toán học kỳ 2, năm học 2017-2018
- **Liên kết tĩnh (2):** Đây là chuỗi quy định URL của một đề thi. Chuỗi này thường được tự động tạo sau khi điền xong Tiêu đề. Do đó, bạn có thể không cần quan tâm đến nó, cứ để giá trị có sẵn. Ví dụ: tương ứng với tiêu đề bên trên thì chúng ta sẽ có liên kết tĩnh tương ứng là `de-thi-toan-hoc-ky-2-nam-hoc-2017-2018`.
- **Chủ đề (3):** Chọn Chủ đề cho đề thi, danh sách đề thi quản lý tại [Quản lý đề thi](/test/#quan-ly-e-thi)
- **Hình ảnh (5):** Chọn ảnh đại diện cho đề thi, ảnh này sẽ hiển thị bên cạnh đề thi
- **Giới thiệu (6):** Mô tả ngắn gọn về nội dung đề thi
- **Nội dung (7):** Nhập nội dung mô tả chi tiết cho đề thi
- **Nhóm tham gia thi (8):** Chọn nhóm thành viên được phép thực hiện đề thi này. Xem thêm [Quản lý nhóm thành viên](/system/#quan-ly-nhom-thanh-vien)
- **Nhóm được bình luận (9):** Nhóm thành viên được phép bình luận trong trang xem chi tiết đề thi.
- **Nhóm xem đáp án sau bài làm (10):** Nhóm thành viên được phép xem đáp án sau khi làm bài.

![](./images/test/them-de-thi-1.png)

- **Hình thức kiểm tra (1):**
	- **Tự luyện:** Cho phép một thành viên thi nhiều lượt, mỗi lượt thi hệ thống sẽ tự động thay đổi vị trí các câu hỏi và đáp án. Mỗi lượt thi đều chấm điểm.
	- **Chấm điểm:** Đề thi chỉ cho phép mỗi thành viên thi một lượt và được chấm điểm. Phương án này phù hợp với việc tổ chức các kỳ thi để lấy kết quả thi.
- **Số lượng câu hỏi (2):** Nhập số lượng câu hỏi cho đề thi
- **Thang điểm (3):** Nhập thang điểm cho đề thi. Ví dụ: thang điểm 10 thì nhập là 10
- **Thời gian làm bài (4):** Nhập thời gian làm bài cho đề thi, **thời gian tính bằng đơn vị phút**.
- **Số câu hỏi trên trang (5):** Nhập số câu hỏi hiển thị trên một trang. Trường hợp đề có nhiều câu hỏi thì việc phân trang sẽ giúp tiết kiệm 
- **Phương thức nhập câu hỏi (6):**
	- **Nhập câu hỏi mới:** Sau khi thêm đề thi thành công, hệ thống sẽ chuyển bạn đến giao diện nhập nội dung câu hỏi
	- **Nhập từ Microsoft Word:** Sau khi thêm đề thi thành công, hệ thống sẽ chuyển bạn đến giao diện nhập nội dung từ file Word
- **Tích chọn các tính năng mở rộng cho đề thi (7):** 
	- **Hiển thị ngẫu nhiên câu hỏi và đáp án:** Sau mỗi lượt thi, các câu hỏi sẽ được hiển thị ngẫu nhiên, các đáp án sẽ ngẫu nhiên thay đổi vị trí.
	- **Hiển thị xếp loại sau làm bài:** Sau khi nộp bài, hệ thống căn cứ vào kết quả và xếp loại bài thi của bạn. Bạn cần cấu hình xếp loại để hiển thị đúng tiêu chí này.
	- **Lưu lịch sử làm bài:** Hệ thống tự động lưu lại lịch sử thi của thành viên
	- **Cho phép làm lại bài:** Cho phép thành viên có thể làm lại bài thi
	- **Cho phép in đề:** Hệ thống sẽ in đề thi trực tiếp

Sau khi điền đầy đủ các trường thông tin cần thiết, nhấn **Cập nhật** để thêm đề thi. Dựa vào lựa chọn **Phương thức nhập câu hỏi (6)**, hệ thống sẽ chuyển bạn đến trang tương ứng để tiếp tục nhập câu hỏi cho đề thi.

## Quản lý câu hỏi của đề thi