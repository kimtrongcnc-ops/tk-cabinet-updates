# TK CABINET 1.99.259

Bộ cài đã ký và mã hóa cho SketchUp 2023–2026.

## Cài đặt và cập nhật

Trong SketchUp chọn **Extensions → TK CABINET → Kiểm tra bản cập nhật**. Lưu bản vẽ, cài cập nhật rồi đóng và mở lại SketchUp.

Cài lần đầu: tải [bộ cài RBZ 1.99.259](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.259_MA_HOA_SK2023_2026.rbz), chọn **Extension Manager → Install Extension**. Máy khách không cần tài khoản GitHub. Cần key còn hạn của máy đang dùng.

## Tạo cánh

- Chọn hai điểm chéo để xác định vùng cánh; bấm cạnh hồi/đợt trong vùng để chia các cánh khác kích thước.
- Ctrl chọn từng khoang trong vùng; Shift đưa cánh vào trong/ra ngoài; Tab đổi mặt đứng/nằm ngang.
- Enter tạo dàn cánh; Space thoát. Khe hở ngoài và giữa lấy từ cài đặt.
- Nhận khoang theo vùng đã chọn, tránh bộ quét vòng cạnh toàn mô hình gây treo.

Bản này giữ nguyên mã Tạo ván, Sửa khoang, Nẹp và Nesting của bản nội bộ 1.99.258.

## Kiểm tra

Đã kiểm tra nguồn trong SketchUp: tủ xoay, ba cánh khác kích thước, khe hở chung, chu kỳ phím Tab/Shift/Ctrl và ba khoang trong component lồng nhau. Gói phát hành đã kiểm tra chữ ký, mã hóa và SHA-256, cài trên máy phát triển cho SketchUp 2023 và 2026. Chưa xác nhận khởi động mới gói 259 trên mọi máy hoặc mọi cấu trúc tủ; chưa thử cắt CNC thực tế.

Bản kê latest.json có chữ ký nhà phát hành. Chỉ phân phối gói đã mã hóa; không kèm mã nguồn hoặc công cụ cấp key.
