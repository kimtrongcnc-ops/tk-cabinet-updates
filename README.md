# TK CABINET 1.99.216

Bộ cập nhật đã ký và mã hóa cho SketchUp 2023–2026.

## Tám nhóm công cụ và cài đặt chung

- Tám thanh TK theo thứ tự làm việc, tổng cộng 56 nút: Tạo tủ; Làm Layer; Vật tư; Liên kết; Báo cáo; Xóa; Co kéo và đánh dấu; Tủ mẫu và góc nhìn.
- Cài đặt chung nằm cuối nhóm 4, gồm 52 trang cài đặt và nút **Lưu tất cả**. Chọn ngôn ngữ tại Cài đặt chung.
- Tạo tủ mới, Chỉnh sửa tủ và toàn bộ Nesting, gồm Cài dao và Cài tham số, tiếp tục có cài đặt riêng.
- Đặt tên có hai bảng **Đặt tên tủ** và **Đặt tên tấm**, có các ô tên mẫu riêng. Chọn đối tượng, Nạp vùng chọn, chọn tên mẫu rồi Xác nhận đổi tên. Quản lý mẫu tên trong Cài đặt chung.
- Tủ mẫu có thư viện SKP, ảnh xem trước, tìm kiếm, loại tủ, lưu tủ đang chọn, nhập và đặt mẫu. Mẫu trùng tên được lưu thành bản mới.
- Bổ sung nhóm co kéo/đánh dấu, cảnh nhìn, Dim nhanh và Sửa độ dày. Xóa tất cả chỉ xóa liên kết, vật liệu và dán cạnh trong vùng chọn; Phá khối là lệnh riêng.

## Cập nhật

Trong SketchUp chọn **Extensions → TK CABINET → Kiểm tra bản cập nhật**, hoặc cài [gói RBZ đã ký](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.216_MA_HOA_SK2023_2026.rbz) qua **Extension Manager → Install Extension**. Lưu bản vẽ và khởi động lại SketchUp sau khi cài.

Nếu một thanh công cụ đang ẩn, vào **View → Toolbars**, bật các thanh **TK 1** đến **TK 8**.

Máy khách không cần tài khoản GitHub. Cần key còn hạn cho máy đang dùng; key, cài dao và Post đã lưu được giữ khi cập nhật. Bản kê `latest.json` có chữ ký để TK xác minh gói tải về. Gói phát hành chứa 54 tệp Ruby đã mã hóa và chữ ký SketchUp; các tài nguyên HTML/JavaScript vẫn là tài nguyên giao diện thông thường.

## Phạm vi kiểm tra

Gói mã hóa đã tự nạp thành công trên SketchUp **23.0.367** và **26.1.189**: đủ tám thanh công cụ, 56 lệnh, 52 trang cài đặt và hai bảng đặt tên. Các thử nghiệm khởi động dùng bản vẽ riêng và không làm thay đổi hình học. Bản nguồn đã được kiểm tra Ruby 2.7/3.2, giao diện và các lệnh mới trên bản vẽ thử.

Sửa độ dày hiện từ chối tấm có gia công âm/vát chiều dày, scale không đều hoặc khóa; chưa tự sửa tiếp giáp. Tăng độ mịn chỉ chưa chia lại cung đã tạo thành khối. Xóa liên kết chưa phục hồi vết cắt gỗ thật. Chưa xác nhận tương đương mọi chức năng của plugin khác hoặc nhận mọi cấu trúc phụ kiện.

## Nhập sơ đồ vào Aspire

Giữ các chức năng từ 1.99.215: mỗi ván/mặt gia công nằm trên một Sheet riêng; tách Job theo khổ ván và độ dày, giữ Layer và tọa độ xếp tấm.

1. Trong TK chọn **Xuất ASPIRE**, rồi chọn thư mục lưu bộ DXF.
2. Trong Aspire chọn **Gadgets → TK Nhap So Do**. Lần đầu nếu chưa thấy mục TK, đóng và mở lại Aspire một lần.
3. Nếu có Job khác đang mở, lưu và đóng Job đó bằng lệnh Aspire trước khi nhập.
4. Chọn nơi lưu/tên file rồi **Save** từng Job. Hủy Save giữ nguyên sơ đồ; bấm Tiếp tục để lưu lại.

Luồng nhập đã được kiểm tra ở bản 1.99.215 trên Aspire 9.514: 25 Sheet, 620 đối tượng, 5 Layer và 3 Job khác khổ/độ dày; chưa thử trực tiếp các phiên bản Aspire khác. Bảng TK và file `DANH_SACH_SHEET.html` trong thư mục xuất giúp đối chiếu số ván, màu và mặt TOP/BOTTOM.

Bộ nhập sử dụng API Gadget công khai, không cần runtime Peo. Giữ xử lý biên cong, chung dao cho lỗ trong và biên ngoài, bỏ lỗ quá nhỏ kèm cảnh báo; NC đi kèm sơ đồ và Excel vật tư. Chưa chạy cắt CNC thực tế.

Phần mềm thuộc bản quyền của nhà phát hành. Kho này cung cấp các bộ cài, không cấp quyền sửa đổi hoặc phân phối lại mã nguồn.
