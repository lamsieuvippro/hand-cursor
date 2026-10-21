HAND CURSOR - Minecraft 1.21.11 (Fabric) v1.1.1
Cần: Fabric API 0.141.1+1.21.11, YetAnotherConfigLib 3.8.2+1.21.11-fabric. Mod Menu là tuỳ chọn (để mở màn hình Config).

CÁC BẢN SỬA ĐỔI (v1.1.1):
- Khắc phục lỗi so sánh Model Enum trong Fabric 1.21.11 (nhận diện chính xác skin Steve / Alex).
- Khắc phục triệt để lỗi con trỏ hệ thống không hiện lại sau khi đóng GUI.
- Thêm tùy chỉnh Offset X, Offset Y trong menu Config để căn chỉnh góc trỏ tay theo ý muốn.

BUILD
1. Cài JDK 21.
2. Tải template tại https://fabricmc.net/develop/template/ (chọn 1.21.11), chép "gradle", "gradlew", "gradlew.bat" vào thư mục này.
3. gradlew build  ->  build/libs/handcursor-1.1.1.jar

CẤU HÌNH: Mod Menu -> Hand Cursor -> Config  (hoặc sửa file config/handcursor.json5)
