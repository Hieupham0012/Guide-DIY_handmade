# Lưu ý: Mọi thao tác sai đều để lại vấn đề, nên cân nhắc làm chỉnh chu từng bước thật đúng. Tham khảo thêm các video để chọn ra 1 video dễ hình dung nhất.
# Mục các tiến hành theo đúng quy trình "chi tiết bạn kéo xuống dưới"
## [I. xác đinh mạch trái phải ](#Mot)
## 1. xác đinh mạch trái phải
## 2. Hàn led đầu tiên
## 3. Hàn diode
## 4. hàn hotswap
## 5. hàn chân MCU cái
## 6. hàn chân nối điểm màn oled cùng mặt với mcu "nếu có"
## 7. hàn chân công tắc pin "nếu có"
## 8. cắm chân 0.6mm kèm theo vào chân cái và gắn MCU vào
## 9. hàn chân oled, trrs 3.5mm, reset, núm xoay "nếu có".
## 10. kiểm tra và nạp code "shop có hướng dẫn nạp cả qmk và zmk"

<a name="Mot"></a>
## I. xác đinh mạch trái phải 
# Mục 1: xác đinh mạch trái phải
## -hàn mặt sau trước nên sẽ ngược trái phải. cố gắng xác định vì trong quá trình làm khi hàn hết lên thì lại hàn cả 2 trái hoặc cả 2 phải thì quá trình rã hàn sẽ hư hại sản phẩm quá trình diy có thể thất bại sớm
## -Lời khuyên: hoàn thành 1 mạch xong đến mạch thứ 2 phải chú ý check lại mạch 1
## -đối với mạch đơn thì không cần check mục này.
# Mục 2: Hàn led đầu tiên
## -hàn led đầu tiên vì led có lỗ và mặt phẳng dễ hàn led nhất, cần xác định rõ nếu chơi led quy trình diy sẽ phức tạp hơn gấp đôi, led sáng theo thứ tự nên 1 sáng thì 2 mới sáng, nếu led 1 không thì tất cả led đều không sáng.
## -hàn led cần xác định chân: có 2 loại sk6812 có chân và không chân "các chân của 2 loại khác nhau hoàn toàn về cấu tạo chân"
## -led kèm theo là loại đồng nhất chân chỉ cần xác định chân vcc và gnd trên mạch hàn đúng chân vào led.
## -chú ý cạnh dấu để phán đoán, điểm đánh dấu trên mạch sẽ đánh dấu theo đúng chân nào đó không mặc định chân cụ thể. ví dụ: có thể là đánh dấu GND hoặc VCC hoặc thậm chí đánh dấu vào chân in, không quan trọng nhưng tất cả đánh dấu đều mặc định 1 chân nào đó theo mạch đó nên quan trọng chỉ cần xác định đúng là được. Hình ảnh vị trí chân led 2 dạng dưới đây

  ### <img src="https://i.imgur.com/jXz37cf.png">
  ### <img src="https://i.imgur.com/rBJCOe1.png">
## hàn từ vị trí số 1 đến hết, led sáng đúng thứ tự nếu sai thì các led sau không sáng hoặc sáng nhưng chập chờn.
# Mục 3: Hàn diode
## xác định hướng diode. Đối với các mạch có ký hiệu thì chú ý hướng như hình. Đối với mạch không có thì chủ yếu là lỗ tròn qua lỗ vuông là hướng.
   ### <img src="https://i.imgur.com/BYdDaLz.png">
# Mục 4: hàn hotswap
## trên mạch có hình minh hoạ gắn đúng hướng là được.
## đối với loại chân giả không có điểm hàn hotswap. gắn chân giả vào lỗ cố định băng dính và hàn chân giả rồi cắm switch vào test thử
# Mục 5: hàn chân MCU cái
### <img src="https://i.imgur.com/jj9xJQ7.jpg">
## chân MCU cái có 12 chân mỗi bên
## MCU nằm ở mặt trên nên quay mạch lại thực hiện. Không nằm cùng hướng điode nên chú ý hàn ngược
## chú ý: hàn sai hướng MCU rã hàn đoạn này hầu như hư mạch khônng cứu được hoặc cứu thì đa số chập chạm. Nói tóm lại là gần như diy thất bại.
# Mục 6: hàn chân nối điểm màn oled cùng mặt với mcu "nếu có"
### <img src="https://i.imgur.com/VkqYA7O.jpg">
## Chú y: hàn đúng mặt không hàn nhầm xuống mặt dưới. mạch sẽ không hư nhưng sẽ không hoạt động gì cả.
# Mục 7:hàn chân công tắc pin "nếu có"
## công tắc pin sẽ có chân chờ sẵn PCB hỗ trợ promini và nrf52840 bluetooh
## nếu không có chân chờ công tắc pin có thể cạo phần mạch phần mass hàn cố định và đầu nối pin vào chân raw+gnd trên mạch để sử dụng đối với PCB không hỗ trợ
# Mục 8: Cắm chân 0.6mm kèm theo vào chân cái và gắn MCU vào
## cắm các chân kèm theo vào lỗ cái rồi đặt MCU vào.
## chú ý: cắm kịch đồng 0,6mm xuống chân cái.
### <img src="https://i.imgur.com/mYRfM89.jpg">
# Mục 9: hàn chân oled, trrs 3.5mm, reset, núm xoay "nếu có".
### <img src="https://i.imgur.com/KRrI6t9.jpg">
# Mục 10: kiểm tra và nạp code "shop có hướng dẫn nạp cả qmk và zmk"
## Chú ý: nếu nạp với MCU atmega32u4 thì sẽ nạp qua qmk tool box. Còn Nrf52840 sẽ nạp zmk urf2 kéo thả file đơn giản

