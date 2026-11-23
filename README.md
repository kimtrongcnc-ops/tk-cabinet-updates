# TK CABINET 1.99.594 — bộ cập nhật đầy đủ cho SketchUp 2023–2026

[Tải bộ cập nhật 1.99.594](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.594/TK_CABINET_1.99.594_CAP_NHAT_DAY_DU.rbz) · [Bộ cài đặt gốc](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.594/TK_CABINET_1.99.594_CAI_DAT_GOC.json) · [Tất cả tệp phát hành](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/tag/v1.99.594)

Tải **TK_CABINET_1.99.594_CAP_NHAT_DAY_DU.rbz**, cài bằng Extension Manager. Hoặc vào TK → Cài đặt chung → Kiểm tra bản cập nhật. Máy bị kẹt bộ tải cũ có thể cài RBZ này trực tiếp.

- Gộp đầy đủ các sửa từ 585 đến 593 cùng toàn bộ chức năng và thư viện CNC của bộ 584.
- Bút tấm bắt góc, cạnh, trung điểm và mặt; giữ nhập kích thước bằng số trên 2023.
- Nhãn giữ thứ tự theo khoang và vị trí; nhận tấm ẩn, khóa, ngoài màn hình; giữ nhãn đã đúng. Sửa xoay mũi tên trên tấm sao chép.
- Nesting lấy chiều vân theo mũi tên nhãn. Chỉ bỏ CAM nằm hoàn toàn trong phần lòng đã khoét của chính tấm đó; giữ CAM trên khung và tấm khác.
- Bào nền cho bước ngang đến 80% đường kính dao, có kiểu từ trong ra ngoài/từ ngoài vào trong. Ziczac quét ngang/dọc rồi chạy vòng sửa sát thành; giữ mục Hướng và không trừ nẹp ở đường không có nẹp. Thu gọn bảng thông số.
- Giữ các sửa PDF, màu/vân/nẹp, phối cảnh có cánh/bỏ cánh, xoay một lần bấm, chỉnh trực tiếp, kích thước và mẫu cài đặt trên 2023.
- Lấy bộ máy gốc làm mặc định: 129 thông số, 43 nhóm công cụ, 42 mẫu công cụ, 4 mẫu chung và 2 postprocessor. Mặc định áp dụng khi chưa có giá trị; thông số riêng và key của máy đã dùng được giữ. File CAI_DAT_GOC.json cho phép chủ động nhập toàn bộ cấu hình gốc.
- Giữ bộ tải tiếp khi đứt mạng, kiểm tra toàn vẹn, chuẩn bị thư viện và nạp sớm sau khi mở lại. Nâng cấp thẳng từ bản cũ, không cần cài từng bản trung gian.

Lưu bản vẽ và đóng hết SketchUp cùng phiên bản khi bộ tải yêu cầu mở lại. Nếu đang dùng bộ tải cũ, lần mở lại đầu tiên nạp bộ tải mới; sau khi tải/chuẩn bị xong, mở lại để cài chương trình. Gói đầy đủ khoảng 1,11 GB. Không cài DAY_DU.zip trực tiếp bằng Extension Manager.

Đã kiểm tra trực tiếp trên ADMIN-PC, SketchUp 23.0.367/Ruby 2.7.2: sáu nhóm thử nhãn, nhập số/bắt mép, xoay/vân, lọc CAM; nesting đủ tám tấm; tám kiểm tra giao diện CNC và mười kiểm tra PDF. Mở lại đã nạp đủ các mô-đun sửa. Bộ mặc định đã qua xác thực và 139 kiểm tra giá trị/giữ cấu hình riêng. Chưa chạy cắt trên máy CNC vật lý.

Mã Ruby bên trong được ký và mã hóa chính thức. Nguồn đọc được lưu riêng trên máy gốc; không đưa mã kích hoạt, khóa riêng hoặc đường dẫn cá nhân vào bộ mặc định.
