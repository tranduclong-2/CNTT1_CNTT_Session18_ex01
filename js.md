# BÀI 1: SỰ CỐ KHÔNG TRUY CẬP ĐƯỢC HỆ THỐNG QUẢN TRỊ
## Phần 1. Phân tích
### 1. DNS là gì?
DNS là hệ thống giúp chuyển đổi tên miền thành địa chỉ IP để máy tính có thể tìm và kết nối đến máy chủ website.
- Input: Tên miền phong-dieu-phoi.greenlog.vn.
- Output: Địa chỉ IP của máy chủ.
### 2. Quy trình DNS Lookup
1. Người dùng nhập tên miền vào trình duyệt.
2. Máy tính kiểm tra DNS Cache.
3. Nếu chưa có, máy tính gửi yêu cầu đến DNS Server.
4. DNS Server tìm địa chỉ IP tương ứng.
5. Trả địa chỉ IP về máy tính.
6. Trình duyệt sử dụng IP để truy cập website.
### 3. Nguyên nhân lỗi
Nếu Nam nhập đúng tên miền, nhưng trang vẫn trả lời 404 NOT FOUND có thể trang không tồn tại.
