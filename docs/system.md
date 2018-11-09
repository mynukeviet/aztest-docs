---
title: Quản trị hệ thống
---

## Thay đổi thông tin website

Truy cập **Cấu hình** (Menu ngang)

![](images/system/cau_hinh_site.png)

Trong giao diện này, bạn có thể thay đổi nội dung theo mong muốn, sau đó nhấn **Lưu cấu hình** ở cuối trang để lưu lại thiết lập.

Ngoài ra, bạn cũng có thể thay đổi các thông tin nâng cao hơn tại phần **Cấu hình / Cấu hình chung** (Menu ngang)

## Cấu hình máy chủ gửi thư (Email)

Mặc định, AZtest đã thiết lập máy chủ gửi thư để website có thể gửi thư đi mà không cần cấu hình thêm. Song, AZtest cũng cung cấp giải pháp để những người am hiểu kỹ thuật có thể tự cấu hình máy chủ gửi thư của riêng họ.

Truy cập **Cấu hình / Cấu hình SMTP** (Menu ngang)

![](images/system/cau_hinh_email.png)

Trong 3 tùy chọn ở đây, chọn giao thức SMPT và điền các thông số như hình hướng dẫn rồi lưu lại.

## Quản lý module

Hệ thống AZtest được cấu thành bởi các tính năng riêng biệt (gọi là modules). Ngoài các module được kích hoạt sẵn khi khởi tạo website, bạn cũng có thể cài đặt cho website của mình nhiều module với các mục đích khác nhau.

Truy cập "**Quản lý modules**" (Menu ngang)

Tại trang chính, bạn có thể thấy danh sách các modules đã được cài đặt trước đó. Bạn có thể thực hiện các thao tác như kích hoạt, nghưng kích hoạt, sửa, cài lại và xóa modules.

![](images/system/quan_ly_module.png)

### Cài đặt module mới

Truy cập "**Quản lý modules / Thiết lập module mới**" (Menu ngang)

- Các module chưa được cài đặt sẽ hiển thị trong phần **Các module hệ thống**
- Click **Thiết lập** ở cuối mỗi module để tiến hành cài đặt
- Bạn có thể chọn cài đặt thêm dữ liệu mẫu hoặc không tại hộp thoại tiếp theo
- Click **Thiết lập** để chuyển sang bước tiếp theo

![](images/system/thiet-lap-module.png)

- Ở bước cuối cùng này, bạn có thể bỏ qua, hoặc có thể hiệu chỉnh thêm một số thông tin như mong muốn, clic **Thực hiện** nếu có thay đổi

![](images/system/thiet-lap-module-1.png)

## Thay đổi giao diện website

Truy cập **Quản lý giao diện** (Menu ngang)

![](images/system/quan_ly_giao_dien.png)

Tại đây, bạn có thể chọn một trong các giao diện có sẵn để sử dụng cho website của mình bằng cách rê chuột lên (ảnh đại diện) của giao diện, chọn **Kích hoạt sử dụng**.

Sau khi kích hoạt, bạn có thể quay trở lại trang chủ đề xem website với giao diện mới.

## Quản lý nhóm thành viên

Truy cập "**Tài khoản / Nhóm thành viên**" (Menu dọc)

![](images/system/nhom_thanh_vien.png) 

Trên giao diện này, bạn có thể sửa, xóa các nhóm thành viên

> Các nhóm ở vị trí 1, 2, 3, 4 là các nhóm mặc định của hệ thống, bạn không thể sửa hoặc xóa cũng như ngưng kích hoạt chúng

### Thêm nhóm

Trên giao diện danh sách nhóm, click nút **Thêm nhóm**
 
![](images/system/them_nhom_thanh_vien.png)

Trên giao diện này, bạn chỉ cần nhập **Tên nhóm** (các trường có dấu sao (*)), các thông tin khác có thể bỏ qua

Click **Lưu** ở cuối trang để hoàn tất

## Quản lý tài khoản thành viên

Truy cập **Tài khoản** (menu dọc)

![](images/system/tai_khoan.png)

### Thêm tài khoản

Truy cập **Tài khoản / Thêm tài khoản mới** 

![](images/system/them_tai_khoan.png)

Bảng mô tả một số thông tin quan trọng

| Thông tin     | Bắt buộc         | Mô tả		   |
|---------------|------------------|---------------|
| Tài khoản 	| Có | Tên truy cập. Tên truy cập không được trùng nhau. Quy tắc đặt tên truy cập được quy định tại **Tài khoản / Cấu hình module / Các ký tự cho phép khi tạo tài khoản** |
| Email 	| Có | Email liên hệ. Bạn cần cung cấp một email đúng để có thể tương tác với thành viên về sau |
| Mật khẩu 	| Có | Mật khẩu truy cập. Quy tắc đặt tên truy cập được quy định tại **Tài khoản / Cấu hình module / Số ký tự của mật khẩu** |
| Họ và tên	| Có | Họ tên thật của thành viên |
| Hiển thị email	| Không | Nếu chọn, email của thành viên sẽ hiển thị trên trang thông tin thành viên (Tất cả mọi người đều thấy) |
| Là tài khoản của nhóm	| Không | Chọn nhóm mà thành viên sẽ tham gia sau khi khởi tạo |
| Là thành viên chính thức	| Không | Nếu chọn, tài khoản sẽ được sử dụng toàn quyền của thành viên, ngược lại, một số quyền bị giới hạn |
| Gửi email thông báo	| Không | Gửi email thông báo tài khoản đã được tạo, thông tin bao gồm tên đăng nhập và mật khẩu. Quá trình gửi mail có thể làm chậm tiến trình import, bạn cần cân nhắc khi sử dụng tùy chọn này |

