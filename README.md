# TK CABINET 1.99.269

Bộ cài đã ký và mã hóa cho SketchUp 2023–2026.

## Cài đặt và cập nhật

Trong SketchUp chọn **Extensions → TK CABINET → Kiểm tra bản cập nhật**. Lưu bản vẽ, cài cập nhật rồi đóng và mở lại SketchUp. Cài lần đầu: tải [bộ cài RBZ 1.99.269](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.269_MA_HOA_SK2023_2026.rbz), chọn **Extension Manager → Install Extension**. Máy khách không cần tài khoản GitHub. Cần key còn hạn của máy đang dùng.

## Thay đổi

- Xếp tấm mở sơ đồ hiện có; chỉ nút Tạo sơ đồ xếp tấm mới chạy xếp mới. Nesting bổ sung nằm bên phải.
- Chống văng có nhóm Tự động, Thủ công, Thứ tự cắt riêng; công cụ xếp tấm không xuất hiện trong mục này.
- Nút Load dao xuất NC. Chỉ layer đang tích ở sơ đồ được đưa sang danh sách gán dao; bỏ tích loại nguồn đó khỏi đường dao và yêu cầu tải lại đường dao. Giữ hồ sơ dao đã lưu.
- Căn giữa giữ mép ngoài cánh, hỗ trợ cánh dài đã đúng và cánh ngắn cần chỉnh; hướng dẫn được rút gọn.
- Thư viện màu bên trái, nhập thư viện ngoài, hút màu và tẩy màu; giữ thông tin nẹp khi tô hoặc tẩy màu.
- Xóa tất cả xử lý nhóm tấm kèm đường phụ và liên kết cũ; giữ hình học mặt tấm. Không tự lấp các lỗ đã khoét thành hình học.

## Kiểm tra và giới hạn

Đã kiểm tra chuyển chế độ, lọc layer và thay đổi khóa kiểm tra đường dao khi bỏ tích. Với toàn bộ layer được tích, dữ liệu khai báo CNC giống bản 268 về hình học, dao, tốc độ, chiều sâu và số lượt. Đã kiểm tra cú pháp 138 tệp, chữ ký và nội dung gói; các kiểm tra nguồn căn giữa, màu/nẹp và xóa tấm đã chạy trong SketchUp 2026.

Chưa chạy cắt CNC thực tế, chưa xác nhận thao tác đầy đủ trên mọi máy hoặc SketchUp 2023. Các kiểm tra giao diện cũ 187/198 có kỳ vọng không còn phù hợp; không được tính là đã đạt. Bản kê latest.json có chữ ký nhà phát hành. Không kèm khóa riêng hoặc công cụ cấp key.
