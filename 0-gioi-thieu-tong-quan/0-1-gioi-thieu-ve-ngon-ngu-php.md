---
title: Giới thiệu về ngôn ngữ PHP
---

Trong chủ đề này, chúng ta sẽ tìm hiểu cụ thể về ngôn ngữ PHP, bao gồm:

  - PHP là gì?
  - Tóm tắt lịch sử hình thành của ngôn ngữ PHP.
  - Lý do chọn ngôn ngữ PHP.

## PHP là gì ?

*PHP* (viết tắt hồi quy "PHP: Hypertext Preprocessor") là một ngôn ngữ lập
trình kịch bản hay một loại mã lệnh chủ yếu được dùng để phát triển các
ứng dụng viết cho máy chủ, mã nguồn mở, dùng cho mục đích tổng quát.
Nó rất thích hợp với web và có thể dễ dàng nhúng vào trang HTML.
Do được tối ưu hóa cho các ứng dụng web, tốc độ nhanh, nhỏ gọn, cú pháp giống
C và Java, dễ học và thời gian xây dựng sản phẩm tương đối ngắn hơn so với các
ngôn ngữ khác nên PHP đã nhanh chóng trở thành một ngôn ngữ lập trình web
phổ biến nhất thế giới.

## Lịch sử hình thành PHP

Vào khoảng năm 1994, Rasmus Lerdorf đưa một số đoạn Perl Script vào trang Web
để theo dõi xem ai đang đọc tài liệu của ông ta. Dần dần, người ta bắt đầu
thích các đoạn Script này và sau đó đã xuất bản một gói công cụ có tên là
"Personal Home Pages" (nghĩa đầu tiên của PHP).
Ông ta đã viết một cơ chế nhúng và kết hợp với một số công
cụ khác để phân tích đầu vào từ các mẫu biểu HTML: FI, Form Interpreter hay
Phiên dịch mẫu biểu, được tạo ra theo cách đó và được đặt tên là PHP/FI hay
PHP2. Nó được hoàn thành vào khoảng giữa năm 1995.

Sau đó, người ta bắt đầu sử dụng các công cụ này để xây dựng những thứ
rắc rối hơn, và đội ngũ phát triển đã thay đổi từ một người duy nhất thành một
nhóm các nhà phát triển nòng cốt trong dự án, và nó đã được tổ chức hoá.
Đó là sự bắt đầu của PHP3. Đội ngũ các nhà phát triển
(Rasmus Lerdorf, Andi Gutmans, Zeev Suraski, Stig Bakken, Shane Caraveo
và Jim Winstead) đã cải tiến và mở rộng bộ máy nhúng và bổ sung thêm một số
hàm API đơn giản cho phép các lập trình viên khác tự do bổ sung nhiều tính
năng vào ngôn ngữ bằng cách viết các module cho nó.
Cấu trúc của ngôn ngữ đã được tinh chế, được kết cấu thân thiện hơn đối với
những người đến từ các ngôn ngữ hướng đối tượng hay các ngôn ngữ hướng thủ tục.
Nếu bạn đã biết một vài ngôn ngữ lập trình khác thì khi đến với PHP,
bạn sẽ không cảm thấy khó khăn.

Phiên bản mới nhất cho đến thời điểm này là PHP 7.0.

Các bạn có thể tham khảo chi tiết tại trang web PHP:
[Hypertext Preprocessor](http://www.php.net/)

## Lý do chọn ngôn ngữ lập trình PHP

 - Mã nguồn mở và miễn phí.
 Cái này thì mình không cần giải thích nhiều đúng không. Tất nhiên miễn phí là
 rất tốt phải không nào!

 - Mạnh mẽ.
 Tuy là miễn phí nhưng PHP là một công cụ rất mạnh mẽ cho việc sử dụng chúng
 với nhiều dự án web, có thể thực hiện tốt hầu hết các yêu cầu mà trang web
 cần. Hơn hết chúng đang phát triển với tốc độ cải thiện rất nhiều so với các
 phiên bản cũ.

 - Phổ biến.
 PHP rất phổ biến. Cho đến hiện tại có hơn 70% trang web trên toàn cầu sử dụng
 PHP và là ngôn ngữ phổ biến thứ 6 trên các ngôn ngữ chỉ sau Java, C, C++, C#
 và Python (thống kế đến nửa năm 2016). Các trang web nổi tiếng sử dụng PHP:
 Facebook, Wikipedia, Yahoo,...

 - Chuyên sử dụng cho Web.
 Như mình đã đề cập ở phần lịch sử thì nguồn gốc của PHP là sử dụng cho Web
 cho nên chúng hỗ trợ rất mạnh mẽ cho các dự án web của chúng ta.

 - Có lập trình hướng đối tượng.
 Từ phiên bản PHP 5 trở đi, PHP đã cung cấp đầy đủ cho lập trình hướng đối
 tượng, mô hình MVC để có thể xây dựng dự án web một cách khoa học hơn. Nhưng
 trong khóa học này chúng ta sẽ không tìm hiểu về lập trình hướng đối tượng mà
 chỉ nắm chắc kiến thức PHP căn bản thôi.

 - Nhiều tài liệu và cộng đồng hỗ trợ.
 Tất nhiên rồi, vì nó rất phổ biến nên chỉ cần bạn gặp rắc rối chỉ cần một từ
 khóa đơn giản trên google, stackoverflow,... thì bạn có thể giải quyết vấn đề
 nhanh chóng.

 - An toàn.
 Tuy không phải là an toàn nhất nhưng nếu biết cách xây dựng ứng dụng thì
 mình tin chắc bản có thể tránh được các nguy cơ bảo mật và tất nhiên trong
 khóa học này mính sẽ đưa ra các biện pháp an toàn thông tin tráng các lỗi bảo
 mật khi lập trình với kinh nghiệm cá nhân.

Ở trên đây, là một số lý do mà chúng ta nên chọn PHP làm ngôn ngữ chính cho
trang web của mình, hi vọng chúng sẽ thuyết phục bạn thích thú hơn trong khóa
 học này.

Hẹn gặp lại các bạn trong bài học tiếp theo!
