# Install

`npm install`

Sau đó vào packages.json và xem các script
* `npm run start`: Chạy NodeJS app bình thường
* `npm run start:dev`: Chạy project NodeJS app dưới dạng develop, khi thay đổi thì ứng dụng tự refresh sử dụng package **nodemon**

# Packages
* Express-validator: Dùng để validate request (required, min-length, ...)
* Multer: Thực hiện file upload
* Body-parser: Xử lí form body
* Jwt: tạo token jwt cho đăng nhập
* Jest: Unit test và integration test

# chạy db : npx sequelize-cli db:migrate

*seeder: npx sequelize-cli db:seed:all


