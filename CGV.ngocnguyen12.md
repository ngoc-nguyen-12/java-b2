- Model:
      + User(Khách hàng, nhân viên, quản lý)
      + Phim
      + Phòng chiếu
      + Vé
      + Lịch chiếu
      + Hóa đơn
- Quy trình book chỗ:
      + Hiển thị danh sách các bộ phim
      + Chọn phim
      + Hiển thị danh sách lịch chiếu, chọn lịch
      + Hiển thị các chỗ ngồi trong phòng chiếu và trạng thái của các chỗ ngồi
      + Chọn chỗ và số lượng (loại vé phân theo chỗ ngồi)
      + Đặt mua
      + Hệ thống cập nhật thông tin vào phiếu đặt vé của khách hàng
      + Hiển thi form thông tin vé của khách hàng để khách hàng điền thông tin còn trống
      + Chọn hình thức thanh toán
      + In phiếu 
- Trạng thái:
      + Chọn phim
      + Chọn lịch chiếu
      + Chọn chỗ
      + Book vé
      + Thanh toán
- Phát sinh:
      + Chỗ ngồi có các trạng thái: trống, đang chọn, chờ thanh toán, đã thanh toán
      + Khách hàng đến mục thanh toán có thể hủy vé (bấm nút "hủy")
      + Hệ thống tự động hủy vé nếu khách hàng thanh toán lâu quá 3 phút, màn hình thông báo cho khách hàng và hiển thị về trang chủ.