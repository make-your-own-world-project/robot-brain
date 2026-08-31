> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Giữ hồ sơ. Thay thế mô hình.

![Hồ sơ của một người vẫn ở một nơi trong khi các bộ phận làm việc riêng biệt xử lý một số công việc hạn chế.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain is software for preserving the history and meaning behind long-running human work. Nó không phải là một mô hình ngôn ngữ, một chatbot hay một dịch vụ chuyển tiếp mọi câu hỏi đến một mô hình.

Các mô hình ngôn ngữ lớn có thể nghiên cứu, viết, giải thích và giúp giải quyết các vấn đề khó khăn. Các dịch vụ trả phí được xây dựng xung quanh chúng vẫn chỉ là không gian làm việc tạm thời. Họ có thể rút ngắn một cuộc trò chuyện dài, mất đi những hướng dẫn trước đó, tách kết luận khỏi bằng chứng của họ và tiếp tục viết như thể lịch sử còn thiếu vẫn còn hiện diện. Sau đó, một người sẽ dành nhiều thời gian hơn và trả phí để xây dựng lại bối cảnh đã được cung cấp.

Phần mềm này thay đổi nơi giá trị lâu dài tồn tại. Các cuộc trò chuyện, tài liệu, quyết định, nỗ lực thất bại, sửa chữa và các câu hỏi chưa được trả lời của người đó vẫn được lưu trong hồ sơ mà người đó kiểm soát. Các chương trình địa phương có thể kiểm tra những hồ sơ đó. Một mô hình ngôn ngữ có thể trợ giúp cho một công việc đã chọn, nhưng sự đóng góp của nó sẽ được ghi vào hồ sơ dưới dạng tác phẩm có ngày tháng, có thể xem xét được. Mô hình sau đó có thể được thay thế mà không cần mang theo lịch sử.

[Đọc tài liệu này bằng ngôn ngữ khác.](../README.md)

## Sự khác biệt trong một lần xem

| Dịch vụ mô hình ngôn ngữ thương mại | Robot Brain |
|---|---|
| Tạo ra câu trả lời từ tài liệu hiện đang ở chế độ xem làm việc của nó. | Giữ nguồn hoàn chỉnh và lịch sử xung quanh nó. |
| Có thể rút ngắn hoặc mất đi cuộc trò chuyện trước đó khi công việc phát triển. | Lưu các cuộc hội thoại bên ngoài mọi mô hình để có thể sử dụng lại. |
| Tổng hợp kiến ​​thức đã học được từ nhiều nguồn mà không có đường dẫn đầy đủ về từng nguồn và hoàn cảnh của nó. | Giữ từng nguồn đã biết, phát hiện sau này, chỉnh sửa và không đồng ý dưới dạng một bản ghi riêng. |
| Có thể viết, tìm kiếm, lập kế hoạch và đánh giá câu trả lời của chính mình trong một lần trao đổi. | Cho phép lưu, tìm kiếm, phân tích, viết, kiểm tra và phê duyệt các phần riêng biệt với thẩm quyền hạn chế. |
| Kiểm soát kiểu máy, quy tắc dịch vụ, giới hạn sử dụng và thay đổi sản phẩm. | Để lại hồ sơ lâu dài dưới sự kiểm soát của người đó. |
| Được trả tiền cho những nỗ lực thất bại và những trao đổi khắc phục cũng như công việc hữu ích. | Giữ lại những sai sót và sửa chữa để những bài học của họ không phải mua lại. |

Robot Brain có thể gọi một mô hình ngôn ngữ địa phương hoặc trực tuyến. Điều đó không biến nó thành một proxy mẫu. Nó có thể bảo tồn, tìm kiếm, so sánh, sắp xếp và xây dựng lại công việc trước đó mà không cần gọi mô hình đã tham gia vào cuộc trò chuyện ban đầu. Khi một mô hình hữu ích, yêu cầu là một bước trong quy trình lớn hơn tồn tại độc lập với mô hình đó.

## Tại sao cái này được xây dựng

Các mô hình đa năng được trả lương cao nhất hiện có trong quá trình phát triển là những người giám sát có năng lực nhưng không đáng tin cậy trong thời gian dài làm việc.

Các lỗi được ghi lại bao gồm các hướng dẫn bị mất, bằng chứng bị thiếu, các kết nối được phát minh, các tuyên bố hoàn thành sớm, các thay đổi không mong muốn và hư hỏng các tệp đang hoạt động. Việc sửa chữa những thất bại đó đòi hỏi nhiều yêu cầu hơn, nhiều thử nghiệm hơn, nhiều trợ cấp được trả hơn cũng như nhiều thời gian và sức lực của người đó hơn. Các dịch vụ không tự động trả lại mức sử dụng đã chi cho công việc không sử dụng được hoặc những trao đổi cần thiết để sửa chữa nó.

Vấn đề lớn hơn bất kỳ câu trả lời tồi nào. Một trình tạo văn bản tạm thời được yêu cầu đóng vai trò là bộ nhớ, nhà sử học, nhà nghiên cứu, nhà văn, người kiểm tra và người đánh giá cuối cùng. Việc thay đổi mô hình không làm thay đổi sự sắp xếp đó.

Robot Brain được xây dựng dựa trên một sự sắp xếp khác: giữ hồ sơ con người trước tiên, để một số bộ phận có thể thay thế đóng góp vào đó và yêu cầu bằng chứng bên ngoài mô hình tạo ra trước khi công việc quan trọng được chấp nhận.

## Những gì một người mẫu được đào tạo không thể giữ được

Một mô hình ngôn ngữ lớn học các mẫu từ bộ sưu tập khổng lồ công việc của con người. Những mẫu đó làm cho mô hình trở nên hữu ích, nhưng mô hình không phải là một thư viện gồm các tác phẩm hoàn chỉnh đã định hình nên nó.

Bên trong mô hình, ảnh hưởng từ sách, bài báo, cuộc trò chuyện, bản dịch, cộng đồng, nhãn hiệu và phản hồi của con người được kết hợp với nhau. Mô hình thường không thể hiển thị nguồn nào đã định hình một câu cụ thể. Nó không thể khôi phục lại mục đích, độc giả, bằng chứng, sự bất đồng, sự sửa chữa sau này hoặc quan điểm còn thiếu của mọi tác giả.

Đó là sự mất đi ý nghĩa ngay cả khi tác phẩm gốc vẫn còn tồn tại ở nơi khác. Mô hình vẫn giữ lại một số tính hữu ích của công việc trong khi loại bỏ đường dẫn đáng tin cậy quay trở lại cài đặt của con người.

Vấn đề tương tự xuất hiện trong quá trình sử dụng thông thường. Câu trả lời cuối cùng có thể tồn tại sau khi cuộc trò chuyện mang lại ý nghĩa cho nó đã được rút ngắn lại. Kết luận vẫn còn, nhưng những nỗ lực thất bại, sự không chắc chắn và lý do đằng sau nó sẽ biến mất khỏi quan điểm hoạt động của mô hình.

Dự án này không giải quyết vấn đề đó bằng cách đào tạo một mô hình khác về cuộc sống của một con người. Lịch sử cá nhân vẫn có thể đọc và theo dõi được thay vì bị trộn vào một mô hình được đào tạo khác. Mô hình làm việc với các bản ghi đã chọn; chúng không trở thành kỷ lục.

## Mỗi phần làm gì

Phần mềm hoạt động tách biệt các công việc mà dịch vụ trò chuyện thường thực hiện giống như một hoạt động:

1. **Trình lưu nguồn lưu lại những gì đã xảy ra.** Nó lưu giữ cuộc trò chuyện, tài liệu, hình ảnh hoặc tài liệu khác mà không thay thế bằng bản tóm tắt.
2. **Bản sao có thể tìm kiếm giúp tìm nguồn dễ dàng hơn.** Văn bản, mô tả và chỉ mục được sao chép sẽ quay trở lại nguồn không thay đổi và có thể được xây dựng lại.
3. **Độc giả địa phương tập trung kiểm tra các đặc điểm cụ thể.** Các phương pháp riêng biệt xem xét ngôn ngữ, câu nói, mối quan hệ, lý luận, thời gian, trải nghiệm con người và giá trị. Mỗi báo cáo chỉ báo cáo những phát hiện của riêng mình và những đoạn văn đằng sau chúng.
4. **Bản ghi lịch sử giúp hiển thị các thay đổi.** Những phát hiện mới, chỉnh sửa, bất đồng, nỗ lực thất bại và câu hỏi mở được thêm vào mà không cần viết lại các sự kiện trước đó.
5. **Trình tạo yêu cầu thu thập những gì một công việc cần.** Nó chọn các nguồn và phát hiện có liên quan, đồng thời ghi lại những gì được đưa vào hoặc bị bỏ qua.
6. **Mô hình ngôn ngữ có thể thêm trợ giúp hạn chế.** Mô hình địa phương có thể cung cấp kiến ​​thức tổng quát. Một mô hình trực tuyến có thể hỗ trợ những nghiên cứu hoặc viết bài khó. Cả hai phản hồi đều vẫn là đóng góp có niên đại và có thể được kiểm tra, từ chối hoặc thay thế.
7. **Kiểm tra riêng biệt so sánh kết quả với yêu cầu và bằng chứng.** Mô hình đã viết câu trả lời không thể tuyên bố công việc của chính nó được chấp nhận.
8. **Một màn hình cho phép một người sử dụng phần mềm.** Bao gồmLibreChatfork là một trong những màn hình như vậy. Việc thay thế nó không thay thế các bản ghi hoặc các bộ phận làm việc khác.

Không có bộ phận nào được trình bày như một trợ lý toàn năng. Công việc hạn chế của họ là những gì làm cho mỗi bộ phận có thể thay thế được.

## Làm cho cuộc trò chuyện đã hoàn tất trở nên hữu ích trở lại

Một cuộc trò chuyện đã hoàn thành bao gồm yêu cầu của người đó, câu trả lời thực tế của mô hình ngôn ngữ, công việc đã thực hiện, lỗi, bản sửa lỗi và điểm kết thúc quá trình trao đổi. Những thông báo đó bảo tồn những gì mô hình ban đầu đã đóng góp mà không yêu cầu mô hình đó phải giải thích sau này.

Độc giả địa phương tập trung kiểm tra trao đổi đã lưu từ nhiều góc độ. Họ có thể tìm thấy các mô hình và mối quan hệ chi tiết mà không cần dựa vào kiến ​​thức rộng rãi về thế giới. Những phát hiện riêng biệt của họ vẫn được kết nối với các phần chính xác của cuộc trò chuyện.

Những phát hiện đó có thể vẫn cần có kiến ​​thức nền tảng thông thường trước khi chúng hình thành nên một giải thích rõ ràng. Đối với bước giới hạn đó, một bước nhỏQwenmô hình chạy cục bộ thông quavLLM. Nó bổ sung một cái nhìn tổng quan về ngày tháng giúp kết nối các phát hiện chi tiết và giải thích những gì cuộc trao đổi đã đạt được.

Qwenkhông khôi phục những suy nghĩ ẩn giấu hoặc lịch sử đào tạo của mô hình trực tuyến. Nó cung cấp kiến ​​thức nền tảng rộng không chỉ có ở mô hình ban đầu. Sự đóng góp hữu ích của mô hình ban đầu đã được bảo tồn bằng những từ ngữ mà nó tạo ra.

cácQwentổng quan được lưu trữ bên cạnh nguồn và những phát hiện trước đó. Nó có thể được sửa chữa hoặc thay thế. Cuộc trò chuyện ban đầu và phân tích địa phương chi tiết vẫn không thay đổi.

## Những gì đang làm việc bây giờ

Việc triển khai hiện tại có thể bảo tồn một cuộc hội thoại đã hoàn thành, kiểm tra nó thông qua các phương pháp cục bộ riêng biệt, thêm phần đọc kiến ​​thức chung cục bộ và tập hợp mọi đóng góp được giữ lại vào một bản ghi có thể được xây dựng lại sau này.

Nó cũng có thể chuẩn bị một yêu cầu giới hạn cho một mô hình trực tuyến khi sự trợ giúp từ bên ngoài hữu ích. Dịch vụ đó chỉ nhận được tài liệu đã chọn. Câu trả lời của nó quay trở lại hồ sơ địa phương, nơi các cuộc kiểm tra và sự chấp thuận của con người-không phải mô hình-quyết định những gì được lưu giữ.

Đây là thành tựu trọng tâm: công việc từng phụ thuộc vào một cuộc trò chuyện tạm thời có thể vẫn hữu ích sau khi màn hình trò chuyện, mô hình và nhà cung cấp không còn nữa.

## Đọc lời giải thích đầy đủ

- [Tại sao các mô hình ngôn ngữ lớn không thể lưu giữ toàn bộ câu chuyện](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Mỗi bộ phận làm gì-và không có mô hình nào kiểm soát được những gì](02-A-Lasting-Record-Outside-the-Model.md)
- [Giữ lại sự sửa chữa mà không xóa lỗi](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Thực hiện theo một yêu cầu trở lại bằng chứng](04-How-Every-Claim-Can-Be-Checked.md)
- [Xây dựng tài liệu trước khi viết văn xuôi](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Giải thích cùng một sự thật cho những độc giả khác nhau](06-One-Meaning-Different-Readers.md)
- [Giữ lịch sử riêng tư dưới sự kiểm soát của người đó](07-Privacy-and-Control-Stay-With-People.md)
- [Việc triển khai hiện tại làm gì](08-What-Works-Today.md)
- [Tại sao thiết kế lại rút ra từ nhiều lĩnh vực](09-How-Research-Strengthens-the-System.md)
- [Trợ giúp mà không cần bàn giao hồ sơ cá nhân](11-Contribute-Without-Giving-Up-Control.md)
- [Các từ được sử dụng xuyên suốt các tài liệu này](12-A-Short-Guide-to-Key-Terms.md)
- [Thực hiện theo một yêu cầu thông qua các bộ phận làm việc](13-The-Parts-Running-Today.md)
- [Sử dụng mô hình ngôn ngữ cho công việc chứ không phải làm bộ nhớ](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Những sai sót được quan sát thấy trong các dịch vụ mô hình ngôn ngữ phải trả phí-và các biện pháp bảo vệ mà chúng mang lại](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Bài học làm thay đổi thiết kế](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Ghi chú sử dụng công cộng, tín dụng và quyền riêng tư](18-Use-Attribution-and-Limits.md)
- [Làm thế nào một cuộc trò chuyện hoàn thành trở thành kiến ​​thức lâu dài](19-What-the-System-Accomplishes.md)
- [Điều gì xảy ra tiếp theo](20-Where-the-System-Goes-Next.md)

## Tín dụng, nguồn và quyền

- [Điều gì đã giúp hình thành công việc này](10-What-Helped-Shape-This-Work.md)
- [Nghiên cứu đằng sau thiết kế](14-Sources-Behind-the-Design.md)
- [Nguồn, giấy phép và kiểm tra phát hành công khai](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Giấy phép

Văn bản gốc, sơ đồ và hình minh họa của dự án được cung cấp theo giấy phép của tổ chức.[Giấy phép quốc tế Creative Commons Ghi công 4.0](../../LICENSE.md), trừ khi tài liệu nêu các điều khoản khác. Tài liệu do người khác tạo ra có các quyền và điều khoản riêng.

## Độc lập và riêng tư

Đây là một dự án cá nhân độc lập được phát triển dựa trên thời gian, thiết bị, tài khoản và dịch vụ trả phí cá nhân. Không có nhà tuyển dụng nào tham gia vào nó. Việc đề cập đến bất kỳ cá nhân, chủ lao động, tổ chức, nhà cung cấp mô hình, nhóm nghiên cứu, quy tắc chung hoặc dự án bên ngoài nào không ngụ ý tham gia, phê duyệt, hợp tác hoặc chứng thực.

Bản phát hành công khai không bao gồm hồ sơ riêng tư, chi tiết nhận dạng, mật khẩu, thông tin kết nối riêng tư, thông tin về chủ lao động và hướng dẫn tiếp cận các dịch vụ riêng tư. Mô tả về các lỗi mô hình được giới hạn ở hành vi được ghi lại và ảnh hưởng của nó; họ không yêu cầu nguyên nhân hoặc động cơ không được tiết lộ. Các tài liệu này không phải là lời khuyên chuyên môn hay lời hứa hẹn về kết quả.

![Con đường từ bộ nhớ do nhà cung cấp kiểm soát tới các hồ sơ được lưu giữ ở những người mà họ quan tâm.](../../illustrations/open-door-human-future.png)
