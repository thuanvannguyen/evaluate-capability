# 3. Công cụ lập trình cơ bản

## 3.1. Giới thiệu về IDE (Visual Studio Code)

### 1. **Visual Studio Code là gì?**

- Visual Studio Code (VSCode) là một **môi trường phát triển tích hợp (IDE)** mạnh mẽ và phổ biến, được phát triển bởi Microsoft.
- VSCode hỗ trợ nhiều ngôn ngữ lập trình, có giao diện thân thiện và hàng nghìn extension giúp lập trình viên tăng năng suất làm việc.
- Một số tính năng nổi bật:
  - **Tự động hoàn thành mã** (IntelliSense).
  - **Debugging** trực tiếp trong IDE.
  - **Quản lý dự án và thư mục** dễ dàng.
  - **Tích hợp Git** để quản lý phiên bản.

### 2. **Cài đặt và thiết lập cơ bản Visual Studio Code**

- **Bước 1**: Truy cập trang chủ [Visual Studio Code](https://code.visualstudio.com/) và tải phiên bản phù hợp với hệ điều hành của bạn (Windows, macOS, Linux).
- **Bước 2**: Thực hiện các bước cài đặt theo hướng dẫn (chỉ cần nhấn "Next" và hoàn thành cài đặt).
- **Bước 3**: Sau khi cài đặt xong, mở VSCode lên. Bạn sẽ thấy giao diện làm việc của IDE:
  - **Explorer**: Hiển thị cấu trúc thư mục của dự án.
  - **Editor**: Nơi để viết mã nguồn.
  - **Terminal tích hợp**: Cho phép chạy lệnh ngay bên trong VSCode.
  - **Panel Git**: Giúp bạn quản lý mã nguồn với Git dễ dàng.

## 3.2. Cài đặt extension cần thiết

### 1. **Giới thiệu về Extension**

- VSCode hỗ trợ rất nhiều **extension** giúp cải thiện quá trình lập trình, từ việc kiểm tra lỗi cú pháp, định dạng mã, đến quản lý dự án.
- Để cài đặt extension, bạn chỉ cần vào tab **Extensions** (hoặc nhấn tổ hợp phím `Ctrl + Shift + X`), sau đó tìm tên extension và nhấn **Install**.

### 2. **ESLint** - Kiểm tra lỗi mã nguồn

- **ESLint** là một công cụ giúp bạn **kiểm tra lỗi cú pháp** và **tuân thủ quy chuẩn code**.
- **Cài đặt ESLint**:
  1.  Mở tab **Extensions** và tìm kiếm **"ESLint"**.
  2.  Nhấn **Install** để cài đặt.
- **Cách sử dụng ESLint**:
  - Sau khi cài đặt, ESLint sẽ tự động kiểm tra mã nguồn khi bạn đang viết và hiển thị các lỗi cú pháp hoặc lỗi quy chuẩn ngay trong trình soạn thảo.
  - Lỗi sẽ được đánh dấu bằng màu đỏ và có thể xem chi tiết lỗi ở cuối trang.

### 3. **Prettier** - Định dạng mã nguồn

- **Prettier** là công cụ giúp **định dạng mã nguồn** một cách đồng nhất, giúp mã nguồn trở nên dễ đọc và tuân thủ các quy chuẩn code.
- **Cài đặt Prettier**:
  1.  Tương tự như ESLint, mở tab **Extensions** và tìm **"Prettier"**.
  2.  Nhấn **Install** để cài đặt.
- **Cách sử dụng Prettier**:
  - Sau khi cài đặt, Prettier sẽ tự động định dạng code khi bạn lưu tệp (`Ctrl + S`).
  - Bạn có thể tùy chỉnh các quy tắc định dạng của Prettier thông qua tệp cấu hình `.prettierrc` hoặc sử dụng các cấu hình mặc định.

## 3.3. Sử dụng terminal cơ bản

### 1. **Terminal trong VSCode**

- **Terminal** là nơi bạn có thể thực hiện các lệnh shell trực tiếp, chẳng hạn như **tạo thư mục**, **chạy dự án**, hoặc **quản lý phiên bản với Git**.
- VSCode cung cấp **terminal tích hợp** giúp bạn không cần phải mở thêm cửa sổ dòng lệnh ngoài. Để mở terminal:
  - **Bước 1**: Vào menu **View** -> **Terminal** hoặc nhấn tổ hợp phím `Ctrl + ~`.
  - **Bước 2**: Terminal sẽ hiện ra ở phía dưới cùng của VSCode, cho phép bạn nhập và chạy các lệnh.

### 2. **Thực hành các lệnh cơ bản**

- **cd**: Di chuyển đến một thư mục khác.
  - Cú pháp: `cd <đường dẫn thư mục>`
  - Ví dụ: `cd /Users/Documents/MyProject`
- **ls**: Liệt kê các tệp và thư mục trong thư mục hiện tại.
  - Cú pháp: `ls`
- **mkdir**: Tạo một thư mục mới.
  - Cú pháp: `mkdir <tên thư mục>`
  - Ví dụ: `mkdir src`
- **touch**: Tạo một tệp mới.
  - Cú pháp: `touch <tên tệp>`
  - Ví dụ: `touch index.js`

## 3.4. Thực hành cấu hình môi trường phát triển

### 1. **Tạo project JavaScript/Node.js mới**

- Để tạo một dự án JavaScript/Node.js mới, bạn có thể sử dụng terminal tích hợp trong VSCode:
  1.  Mở terminal (`Ctrl + ~`).
  2.  Di chuyển đến thư mục nơi bạn muốn tạo dự án:
      - Ví dụ: `cd /Users/Documents/Projects`
  3.  Tạo thư mục mới cho dự án:
      - Ví dụ: `mkdir my-nodejs-app`
  4.  Di chuyển vào thư mục dự án:
      - `cd my-nodejs-app`
  5.  Khởi tạo dự án Node.js mới:
      - Chạy lệnh: `npm init -y`
      - Sau lệnh này, một tệp `package.json` sẽ được tạo ra, chứa các thông tin về dự án của bạn.
  6.  Tạo tệp **index.js**:
      - Chạy lệnh: `touch index.js`
  7.  Mở tệp **index.js** và bắt đầu viết mã JavaScript/Node.js.

## 3.5. Sử dụng Git trong VSCode

### 1. **Giới thiệu về Git**

- **Git** là một hệ thống quản lý phiên bản phân tán, giúp bạn theo dõi lịch sử thay đổi của mã nguồn, làm việc theo nhóm dễ dàng và tránh mất dữ liệu.
- VSCode tích hợp sẵn Git, cho phép bạn thực hiện các thao tác Git trực tiếp trong IDE mà không cần sử dụng dòng lệnh.

### 2. **Cài đặt Git**

- Nếu chưa cài đặt Git, bạn có thể tải và cài đặt từ trang [Git](https://git-scm.com/).
- Sau khi cài đặt, mở **VSCode** và bắt đầu sử dụng.

### 3. **Thực hành sử dụng Git trong VSCode**

1.  **Khởi tạo Git cho dự án**:
    - Mở terminal và chạy lệnh `git init` để khởi tạo Git cho dự án hiện tại.
2.  **Thêm tệp vào phiên bản**:
    - Sử dụng lệnh `git add .` để thêm tất cả các tệp vào lần commit tiếp theo.
3.  **Commit thay đổi**:
    - Sử dụng lệnh `git commit -m "First commit"` để lưu lại các thay đổi kèm theo thông điệp commit.
4.  **Tích hợp Git với giao diện VSCode**:
    - Bạn có thể thực hiện các thao tác Git trực tiếp từ tab **Source Control** (biểu tượng nhánh cây trên thanh sidebar).
    - Tại đây, bạn có thể:
      - Xem các thay đổi chưa được commit.
      - Thêm tệp vào commit bằng cách nhấn vào dấu cộng (+).
      - Commit các thay đổi với một thông điệp.
    - Ngoài ra, bạn có thể **kết nối với GitHub** để quản lý phiên bản mã nguồn trên nền tảng này.

## Tổng kết phần 3:

- **Cài đặt Visual Studio Code**: Học cách cài đặt và thiết lập các tính năng cơ bản của IDE này.
- **Sử dụng extension hữu ích**: Cài đặt các extension như ESLint và Prettier để kiểm tra lỗi cú pháp và định dạng mã.
- **Thao tác với terminal**: Học viên thực hành các lệnh cơ bản và tạo dự án mới trực tiếp từ terminal.
- **Quản lý phiên bản với Git**: Học viên thực hành sử dụng Git để quản lý lịch sử thay đổi của mã nguồn trong dự án của mình.
