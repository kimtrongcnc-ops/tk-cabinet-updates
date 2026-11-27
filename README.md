# TK CABINET 1.99.620

[Tải bộ cập nhật đã mã hóa](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.620/TK_CABINET_1.99.620_CAP_NHAT.rbz) · [Tất cả bộ cài](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/tag/v1.99.620)

Bản 1.99.620 tổng hợp sửa đổi 595–619 và sửa tương thích khi khởi động SketchUp 2023. Giữ các thiết lập và key hiện có. Mã Ruby bên trong chương trình và bộ cập nhật đã được mã hóa, ký bằng dịch vụ chính thức của SketchUp.

## Cập nhật

Trong TK mở Cài đặt chung → Kiểm tra cập nhật. Nếu bộ tải cũ bị kẹt, tải file `TK_CABINET_1.99.620_CAP_NHAT.rbz` ở trên rồi vào Extension Manager → Install Extension để cài bộ tải mới. Lưu bản vẽ, đóng hết các cửa sổ SketchUp cùng phiên bản và mở lại. Khi báo đã chuẩn bị xong, lưu bản vẽ và mở lại SketchUp lần nữa để hoàn tất thay chương trình.

Bộ tải mới kiểm tra toàn bộ 48.042 tệp thư viện đã có trên máy. Nếu thư viện đầy đủ, chỉ cần tải lại **toàn bộ chương trình 118 MB** thay vì bộ 1,11 GB, giảm khoảng 89% dung lượng tải. Nếu thư viện thiếu hoặc sai, bộ tải tự chọn gói đầy đủ. Thời gian thực tế phụ thuộc mạng và ổ đĩa. Tải bị ngắt có thể tiếp tục; có đường tải Windows dự phòng khi curl không chạy được. Bộ tải không thay đổi thiết lập bảo mật của Windows.

## Máy khó tải: tải bằng trình duyệt hoặc chép qua USB

1. Cài bộ cập nhật nhỏ ở trên.
2. Nếu máy đã có thư viện CNC đầy đủ, tải [gói chương trình 118 MB](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.620/TK_CABINET_1.99.620_MA_HOA.rbz). Chép vào `%APPDATA%\TK CABINET\Updates\23\TK_620_program.rbz` cho SketchUp 2023, hoặc thay `23` bằng `26` cho SketchUp 2026. Tạo thư mục nếu chưa có. Không cài riêng gói này chồng vào thư mục TK cũ.
3. Nếu chưa có thư viện, tải [bộ đầy đủ](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.620/TK_CABINET_1.99.620_DAY_DU.zip), chép nguyên ZIP vào cùng thư mục với tên `TK_620.zip`.
4. Trong SketchUp chọn Extensions → Tải lại TK CABINET. Bộ tải kiểm tra, chuẩn bị từ file đã chép, rồi yêu cầu mở lại SketchUp để cài. Giữ file ZIP nguyên vẹn, không cần giải nén thủ công.

## Các nhóm sửa được gộp

- Mô-đun tủ và thông số dạng chuỗi; Phá khối giữ nhóm tấm.
- Nhận tấm xoay/nghiêng, chiều dày và chiều vân theo nhãn; bo góc tấm khuyết/thủng; nhãn và xếp tấm.
- Cắt nhanh/dao tùy biến đổi hướng bằng Tab; tạo cánh, khóa điểm, thước, Enter/Space, nhớ trạng thái; dán cạnh nhớ lựa chọn.
- Mẫu cài đặt gom nhóm, bảng cây bên trái và điều kiện chọn mẫu.
- CNC: cân nan/khe theo tỷ lệ gốc, chèn họa tiết, chạy viền đối xứng, giữ độc lập các mục và áp dụng vào tấm bên ngoài.
- Tương thích Ruby 2.7 của SketchUp 2023: lớp xử lý mới phải được gắn đúng vào công cụ, khắc phục lớp cũ che mất phần sửa sau khi mở lại SketchUp.

Kiểm tra trên SketchUp 2023.0.367 / Ruby 2.7.2, gồm hình học xoay/nghiêng, thao tác công cụ, CNC và mở/chuyển chế độ bản vẽ PDF. Đây là kiểm tra phần mềm; không thay cho kiểm tra đường dao và chạy thử trên máy CNC thực tế.
