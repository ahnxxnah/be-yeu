# Bé Yêu — Ứng dụng theo dõi chăm sóc bé

Ứng dụng web tĩnh bằng tiếng Việt, chạy trực tiếp trên điện thoại và máy tính.

## Tính năng
- Tạo, chuyển đổi, sửa, xóa nhiều hồ sơ bé.
- Ghi chiều cao / cân nặng, biểu đồ và so sánh xu hướng giữa các lần đo.
- Lưu danh mục sữa với nhóm tháng tuổi và công thức pha *do người dùng tự nhập theo nhãn*; ghi từng cữ sữa theo thời gian và ml.
- Ghi ăn dặm, bữa chính, bữa phụ, thực đơn và thời gian ăn.
- Lịch tiêm dự kiến, chi phí, trạng thái hoàn thành, theo dõi sau tiêm.
- Thuốc kê đơn theo số ngày và số lần/ngày, ô đánh dấu từng lần dùng; thuốc không kê đơn theo từng lần.
- Chỉnh sửa hoặc xóa từng bản ghi; xuất/nhập JSON, chế độ gộp hoặc thay thế dữ liệu.

## Cách dùng
Mở file `index.html` trên trình duyệt. Bấm **Thêm bé** để tạo hồ sơ đầu tiên. Dữ liệu được lưu ở `localStorage` của trình duyệt, *không đồng bộ* giữa các thiết bị. Nên **Xuất JSON** định kỳ trong phần **Dữ liệu** và giữ file sao lưu ở nơi an toàn.

## Đăng lên GitHub Pages
1. Tạo repository mới trên GitHub (nên để private nếu bạn lưu thông tin thật, nhưng GitHub Pages có thể xuất bản công khai tuỳ gói/cấu hình).
2. Upload file `index.html` tại thư mục gốc, commit.
3. Vào **Settings → Pages → Build and deployment → Deploy from a branch**, chọn branch `main` và thư mục `/(root)`.
4. Vào link Pages được GitHub cung cấp để sử dụng trên điện thoại. *Lưu ý: GitHub Pages xuất bản mã ứng dụng, không tải dữ liệu cá nhân lên GitHub do app chỉ lưu cục bộ.*

## Lưu ý sức khỏe
Thông tin nhận xét tăng trưởng chỉ phản ánh thay đổi giữa các lần đo của cùng một bé, không phải đánh giá chuẩn WHO, chẩn đoán hay tư vấn điều trị. Lịch tiêm và liều thuốc do người dùng nhập, ứng dụng không kê đơn, không nhắc giờ, không tự tính liều. Xác nhận với bác sĩ/nhân viên y tế khi cần.

**Bảo mật khi xuất bản:** Không đưa tệp JSON sao lưu hoặc bất kỳ thông tin thật của bé vào repository GitHub. Nếu thiết bị dùng chung, người khác dùng trình duyệt cùng hồ sơ có thể xem nội dung lưu cục bộ. Giới hạn dữ liệu riêng tư khi sử dụng máy chung.