### Xóa tài khoản

- Sau khi xóa, mọi thông tin, dữ liệu liên quan đến tài khoản đều bị xóa 
- Thành viên sẽ nhận được thông báo về việc xóa tài khoản qua email

### Nhập danh sách thành viên từ Excel

Truy cập **Tài khoản / Nhập từ Excel** (Menu dọc)

![](images/system/nhap_file_excel.png)

- Click **Tải file mẫu** để download về file excel mẫu
- Trên bảng tính mẫu, tiến hành nhập thông tin theo các trường gợi ý 
- Click nút **Choose File**, tìm tới file đã nhập thông tin thành viên ở bước 2
- Click **Kiểm tra dữ liệu**, lúc này hệ thống sẽ kiểm tra thông tin bạn nhập vào, nếu có lỗi sẽ thông báo để bạn tiến hành kiểm tra và sửa lỗi. Thực hiện cho đến khi file không còn lỗi
- Click **Tiếp theo** để hoàn tất

 
## Bổ nhiệm người quản trị

Truy cập **Tài khoản / Quản trị / Thêm quản trị** (Menu dọc)

> Trước khi thêm người quản trị, bạn cần [tạo tài khoản thành viên](/system/#them-tai-khoan)

![](images/system/bo_nhiem.png)

| Thông tin | Bắt buộc | Mô tả |
|-----------|----------|-------|
| Chỉ định thành viên | Có | Chọn tài khoản thành viên muốn bổ nhiệm làm người quản trị |
| Chức danh | Có | Điền chức danh của người quản trị |
| Giao diện người quản trị | Không | Chọn giao diện của người quản trị khi đăng nhập vào khu vực quản lý |
| Trình soạn thảo | Không | Nếu chọn ***Không sử dụng**, người quản trị này sẽ không được sử dụng trình soạn thảo mà chỉ là một ô đơn thuần text |
| Các kiểu file được phép tải lên | Không | Các loại file có thể upload lên hệ thống |
| Quyền hạn | Có | Chọn các module mà người quản trị này được quản lý |

Sau khi điền đầy đủ các thông tin, click **Thêm Quản trị website** để hoàn tất

## Quản lý File

Khu vực **Quản lý File** giúp người quản trị quản lý (upload, sửa thông tin, xóa, tạo thư mục,...) các thư mục, tập tin được upload lên hệ thống

Truy cập **Quản lý File** (Menu ngang)

![](images/system/quan-ly-file.png)

Trên đây là giao diện quản lý file. Các khu vực quan trọng bạn cần biết:

- **Quản lý thư mục (1):** Tại khu vực này, bạn có thể truy cập đến thư mục. Danh sách thư mục ở đây sẽ bao gồm toàn bộ thư mục của các module khác. Click phải chuột vào tên thư mục, bạn sẽ thấy:
![](images/system/quan-ly-thu-muc.png)

	- **Tạo thư mục:** Tạo thêm thư mục là thư mục con của thư mục đang được click
	- **Tạo lại ảnh thumb**

- **Quản lý File (2):** Khi click vào thư mục, danh sách file ở bảng bên phải sẽ hiển thị các file thuộc thư mục được chọn. Click phải chuột vào file, bạn sẽ thấy:
![](images/system/quan-ly-file-1.png)

| Thông tin | Mô tả |
|-----------|-------|
| Tải về | Download file được chọn về máy |
| Xem chi tiết | Hiển thị thông tin chi tiết về file. Thông tin: tên file, kích thước, dung lượng, thời gian cập nhật,.... |
| Thêm logo | Xem [Cấu hình đóng dấu ảnh](/system/#cau-hinh-ong-dau-anh) |
| Công cụ ảnh | Sử dụng công cụ này để cắt hình ảnh về một kích thước nhỏ hơn cùng tỉ lệ |
| Cắt ảnh | Sử dụng công cụ này để chọn vùng ảnh cần cắt |
| Xoay ảnh | Sử dụng công cụ này để xoay hướng ảnh |
| Di chuyển | Sử dụng công cụ này để di chuyển ảnh đến một thư mục khác |
| Đổi tên file | Sử dụng công cụ này để đổi tên file |
| Xóa file | Sử dụng công cụ này để xóa file ra khỏi hệ thống |

- **Tìm kiếm file (3):** Bạn có thể dễ dàng lọc file theo các tiêu chí được cung cấp tại khu vực này
- **Tải lên một file mới (4):** Xem [Tải lên một file mới](/system/#tai-len-mot-file-moi)

### Tải lên một file mới

Tại khu vực 4, bạn click vào nút **Chọn kiểu upload**, khi đó sẽ có hai lựa chọn, tùy vào vị trí lưu file bạn cần chọn phương án phù hợp.

- **Upload từ internet:** Trường hợp này khi bạn có URL của một file được lưu trữ trực tuyến. Ví dụ: `https://docs.aztest.vn/images/system/quan-ly-file-1.png`. Nhập được dẫn này vào ô **Nhập URL file** sau đó nhấn **Upload file**, hệ thống sẽ tiến hành download file về máy chủ.

![](images/system/upload-file-tu-internet.png)

- **Upload từ máy tính:** Trường hợp file lưu tại máy tính, click **Upload từ máy tính**, sau đó chọn đến file cần upload. Có thể chọn nhiều file để upload cùng lúc. Sau khi chọn file, hệ thống sẽ hiện thị lại thông tin của file, bạn có thể điều chỉnh lại mô tả hình ảnh (1) hoặc xóa file khỏi danh sách tại giao diện này. Cuối cùng, click **Upload file (2)** để tiến hành upload file lên hệ thống.

![](images/system/upload-file-moi.png)

### Cấu hình đóng dấu ảnh
