# NCKH_2025
Hệ thống cống ngăn mặn

**Mô tả:**
Hệ thống này được thiết kế để tự động điều khiển việc đóng mở cống nhằm ngăn chặn sự xâm nhập của nước mặn vào các vùng nước ngọt, bảo vệ nguồn nước cho việc tưới tiêu nông nghiệp tại khu vực Đồng bằng sông Cửu Long và Đồng bằng sông Hồng. Hệ thống sử dụng cảm biến pH, Mực nước để đo độ mặn, mực nước giữa 2 bên để so sánh giá trị và đưa ra quyết định đóng mở cống dựa trên ngưỡng cài đặt.

**Nguyên lý hoạt động:**
Khi độ mặn vượt quá ngưỡng cho phép, tức là nước mặn đang tiến vào nội đồng thì thực hiện đóng cống, ngược lại thì mở cống. Hệ thống cũng có thể được điều khiển bằng tay thông qua điện thoại hoặc các button trên bộ điều khiển khi có giám sát viên vận hành ở cống.

**Các thành phần chính:**
* Cảm biến pH
* Cảm biến mực nước
* Vi điều khiển: ESP32
* Zigbee CC2530
* Động cơ bước
