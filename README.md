# ungdungnhantinthoigianthuc
Tài liệu mô tả chức năng
Chức năng phía người dùng (Client)
 Đăng ký / Đăng nhập
Tạo tài khoản (username, email, password) 
Đăng nhập hệ thống 
Xác thực người dùng 
Gửi và nhận tin nhắn thời gian thực
-	Gửi tin nhắn văn bản 
-	Tin nhắn hiển thị ngay lập tức cho người nhận 
-	Không cần reload trang 
 Danh sách bạn bè / người dùng
-	Hiển thị danh sách người dùng đang online/offline 
-	Tìm kiếm người dùng 
-	Thêm / xóa bạn bè 
Chat cá nhân (1-1)
-	Nhắn tin riêng giữa 2 người 
-	Hiển thị lịch sử chat 
-	Trạng thái tin nhắn: Đã gửi , Đã nhận , Đã xem
Chat nhóm
-	Tạo nhóm chat 
-	Thêm / xóa thành viên 
-	Nhắn tin trong nhóm 
Trạng thái online/offline
-	Hiển thị người đang hoạt động 
-	Cập nhật trạng thái theo thời gian thực 
Thông báo (Notification)
-	Thông báo khi có tin nhắn mới 
-	Hiển thị số lượng tin chưa đọc 
Gửi file / hình ảnh (nâng cao)
-	Gửi ảnh, file 
-	Preview nội dung 
Chức năng phía quản trị (Admin)
Quản lý người dùng
-	Xem danh sách user 
-	Khóa / mở tài khoản 
Quản lý nội dung
-	Báo cáo vi phạm
Quản lý hệ thống
-	Giám sát server 
-	Thống kê số lượng người dùng online 
Chức năng hệ thống (System)
 Real-time communication
-	Sử dụng WebSocket để truyền dữ liệu 2 chiều 
-	server push dữ liệu ngay lập tức 
Lưu trữ dữ liệu
-	Lưu lịch sử tin nhắn 
-	Lưu thông tin user 
Bảo mật
-	Mã hóa mật khẩu 
-	Xác thực token (JWT) 
Đồng bộ dữ liệu
-	Đồng bộ tin nhắn giữa nhiều thiết bị 
-	Load lại lịch sử khi đăng nhập lại 
Các yêu cầu phi chức năng
-	Hiệu năng cao (real-time) 
-	Độ trễ thấp 
-	Bảo mật tốt 
-	Khả năng mở rộng (scalable)

