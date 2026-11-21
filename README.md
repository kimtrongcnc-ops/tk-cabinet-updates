# TK CABINET 1.99.574

**Sửa bộ cập nhật B — 21/11/2026:** tải và kiểm tra gói ở tiến trình riêng ẩn, có tiến độ; tự thử lại và tải tiếp khi gián đoạn, dùng lại tệp đã tải đủ. Giữ kiểm tra chữ ký/SHA-256 trước khi cài. Bộ chương trình đầy đủ vẫn là 1.99.574, giữ toàn bộ sửa đổi dưới đây.

TK CABINET 1.99.574 gộp toàn bộ bộ chương trình trước đó và các sửa đổi đến bản 574.

- Gắn nhãn: tăng tốc nhưng giữ nhận diện khoang, vị trí, tên và thứ tự tấm; giữ quy tắc chọn mặt theo layer, ưu tiên mặt có rãnh khi đối chiếu hai mặt. Khi tạo/sửa gia công bằng công cụ TK, nhãn đã gắn được cập nhật theo lệnh, không theo dõi nền mô hình.
- Cài đặt: chuyển cài đặt chung và nesting giữa máy/phiên bản, kèm biên dạng mẫu tự vẽ; giữ cài đặt riêng và key của máy nhận.
- CAM và xuất NC: sửa các trường hợp dán nẹp/layer chặn xuất, đường bào lòng chạy liên tục theo chiều đã chọn và mô phỏng trên SketchUp cũ.
- Nesting: tăng tốc xếp; tận dụng các lỗ thủng, lòng khung kính và ô khuyết hợp lệ; hiển thị đường layer viền lòng mảnh; sửa nền vàng lóe khi mở.
- Công cụ: Xóa tất cả nhận diện thêm gia công của bên khác; tạo cánh theo hướng bắt điểm, nháy đúp Enter hoặc phím cách để hoàn tất.
- PDF: bổ sung mặt cắt theo bố trí khoang, gộp khoang giống nhau; giữ quy tắc cũ của số tấm, vòng tròn, đường dẫn, hướng chữ và vị trí trên trang chính.

Máy đang dùng TK: Cài đặt chung → Kiểm tra bản cập nhật. Lưu bản vẽ, chờ tải bộ đầy đủ, đóng hết cửa sổ SketchUp cùng phiên bản rồi mở lại. Nếu lần mở lại đầu tiên còn thông báo đang tải, chờ tải hoàn tất rồi mở lại thêm lần nữa.

Bộ CAP_NHAT_B.rbz dùng cho cập nhật máy đã có TK và tự tải bộ đầy đủ. Bộ MA_HOA.rbz là bộ cài đầy đủ đã ký/mã hóa. Mã nguồn chỉnh sửa được giữ riêng tại máy phát triển, không nằm trong gói công khai.

## Tải bộ cài

- [Bộ cài đầy đủ 1.99.574](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.574/TK_CABINET_1.99.574_MA_HOA.rbz)
- [Bộ cập nhật 1.99.574](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.574/TK_CABINET_1.99.574_CAP_NHAT_B.rbz)

Chọn đúng hai tệp trên. Bộ CAP_NHAT cũ và các tệp có `KIEM_TRA_1` chỉ lưu đối chiếu, không dùng để cài.

Máy đã lên đủ 1.99.574 không cần cài lại. Máy cũ còn lỗi cập nhật: kiểm tra cập nhật lại; nếu vẫn mắc bộ tải cũ, cài bộ CAP_NHAT_B bằng Extension Manager, lưu bản vẽ và mở lại SketchUp. Chờ thông báo “Đã tải và kiểm tra xong”, rồi đóng hết SketchUp cùng phiên bản và mở lại để hoàn tất.

Đã kiểm tra bản đầy đủ trên máy khách SketchUp 2023 và cập nhật từ 1.99.549 trên máy SketchUp 2026: đủ 44 phần sửa, 1.892 tệp khớp gói ký, cài đặt và thanh công cụ giữ nguyên. Bộ tải B đã thử tải thật, tải tiếp sau gián đoạn, tệp lỗi và mất mạng.

Kênh cập nhật dùng manifest có chữ ký và kiểm tra SHA-256 của gói tải về. Bộ cài đầy đủ được ký bằng SketchUp Extension Warehouse.
