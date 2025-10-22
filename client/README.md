Trong dự án này, người dùng có thể đăng ký tài khoản, khám phá các bộ phim và đặt vé xem phim. Khi đặt vé, người dùng có thể chọn chỗ ngồi ưa thích của mình.

Chúng ta cũng sẽ xây dựng bảng điều khiển dành cho quản trị viên (Admin Dashboard), nơi quản trị viên có thể thêm phim mới và quản lý các đơn đặt vé.

Để tạo tính năng xác thực người dùng, chúng ta sẽ sử dụng Clerk — một dịch vụ cho phép tích hợp nhiều hình thức đăng ký như đăng ký bằng email, tài khoản mạng xã hội hoặc số điện thoại.

Nhờ Clerk, chúng ta còn có thể thêm tính năng đa phiên đăng nhập (multi-session), cho phép người dùng tạo nhiều hồ sơ khác nhau trên cùng website và chuyển đổi giữa các tài khoản mà không cần đăng xuất.

Ngoài ra, dự án còn sử dụng Inngest để quản lý các tác vụ nền (background jobs) và lên lịch tự động. Với Inngest, hệ thống sẽ gửi email tự động cho tất cả người dùng mỗi khi có phim mới được thêm vào, đồng thời gửi email xác nhận đặt vé và email nhắc nhở vài giờ trước khi phim được chiếu.

Khi người dùng đặt vé nhưng thanh toán bị hủy hoặc thất bại, ghế của họ sẽ được giữ chỗ trong 10 phút để họ có thể thử thanh toán lại. Nếu sau 10 phút mà người dùng vẫn không hoàn tất thanh toán, ghế đó sẽ được tự động giải phóng để người khác có thể đặt.
