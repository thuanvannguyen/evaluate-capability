# 1. Tư duy logic và giải quyết vấn đề

## 1.1. Phân tích vấn đề và chia nhỏ

### Phân tích bài toán theo từng bước

1. **Xác định mục tiêu của bài toán**:

   - Khi tiếp cận một bài toán, việc đầu tiên học viên cần làm là xác định rõ ràng **mục tiêu** của bài toán. Mục tiêu này giúp ta hiểu rõ bài toán cần giải quyết điều gì, tránh lạc hướng trong quá trình lập trình.
   - Ví dụ: Đối với bài toán "Quản lý sinh viên", mục tiêu có thể là tạo một hệ thống có thể **thêm**, **sửa**, **xóa** thông tin sinh viên và quản lý các dữ liệu liên quan một cách dễ dàng.

2. **Hiểu rõ yêu cầu**:

   - **Phân tích yêu cầu** của bài toán là bước quan trọng tiếp theo. Học viên cần hiểu rõ từng yêu cầu chi tiết để xây dựng các chức năng một cách hợp lý.
   - Ví dụ: Trong hệ thống "Quản lý sinh viên", yêu cầu chi tiết có thể bao gồm:
     - Thêm sinh viên với các thông tin như họ tên, mã số sinh viên, lớp, ngày sinh.
     - Chức năng sửa thông tin sinh viên đã có.
     - Xóa sinh viên khỏi hệ thống.
     - Liệt kê danh sách sinh viên.

3. **Chia nhỏ bài toán thành các bước đơn giản**:
   - Đối với những bài toán phức tạp, học viên cần chia nhỏ thành các bước nhỏ hơn để dễ dàng giải quyết.
   - Ví dụ: Bài toán "Quản lý sinh viên" có thể được chia nhỏ như sau:
     1. Tạo cơ sở dữ liệu chứa thông tin sinh viên.
     2. Tạo giao diện cho người dùng thêm, sửa, xóa thông tin sinh viên.
     3. Tạo chức năng để thao tác dữ liệu với cơ sở dữ liệu (CRUD - Create, Read, Update, Delete).
     4. Kiểm tra tính năng bằng cách thử nghiệm thêm, sửa, xóa sinh viên.

---

## 1.2. Cách tiếp cận bài toán và giải quyết vấn đề

### Tư duy tìm giải pháp thay thế

1. **Đưa ra nhiều cách giải quyết bài toán**:

   - Trong quá trình lập trình, học viên cần học cách **suy nghĩ sáng tạo**, tìm ra nhiều giải pháp khác nhau để giải quyết một vấn đề.
   - Ví dụ: Đối với bài toán "Quản lý sinh viên", có thể có nhiều cách tổ chức dữ liệu:
     - Dùng mảng để lưu trữ sinh viên tạm thời nếu chỉ thao tác dữ liệu nhỏ.
     - Sử dụng cơ sở dữ liệu MySQL hoặc MongoDB nếu hệ thống cần lưu trữ lâu dài và quản lý dữ liệu lớn.

2. **Thảo luận và so sánh các giải pháp**:
   - Sau khi có nhiều giải pháp, học viên nên **thảo luận** với nhau hoặc với giảng viên để so sánh các giải pháp:
     - Ưu điểm và nhược điểm của từng cách.
     - Cách nào tiết kiệm tài nguyên hơn, nhanh hơn hoặc dễ triển khai hơn.
     - Cách nào có thể mở rộng khi dự án phát triển.

---

### Thực hành lập kế hoạch trước khi code

1. **Lập kế hoạch bằng sơ đồ tư duy**:

   - Trước khi bắt tay vào viết mã, học viên nên lập **sơ đồ tư duy** hoặc **sơ đồ luồng** để hình dung rõ ràng các bước giải quyết vấn đề.
   - Ví dụ: Đối với bài toán "Quản lý sinh viên", sơ đồ luồng có thể như sau:
     - **Bước 1**: Người dùng nhập thông tin sinh viên vào giao diện.
     - **Bước 2**: Hệ thống kiểm tra dữ liệu nhập.
     - **Bước 3**: Hệ thống lưu dữ liệu vào cơ sở dữ liệu (nếu là chức năng thêm).
     - **Bước 4**: Cập nhật danh sách sinh viên.

2. **Tạo checklist các bước cần làm**:
   - Việc lập một **checklist** các bước cần làm giúp học viên dễ dàng kiểm soát quá trình thực hiện bài toán:
     1. Tạo giao diện người dùng.
     2. Kết nối cơ sở dữ liệu.
     3. Thực hiện chức năng thêm sinh viên.
     4. Thực hiện chức năng sửa sinh viên.
     5. Thực hiện chức năng xóa sinh viên.
     6. Kiểm tra toàn bộ hệ thống.

---

## 1.3. Thực hành với bài toán tư duy

### Bài toán mê cung

1. **Giới thiệu bài toán mê cung**:
   - Bài toán mê cung là một ví dụ điển hình giúp học viên rèn luyện tư duy logic.
   - Nhiệm vụ của học viên là tìm được đường ra khỏi mê cung dựa trên các quy tắc và lối đi trong mê cung.
2. **Thực hành giải quyết bài toán**:
   - **Bước 1**: Phân tích mê cung và xác định điểm xuất phát, điểm đích.
   - **Bước 2**: Xác định các lối đi có thể.
   - **Bước 3**: Học viên suy nghĩ và thử nghiệm nhiều cách để tìm ra lối đi ngắn nhất hoặc tối ưu nhất.
3. **Thảo luận và tìm giải pháp khác**:
   - Sau khi giải quyết bài toán, học viên sẽ thảo luận với giảng viên về cách tiếp cận và đưa ra các cách giải quyết khác nhau, giúp phát triển tư duy sáng tạo.

---

## Tổng kết phần 1:

- **Phân tích bài toán và chia nhỏ**: Cách tiếp cận và chia nhỏ bài toán giúp giải quyết từng phần đơn giản trước khi giải quyết toàn bộ vấn đề.
- **Tư duy giải pháp thay thế**: Khuyến khích học viên suy nghĩ nhiều cách tiếp cận khác nhau, sau đó chọn giải pháp tối ưu.
- **Thực hành bài toán tư duy**: Giải quyết bài toán mê cung giúp rèn luyện tư duy logic và kỹ năng giải quyết vấn đề.
