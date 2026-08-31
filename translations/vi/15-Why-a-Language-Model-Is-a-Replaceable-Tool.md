> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Tất cả ngôn ngữ](../README.md)

# Sử dụng mô hình ngôn ngữ cho công việc chứ không phải làm bộ nhớ

![Các công cụ, tệp được đào tạo và bộ sưu tập nguồn lưu giữ các bản ghi riêng biệt về nguồn gốc và điều khoản của chúng.](../../illustrations/tool-model-source-index.png)

Robot Brain không phải là mô hình ngôn ngữ có thêm bộ nhớ. Chính phần mềm lưu trữ, phân tích, lắp ráp và kiểm tra hồ sơ sẽ quyết định khi nào một mô hình ngôn ngữ sẽ hữu ích và nó có thể thực hiện công việc hạn chế nào.

Mô hình mạnh mẽ nhất hiện có không phải lúc nào cũng là lựa chọn tốt nhất cho công việc đó.

Mô hình ngôn ngữ trả phí có thể phù hợp với những nghiên cứu hoặc bài viết khó. Một mô hình cục bộ nhỏ có thể đủ để giải thích cơ bản. Tìm kiếm có thể là đủ để tìm thấy một đoạn văn. Một quy trình cố định có thể an toàn hơn khi câu trả lời phải tuân theo một quy tắc chính xác. Đôi khi câu trả lời hay nhất là câu trả lời đã được kiểm tra và lưu lại.

Người xây dựng yêu cầu đưa ra lựa chọn đó dựa trên nhu cầu của công việc. Nó có thể sử dụng một mô hình, kết hợp một số phương pháp giới hạn, sử dụng lại công việc đã được kiểm tra hoặc không thực hiện lệnh gọi mô hình nào cả. Đó là lý do tại sao đây không phải là proxy chỉ chuyển tiếp yêu cầu đến dịch vụ khác.

## Mô hình trực tuyến trả phí

Các dịch vụ mô hình ngôn ngữ thương mại đã giúp xây dựng dự án này. Họ hỗ trợ nghiên cứu, viết mã, viết và đánh giá.

Họ cũng đánh mất những hướng dẫn trước đó, rút ​​ngắn cuộc trò chuyện, đoán nguyên nhân, chôn những câu trả lời ngắn vào phần phụ và báo cáo công việc đã hoàn thành trước khi kiểm tra. Việc sửa chữa những thất bại đó cần nhiều trợ cấp được trả hơn và nhiều thời gian của con người hơn.

Giới hạn sâu hơn của họ không phải là một lời nhắc tồi. Một mô hình được đào tạo không thể xây dựng lại toàn bộ lịch sử công việc của con người đã dạy nó. Nó giữ nguyên các khuôn mẫu trong khi mất đi các liên kết đáng tin cậy đến mọi tác giả, mục đích, đối tượng, tranh chấp, đính chính và quan điểm còn thiếu.

Kiến thức rộng rãi đó vẫn hữu ích. Đơn giản là nó không nên trở thành nơi duy nhất tồn tại lịch sử của ai đó.

Đối với một yêu cầu trực tuyến,Robot Brain ghi lại mô hình nào đã được sử dụng, mô hình nào đã nhận được, mô hình nào được trả về, chi phí dịch vụ là bao nhiêu, hoạt động kiểm tra nào đã được thực hiện và liệu kết quả có được lưu giữ hay không. Nền tảng không được hỗ trợ vẫn là gợi ý của mô hình chứ không phải là dữ kiện có nguồn gốc.

## Mô hình địa phương không được đào tạo trên người

Quá trình cài đặt hiện tại chạy một lượng nhỏQwenmô hình ngôn ngữ thông quavLLMtrên phần cứng cục bộ.Qwenlà một người đóng góp có thể thay thế được, chứ không phải bản thân dự án.

Nó không học bằng cách đào tạo về các cuộc trò chuyện, công việc hoặc cuộc sống của con người. Việc đào tạo sẽ trộn lịch sử đó vào một mô hình và làm suy yếu con đường quay trở lại những từ ngữ và sự kiện ban đầu.

Thay vì,Qwennhận tài liệu đã chọn cho một công việc sau khi cuộc trò chuyện kết thúc. Các phương pháp địa phương khác đã xem xét ngôn ngữ, các tuyên bố, các mối quan hệ, lập luận, thời gian, kinh nghiệm của con người và các giá trị trong trao đổi.Qwenthêm nền tảng rộng mà các phương pháp đó không chia sẻ. Điều này giúp giải thích điều gì đã xảy ra và tại sao dễ dàng hơn.

Qwenkhông tiết lộ những suy nghĩ ẩn giấu, quá trình đào tạo hoặc lý luận riêng tư của trợ lý trực tuyến. Đóng góp hữu ích của trợ lý trực tuyến đã có trong cuộc trò chuyện đã lưu. Kiến thức nền tảng chung không phải chỉ có ở trợ lý đó mà có thể giúp kết nối các phần đã ghi lại bằng một mô hình phù hợp khác.

cácQwenviệc đọc được lưu cùng với tên model và ngày tháng. Nó vẫn tách biệt khỏi cuộc trò chuyện và có thể được sửa hoặc thay thế sau này. Yêu cầu không bao giờ phải rời khỏi phần cứng cục bộ.

## Tìm kiếm không phải là một lời giải thích

Tìm kiếm có thể tìm thấy những đoạn văn có từ hoặc chủ đề liên quan. Nó không thể quyết định tại sao một sự kiện lại quan trọng, liệu một hành động có gây ra một hành động khác hay không hoặc ý nghĩa của ai đó.

Những kết luận đó cần bằng chứng, lịch sử và chỗ để sửa chữa.

## Chi phí bao gồm thời gian của người đó

Giá cả và tốc độ không phải là chi phí duy nhất. Một câu trả lời rẻ tiền sẽ trở nên đắt đỏ khi ai đó dành hàng giờ để tìm ra lỗi, giải thích lại lịch sử và sửa chữa kết quả.

Do đó, người tạo yêu cầu sẽ xem xét phí dịch vụ, chờ đợi, thử lại, sử dụng năng lượng và kiểm tra của con người. Một mô hình nhỏ hơn, một phương pháp cục bộ cố định hoặc một kết quả đã lưu có thể tạo ra nhiều giá trị hơn khi công việc của nó dễ kiểm tra hơn.

## Nguồn vẫn có thể xác định được

Các hồ sơ gốc, văn bản sao chép, phản hồi mẫu, nghiên cứu công khai, trích dẫn và đánh giá sau này vẫn là những thứ khác nhau.

Khi được biết và được phép, hồ sơ sẽ lưu giữ người sáng tạo, mục đích, đối tượng, ngày tháng, ngôn ngữ, bằng chứng, sự bất đồng, quyền và những chỉnh sửa sau này. Bản thân tính khả dụng và tín dụng công khai không cấp phép phân phối lại tài liệu được bảo vệ.

Kho lưu trữ này bao gồm tài liệu công khai và hình minh họa do dự án tạo ra. Nó loại bỏ các hồ sơ riêng tư, mật khẩu, chi tiết truy cập, bí mật của nhà cung cấp và tài liệu bên ngoài chưa được xóa để phát hành.
