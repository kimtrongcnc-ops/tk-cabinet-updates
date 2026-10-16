# TK CABINET

Các bản cập nhật chính thức của TK CABINET cho SketchUp.

Bản hiện tại: **1.99.205 — ngày 17/10/2026**.

[Tải bộ cài TK CABINET 1.99.205 (.rbz)](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.205_MA_HOA_SK2023_2026.rbz)

## Thay đổi trong bản 1.99.205

- Giữ bố cục cài dao và báo cáo tấm quen thuộc. Thêm Z in đậm cạnh số lần cắt: xanh khi không âm, đỏ khi âm; tính theo độ dày và gốc Z đang dùng.
- Mô phỏng 3D có vân gỗ, màu lõi ở cạnh cắt, xem được mặt dưới và dao đang chạy. Có thanh tốc độ và nút ẩn gỗ thừa đã cắt rời; giữ nút ẩn/hiện đường chạy.
- Viền lật mặt điều chỉnh được, tính cả bán kính dao, phần ván bị xén và tọa độ hai mặt khi lật trái–phải. Chặn xuất khi khoảng chừa mép không đủ.
- Cam/chốt, rãnh hậu và khoan hậu nhận tấm trong group/module theo độ dày cài đặt. Dải mặc định cam/chốt 16–19 mm, hậu 5–10 mm; vẫn kiểm tra điều kiện ghép của từng chức năng.
- Thêm kiểu hèm kính + cắt lòng với hai đường dao: bào hèm trước, cắt lòng sau.
- Áp dụng giảm tốc cuối đường/cung tròn và nội suy G2/G3 khi Post hỗ trợ.

Đã kiểm tra bằng dữ liệu thử, mô phỏng và kiểm tra mã xuất; chưa chạy cắt thực tế trên máy CNC. Sau cập nhật, nạp lại đường dao và đối chiếu mô phỏng, gốc Z, dao cùng Post trước khi chạy máy.

## Cập nhật từ bản 1.99.203 trở lên

Kết nối Internet, lưu công việc và đóng cửa sổ Nesting. Vào **Extensions → TK CABINET → Kiểm tra bản cập nhật**. Đồng ý để TK tự tải, kiểm tra và cài bản mới. Khi hoàn tất, đóng hết SketchUp rồi mở lại. Máy khách không cần tài khoản GitHub.

## Cài lần đầu hoặc nâng cấp từ bản cũ

1. Tải file `.rbz` ở trên, không giải nén.
2. Lưu công việc trong SketchUp.
3. Vào **Extensions → Extension Manager → Install Extension**, chọn file vừa tải.
4. Đóng hết cửa sổ SketchUp rồi mở lại.

Cần key còn hạn dành cho máy đang sử dụng. Key, cài dao và Post đã lưu được giữ khi cập nhật; không cần kích hoạt lại nếu key hiện tại còn hợp lệ.

## Tệp phát hành

- File `.rbz`: bộ cài đã được SketchUp Extension Warehouse ký và mã hóa các tệp Ruby bên trong.
- `latest.json`: thông tin bản cập nhật có chữ ký của nhà phát hành, được TK đọc tự động. Người dùng không cần mở hoặc chỉnh sửa file này.

Phần mềm thuộc bản quyền của nhà phát hành. Kho này cung cấp các bộ cài, không cấp quyền sửa đổi hoặc phân phối lại mã nguồn.
