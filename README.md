# TK CABINET

Các bản cập nhật chính thức của TK CABINET cho SketchUp.

Bản hiện tại: **1.99.209 — ngày 17/10/2026**.

[Tải bộ cài TK CABINET 1.99.209 (.rbz)](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.209_MA_HOA_SK2023_2026.rbz)

## Thay đổi trong bản 1.99.209

- **Xuất ASPIRE chỉ lấy sơ đồ tấm và Layer hình học**, giữ tỷ lệ 1:1 mm. Không phụ thuộc cài đặt tem, dao, Post hoặc mã NC.
- Sửa lỗi **“Cài đặt tem nhãn không hợp lệ”** sau khi thêm chỉnh nét viền sơ đồ tem. Lưu thiết lập, lưu sơ đồ và xuất NC nhận đúng thông số nét viền; giữ tương thích mẫu tem cũ.
- Giữ các cải tiến của bản 1.99.208: bố cục Xếp tấm, in tem qua trình duyệt, dao mới lên đầu, kéo thả có khoảng trống, tâm xoay 3D cố định và Space thoát DIM.

Đã kiểm tra dữ liệu từ giao diện qua bộ xuất Ruby, đối chiếu tọa độ và Layer DXF, đọc/lưu sơ đồ và kiểm tra xuất NC. Kiểm tra Ruby của SketchUp 2023 đạt. Chưa chạy máy CNC hay in giấy thực tế.

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
