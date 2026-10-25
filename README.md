# TK CABINET 1.99.297

Bộ cài đã ký và mã hóa cho SketchUp 2023–2026.

Trong SketchUp chọn **Extensions → TK CABINET → Kiểm tra bản cập nhật**. Lưu bản vẽ rồi đóng và mở lại SketchUp sau khi cài.

[Tải bộ cài 1.99.297](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.297_MA_HOA_SK2023_2026.rbz)

## Cập nhật cụm bo và uốn cong

- Tích hợp phần cụm bo, hai kiểu xương, mẫu xương, ngậm hồi/phủ hậu, xem trước, bo đợt và nóc vào bộ cài đầy đủ.
- Tách khoang trên/dưới để chỉnh đợt; đổi chiều cao giữ vị trí ngang của cụm. Khi cao hết tủ, xử lý nóc/đáy/đợt và khôi phục hậu chung; sửa phần nóc thò ra phía sau.
- Phôi uốn chỉ tạo nét trên layer riêng, giữ nguyên hình học tấm. Cài đặt Uốn cong TK dùng chung thông số và cách tính nét với phôi bo.
- Đối chiếu bốn mẫu ZSU R40/50/60/80 ở góc 90 độ: chiều dài phôi và số nét khớp mẫu đo. Sửa thiếu nét R50; cung tham chiếu tính theo đoạn thực của mô hình.
- Kế thừa toàn bộ bộ cài 1.99.296; không thay thế riêng các module tạo ván độc lập, cánh, nẹp và nesting.

## Kiểm tra và giới hạn

157 tệp Ruby/JavaScript đã kiểm cú pháp. Gói mã hóa có 86 tệp RBE và chữ ký SketchUp; các tài nguyên không phải Ruby khớp gói chuẩn bị. Không kèm khóa riêng hoặc công cụ cấp key.

Đã chạy hai bài kiểm tra phím tạo ván và sáu bài kiểm tra native về khoang trên/dưới, đổi chiều cao/chế độ, tiếp giáp tấm, phôi kèm, tổ hợp khoang và khoang giật cấp. Sáu bài cũng đạt khi nạp phần tích hợp RBE vào SketchUp 2026 đang chạy; mọi hình học thử được hủy, không lưu vào bản vẽ. Đây chưa phải kiểm tra khởi động mới trên mọi máy.

Đã kiểm tra tính toán góc/bán kính/hướng xoay, nhưng mẫu ZSU đối chiếu trực tiếp mới ở góc 90 độ. Bào nền có lớp lót/mô phỏng, khe xương và tham chiếu nhiều cung chưa được xác nhận tương đương ZSU. Chưa kiểm tra cắt CNC thực tế hoặc thao tác đầy đủ trên SketchUp 2023. Không coi mọi yêu cầu cũ trong hội thoại là đã được kiểm thử lại trong lần phát hành này.
