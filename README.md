# Công cụ dịch thuật Terminal với Nhịp thở Gauss 🌬️🔔

## Giới thiệu
Đây là một công cụ CLI dịch thuật đơn giản sử dụng `googletrans`. 
Điểm khác biệt nằm ở **tư duy vận hành**: Hệ thống không gửi request liên tục mà có "nhịp thở" dựa trên Công thức hàm mật độ xác suất Phân phối chuẩn (Gaussian Distribution)

## Tại sao lại dùng Gauss?
Thay vì nghỉ một khoảng thời gian cố định, công cụ này mô phỏng hành vi con người:
- Có lúc đọc nhanh, có lúc đọc chậm.
- Đảm bảo hạ tầng Google không bị quá tải đột ngột.
- Tối ưu hóa tài nguyên Cloud một cách văn minh.
Chỉ là giao tiếp với hệ thống một cách văn minh và lịch sự, nếu coi đây là phá hoại thì sẽ không có ý tưởng này. Có thể là tôi nghĩ vậy.
## Triết lý của tác giả
> "Cú pháp tôi có thể tra, nhưng nhịp thở hình chuông này là của tôi." - Một kẻ tự do về tâm hồn, yêu toán ứng dụng. Nhớ lấy điều đó!

## Cách sử dụng
1. Cài đặt thư viện: `pip install googletrans numpy nltk matplotlib`
2. Chạy file: `python your_file_name.py`

## Bản quyền (License)
Dự án sử dụng giấy phép **GNU GPLv3**. Cấm các hành vi lợi dụng code để tạo bot phá hoại hạ tầng.

---
## Lời nhắn nhủ từ một kẻ tự do tâm hồn
Đây không phải hành vi phá hoại hệ thống, nhớ lấy điều đó. Khi bạn sử dụng cho mục đích phá hoại, thì những hộ vệ của công lý đều soi vào bạn.
Mỗi dòng code tồn tại đều có lý do. Những con người theo trí tuệ nhân tạo còn gặp khó vì OpenNMT quá đỗi cổ đại, thì tôi cũng vậy.
Tôi ở đây là vì OpenNMT đã trả kết quả Unknown lần thứ 3 khiến tôi không thể giữ được bình tĩnh nữa. Sự sáng tạo vĩ đại nhất, thường đến từ những khoảnh khắc chứng kiến cả thế giới sụp đổ mà không thể làm gì, nó quá tuyệt vọng phải không?
Tôi đã tìm thấy thư viện googletrans như một giải pháp tốt hơn, tuy nhiên hệ thống dịch máy đơn giản ban đầu có tần suất request dạng thẳng tắp.
Ồ, vậy chúng ta làm gì? Một ý tưởng điên rồ xuất hiện sau khi tôi nghiên cứu về công thức hàm mật độ xác suất Gauss, là tôi có thể kết hợp thư viện googletrans với công thức đó. Dù không ai dạy, nhưng đó là niềm tự hào của tôi. Nếu bạn thấy dự án này khiến bạn rục rịch về những ý tưởng điên rồ hơn, thì hãy thử kết hợp những kiến thức bạn đã học, có thể tạo ra những điều bất ngờ. Vật lý giải thích nguyên lý của vũ trụ, mà vũ trụ lại là Toán học.
"Bà tôi từng nói: Kẻ tầm thường copy code, kẻ giỏi tra syntax, nhưng bậc thầy là kẻ biết biến những con số khô khan thành nhịp đập của sự sống."

## Lời cảm ơn
Một lần nữa thì tôi xin cảm ơn người bạn Vũ Hữu Khánh cùng lớp thiết kế game khoá 25 ở Đại Học Hải Phòng đã giúp tôi biết thêm kiến thức về Java, Web, Operating System, Network,SQL. Cảm ơn Google vì đã cho tôi kế thừa bộ não vĩ đại nhất thế giới công nghệ, cảm ơn ông Carl Friedrich Gauss - một nhà toán học lỗi lạc đã giúp tôi mở mang tầm mắt về toán học.
