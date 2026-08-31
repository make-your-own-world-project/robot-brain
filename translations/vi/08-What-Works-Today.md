> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../08-What-Works-Today.md) | [Tất cả ngôn ngữ](../README.md)

# Việc triển khai hiện tại làm gì

![Ý tưởng, thử nghiệm, thất bại và khả năng đã được chứng minh vẫn được tách biệt rõ ràng.](../../illustrations/evidence-implementation-gates.png)

Robot Brain đang chạy phần mềm để bảo tồn và xây dựng lại ý nghĩa xung quanh tác phẩm được ghi lại. Đây không phải là một đề xuất cho chatbot và việc triển khai hiện tại của nó không phải là một mô hình ngôn ngữ.

## Khả năng triển khai hiện tại

Các lần chạy được ghi lại cho thấy phần mềm có thể:

- lưu giữ cuộc trò chuyện đã hoàn thành mà không thay thế nó bằng một bản tóm tắt
- giữ lời nói của người đó tách biệt khỏi câu trả lời mẫu và phần giải thích sau này
- tạo ra những phát hiện chi tiết về ngôn ngữ, ý nghĩa, lý luận, thời gian, trải nghiệm của con người và các giá trị
- kết nối từng phát hiện được giữ lại với phần cuộc trò chuyện đằng sau nó
- tiếp tục sửa chữa, bất đồng, công việc thất bại và các câu hỏi chưa được trả lời
- thêm tổng quan về kiến ​​thức chung địa phương mà không cần gọi mô hình trực tuyến ban đầu
- thu thập các khoản đóng góp được giữ lại cho việc tái thiết được yêu cầu
- ghi lại những gì đã được kiểm tra, từ chối, sửa chữa và chấp nhận
- thay thế màn hình hoặc mô hình ngôn ngữ tham gia mà không thay thế lịch sử đã lưu

Đây là những chức năng của phần mềm xung quanh các mô hình. Chúng không phải là những khả năng được yêu cầu choQwen,LibreChathoặc trợ lý trực tuyến.

## Điều gì đã xảy ra trong cột mốc cuộc trò chuyện đã hoàn thành

Cuộc trò chuyện đã thử nghiệm đã được lưu cùng với tin nhắn của người đó và các câu trả lời của mô hình trực tuyến theo thứ tự.

Các phương pháp tập trung vào địa phương sau đó tạo ra các hồ sơ riêng biệt về việc trao đổi. Công việc của họ bao gồm ngôn ngữ và ý nghĩa, lý luận, quan sát tâm lý, quan sát triết học, các mối quan hệ và sự thay đổi theo thời gian. Mỗi đóng góp được giữ lại vẫn gắn liền với nguồn nguyên liệu và phương pháp tạo ra nó.

Những phương pháp chi tiết đó cố tình không mang theo kiến ​​thức nền tảng rộng rãi của mô hình có mục đích chung. Một địa phương nhỏQwenmô hình, được phục vụ bởivLLM, đọc tài liệu đã chọn và thêm phần tổng quan về ngày tháng. Công việc của nó là cung cấp nền tảng thông thường kết nối những phát hiện riêng biệt và làm cho việc trao đổi trở nên dễ hiểu về tổng thể.

Qwenđã không khôi phục được những suy nghĩ ẩn giấu, lịch sử đào tạo hoặc trạng thái nội bộ riêng tư của mô hình ban đầu. Đóng góp hữu ích của mô hình ban đầu đã có trong các tin nhắn đã lưu của nó. Kiến thức nền tảng rộng được cung cấp bởi một mô hình địa phương có thể thay thế được vì kiến ​​thức đó không phải chỉ có ở nhà cung cấp ban đầu.

## “Hoàn thành” có nghĩa là gì đối với cột mốc này

Từ này đề cập đến danh sách đóng góp được duy trì cho lần chạy này. Mọi thông điệp nguồn và mọi đóng góp mà quá trình giữ lại để tái thiết đều có thể được tìm thấy và thu thập lại.

Điều đó không có nghĩa là một mô hình cung cấp một cách giải thích hoàn chỉnh. Thành tựu là các phần được chấp nhận sẽ được bảo tồn, phân tách theo nguồn và phương pháp, đồng thời có sẵn để tái tạo mà không cần chạy lại trao đổi trực tuyến ban đầu.

## Cách thức hỗ trợ yêu cầu bồi thường

Quá trình chạy ghi lại phần nào đã thực hiện, phần nào đã nhận được, phần nào được trả về, phần đóng góp nào bị từ chối và phần kiểm tra nào đã được thông qua. Việc xây dựng lại được đo lường dựa trên danh sách các bản ghi dự kiến ​​đã lưu của chính nó.

Kiểm thử thành phần được mô tả là kiểm thử thành phần. Một lần chạy được kết nối được mô tả là một lần chạy được kết nối. Công việc theo kế hoạch vẫn tách biệt với việc thực hiện hiện tại.

Công việc tiếp theo bao gồm thử nghiệm độc lập rộng hơn, hỗ trợ nhiều loại hồ sơ hơn, nhiều ngôn ngữ và văn hóa hơn, màn hình đánh giá rõ ràng hơn và đo lường tốt hơn thời gian mọi người dành để đọc và sửa kết quả.
