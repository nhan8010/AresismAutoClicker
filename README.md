# Auto Clicker Android

Ứng dụng Android không cần root, dùng AccessibilityService để thực hiện thao tác chạm.

## Chức năng
- Bấm đơn: chỉ đặt 1 điểm.
- Đa điểm: đặt nhiều điểm, bấm tuần tự 1 → 2 → 3...
- Kéo/thả điểm bấm trực tiếp trên màn hình.
- Chỉnh thời gian giữa các điểm và thời gian nghỉ sau mỗi vòng.
- Start/Stop bằng thanh điều khiển nổi.
- Lưu / nạp / xóa nhiều bộ nút bấm.
- Lưu dữ liệu bằng SharedPreferences, không mất sau khi thoát app.

## Quyền
Android bắt buộc người dùng tự bật dịch vụ Trợ năng cho Auto Clicker. Không cần root và không cần quyền hiển thị đè riêng vì overlay dùng TYPE_ACCESSIBILITY_OVERLAY.

## Build
Mở thư mục này bằng Android Studio (JDK 17+), sync Gradle và Build APK.
