********** Nhiệm Vụ Cần Làm ************

** fix bug **
	can not find site : /* /index.html 200 (file name : _rediects) cấu hình lỗi netlify


*FrontEnd:
 
	- chỉnh sửa lại một số chổ cần thiết :
		+ render tất cả sản phẩm trong giỏ -> xong
		+ render thông tin người dùng -> tạm thời chưa làm
		+ fix các điều kiện của ô input trong form ->  xong
		+ sửa lại logic code phần giỏ hàng (xử dụng debouce để gửi dữ liệu khi người dùng change quantity) -> xóng

		++ xong tất cả nhiệm vụ trên thì tiếp tục tách các item trong dom được 
		render bằng map con ra một component Item riêng để dễ quản lý các Item con -> xong

		
		+*+ Nhiệm vụ đặc biệt:  viết giao diện Admin 
			+ dashboar: -> xong
			+ all product: xong giao diện chưa đổ dữ liệu
			+ add product: xong giao diện chưa đổ dữ liệu
			+ all user: xong giao diện chưa đổ dữ liệu

	- tạo các hàm xử lý để gửi dữ liệu cho server:
		+ đăng nhập/đăng ký -> xong
		+ thêm sản phẩm -> xong
		+ xóa sản phẩm ra khỏi giỏ -> xong

		+ thanh toán -> xong
		+ liên hệ

*BackEnd:  ( HOÀN THÀNH XONG BACKEND RỒI MỚI LÀM FRONTEND )
		
	**** Lưu ý ****
	 tìm hiểu và tích hợp thư viện google anlytics

	- tạo các chức năng cơ bản:
		-- User :
			+ đăng nhập/đăng ký -> xong
			+ mua hàng -> xong
			+ thanh toán -> xong
			+ xóa sản phẩm khỏi giỏ -> xong
			+ lấy ra tất cả sản phẩm chưa thanh toán trong giỏ -> xong
			+ liên hệ ->

		-- admin :
			+ thêm sản phẩm -> xong
			+ xóa sản phẩm -> xong
			+ phân quyền cho người dùng -> xong
			+ xóa người dùng -> xong
			+ cập nhật thông tin sản phẩm -> xong
			
	
	- Viết các API để lấy dữ liệu cho từng trang:
		+ Home -> xong
			{
				category: tất cả các danh mục
				data: mỗi danh mục trả về 6 sản phẩm
			}
		+ Phân trang sản phẩm -> xong
		+ phân trang sản phẩm trong admin: ->
		+ Thông tin người dùng -> 
		