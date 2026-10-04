Bài nâng cao đã làm là NC2 và NC3

1. **Bài NC2 (Đếm số buổi học đã chọn):**
   - **Mô tả:** Lắng nghe sự kiện thay đổi trạng thái (`OnCheckedChangeListener`) của các `CheckBox` (buổi Sáng, Chiều, Tối).
   - **Hoạt động:** Mỗi khi người dùng check hoặc uncheck vào bất kỳ ô nào, ứng dụng sẽ tự động tính toán lại số lượng các buổi học đang được chọn và cập nhật hiển thị ngay lập tức lên giao diện thông qua một `TextView`.

2. **Bài NC3 (Chuyển đổi chế độ tối - Dark Mode):**
   - **Mô tả:** Tích hợp `MaterialSwitch` để cho phép người dùng bật/tắt giao diện chế độ tối (Dark Mode) cho toàn bộ ứng dụng.
   - **Hoạt động:** Khi người dùng thay đổi trạng thái của Switch, ứng dụng sử dụng `AppCompatDelegate.setDefaultNightMode()` để áp dụng chế độ `MODE_NIGHT_YES` (bật) hoặc `MODE_NIGHT_NO` (tắt). Đặc biệt, ứng dụng còn tự động kiểm tra và đồng bộ lại trạng thái của Switch cho khớp với cài đặt hiển thị hiện hành khi vừa được khởi động lại.
