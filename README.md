
  # Đồ án Thương mại điện tử - Nhóm 06

Trang web bán điện thoại di động C2C viết bằng .Net

## Mục đích

Các hướng dẫn này sẽ giúp bạn có một dự án và chạy trên máy cục bộ của mình cho mục đích phát triển và thử nghiệm. Xem triển khai sau đây để biết về cách triển khai dự án trên một hệ thống trực tiếp.

### Các phần mềm sử dụng

Sử dụng visual studio, sublime text, SQL server

### Các tài khoản để test

Webmaster:

```
Tài khoản đăng nhập: Username/Password
admin/admin123
```

Account merchant:

```
Tài khoản đăng nhập: Username/Password
merchantA / merchant1
merchantB / merchant2

```

Account customer:

```
Tài khoản đăng nhập: Username/Password
customerX / customer1
customerY / customer2

```

### Hướng dẫn cài đặt

Để cài đặt webapps ta cần thực hiện các bước sau:

Bước 1: Clone Project về máy (nếu đã có file cài đặt, bỏ qua bước này)
![Clone Project](/readme/clone_project.png?raw=true "Clone Project")

Bước 2: Bỏ file nén vào thư mục htdocs của XAMPP. Giải nén file và đổi tên thư mục vừa giải nén thành ??
Ví dụ: Giả sử bạn cài XAMPP ở ô C ta sẽ có đường dẫn của file sau bước này là:
```
C:\xampp\htdocs\TMDT_N01
```

Bước 3: Tạo 1 cơ sở dữ liệu mới trong database của SQL server với tên là webmobile

```
webmobile
```

Bước 4: Import file dữ liệu mới nhất nằm trong thư mục database vào cơ sở dữ liệu vừa tạo.
Ví dụ:

```
import file database/webmobile.sql vào CSDL webmobile
```

Bước 5: 
