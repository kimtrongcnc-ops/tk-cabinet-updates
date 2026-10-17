# TK CABINET

Các bản cập nhật chính thức của TK CABINET cho SketchUp.

Bản hiện tại: **1.99.208 — ngày 17/10/2026**.

[Tải bộ cài TK CABINET 1.99.208 (.rbz)](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.208_MA_HOA_SK2023_2026.rbz)

## Thay đổi trong bản 1.99.208

- **Xếp tấm** mở sơ đồ và công cụ chống văng. Bấm **Load sơ đồ xếp tấm** để xếp các tấm đang chọn trong SketchUp. Khi đổi trang, sơ đồ được giữ trong cùng cửa sổ; đóng Nesting rồi mở lại sẽ bắt đầu trống để Load hoặc tải sơ đồ cũ.
- Bỏ nút Chống văng và Xem tấm trên thanh trên cùng. Nút **Chọn đường dao chạy** giữ vị trí cũ ở cửa sổ rộng. Chuyển Cài đặt xếp tấm sang phải, tăng kích thước Lưu thiết lập; thông báo hoàn tất chống văng đổi sang xanh đậm.
- Thêm chỉnh **Độ dày nét viền sơ đồ** trong phần Sửa tem. Viền ván và chi tiết trên sơ đồ đổi cùng nhau, lưu theo mẫu và giữ khi in; nét dấu vị trí và nét chữ chỉnh riêng.
- **In tem / PDF** mở bản tem trong trình duyệt mặc định và yêu cầu hiện hộp thoại in, khắc phục phụ thuộc lệnh in trong HtmlDialog đời cũ. Giữ tem được chọn, khổ tem và có nút in lại.
- Đường dao mới tạo hoặc tự sinh theo Layer được chèn lên đầu và cuộn đến dòng mới. Các đường dao cũ giữ thứ tự đã xếp.
- Khi kéo dao, các dòng tự dạt ra và hiện khoảng trống để thả; Esc hủy kéo.
- Tâm tấm giữ cố định khi xoay và thu/phóng 3D. Space thoát DIM và giữ số đo đã đặt; chạy/dừng mô phỏng bằng nút ▶/Ⅱ, không dùng Space.
- Bỏ nút Đọc Z; chọn dao hoặc Layer sẽ tự đọc bằng giọng cũ theo ngôn ngữ đang chọn. Bấm lại vẫn đọc dù không đổi độ sâu. Âm đọc có sẵn trong bộ cài, không cần đăng nhập.

Đã kiểm tra bố cục, thao tác Load, đọc Z và bản in thử 4 tem thành 4 trang PDF khổ 60 × 40 mm; mã tạo bản in chạy được trên thư viện Ruby của SketchUp 2023. Chưa kiểm tra trực tiếp hộp thoại in trong SketchUp 2023 hoặc máy in thật.

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
