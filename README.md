WEBSITE GIỚI THIỆU LỄ HỘI KHMER
1. Giới thiệu đề tài
Website giới thiệu Lễ hội Khmer được xây dựng nhằm cung cấp thông tin về các lễ hội Khmer, bao gồm tên lễ hội, nguồn gốc, thời gian, địa điểm, hoạt động và hình ảnh minh họa.
2. Công nghệ sử dụng
	ASP.NET Web Forms
	Ngôn ngữ lập trình C#
	Microsoft SQL Server
	HTML, CSS
	Visual Studio

3. Các chức năng chính
Hiển thị danh sách lễ hội trên trang chủ.
Xem thông tin chi tiết của lễ hội.
Hiển thị trang giới thiệu website.
Hiển thị trang liên hệ.
Đăng nhập khu vực quản trị.
Quản lý thông tin lễ hội theo các chức năng đã được triển khai trong dự án.

4. Yêu cầu cài đặt
Visual Studio hỗ trợ ASP.NET Web Forms.
Phiên bản .NET Framework tương thích với dự án.
Microsoft SQL Server.
SQL Server Management Studio (SSMS) để quản lý cơ sở dữ liệu.

5. Cấu trúc dự án
Default.aspx: Trang chủ.
ChiTietLeHoi.aspx: Trang chi tiết lễ hội.
GioiThieu.aspx: Trang giới thiệu.
LienHe.aspx: Trang liên hệ.
DangNhap.aspx: Trang đăng nhập.
QuanLyLeHoi.aspx: Trang quản lý lễ hội.
Site.Master: Giao diện dùng chung nếu được cấu hình.
Web.config: File cấu hình ứng dụng và chuỗi kết nối.

6. Cài đặt cơ sở dữ liệu
Mở SQL Server Management Studio.
Kết nối đến SQL Server.
Mở file script SQL được cung cấp trong thư mục 03_DATABASE.
Kiểm tra tên cơ sở dữ liệu và các đối tượng trong script.
Thực thi script để tạo cấu trúc bảng và dữ liệu.
Kiểm tra bảng dbo.LeHoi và dữ liệu lễ hội.

7. Cấu hình kết nối
Mở file Web.config và tìm chuỗi kết nối có tên KetNoiLeHoi.
Điều chỉnh tên máy chủ, tên cơ sở dữ liệu và phương thức xác thực theo cấu hình SQL Server trên máy tính đang chạy ứng dụng.
Không chia sẻ mật khẩu cá nhân hoặc thông tin kết nối nhạy cảm.

8. Cách chạy chương trình
Mở dự án bằng Visual Studio.
Kiểm tra phiên bản .NET Framework và các thành phần cần thiết.
Cấu hình chuỗi kết nối SQL Server.
Chọn trang Default.aspx làm trang khởi chạy nếu cần.
Nhấn F5 hoặc Ctrl + F5 để chạy website.
Kiểm tra các trang và chức năng đã được triển khai.

9. Lưu ý
Khi chuyển dự án sang máy tính khác, cần cấu hình lại chuỗi kết nối và bảo đảm các file hình ảnh, tài nguyên và cơ sở dữ liệu được cung cấp đầy đủ.
Các chức năng cần được kiểm tra trên môi trường thực tế trước khi sử dụng.
