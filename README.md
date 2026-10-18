# TK CABINET 1.99.214

Bộ cập nhật đã ký và mã hóa cho SketchUp 2023–2026.

## Nhập toàn bộ sơ đồ vào Aspire

- Mỗi ván/mặt gia công nằm trên một Sheet riêng, giữ nguyên Layer và tọa độ xếp tấm.
- Tách Job theo khổ ván và độ dày; đặt đơn vị mm và độ dày tự động.
- Chọn Save cho từng Job, đổi tên trong File name nếu cần. Hủy Save giữ nguyên sơ đồ; bấm Tiếp tục để lưu lại.
- Đã kiểm tra trên Aspire 9.514: 25 Sheet, 620 đối tượng, 5 Layer khớp tọa độ; 3 Job khác khổ/độ dày chuyển đúng, hủy và lưu lại không nhập trùng. Chưa thử trực tiếp các phiên bản Aspire khác.

## Cách dùng

1. Trong TK chọn **Xuất ASPIRE**, rồi chọn thư mục lưu bộ DXF.
2. Trong Aspire chọn **Gadgets → TK Nhap So Do**. Lần đầu nếu chưa thấy mục TK, đóng và mở lại Aspire một lần.
3. Nếu có Job khác đang mở, lưu và đóng Job đó bằng lệnh Aspire trước khi nhập.
4. Chọn nơi lưu/tên file rồi **Save** từng Job.

Aspire 9.5 gọi ván đầu là Default Sheet, tiếp theo Sheet 1, Sheet 2… Bảng TK và file `DANH_SACH_SHEET.html` trong thư mục xuất giúp đối chiếu số ván, màu và mặt TOP/BOTTOM.

Bộ nhập được TK triển khai qua API Gadget công khai, không cần runtime Peo. Mở riêng từng DXF vẫn dùng được; khi mở riêng cần tự chọn mm và độ dày trong Job Setup.

## Cập nhật

Trong SketchUp chọn **Extensions → TK CABINET → Kiểm tra bản cập nhật**, hoặc cài [gói RBZ đã ký](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.214_MA_HOA_SK2023_2026.rbz) qua Extension Manager. Lưu bản vẽ và khởi động lại SketchUp sau khi cài.

Máy khách không cần tài khoản GitHub. Cần key còn hạn cho máy đang dùng; key, cài dao và Post đã lưu được giữ khi cập nhật. `latest.json` có chữ ký của nhà phát hành để TK xác minh gói tải về. Chỉ bộ cài đã ký/mã hóa, bản kê cập nhật và hướng dẫn được phát hành; không bao gồm khóa riêng hoặc công cụ cấp phép.

Giữ các chức năng từ 1.99.213: nhận biên tấm cong, dùng chung dao cho lỗ trong và biên ngoài, bỏ lỗ quá nhỏ kèm cảnh báo; NC đi kèm sơ đồ và Excel vật tư. Chưa chạy cắt CNC thực tế.

Phần mềm thuộc bản quyền của nhà phát hành. Kho này cung cấp các bộ cài, không cấp quyền sửa đổi hoặc phân phối lại mã nguồn.
