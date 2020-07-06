# Control SmartLock using Bluetooth BLE
Yêu cầu: 
    1. Bật Bluetooth và Location (Bắt buộc để tìm SmartLock)
    2. Cấp quyền truy cập vị trí cho ứng dụng

Chức năng:
    1. Tự tìm kiếm khóa NodeLock
    2. Scanning: Tiếp tục tìm kiếm khóa NodeLock
    3. Unlock: Mở khóa NodeLock
    4. Query Power
    5. Reset Motor

Cài đặt:
    1. Clone source code hoặc tải source đã được nén.
    2. Mở Android Studio, import code 
    3. Cài các API mà project yêu cầu nếu thiếu
    compileSdkVersion 29
    buildToolsVersion "29.0.0"
    