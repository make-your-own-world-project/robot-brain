> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../14-Sources-Behind-the-Design.md) | [Tất cả ngôn ngữ](../README.md)

# Nghiên cứu đằng sau thiết kế

![Các truyền thống nghiên cứu khác nhau đóng góp những phương pháp hạn chế trong khi vẫn giữ được lịch sử của riêng mình.](../../illustrations/academic-framework-lineages.png)

Trang này dành cho những độc giả muốn theo dõi nghiên cứu. Lời giải thích chính không yêu cầu nó.

Danh sách này bao gồm các ý tưởng và công cụ đã được sử dụng, thử nghiệm, so sánh, bác bỏ hoặc đơn giản là nghiên cứu. Những mối quan hệ đó không giống nhau. Việc liệt kê một nguồn không có nghĩa là các tác giả của nó đã tham gia hoặc xác nhận dự án.

## Giữ nguồn và thay đổi theo thời gian

- Nghiên cứu về lịch sử nguồn và sự thay đổi thông tin đã định hình cách các hồ sơ lưu giữ tài liệu đến từ đâu, khi nào nó được áp dụng và những gì sau này sẽ thay thế nó.
- [than chì](https://github.com/getzep/graphiti)đã được xem xét như một cách tiếp cận để ghi lại các kết nối thay đổi theo thời gian.
- Các phương pháp ghi lại thay đổi đã được thiết lập đã đưa ra quy tắc rằng bản tóm tắt hiện tại không được thay thế nguồn đằng sau nó.

Những ý tưởng này giúp duy trì đường đi mà câu trả lời mẫu mới hoặc bản tóm tắt viết lại sẽ ẩn đi.

## Tách biệt các yêu cầu, hỗ trợ và không đồng ý

- [Lý thuyết cấu trúc tu từ của Mann và Thompson](https://aclanthology.org/J88-2003/)cung cấp tên cho mối quan hệ giữa các phần của tài liệu, chẳng hạn như điểm chính và phần giải thích về nó.
- [Sơ đồ lập luận của Walton, Reed và Macagno](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2)cung cấp các câu hỏi tập trung để kiểm tra sự hỗ trợ và kết luận.
- [oAMF](https://github.com/arg-tech/oAMF)và xAIF đã cung cấp các phương pháp tiếp cận để ghi lại các xác nhận quyền sở hữu và các kết nối của chúng.
- [PropBank](https://aclanthology.org/J05-1004/)ảnh hưởng đến cách ghi lại các tuyên bố và vai trò trong đó.
- [RSTformer](https://aclanthology.org/2023.acl-long.306/)và các công việc liên quan đã được kiểm tra để tìm kiếm cấu trúc tài liệu. Họ không được sử dụng làm thẩm phán cuối cùng về ý nghĩa hoặc lý luận.

Những nguồn này giúp ngăn chặn một đoạn văn trau chuốt che giấu sự khác biệt giữa một tuyên bố, sự ủng hộ, sự điều chỉnh và sự không đồng tình.

## Tìm kiếm tài liệu hữu ích mà không nhầm lẫn sự tương đồng với sự thật

- [Mức độ liên quan cận biên tối đa của Carbonell và Goldstein](https://aclanthology.org/X98-1025/)những cách có hiểu biết để cân bằng giữa sự liên quan và sự lặp lại.
- [Lin và Bilmes về tóm tắt tài liệu theo mô-đun phụ](https://aclanthology.org/P11-1052/)những cách có hiểu biết để chọn một nhóm đoạn văn hữu ích trong giới hạn kích thước.
- [Điểm thực tế](https://aclanthology.org/2023.emnlp-main.741/)các câu hỏi có hiểu biết về cách hỗ trợ chính xác các yêu cầu bồi thường.
- Nghiên cứu về các bản tóm tắt được xây dựng từ các mối quan hệ được ghi lại đã cung cấp thông tin cho các bài kiểm tra giúp rút ngắn nội dung mà không loại bỏ các kết nối quan trọng.

Tìm kiếm và tóm tắt có thể hướng một người tới bằng chứng. Họ không thể quyết định tại sao điều gì đó lại quan trọng hoặc biến một đoạn văn thành sự thật.

## Lên kế hoạch trước khi viết

- [Reiter và Dale xây dựng hệ thống tạo ngôn ngữ tự nhiên](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD)ảnh hưởng đến sự tách biệt giữa việc chọn nội dung, dàn ý và viết câu.
- [NLG từng bước](https://aclanthology.org/N19-1236/)Và[lập kế hoạch vĩ mô chuyển dữ liệu thành văn bản](https://aclanthology.org/D19-1318/)so sánh có hiểu biết về các phương pháp lập kế hoạch tài liệu.
- [SimpleNLG](https://github.com/simplenlg/simplenlg),[Khung ngữ pháp](https://www.grammaticalframework.org/), Và[OpenCCG](https://github.com/OpenCCG/openccg)được đánh giá là cách chuyển nội dung đã được hoạch định thành câu.
- Nghiên cứu về thông tin đã biết và mới, mối liên hệ giữa các câu, các kiểu giao tiếp và hình thức tài liệu ảnh hưởng đến cách sắp xếp các giải thích cho những độc giả khác nhau.

Cùng với nhau, công việc này hỗ trợ lập kế hoạch cho một tài liệu trước khi yêu cầu một mô hình ngôn ngữ viết nó.

## Sự hiểu biết và chi phí đọc của con người

- Nghiên cứu về cách mọi người xây dựng sự hiểu biết và quản lý nỗ lực tinh thần đã đưa ra những giới hạn về độ dài, khái niệm mới và sự lặp lại.
- [Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270),[TAACO](https://www.linguisticanalysistools.org/taaco.html),[tài liệu](https://docuscope.github.io/), TextDescriptives và LFTK được đánh giá là những cách để so sánh cách viết.
- Lý thuyết về Quyền tự quyết, nghiên cứu về ý nghĩa cuộc sống và nghiên cứu về các giá trị đã đưa ra những câu hỏi hạn chế về ý nghĩa cá nhân. Chúng không hỗ trợ chẩn đoán tự động hoặc hồ sơ rộng rãi của mọi người.

## Công cụ chỉnh sửa hạn chế

[LaserTagger](https://github.com/google-research/lasertagger),[GECToR](https://github.com/grammarly/gector), Và[Chỉnh sửaT5](https://aclanthology.org/2022.findings-acl.260/)được đánh giá cho các nhiệm vụ chỉnh sửa giới hạn số lượng từ ngữ mới có thể được giới thiệu.

## Quyền và hồ sơ đầy đủ hơn

Tài liệu này không bao gồm các bản sao của sách, bài báo, chương trình, tệp mô hình được đào tạo hoặc bộ sưu tập nghiên cứu được nêu tên.[Nguồn, giấy phép và quyền riêng tư](../../SOURCES-LICENSES-AND-PRIVACY.md)ghi lại việc đánh giá giấy phép cho các chương trình và tệp được đào tạo đã thực sự được sử dụng hoặc thử nghiệm.

Hồ sơ nghiên cứu tư nhân chứa nhiều tài liệu, tiêu chuẩn công, công cụ, bộ sưu tập, tác phẩm văn hóa, phương pháp tiếp cận bị từ chối và kết quả thử nghiệm. Tín dụng công có thể tăng lên khi những hồ sơ đó được kiểm tra, bao gồm cả những ý tưởng chủ yếu giúp ích bằng cách chỉ ra những gì không hiệu quả.
