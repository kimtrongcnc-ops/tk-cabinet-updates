# TK CABINET

Các bản cập nhật chính thức của TK CABINET cho SketchUp.

Bản hiện tại: **1.99.207 — ngày 17/10/2026**.

[Tải bộ cài TK CABINET 1.99.207 (.rbz)](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.207_MA_HOA_SK2023_2026.rbz)

## Thay đổi trong bản 1.99.207

- **Xuất NC** chọn nơi lưu rồi hiện hộp **Save / Hủy**. Bấm Save một lần để lưu cả bộ NC và sơ đồ xếp tấm vào cùng thư mục bộ; NC vẫn chia theo vật liệu và độ dày, sơ đồ nằm trong `Xep_tam`. Lưu xong tự mở thư mục. Hủy thì không ghi bộ mới.
- **Chọn đường dao chạy** thay tên mục Xuất CNC. Nút Xuất NC nằm cạnh Load đường dao; bỏ các nút xuất trùng.
- Mở mô phỏng bằng nút ▶ của từng tấm để xem đúng tấm, đúng mặt. Giữ danh sách tấm bên trái, hình 3D ở giữa và G-code bên phải; bỏ nút Xuất NC trong mô phỏng. Quay lại không cần Load lại nếu dữ liệu chưa đổi.
- Giảm khối lượng dựng hình và giới hạn nhịp vẽ mô phỏng; chỉ dựng tấm đang xem. Giữ hình học cắt, lỗ khoan và các góc nhìn.
- Khi phóng toàn màn hình, vùng xem tấm mở rộng thành lưới nhiều cột; cửa sổ nhỏ giữ bố cục đang dùng.
- Sau Load, hình xem trước thể hiện đường cắt, lỗ khoan và rãnh theo màu Layer.
- Danh sách Layer có ba vùng thao tác: tìm dao, báo cáo các tấm cùng Layer, và chọn/gán Layer. Báo cáo cùng các thẻ tấm liên quan hiện màu xanh đậm.
- Đọc Z theo ngôn ngữ đang chọn, dùng âm thanh đóng gói sẵn. Bấm Layer, đổi dao hoặc độ sâu đều có thể đọc lại; có nút tắt/mở.
- Bỏ thao tác nháy đúp vùng trống cột Layer để ẩn thông số và dòng hướng dẫn tương ứng; giữ báo cáo tấm.

Đã kiểm tra luồng Save/Hủy, dữ liệu đường dao, mô phỏng và đăng ký hai mặt khi thay hở viền bằng dữ liệu thử. Chưa chạy cắt CNC thực tế hoặc đo hiệu năng trên từng máy khách.

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
