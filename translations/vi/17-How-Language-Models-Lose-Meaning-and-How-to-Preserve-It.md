> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md) | [Tất cả ngôn ngữ](../README.md)

# Bài học làm thay đổi thiết kế

![Bài học từ các phương pháp tiếp cận hiệu quả và thất bại vẫn có sẵn cho thiết kế tiếp theo.](../../illustrations/discoveries-engineering-lessons.png)

Thiết kế đã phát triển thông qua thử nghiệm, bao gồm cả những phương pháp tiếp cận thất bại. Các bài học dưới đây giải thích tại sao nó trông khác với dịch vụ trò chuyện thương mại.

## Nghiên cứu viết đã sử dụng tài liệu công cộng đã được xóa

Để nghiên cứu cách thức tổ chức các loại văn bản khác nhau, dự án đã kiểm tra các sách, bài phát biểu, bài viết của chính phủ Hoa Kỳ và các tờ báo lịch sử được chọn trong phạm vi công cộng. Một số ít các tiêu chuẩn công cho phép công chúng sử dụng một cách rõ ràng đã được kiểm tra riêng biệt.

Công việc đo lường và so sánh văn bản. Nó không đào tạo một mô hình ngôn ngữ chung mới. Các tài liệu công không bao gồm các bản sao của văn bản nguồn.

Mỗi hồ sơ nghiên cứu xác định nguồn công khai, lý do tại sao nó có thể được kiểm tra, phần nào được sử dụng và dấu vân tay kỹ thuật số ngắn xác nhận tài liệu chính xác. Một chỉ số lớn của Project Gutenberg được phát hành theoCC BY 4.0được kiểm tra chỉ để hiểu nội dung của nó; các sách được lập chỉ mục không được tải xuống hoặc đo lường thông qua chỉ mục đó.

## Các phương pháp riêng biệt bảo tồn những gì họ tìm thấy

Các phương pháp địa phương kiểm tra ngôn ngữ, ý nghĩa, mối quan hệ, lý luận, thời gian, kinh nghiệm của con người và các giá trị. Mỗi phương pháp lưu lại những phát hiện của riêng mình cùng với phần hội thoại đằng sau chúng.

Điều này giúp một phương pháp không nuốt chửng các phương pháp khác. Một phát hiện có thể được sửa chữa mà không cần viết lại nguồn hoặc mọi phân tích khác.

## Kiến thức tổng quát kết nối các mảnh ghép

Các phương pháp tập trung có thể tạo ra những phát hiện chính xác nhưng vẫn khó hiểu cùng nhau. Họ không chia sẻ kiến ​​thức nền tảng rộng rãi mà mô hình ngôn ngữ sử dụng khi đọc một đoạn hội thoại thông thường.

Một cái nhỏQwenmô hình đang chạy cục bộ sẽ thêm nền đó sau khi công việc tập trung hoàn tất. Nó giúp giải thích tình huống, mục tiêu của người tham gia, lý do đưa ra yêu cầu và sự kiện này dẫn đến sự kiện khác như thế nào.

Mô hình cục bộ không phục hồi được kiến ​​thức ẩn giấu của trợ lý ban đầu. Sự đóng góp của trợ lý đã có trong tin nhắn của nó.Qwencung cấp nền tảng chung đủ rộng để một mô hình phù hợp khác cung cấp.

Việc đọc nó được ghi ngày tháng và được giữ riêng. Mô hình sau này có thể thêm chế độ xem khác mà không cần viết lại chế độ xem trước đó.

## Đào tạo người mẫu giữ ảnh hưởng nhưng mất toàn bộ hồ sơ con người

Một mô hình ngôn ngữ học các mẫu hữu ích từ tài liệu do con người tạo ra. Nó không giữ cho mọi tác phẩm được nguyên vẹn với người tạo ra nó, mục đích, bằng chứng, sự bất đồng và lịch sử sau này kèm theo.

Mô hình có thể tái tạo từ ngữ hoặc sử dụng tốt một ý tưởng. Nó vẫn không thể xây dựng lại một cách đáng tin cậy lý do tại sao những từ đó tồn tại, tác giả của chúng muốn nói gì, tài khoản của ai bị thiếu hoặc điều gì sau đó đã sửa chữa tác phẩm.

Không có phần mềm nào có thể khôi phục lịch sử mà một mô hình không bao giờ lưu giữ. Thiết kế này có thể ngăn chặn sự mất mát tương tự xảy ra với hồ sơ của chính người đó.

