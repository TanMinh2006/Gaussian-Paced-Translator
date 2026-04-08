# Công cụ dịch thuật Terminal với Nhịp thở Gauss 🌬️🔔

## Giới thiệu
Đây là một công cụ CLI dịch thuật đơn giản sử dụng `googletrans`. 
Điểm khác biệt nằm ở **tư duy vận hành**: Hệ thống không gửi request liên tục mà có "nhịp thở" dựa trên Công thức hàm mật độ xác suất Phân phối chuẩn (Gaussian Distribution)

## Tại sao lại dùng công thức hàm mật độ xác suất của phân phối chuẩn (Gaussian-Distribution)?
Thay vì nghỉ một khoảng thời gian cố định, công cụ này mô phỏng hành vi con người (có đạo đức):
- Có lúc đọc nhanh, có lúc đọc chậm.
- Đảm bảo hạ tầng Google không bị quá tải đột ngột.
- Tối ưu hóa tài nguyên Cloud một cách văn minh.
Chỉ là giao tiếp với hạ tầng Google một cách văn minh và lịch sự, nếu coi đây là phá hoại thì sẽ không có ý tưởng này. Có thể là tôi nghĩ vậy.
## Triết lý của tác giả
> "Cú pháp tôi có thể tra, nhưng nhịp thở hình chuông này là của tôi." - Chỉ là một kẻ yêu thích sự tự do và Toán học thôi, nhớ lấy điều đó!

## Cách sử dụng
1. Cài đặt thư viện: `pip install googletrans asyncio nltk matplotlib`
2. Chạy file: `python your_file_name.py`

## Bản quyền (License)
Dự án sử dụng giấy phép **GNU GPLv3**. Cấm các hành vi lợi dụng code để tạo bot phá hoại hạ tầng.

---
## Lời nhắn nhủ từ một kẻ yêu thích sự tự do
Đây không phải hành vi phá hoại hạ tầng Google, nhớ lấy điều đó. Khi bạn sử dụng cho mục đích phá hoại, thì những hộ vệ của công lý đều soi vào bạn.
Có những dòng code không nên viết, và có những dòng code không nên sửa linh tinh. Những con người theo trí tuệ nhân tạo còn gặp khó vì OpenNMT quá đỗi cổ đại, thì tôi cũng vậy.
Tôi ở đây là vì OpenNMT đã trả kết quả Unknown lần thứ 3 khiến tôi không thể giữ được bình tĩnh nữa. Sự sáng tạo vĩ đại nhất, thường đến từ những khoảnh khắc chứng kiến cả thế giới sụp đổ mà không thể làm gì, nó quá tuyệt vọng phải không?
Tôi đã tìm thấy thư viện googletrans như một giải pháp tốt hơn, tuy nhiên hệ thống dịch máy đơn giản ban đầu có tần suất request dạng thẳng tắp.
Ồ, vậy chúng ta làm gì? Một ý tưởng điên rồ xuất hiện sau khi tôi nghiên cứu về công thức hàm mật độ xác suất Gauss, là tôi có thể kết hợp thư viện googletrans với công thức đó và bùm, kết quả là một đồ thị hình chuông Gauss vĩ đại và mang vẻ đẹp toán học. Dù không ai dạy, nhưng đó là niềm tự hào của tôi. Nếu bạn thấy dự án này khiến bạn rục rịch về những ý tưởng điên rồ hơn, thì hãy thử kết hợp những kiến thức bạn đã học, có thể tạo ra những điều bất ngờ. Vật lý giải thích nguyên lý của vũ trụ, mà vũ trụ lại là Toán học.
Không một ai được phép dùng quyền năng của các vị thần Toán học để làm vấy bẩn mọi thứ.
"Bà tôi từng nói: Kẻ tầm thường copy code, kẻ giỏi tra syntax, nhưng bậc thầy là kẻ biết biến những con số khô khan thành nhịp đập của sự sống."

## Lời cảm ơn
Lời đầu tiên, tôi xin gửi lời cảm ơn chân thành đến người bạn Vũ Hữu Khánh (Lớp Thiết kế Game K25, Đại học Hải Phòng), người đã đồng hành và mở rộng thế giới quan của tôi về Java, Web, Hệ điều hành, Network và SQL.
Tôi tri ân Google vì đã cho phép tôi kế thừa "bộ não" vĩ đại nhất thế giới công nghệ; cảm tạ nhà toán học lỗi lạc Carl Friedrich Gauss, người đã giúp tôi khai phá vẻ đẹp kỳ diệu trong vũ trụ của những con số.
Đặc biệt, xin bày tỏ lòng biết ơn sâu sắc tới Thầy Hồ Phi Tứ (Bộ môn Xác suất Thống kê, Đại học Hải Phòng), người đã truyền lửa đam mê và dẫn dắt tôi dấn thân vào con đường Toán học ứng dụng; cùng Thầy Lê Đắc Nhường, người đã đặt những viên gạch nền tảng đầu tiên trong tư duy lập trình của tôi.

## Về dòng chảy của thế giới công nghệ
Đây là món quà dành cho những ai theo đuổi lĩnh vực AI/Data Science. Đơn giản chỉ có vậy.
## Châm ngôn nhẹ nhàng
Googletrans đã ra đời được 11 năm nhờ các lập trình viên tài hoa. Đúng, câu chuyện về googletrans là do mọi người viết lên, nhưng hồi kết của câu chuyện sẽ do tôi quyết định.
" Thế giới sẽ xoay chuyển thêm một lần nữa, tôi không biết có bài báo hay giáo trình và hướng dẫn nào nói về điều này đâu. "
## Mốc thời gian
Dự án này được hình thành vào 31/03/2026 - 01/04/2026
## Cập nhật
Thư viện asyncio (03/04/2026)
Công thức Markov, Fourier (08/04/2026)
