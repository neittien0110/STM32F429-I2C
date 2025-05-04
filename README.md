# GIAO TIẾP I2C

STM32 có sẵn __3 bộ driver điều khiển I2C__. Đoạn chương trình sau minh họa hiển thị ra màn hình OLED 1"3 qua giao tiếp I2C.

## Kết nối STM32F429 với module cảm biến

## Các bước lập trình

1. Tạo dự án mới.
2. Thiết lập xung nhịp đồng hồ CPU clock rate ở 180 MHz với 2 bước cấu hình như trong ảnh.
   - Kích hoạt RCC.\
    ![RCC Enable](./assets/RCCEnable.png)
   - Thiết lập CPU Clock.\
    ![Thiết lập CPU Clock](./assets/ClockConfigration.png)

## Kết quả
