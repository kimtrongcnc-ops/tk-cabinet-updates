# TK CABINET 1.99.300

Bộ cài đầy đủ đã ký và mã hóa chính thức, kế thừa 1.99.299. Trong SketchUp chọn **Extensions → TK CABINET → Kiểm tra bản cập nhật**. Lưu bản vẽ, cập nhật rồi đóng và mở lại SketchUp.

[Tải bộ cài 1.99.300](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.300_MA_HOA.rbz)

- Sửa lỗi truyền tham số cam trên SketchUp 2023 / Ruby 2.7.
- Cho phép chạy cam, rãnh hậu và khoan mồi trên nhiều vùng tủ; giữ gia công ngoài vùng chọn. Chạy lại thay nét cũ trong vùng, không nhân đôi.
- Cam tự né mặt gỗ tiếp xúc che miệng cam khi bật tùy chọn tránh.
- Rãnh hậu và khoan mồi tự động cô lập tấm nguồn phù hợp, chờ **Yes**, rồi khôi phục hiển thị và tạo gia công.
- Giữ giới hạn độ dày theo cài đặt. Ví dụ tấm 15 mm không thuộc khoảng 16–19 mm: cần chỉnh khoảng phù hợp trong Cài đặt chung.

Không khóa theo năm SketchUp. Mục tiêu tương thích 2021–2027; đã kiểm thử trực tiếp 2023 và 2026. Các bản 2021, 2022, 2024, 2025 và 2027 chưa được kiểm thử trực tiếp, không coi là đã chứng nhận tương thích.

Kiểm tra: tủ xoay 0°, 37°, 90° trên 2023; khởi động mới với bộ mã hóa 1.99.300 và chạy cam/rãnh/khoan mồi đạt. Trên 2026 đã kiểm tra giữ nét tủ cũ, chạy lại, xóa/tạo lại, đồng bộ nhiều vùng, cam né thanh chắn, và thao tác rãnh hậu trên tủ thực tế. Không lưu hình học thử vào bản vẽ của người dùng. Chưa xác nhận mọi biên dạng tấm và chưa thử CNC vật lý trong đợt này.

Không thay đổi thuật toán Nesting, NC, tạo ván, cánh hoặc nẹp dán trong bản sửa này. Giữ nguyên bản quyền và cài đặt riêng từng máy.
