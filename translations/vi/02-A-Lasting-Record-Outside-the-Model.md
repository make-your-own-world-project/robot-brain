> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../02-A-Lasting-Record-Outside-the-Model.md) | [Tất cả ngôn ngữ](../README.md)

# Mỗi bộ phận làm gì-và không có mô hình nào kiểm soát được những gì

![Các nguồn ban đầu hỗ trợ lịch sử lâu dài trong khi các công cụ có thể thay thế thực hiện công việc hạn chế.](../../illustrations/core-architecture-layers.png)

Robot Brain là một tập hợp các bộ phận hợp tác được xây dựng xung quanh một bản ghi lâu dài. Nó không phải là một mô hình ngôn ngữ lớn, một nhóm các mô hình giả vờ là một hoặc một dịch vụ trò chuyện có tính năng tìm kiếm bổ sung.

Sự khác biệt quan trọng vì các vấn đề đang được giải quyết đến từ việc yêu cầu một dịch vụ mô hình ngôn ngữ tạm thời đóng vai trò là bộ nhớ, nhà nghiên cứu, người viết, người kiểm tra và người đánh giá cùng một lúc. Phần mềm này tách biệt những công việc đó và giữ lịch sử của một người bên ngoài mọi mô hình.

## Lưu sự kiện trước khi diễn giải nó

Trình giữ nguồn lưu cuộc trò chuyện, ghi chú, hình ảnh, tài liệu, nhiệm vụ hoặc mục khác khi nó đến. Nó cũng lưu các thông tin thực tế đã biết, chẳng hạn như thời gian đến, nguồn, người tạo khi thiết lập và quyền khi được ghi lại.

Tên tệp, dự đoán mô hình hoặc cách diễn giải sau này không thể âm thầm trở thành sự thật về nguồn. Thông tin còn thiếu vẫn còn thiếu.

## Làm cho tìm kiếm hữu ích mà không cần thay thế nguồn

Phần mềm tạo các bản sao có thể tìm kiếm được như văn bản được trích xuất, mô tả và chỉ mục. Những bản sao này trỏ lại nguồn không thay đổi. Chúng có thể được xây dựng lại khi có phương pháp tốt hơn.

Điều này khác với việc yêu cầu một mô hình ngôn ngữ tóm tắt một đống tệp và sau đó coi bản tóm tắt đó là bộ nhớ. Một bản tóm tắt là một lần xem sau. Nó không bao giờ thay thế vật liệu mà nó mô tả.

## Hãy để độc giả địa phương tập trung đưa ra những phát hiện hạn chế

Các phương pháp cục bộ riêng biệt kiểm tra các tính năng được xác định của nguồn. Một số nhìn vào cấu trúc của ngôn ngữ. Những người khác xác định các tuyên bố, các mối quan hệ có thể có, lập luận, thay đổi theo thời gian hoặc quan sát về trải nghiệm và giá trị của con người.

Những phương pháp này không phải là những chatbot nhỏ. Họ thực hiện các công việc hẹp dựa trên vật liệu đã lưu. Mỗi phát hiện xác định đoạn văn được kiểm tra, phương pháp được sử dụng, ngày tháng và các giới hạn đã biết. Một phương pháp có thể tìm thấy điều gì đó, không tìm thấy gì, từ chối trả lời hoặc thất bại. Nó không thể viết lại công việc của phương pháp khác.

## Hãy giữ lịch sử như lịch sử

Những phát hiện mới được thêm vào bên cạnh các sự kiện trước đó. Sửa chữa không xóa được lỗi lầm. Kết luận sau có thể trở thành hiện hành trong khi kết luận trước đó vẫn hiển thị với các bằng chứng và hoàn cảnh từng hỗ trợ nó.

Điều này cho phép công việc sau này trả lời không chỉ “điều gì được tin bây giờ?” mà còn “điều gì đã thay đổi, tại sao nó thay đổi và chi phí cho sự thay đổi đó là bao nhiêu?”

## Thu thập bằng chứng cho một yêu cầu

Trình tạo yêu cầu bắt đầu với mục đích của câu trả lời hoặc tài liệu. Nó xác định những gì người đọc cần, thu thập các nguồn và phát hiện liên quan đến những câu hỏi đó, đồng thời ghi lại những gì được đưa vào và bỏ đi.

Dịch vụ trò chuyện thương mại thường yêu cầu mô hình hoạt động từ bất kỳ văn bản nào phù hợp với yêu cầu hiện tại. Ở đây, lựa chọn bằng chứng là một bước được ghi lại bên ngoài mô hình. Mô hình không thể lặng lẽ quyết định rằng lịch sử bị thiếu không thành vấn đề.

## Sử dụng người mẫu làm người đóng góp

Một mô hình ngôn ngữ có thể hữu ích cho việc nghiên cứu, hiểu biết sâu rộng hoặc viết lách. Nó nhận được tài liệu đã chọn cho một công việc được khai báo.

Cài đặt hiện tại cũng sử dụng một cục bộ nhỏQwenmô hình cho một mục đích cụ thể: sau khi phân tích cục bộ tập trung đã kiểm tra một cuộc trò chuyện đã hoàn thành,Qwenbổ sung kiến ​​thức nền tảng thông thường giúp kết nối các phát hiện riêng biệt. Nó không trở thành ký ức, khôi phục những suy nghĩ ẩn giấu hoặc quyết định ý nghĩa của việc trao đổi.

Cho dù là cục bộ hay trực tuyến, phản hồi mẫu đều được lưu dưới dạng đóng góp theo ngày. Nó có thể được kiểm tra, sửa chữa, từ chối hoặc thay thế mà không cần thay đổi nguồn.

## Kiểm tra công việc bên ngoài nhà văn

Kiểm tra riêng biệt so sánh câu trả lời hoặc tài liệu đã hoàn thành với các nguồn của nó, nội dung bắt buộc và các giới hạn đã nêu. Phiên bản chính xác đã được thông qua sẽ được ghi lại.

Một mô hình ngôn ngữ không thể khẳng định đúng sự thật bằng cách viết một cách tự tin. Nó cũng không thể chấp nhận công việc của mình bằng cách nói rằng nó đã làm theo hướng dẫn.

## Sử dụng bất kỳ màn hình phù hợp

Bao gồmLibreChatfork cung cấp một màn hình đàm thoại để yêu cầu công việc và đọc kết quả. Nó không lưu trữ hồ sơ lâu dài, chỉ đạo mọi phần khác hoặc phê duyệt câu trả lời.

LibreChatcó thể thay màn hình khác.Qwencó thể được thay thế bằng một mô hình phù hợp khác. Một nhà cung cấp trực tuyến có thể được thay đổi hoặc bỏ qua. Lịch sử nguồn và tác phẩm được chấp nhận vẫn có thể sử dụng được vì không có phần nào trong số đó sở hữu chúng.

## Ranh giới xác định dự án

Các mô hình ngôn ngữ tạo ra những đóng góp tạm thời từ tài liệu mà chúng được hiển thị.Robot Brain bảo tồn nguồn, tổ chức công việc xung quanh nó, ghi lại những thay đổi, chuẩn bị những yêu cầu có giới hạn và kiểm tra những gì nhận được.

Đó là lý do tại sao đây không phải là một mô hình ngôn ngữ khác, một proxy mô hình hay một chatbot tốt hơn. Người mẫu có thể tham gia vào công việc. Công việc không phụ thuộc vào bất kỳ một mô hình nào.