## Xu hướng không phải là một thiết lập đơn giản

Những gì một mô hình có thể nhận ra phụ thuộc vào những gì mọi người đã tạo ra, những kho lưu trữ nào được bảo tồn, những ngôn ngữ nào được thu thập, cách dịch và gắn nhãn tài liệu, những gì người xây dựng khen thưởng và những quy tắc sản phẩm nào được thêm vào sau đó.

Không một điểm số nào có thể giải thích được tất cả những điều đó. Phản ứng thực tế là giữ cho các nguồn luôn rõ ràng, xác định mô hình và ngày tháng đằng sau một phát hiện, duy trì sự bất đồng và để lại thông tin còn thiếu được đánh dấu là thiếu.

## Lời nhắc lớn hơn vẫn chỉ là tạm thời

Việc cung cấp thêm văn bản cho mô hình có thể giúp ích cho một yêu cầu. Nó không tạo ra bộ nhớ đáng tin cậy. Tài liệu đã chọn có thể được rút ngắn trong cuộc trò chuyện và một mô hình khác có thể diễn giải nó theo cách khác sau đó.

Bản ghi đã lưu phải tồn tại trước và sau yêu cầu.

## Những từ tương tự không chứng minh được mối quan hệ

Tìm kiếm có thể tìm thấy kết quả phù hợp có thể. Nó không thể chứng minh rằng một đoạn văn đã gây ra, sửa chữa, mâu thuẫn hoặc tiếp tục một đoạn văn khác.

Những mối quan hệ đó cần có bằng chứng riêng.

## “Không trả lời” có thể là câu trả lời đúng

“Không tìm thấy”, “không áp dụng”, “không xác định” và “sai” có nghĩa khác nhau. Mọi người đọc tập trung và đóng góp theo mô hình ngôn ngữ phải duy trì những khác biệt đó thay vì tạo ra một câu trả lời có khả năng chỉ để tiếp tục cuộc trò chuyện.

## Công việc bị từ chối vẫn dạy được điều gì đó

Một câu trả lời không được hỗ trợ sẽ không được đưa vào kiến ​​thức được chấp nhận. Câu trả lời và lý do từ chối vẫn có thể ngăn chặn việc mua và kiểm tra lại lỗi tương tự.

## Theo dõi xem ai đã nói gì

Những lời nói của con người, những câu trích dẫn, những câu trả lời mẫu, những phát hiện địa phương và những đánh giá sau này không thể kết hợp với nhau mà không làm thay đổi ý nghĩa của chúng.

Mọi đóng góp đều được gắn nhãn với nguồn của nó.

## Lập kế hoạch, viết và kiểm tra là những công việc khác nhau

Người xây dựng yêu cầu có thể chọn bằng chứng phù hợp trong khi mô hình ngôn ngữ vẫn viết tệ. Một mô hình có thể viết rõ ràng từ những bằng chứng sai. Nó cũng có thể đi theo bằng chứng nhưng vẫn khiến người đọc thất vọng vì tạo ra quá nhiều văn bản.

Giữ lựa chọn, viết và kiểm tra riêng biệt sẽ làm cho lỗi có thể nhìn thấy được. Phần bị lỗi có thể được thay thế mà không cần phải xây dựng lại mọi thứ.

## Một tài liệu đầy đủ cần một kế hoạch

Các phần viết độc lập tạo ra sự lặp lại, thay đổi thuật ngữ và các kết nối không được hỗ trợ. Một tài liệu phải được lập kế hoạch và kiểm tra dưới dạng một phần ngay cả khi có nhiều công cụ giúp tạo ra nó.

## Đọc và sửa là chi phí thực tế

Việc đọc phần bổ sung, tìm kiếm những câu trả lời bị chôn vùi và sửa những lỗi lặp đi lặp lại sẽ tiêu tốn thời gian và sức lực của một người. Chi phí đó thuộc về bất kỳ tài khoản trung thực nào về kết quả.

## Sự giúp đỡ bên ngoài không cần toàn bộ lịch sử

Mô hình ngôn ngữ trực tuyến có thể nhận đủ bằng chứng cho một nhiệm vụ mà không cần nhận các hồ sơ không liên quan, lịch sử riêng tư hoặc các công cụ chuẩn bị cho các yêu cầu trong tương lai.

Phản hồi hữu ích sẽ quay trở lại. Bản ghi đầy đủ vẫn ở nơi người đó kiểm soát nó.
