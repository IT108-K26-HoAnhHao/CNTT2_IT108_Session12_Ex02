# Bài 2

## Phần 1 - Phân tích: Sơ đồ cây cấu trúc Heading (SRS)

* **1. Giới thiệu chung**
    * 1.1 Mục đích dự án
    * 1.2 Phạm vi tài liệu
* **2. Mô tả tổng quan**
    * 2.1 Bối cảnh phát triển EdTech
    * 2.2 Nhóm người dùng mục tiêu
* **3. Mô tả tính năng Lớp học ảo**
    * 3.1 Quản lý phòng học trực tuyến
    * 3.2 Tương tác trong buổi học
    * 3.3 Điểm danh & ghi hình
    * 3.4 Tích hợp 200 khóa học
* **4. Yêu cầu phi chức năng**
    * 4.1 Hiệu năng hệ thống
    * 4.2 Bảo mật dữ liệu
* **5. Phụ lục và Tham khảo**


## Phần 2 - Triển khai: Báo cáo bộ công cụ dự án

* **1. Word (SRS):** Sử dụng `Heading 1`, `Heading 2` hỗ trợ Navigation Pane và cập nhật Mục lục (`Update entire table`).
* **2. Excel (Quản lý 200 học viên):** Dùng `Ctrl + Shift + L` lọc đa điều kiện (Khoa **CNTT** và điểm chuyên cần **< 7**). Đảm bảo chỉ có 1 Header Row duy nhất, không chứa hàng tổng cộng ngắt quãng.
* **3. PowerPoint (Slide giới thiệu):** Phối màu tối (Nền Navy, chữ trắng, Accent cam) để đạt độ tương phản cao, chia bố cục 3 vùng minh họa luồng học trực tuyến.



## Phần 3 - Kiểm thử: Xử lý lỗi không tìm thấy tên khi lọc (Hàm TRIM)

* **Nguyên nhân:** Dữ liệu chứa khoảng trắng ẩn (Whitespace Error).
* **Cách xử lý:**
    1. Tạo cột phụ và dùng hàm: `=TRIM(B2)`
    2. Kéo công thức để làm sạch toàn bộ dữ liệu.
    3. Copy và Paste Values đè lên cột gốc.
    4. Bật lại bộ lọc (`Ctrl + Shift + L`) để hiển thị kết quả chính xác.

