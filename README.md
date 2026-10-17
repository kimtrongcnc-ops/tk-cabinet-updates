# TK CABINET 1.99.210

Bộ cập nhật đã ký và mã hóa cho SketchUp 2023–2026.

- Xuất ASPIRE: hiện bảng chọn tấm trước, rồi mở Aspire; bảng TK không tự che lên cửa sổ Aspire. Chỉ xuất hình học tấm và Layer.
- In tem: vẫn cho in khi chữ tràn khổ, giữ cảnh báo phần chữ có thể bị cắt.
- Sửa tem: khung chọn sơ đồ ôm sát hình; kéo và phóng to đúng tỷ lệ. Hiện tên Trên, Phải, Dưới, Trái khi sửa, không in các tên hướng dẫn này.
- Tích bật Layer đọc Z của dao tương ứng theo các tấm của Layer; bỏ tích không đọc. Âm thanh offline theo ngôn ngữ đang chọn.
- Load đường dao chuyển xuống hàng trên danh sách Layer.

Cài file `TK_CABINET_1.99.210_MA_HOA_SK2023_2026.rbz`, lưu bản vẽ rồi đóng/mở lại SketchUp. Máy đã có TK CABINET có thể dùng mục cập nhật trong tiện ích.

`latest.json` có chữ ký xác minh bộ cập nhật. Chỉ gói RBZ đã mã hóa và bản kê cập nhật được phát hành; không bao gồm khóa riêng hay công cụ cấp phép.

Chưa kiểm tra in trên máy in vật lý. Khi đưa DXF vào Aspire, kiểm tra độ dày phôi trong Job Setup trước khi tạo đường dao.

[Tải bộ cài TK CABINET 1.99.210 (.rbz)](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.210_MA_HOA_SK2023_2026.rbz)

## Cập nhật từ bản 1.99.203 trở lên

Kết nối Internet, lưu công việc và đóng cửa sổ Nesting. Vào **Extensions → TK CABINET → Kiểm tra bản cập nhật**. Đồng ý để TK tự tải, kiểm tra và cài bản mới. Khi hoàn tất, đóng hết SketchUp rồi mở lại. Máy khách không cần tài khoản GitHub.

## Cài lần đầu hoặc nâng cấp từ bản cũ

1. Tải file `.rbz` ở trên, không giải nén.
2. Lưu công việc trong SketchUp.
3. Vào **Extensions → Extension Manager → Install Extension**, chọn file vừa tải.
4. Đóng hết cửa sổ SketchUp rồi mở lại.

Cần key còn hạn dành cho máy đang sử dụng. Key, cài dao và Post đã lưu được giữ khi cập nhật; không cần kích hoạt lại nếu key hiện tại còn hợp lệ.

## Tệp phát hành

- File `.rbz`: bộ cài được SketchUp Extension Warehouse ký và mã hóa các tệp Ruby bên trong.
- `latest.json`: thông tin bản cập nhật có chữ ký của nhà phát hành, được TK đọc tự động. Người dùng không cần mở hoặc chỉnh sửa file này.

Phần mềm thuộc bản quyền của nhà phát hành. Kho này cung cấp các bộ cài, không cấp quyền sửa đổi hoặc phân phối lại mã nguồn.
