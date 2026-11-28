# TK CABINET 1.99.620 — bộ tải mới 620B

[Tải bộ cập nhật 620B đã ký và mã hóa — 3,22 MB](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.620_CAP_NHAT_B.rbz)

Bộ tải **620B** khắc phục việc thư viện CNC chỉ thiếu một tệp nhưng phải tải lại cả bộ 1,11 GB. Chương trình TK và thư viện CNC được kiểm tra riêng; phần đã đúng được giữ lại. Chương trình và nội dung thư viện vẫn là bản 1.99.620 đã phát hành. Đây là sửa bộ cập nhật, không phải phát hành thêm chức năng mới.

## Cách cập nhật

Trong TK vào **Cài đặt chung → Kiểm tra cập nhật**. Nếu bộ tải cũ bị kẹt, tải tệp 620B ở trên và cài bằng **Extension Manager → Install Extension**. Lưu bản vẽ, đóng hết SketchUp cùng phiên bản rồi mở lại để bộ tải mới hoạt động.

Bộ tải chuẩn bị dữ liệu ở nền. Có thể xem tiến độ tại **Extensions → Tải lại TK CABINET**. Khi báo đã chuẩn bị xong, lưu bản vẽ, đóng hết SketchUp cùng phiên bản và mở lại để hoàn tất cài đặt. Không tự đóng bản vẽ. Key và cài đặt riêng trên máy được giữ nguyên.

## Điểm khác của bộ tải 620B

- Chương trình TK khoảng 118 MB và thư viện CNC được kiểm tra độc lập. Chỉ tải chương trình nếu chưa có đúng bản.
- Thư viện đầy đủ thì không tải lại. Thiếu hoặc hỏng tệp nào thì tải các phần nhỏ chứa tệp đó và bổ sung đúng tệp; không bắt tải lại toàn bộ thư viện.
- Dữ liệu được chia thành các phần tối đa 8 MiB, tải tối đa 3 phần cùng lúc. Từng phần đều được kiểm tra mã SHA-256 trước khi dùng.
- Mất mạng hoặc đóng SketchUp không làm mất các phần tải xong. Lần sau tiếp tục phần còn thiếu. Tận dụng cả phần dữ liệu hợp lệ mà bộ tải 620 cũ đã tải dở.
- Các bản SketchUp trên cùng tài khoản Windows dùng chung phần tải đã lưu và thư viện CNC đã kiểm tra.
- Có nút **Chọn bộ cài đã tải** để dùng file ZIP tải bằng trình duyệt hoặc chép qua USB. Khi có bộ ZIP đầy đủ và đúng mã kiểm tra, không cần tải qua Internet nữa.

Máy mới chưa có thư viện vẫn cần tải dữ liệu lần đầu. Tải nền giúp giảm thời gian phải chờ khi bấm cập nhật; tốc độ thực tế phụ thuộc mạng và ổ đĩa. Bộ tải mới không làm thay đổi chương trình hay thiết lập bảo mật của Windows.

## Máy cần cài bằng file tải sẵn

1. Cài [bộ tải 620B](https://raw.githubusercontent.com/kimtrongcnc-ops/tk-cabinet-updates/main/TK_CABINET_1.99.620_CAP_NHAT_B.rbz), rồi mở lại SketchUp.
2. Tải [bộ đầy đủ 1.99.620](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/download/v1.99.620/TK_CABINET_1.99.620_DAY_DU.zip), hoặc chép file này từ máy đã tải xong.
3. Khi lượt tải hiện tại đã kết thúc hoặc báo lỗi, mở **Extensions → Tải lại TK CABINET → Chọn bộ cài đã tải**, chọn ZIP trên. Không cần giải nén và không cài ZIP trực tiếp bằng Extension Manager.
4. Đợi báo chuẩn bị xong, lưu bản vẽ rồi mở lại SketchUp để cài.

[Các bộ cài chương trình 1.99.620](https://github.com/kimtrongcnc-ops/tk-cabinet-updates/releases/tag/v1.99.620). Ưu tiên bộ tải **B** ở đầu trang thay cho bộ tải `CAP_NHAT.rbz` cũ trong danh sách release.

## Kiểm tra đã thực hiện

Đã kiểm tra gói mã hóa được SketchUp ký, trình đọc manifest cũ, khởi chạy trên Windows PowerShell, đọc đủ 48.042 tệp thư viện, tải HTTPS thực tế, tải tiếp khi ngắt mạng, tái sử dụng file cũ, sửa một phần thư viện, nhận bộ ZIP ngoại tuyến, từ chối dữ liệu sai mã kiểm tra, và cơ chế sao lưu/phục hồi khi cài lỗi. Bộ tải đã nạp và mở giao diện trên SketchUp 2023.0.367 / Ruby 2.7.2. Chưa kiểm tra riêng từng máy khách.

Thử nghiệm hai tệp thư viện còn thiếu tải 11,9 MB thay vì cả bộ 1,11 GB; chạy lại khi đủ dữ liệu không tải thêm. Đây là một trường hợp kiểm tra, không phải cam kết dung lượng hoặc tốc độ cho mọi máy.
