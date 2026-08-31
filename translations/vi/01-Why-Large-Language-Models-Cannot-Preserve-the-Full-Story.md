> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Tất cả ngôn ngữ](../README.md)

# Tại sao các mô hình ngôn ngữ lớn không thể lưu giữ toàn bộ câu chuyện

![Các phần đã lưu sẽ mất giá trị khi nguồn, mối quan hệ và lịch sử của chúng bị tách rời.](../../illustrations/ordinary-storage-loses-context.png)

Các mô hình ngôn ngữ trả phí mạnh nhất được sử dụng khi xây dựng dự án này có thể mang lại hiệu quả ấn tượng. Họ có thể viết, nghiên cứu, giải thích và giúp giải quyết những vấn đề khó khăn. Họ vẫn chưa thể lưu giữ được toàn bộ lịch sử đằng sau một dự án lâu dài.

Câu trả lời sau có thể ghi nhớ kết luận nhưng sẽ mất đi những lần thử, sửa chữa và bằng chứng thất bại dẫn đến kết luận đó. Các hướng dẫn trước đó có thể biến mất khi cuộc trò chuyện trở nên quá dài. Người mẫu sẽ tiếp tục viết như thể không có gì quan trọng bị mất.

Đó là một vấn đề nghiêm trọng khi lịch sử bị thiếu thể hiện thời gian, kiến ​​thức hoặc kinh nghiệm của ai đó.

## Tập tin là không đủ

Một thư mục có thể chứa mọi ghi chú, cuộc trò chuyện, hình ảnh và nhiệm vụ trong khi vẫn làm mất đi câu chuyện kết nối chúng.

Nhiều tháng sau, một người có thể cần biết:

- điều gì đã bắt đầu công việc
- ý tưởng nào đã được xem xét
- tại sao một lần thử lại thất bại
- bằng chứng nào đã thay đổi kế hoạch
- kết luận nào là hiện tại
- điều gì vẫn chưa được biết
- tại sao một ghi chú cũ lại quan trọng bây giờ

Tìm kiếm có thể tìm thấy một tập tin có từ tương tự. Nó không thể trả lời những câu hỏi đó một cách đáng tin cậy. Việc gửi một đống tệp lớn hơn tới một mô hình ngôn ngữ cũng không tạo ra bộ nhớ vĩnh viễn. Dịch vụ sẽ xem những gì đã được chọn cho yêu cầu đó. Khi yêu cầu kết thúc, các kết nối hữu ích có thể lại biến mất.

## Tập cũng mất cài đặt gốc

Các mô hình ngôn ngữ học các mẫu từ bộ sưu tập khổng lồ công việc của con người. Đó là lý do tại sao chúng hữu ích. Đó cũng là lý do tại sao chúng không thể hoạt động như một kho lưu trữ trung thành về mọi thứ đã hình thành nên chúng.

Ý tưởng từ một cuốn sách, bài viết, cuộc trò chuyện, bản dịch hoặc cộng đồng trở nên trộn lẫn với ý tưởng từ nhiều ý tưởng khác. Mô hình này không giữ nguyên vẹn từng tác phẩm với tác giả, mục đích, đối tượng, bằng chứng, sự bất đồng và những chỉnh sửa sau này.

Tác phẩm gốc có thể vẫn tồn tại ở một nơi khác. Nhà cung cấp cũng có thể giữ các bản sao riêng biệt. Sự mất mát được mô tả ở đây xảy ra bên trong mô hình đã được đào tạo: nó giữ được ảnh hưởng hữu ích từ tác phẩm nhưng không thể xây dựng lại ý nghĩa nhân văn hoàn chỉnh xung quanh nó.

Việc lặp lại một câu không có nghĩa là giữ nguyên ý nghĩa đó. Một mô hình có thể tái tạo các từ quen thuộc mà không biết tại sao chúng được viết, chúng mô tả tình huống nào, thiếu tầm nhìn hoặc điều gì đã xảy ra sau đó.

## Lịch sử còn thiếu cũng che giấu sự thiên vị

Không có mô hình ngôn ngữ nào được học từ toàn thế giới.

Kiến thức của nó phản ánh những gì đã được viết ra, bảo tồn, thu thập, dịch thuật, cấp phép, dán nhãn và chọn lọc. Nó cũng phản ánh những gì còn thiếu. Một số ngôn ngữ và cộng đồng có nhiều tài liệu được xuất bản hơn những ngôn ngữ khác. Các kho lưu trữ bảo tồn quan điểm của các tổ chức quyền lực thường xuyên hơn là kiến ​​thức cá nhân, địa phương hoặc truyền miệng.

Những người xây dựng mô hình đưa ra nhiều lựa chọn hơn về những gì cần loại bỏ, khen thưởng, ngăn cản hoặc coi đó là một câu trả lời hay. Quy tắc sản phẩm thêm một lớp khác. Một câu trả lời hoàn chỉnh có thể mang theo tất cả những ảnh hưởng đó mà không chỉ ra cái nào ảnh hưởng đến một câu cụ thể.

Một trích dẫn được tìm thấy trong một yêu cầu mới không tiết lộ toàn bộ lịch sử này. Nó hiển thị nguồn được sử dụng hoặc đặt tên cho yêu cầu đó, không phải mọi thứ đã dạy mô hình cách diễn giải chủ đề.

## Thay vào đó dự án này giữ lại những gì

Robot Brain giữ nguồn trước khi yêu cầu bất kỳ mô hình nào trợ giúp giải thích nó. Nguồn không thay đổi khi thêm phần tóm tắt, chỉnh sửa hoặc diễn giải mới.

Tác phẩm sau này được lưu bên cạnh với ngày tháng và liên kết quay lại đoạn văn liên quan. Một nỗ lực thất bại có thể vẫn hiển thị. Một kết luận đúng có thể chỉ ra bằng chứng làm thay đổi nó. Nếu không xác định được lý do thay đổi thì hồ sơ sẽ ghi như vậy.

Khi ai đó cần câu trả lời hoặc tài liệu, trình tạo yêu cầu sẽ thu thập phần lịch sử cần thiết cho công việc. Kết quả có thể ngắn hơn bản ghi đầy đủ mà không giả vờ thay thế nó.

Một mô hình ngôn ngữ có thể giúp đạt được kết quả đó. Nó không thể xóa nguồn, viết lại quá khứ hoặc biến một dự đoán không được hỗ trợ trở thành một phần của bản ghi được chấp nhận.

## Bài kiểm tra thực tế

Một kết quả hữu ích sẽ cho phép người đọc trả lời bốn câu hỏi:

1. Chuyện gì đã xảy ra thế?
2. Bằng chứng nào hỗ trợ tài khoản này?
3. Điều gì đã thay đổi, thất bại hoặc vẫn còn gây tranh cãi?
4. Điều gì vẫn chưa được biết?

Nếu hồ sơ không thể trả lời một trong những câu hỏi đó, ngôn ngữ trau chuốt sẽ không che giấu được khoảng trống.
