# TK CABINET 1.99.582

Bộ tải sửa **582B** khắc phục lỗi “Chưa khởi động được trình tải” trên Windows dùng PowerShell mặc định. Chương trình và thư viện đầy đủ 1.99.582 giữ nguyên.

Nếu đã cài bộ tải 582 cũ, lấy 582B qua kiểm tra cập nhật hoặc cài tệp **CAP_NHAT_B.rbz**. Lưu bản vẽ, đóng hết SketchUp cùng phiên bản rồi mở lại để nạp bộ tải mới. Đợi tải/chuẩn bị hoàn tất, sau đó đóng/mở lại để cài chương trình đầy đủ. Nút “Thử lại” trong bảng cũ không thay được bộ tải.

Bản đầy đủ gộp nền 574 và các sửa đổi 576–582 đã hoàn thành trên bộ nguồn gốc.

- Sửa lỗi cập nhật lặp lại sau khi đóng/mở SketchUp do bộ 544 nạp chương trình trước bộ 574.
- Bút tấm nhận số và Enter trên SketchUp 2023, gồm bàn phím số phụ.
- PDF lắp ráp/gửi khách: chỉnh trực tiếp, mặt cắt theo khoang, xoay từng phối cảnh, có cánh/bỏ cánh, màu và vật liệu, khung tên; giữ quy tắc số tấm.
- Các sửa làm mịn, xem mô hình trên điện thoại và thư viện CNC gồm 9.370 hoa văn mới đã tách, phân loại, giữ tỉ lệ.
- Giữ các sửa nhãn, layer, CAM, nesting, mô phỏng và công cụ của nền 574.

## Cập nhật

Trong TK: **Cài đặt chung → Kiểm tra bản cập nhật**. Đợi tải, kiểm tra và chuẩn bị xong, lưu bản vẽ, đóng hết SketchUp cùng phiên bản rồi mở lại. Key và cài đặt riêng được giữ nguyên.

Nếu bị mắc bộ cập nhật cũ, tải [bộ cập nhật 1.99.582](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.582/TK_CABINET_1.99.582_CAP_NHAT_B.rbz) và cài qua **Extension Manager**. Bộ này tự tải cả chương trình và thư viện CNC (khoảng 1,1 GB), có tải tiếp khi gián đoạn. Bước chuẩn bị thư viện có thể mất vài phút.

[Chi tiết bản phát hành và các tệp](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/tag/v1.99.582).

`DAY_DU.zip` là dữ liệu dành cho bộ cập nhật; không cài trực tiếp ZIP bằng Extension Manager.

## Kiểm tra

Đã đối chiếu nguồn, kiểm tra cú pháp Ruby 2.7/3.2 và JavaScript, hồi quy, chữ ký, SHA-256, tải tiếp, chuẩn bị toàn bộ thư viện và phục hồi khi cài lỗi. Bút tấm 581A đã thử trực tiếp trên máy khách SketchUp 2023. Bản 582 chưa cài lên máy khách đang được kiểm tra lỗi cập nhật theo yêu cầu chủ máy; chưa chạy cắt CNC vật lý.

| Tệp | Dung lượng (byte) | SHA-256 |
|---|---:|---|
| TK_CABINET_1.99.582_CAP_NHAT_B.rbz | 26813 | 2257dd26656263efbf2aece8cb540088d1628b818bac333550b8bf2a80e31dec |
| TK_CABINET_1.99.582_DAY_DU.zip | 1111444661 | 19f25ecb21201486e9d2290571b6648c10fd8eaa27621e0f93dcea737472813d |

`latest.json` được ký bằng khóa phát hành hiện có. Khóa riêng không nằm trong kho này.

Bộ tải 582B đã kiểm tra trên Windows PowerShell 5 với ExecutionPolicy Restricted mặc định, đường dẫn Unicode/dấu nháy đơn và lệnh khởi chạy ẩn thực tế. Không thay thiết lập bảo mật Windows; tôn trọng chính sách quản trị đặt rõ. Chưa cài 582B lên máy khách trong đợt kiểm tra này.
