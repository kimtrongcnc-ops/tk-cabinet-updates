# TK CABINET 1.99.213

Bộ cập nhật đã ký và mã hóa cho SketchUp 2023–2026.

- Nhận vòng biên vật lý của tấm cong và lỗ xuyên, kể cả khi cạnh nằm ở nhiều Layer. Cùng một dao cắt lỗ bên trong trước, rồi biên ngoài; bù dao đúng từng phía.
- Lỗ quá nhỏ không vừa dao được bỏ qua kèm cảnh báo số lượng, tên tấm và dao. Các lỗ lớn vẫn chạy. Không tự nối đường hở hoặc bỏ qua lỗi hốc/rãnh riêng.
- Sơ đồ cũ cần nạp/xếp lại từ model để nhận vòng biên mới. Sơ đồ mới giữ đủ dữ liệu biên khi lưu và mở lại.


- Xuất NC: tên bộ được điền sẵn theo tên model và có thể sửa trong hộp Save. Chỉ ghi sau Save; NC, sơ đồ và báo cáo Excel nằm cùng bộ.
- Excel dùng tên bộ xuất kèm đuôi _Vat_tu.xlsx, gồm ván theo màu/độ dày/khổ và số lượng, nẹp dán cạnh theo màu và mét dài, phụ kiện trong model, cùng thông tin phạm vi thống kê. Tấm gia công hai mặt chỉ tính một tấm ván.
- Sửa nhận diện cạnh cắt xuyên trên tấm cong bị tính thành hai mặt; sơ đồ vẽ đúng đường cong, không còn khung chữ nhật dư tại góc cong.
- Thùng ngăn kéo có mẫu lưu/chọn lại, chia tầng và cột, xà chặn và khoảng lùi xà, độ ăn đáy riêng với độ sâu dao. Nét định vị ray dùng chung hai bên, có cách mép dưới.
- Suốt áo luôn tạo một lỗ mồi chính tâm mỗi bát. Lỗ dây LED nằm trên tâm rãnh và chọn riêng trái/phải; rãnh LED có mẫu, kích thước và mô phỏng ánh sáng.
- Lưu mẫu tiếng Việt tương thích SketchUp 2023; giữ các chức năng báo cáo ray, suốt áo, bát treo và độ dài LED.

Cài file `TK_CABINET_1.99.213_MA_HOA_SK2023_2026.rbz`, lưu bản vẽ rồi đóng/mở lại SketchUp. Máy đã có TK CABINET có thể dùng mục cập nhật trong tiện ích.

`latest.json` có chữ ký xác minh bộ cập nhật. Chỉ gói RBZ đã mã hóa và bản kê cập nhật được phát hành; không bao gồm khóa riêng hay công cụ cấp phép.

Đã kiểm tra Ruby 2.7/3.2, lưu/đọc hình học, mô phỏng và sinh NC. Với tấm thử dùng T2 Ø6: 175 lỗ lớn và biên ngoài vẫn cắt, 4 lỗ nhỏ bỏ qua. Chưa chạy cắt CNC thực tế. Mô phỏng sáng là hình hiển thị trong model. Khi cập nhật phải đóng hết SketchUp rồi mở lại để nạp đầy đủ mã mới.

[Tải bộ cài TK CABINET 1.99.213 (.rbz)](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.213_MA_HOA_SK2023_2026.rbz)

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
