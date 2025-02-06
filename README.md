# Lưu ý: Mọi thao tác sai đều để lại vấn đề, nên cân nhắc làm chỉnh chu từng bước thật đúng. Tham khảo thêm các video để chọn ra 1 video dễ hình dung nhất.
# Mục các tiến hành theo đúng quy trình "chi tiết bạn kéo xuống dưới"
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

# Mục 1: xác đinh mạch trái phải
## -hàn mặt sau trước nên sẽ ngược trái phải. cố gắng xác định vì trong quá trình làm khi hàn hết lên thì lại hàn cả 2 trái hoặc cả 2 phải thì quá trình rã hàn sẽ hư hại sản phẩm quá trình diy có thể thất bại sớm
## -Lời khuyên: hoàn thành 1 mạch xong đến mạch thứ 2 phải chú ý check lại mạch 1
## -đối với mạch đơn thì không cần check mục này.
# Mục 2: Hàn led đầu tiên
## -hàn led đầu tiên vì led có lỗ và mặt phẳng dễ hàn led nhất, cần xác định rõ nếu chơi led quy trình diy sẽ phức tạp hơn gấp đôi led sáng theo thứ tự nên 1 sáng thì 2 mới sáng, nếu led 1 không thì tất cả led đều không sáng.
## -hàn led cần xác định chân: có 2 loại sk6812 có chân và không chân "các chân của 2 loại khác nhau hoàn toàn về cấu tạo chân"
## -led kèm theo là loại đồng nhất chân chỉ cần xác định chân vcc và gnd trên mạch hàn đúng chân vào led.
## -chú ý cạnh dấu để phán đoán, điểm đánh dấu trên mạch sẽ đánh dấu theo đúng chân nào đó không mặc định chân cụ thể. ví dụ: có thể là đánh dấu GND hoặc VCC hoặc thậm chí đánh dấu vào chân in, không quan trọng nhưng tất cả đánh dấu đều mặc định 1 chân nào đó theo mạch đó nên quan trọng chỉ cần xác định đúng là được. Hình ảnh vị trí chân led 2 dạng dưới đây

  ### <img src="https://i.imgur.com/jXz37cf.png">
  ### <img src="https://i.imgur.com/rBJCOe1.png">
