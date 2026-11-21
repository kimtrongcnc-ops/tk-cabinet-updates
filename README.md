# TK CABINET 1.99.574

TK CABINET 1.99.574 gộp toàn bộ bộ chương trình trước đó và các sửa đổi đến bản 574.

- Gắn nhãn: tăng tốc nhưng giữ nhận diện khoang, vị trí, tên và thứ tự tấm; giữ quy tắc chọn mặt theo layer, ưu tiên mặt có rãnh khi đối chiếu hai mặt. Khi tạo/sửa gia công bằng công cụ TK, nhãn đã gắn được cập nhật theo lệnh, không theo dõi nền mô hình.
- Cài đặt: chuyển cài đặt chung và nesting giữa máy/phiên bản, kèm biên dạng mẫu tự vẽ; giữ cài đặt riêng và key của máy nhận.
- CAM và xuất NC: sửa các trường hợp dán nẹp/layer chặn xuất, đường bào lòng chạy liên tục theo chiều đã chọn và mô phỏng trên SketchUp cũ.
- Nesting: tăng tốc xếp; tận dụng các lỗ thủng, lòng khung kính và ô khuyết hợp lệ; hiển thị đường layer viền lòng mảnh; sửa nền vàng lóe khi mở.
- Công cụ: Xóa tất cả nhận diện thêm gia công của bên khác; tạo cánh theo hướng bắt điểm, nháy đúp Enter hoặc phím cách để hoàn tất.
- PDF: bổ sung mặt cắt theo bố trí khoang, gộp khoang giống nhau; giữ quy tắc cũ của số tấm, vòng tròn, đường dẫn, hướng chữ và vị trí trên trang chính.

Máy đang dùng TK: Cài đặt chung → Kiểm tra bản cập nhật. Lưu bản vẽ, chờ tải bộ đầy đủ, đóng hết cửa sổ SketchUp cùng phiên bản rồi mở lại. Nếu lần mở lại đầu tiên còn thông báo đang tải, chờ tải hoàn tất rồi mở lại thêm lần nữa.

Bộ CAP_NHAT.rbz dùng cho cập nhật máy đã có TK và tự tải bộ đầy đủ. Bộ MA_HOA.rbz là bộ cài đầy đủ đã ký/mã hóa. Mã nguồn chỉnh sửa được giữ riêng tại máy phát triển, không nằm trong gói công khai.

## Tải bộ cài

- [Bộ cài đầy đủ 1.99.574](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.574/TK_CABINET_1.99.574_MA_HOA.rbz)
- [Bộ cập nhật 1.99.574](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.574/TK_CABINET_1.99.574_CAP_NHAT.rbz)

Chọn đúng hai tệp trên. Các tệp có `KIEM_TRA_1` trong tên chỉ được lưu để đối chiếu lần thử trước.

Kênh cập nhật dùng manifest có chữ ký và kiểm tra SHA-256 của gói tải về. Bộ cài đầy đủ được ký bằng SketchUp Extension Warehouse.
