# Cài Đặt Phần Mềm Lập Trình và Công Cụ Hỗ Trợ

## Tại Sao Cần Có Môi Trường Phát Triển

### Lợi Ích của Phần Mềm Lập Trình

- **Viết mã dễ dàng hơn**: Các phần mềm lập trình cung cấp các công cụ hỗ trợ viết mã như tự động hoàn thành, gợi ý mã, và kiểm tra lỗi cú pháp.
- **Chỉnh sửa mã nhanh chóng**: Với các tính năng như tìm kiếm và thay thế, định dạng mã, và tái cấu trúc mã, việc chỉnh sửa mã trở nên nhanh chóng và hiệu quả.
- **Kiểm tra và chạy mã**: Các công cụ gỡ lỗi và chạy thử giúp phát hiện và sửa lỗi nhanh chóng, đảm bảo mã hoạt động đúng như mong đợi.

## Cài Đặt Trình Soạn Thảo Mã Nguồn

### Visual Studio Code

- **Giới thiệu**: Visual Studio Code (VSCode) là một trình soạn thảo mã nguồn mở và miễn phí, phát triển bởi Microsoft. Nó hỗ trợ nhiều ngôn ngữ lập trình và có nhiều extension hữu ích.
- **Tính năng nổi bật**:
  - **Hỗ trợ đa ngôn ngữ**: VSCode hỗ trợ hầu hết các ngôn ngữ lập trình phổ biến như JavaScript, Python, C++, Java, và nhiều ngôn ngữ khác.
  - **Tiện ích mở rộng**: VSCode có kho tiện ích mở rộng phong phú, cho phép người dùng tùy chỉnh và mở rộng chức năng theo nhu cầu.

### Thực Hành Cài Đặt VSCode

1. **Tải VSCode từ trang chính thức**:

   - Truy cập trang Visual Studio Code.
   - Chọn phiên bản phù hợp với hệ điều hành của bạn (Windows, macOS, Linux).
   - Tải xuống và chạy tệp cài đặt.

2. **Cài đặt VSCode**:
   - Chạy tệp cài đặt và làm theo hướng dẫn trên màn hình.
   - Chọn các tùy chọn cài đặt như thêm VSCode vào menu ngữ cảnh của Windows Explorer.
   - Hoàn tất quá trình cài đặt và khởi động VSCode.

### Cài Đặt Một Số Extension Cần Thiết

- **Prettier**: Hỗ trợ định dạng mã nguồn tự động.
  - Mở VSCode, nhấp vào biểu tượng Extensions (hình vuông ghép) ở thanh bên trái.
  - Tìm kiếm "Prettier - Code formatter" và nhấp vào "Install".
- **Live Server**: Tự động làm mới trang web khi thay đổi mã nguồn.
  - Tìm kiếm "Live Server" trong tab Extensions và nhấp vào "Install".

## Thiết Lập Môi Trường Làm Việc Cơ Bản

### Cách Cấu Hình Giao Diện của VSCode

- **Chọn theme**: Mở Command Palette (Ctrl+Shift+P), gõ "Preferences: Color Theme" và chọn theme yêu thích.
- **Cài đặt font chữ**: Mở Command Palette, gõ "Preferences: Open Settings (JSON)" và thêm dòng `"editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace"`.

### Sử Dụng Terminal Tích Hợp Trong VSCode

- **Mở terminal**: Nhấn Ctrl+` hoặc vào menu View > Terminal.
- **Chạy lệnh trong terminal**: Bạn có thể sử dụng terminal tích hợp để chạy các lệnh như trong terminal thông thường.

## Sử Dụng Terminal Để Điều Khiển Máy Tính

### Các Lệnh Cơ Bản

- **cd**: Thay đổi thư mục hiện tại.
  - Ví dụ: `cd Documents`
- **mkdir**: Tạo thư mục mới.
  - Ví dụ: `mkdir NewProject`
- **ls**: Liệt kê các tệp và thư mục trong thư mục hiện tại.
  - Ví dụ: `ls`
- **rm**: Xóa tệp hoặc thư mục.
  - Ví dụ: `rm index.html`

### Thực Hành Điều Hướng và Thao Tác Với Tệp/Thư Mục Qua Terminal

```jsx
mkdir NewProject

cd NewProject

touch index.html

ls

rm index.html
```
