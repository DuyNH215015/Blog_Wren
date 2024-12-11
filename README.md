# Blog Wren  

Dự án Blog Wren là một ứng dụng Node.js cho phép người dùng tạo và quản lý blog của riêng họ.   

## Mục Lục  

- [Giới thiệu](#giới-thiệu)  
- [Cài đặt](#cài-đặt)  
- [Sử Dụng](#sử-dụng)  
- [Công Nghệ](#công-nghệ)  
- [Đóng Góp](#đóng-góp)  
- [Liên Hệ](#liên-hệ)  
- [Giấy Phép](#giấy-phép)  

## Giới Thiệu  

Blog Wren là một ứng dụng blog được xây dựng bằng Node.js, cho phép người dùng tạo, chỉnh sửa và xóa bài viết. Ứng dụng hỗ trợ xác thực người dùng và quản lý tệp tin, giúp người dùng dễ dàng tải lên hình ảnh cho bài viết của họ.  

## Cài Đặt  

Để cài đặt dự án, bạn cần làm theo các bước sau:  

1. **Clone repository**:  
   ```bash  
   git clone https://github.com/DuyNH215015/Blog_Wren.git  
   cd Blog_Wren  
Cài đặt các phụ thuộc:
bash
npm install  
Sử Dụng
Sau khi cài đặt, bạn có thể sử dụng các lệnh sau để chạy ứng dụng:

Chạy ứng dụng Node.js bình thường:

bash
npm run start  
Chạy ứng dụng ở chế độ phát triển (tự động làm mới khi có thay đổi):

bash
npm run start:dev  
Chạy cơ sở dữ liệu
Để chạy cơ sở dữ liệu, bạn có thể sử dụng các lệnh sau:

Chạy migration:

bash
npx sequelize-cli db:migrate  
Chạy seeder:

bash
npx sequelize-cli db:seed:all  
Công Nghệ
Dự án sử dụng các công nghệ và thư viện sau:

Express-validator: Dùng để xác thực yêu cầu (required, min-length, ...).
Multer: Thực hiện việc tải lên tệp tin.
Body-parser: Xử lý dữ liệu từ form body.
JWT: Tạo token JWT cho việc đăng nhập.
Jest: Thực hiện unit test và integration test.
Đóng Góp
Nếu bạn muốn tham gia đóng góp vào dự án, hãy làm theo các bước sau:

Fork repo này.
Tạo một nhánh mới:
bash
git checkout -b feature/your-feature  
Commit thay đổi của bạn:
bash
git commit -m 'Add some feature'  
Push nhánh của bạn:
bash
git push origin feature/your-feature  
Tạo Pull Request.
Liên Hệ
Nếu bạn có bất kỳ câu hỏi nào, hãy liên hệ với tôi qua:

GitHub: DuyNH215015
