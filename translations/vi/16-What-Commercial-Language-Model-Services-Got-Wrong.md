> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Tất cả ngôn ngữ](../README.md)

# Những sai sót được quan sát thấy trong các dịch vụ mô hình ngôn ngữ phải trả phí-và các biện pháp bảo vệ mà chúng mang lại

![Những thất bại được ghi lại đã trở thành những thử nghiệm và biện pháp bảo vệ cho công việc sau này.](../../illustrations/failures-became-blueprint.png)

## Đây là những lựa chọn trả phí mạnh nhất hiện có

Dự án này sử dụng các dịch vụ mô hình ngôn ngữ trực tuyến trả phí để nghiên cứu, viết mã, viết và đánh giá. Các tài khoản bao gồm các mô hình chung mạnh nhất mà các dịch vụ được cung cấp vào thời điểm đó. Việc chọn một tùy chọn trả phí có khả năng hơn không ngăn được những lỗi dưới đây.

Mỗi ví dụ đều đến từ một bản ghi dự án có ngày tháng. Các bảng mô tả những gì một mô hình trả phí đã làm, điều gì xảy ra tiếp theo và biện pháp bảo vệ nào được xây dựng bên ngoài mô hình. Đây là những sai sót được quan sát thấy trong các dịch vụ thương mại, không phải những sai sót doRobot Brain. Cột bên phải mô tả dự án này phản hồi như thế nào.

Hồ sơ không đoán được động cơ của nhà cung cấp hoặc khẳng định biết nguyên nhân kỹ thuật chưa được tiết lộ. Tên nhà cung cấp bị bỏ qua vì các biện pháp bảo vệ phản ứng với hành vi lặp đi lặp lại chứ không phải của một công ty.

## Chi phí thất bại là bao nhiêu

Cái giá không chỉ giới hạn ở một câu trả lời sai.

- **Mất thời gian.** Công việc được mô tả là đã hoàn thành phải được người đó kiểm tra, giải thích lại, sửa chữa và kiểm tra. Một số thất bại tiêu tốn hàng giờ.
- **Trợ cấp sử dụng trả phí, đôi khi được gọi là hạn ngạch, đã bị mất.** Các lần thử lại, ngữ cảnh lặp lại, bản nháp thay thế và các bản chỉnh sửa đều sử dụng trợ cấp giới hạn tương tự như công việc hữu ích. Trong các phiên được ghi lại này, không có hạn ngạch tự động nào được trả lại cho đầu ra không sử dụng được hoặc các trao đổi khắc phục.
- **Dịch vụ đã được thanh toán theo một trong hai cách.** Phí đăng ký hoặc phí sử dụng vẫn được giữ nguyên trong khi người dùng cũng dành thời gian và công sức cần thiết để tìm và sửa chữa lỗi.
- **Mọi thứ đang hoạt động đã bị hỏng.** Chỉnh sửa chưa hoàn chỉnh khiến dịch vụ trực tiếp không thể chạy. Các thay đổi đã được thực hiện đối với bản sao cài đặt sai. Đầu ra đã được di chuyển khỏi vị trí cần thiết thay vì sửa chữa quyền truy cập.
- **Hồ sơ lịch sử đã gặp rủi ro.** Văn bản được tạo được trộn lẫn với tài liệu của con người và các hồ sơ đã được thay đổi hoặc xóa trước khi người đó chấp thuận thay đổi đó.
- **Sự chú ý bị tiêu tốn mà không được phép.** Các câu trả lời quan trọng được giấu trong những lời giải thích lặp đi lặp lại, buộc người dùng phải đọc mọi thứ để tìm ra phần nhỏ quan trọng.

Đây là lý do tại sao các quy tắc quan trọng không chỉ tồn tại trong lời nhắc ở đây.Robot Brain kiểm tra những gì thực sự đã xảy ra và có thể từ chối đóng góp ngay cả khi mô hình cho biết nó đã thành công.

## Sự liên tục và thất bại về kiến ​​thức

| Thất bại quan sát được | Chuyện gì đã xảy ra thế | Đã thêm tính năng bảo vệ bên ngoài mô hình ngôn ngữ |
|---|---|---|
| Nghe liên tục sau khi mất lịch sử | Một dịch vụ đã rút ngắn cuộc trò chuyện trước đó để phù hợp với giới hạn hoạt động của nó. Nó giữ lại một số kết luận nhưng bị mất nguồn, chỉnh sửa, các lựa chọn thay thế bị từ chối, thứ tự sự kiện và mục đích của người dùng trong khi vẫn tiếp tục nghe trôi chảy. | Giữ cuộc trò chuyện hoàn chỉnh theo thứ tự. Lưu riêng phiên bản rút gọn và ghi lại những gì nó bao gồm, bỏ qua và có thể bị mất. |
| Một câu trả lời mới thay thế lịch sử đã ghi | Một câu trả lời theo mô hình ngôn ngữ mới hơn có thể thay thế mọi thứ trước nó, mặc dù nó đến từ những thông tin, quy tắc và lựa chọn khác nhau về thế giới. | Lưu từng phát hiện với thời gian của nó. Không bao giờ để câu trả lời mới nhất ghi đè lên những kết quả đã được chấp nhận, bị từ chối hoặc không chắc chắn trước đó. |
| Việc học theo mô hình ngôn ngữ đã phá hủy con đường trở về cội nguồn | Mô hình ngôn ngữ giữ lại các khuôn mẫu hữu ích đồng thời tách chúng ra khỏi người tạo ra nguồn, mục đích, đối tượng, bằng chứng, sự bất đồng và lịch sử sau này. | Giữ các nguồn không thay đổi và các kết nối đã biết của chúng bên ngoài mọi mô hình ngôn ngữ. Hãy coi kiến ​​thức mô hình ngôn ngữ không được hỗ trợ như một gợi ý trừ khi có bằng chứng riêng biệt kết nối nó với một nguồn. |
| Mất hoàn cảnh đằng sau những gì mô hình ngôn ngữ học được từ | Mô hình ngôn ngữ vẫn hữu ích trong khi câu trả lời của nó không thể tiết lộ tất cả con người, nguồn gốc, mục đích, những bất đồng, sự cho phép và nền văn hóa đã định hình nên nó. | Giữ các trường hợp đã biết và ghi công với các nguồn được lưu bên ngoài mô hình ngôn ngữ. Hãy coi kiến ​​thức đã học không được hỗ trợ như một gợi ý về mô hình ngôn ngữ, chứ không phải một thực tế gắn liền với một nguồn. |
| Sự thiên vị ẩn khỏi những gì đã được chọn | Những gì mô hình ngôn ngữ có thể nhận ra phản ánh ngôn ngữ, nguồn, kho lưu trữ, nhãn, người đánh giá và mục tiêu được sử dụng để xây dựng nó. Câu trả lời của nó không tiết lộ tất cả những ảnh hưởng đó. | Ghi lại các giới hạn đã biết của mô hình ngôn ngữ và những gì đã biết về tài liệu mà nó đã học được. So sánh một số công cụ hạn chế và không coi một câu trả lời mượt mà là một cái nhìn hoàn chỉnh. |
| Lịch sử chia sẻ đang được âm thầm viết lại | Một số công nhân đang chỉnh sửa một lịch sử chính có thể làm mất hoặc kết hợp các quyết định không tương thích. | Thêm lịch sử nguồn mới mà không ghi đè các mục trước đó. Xây dựng chế độ xem hiện tại từ lịch sử đó mà không cần viết lại bản ghi sự kiện. |
| Thời gian và trạng thái khác nhau được coi là bình đẳng | Các tuyên bố hiện tại, lịch sử, thử nghiệm, thử nghiệm riêng biệt và thay thế được trình bày như thể chúng có cùng quan điểm. | Lưu trữ thời gian và trạng thái hiện tại với mọi yêu cầu và phần hệ thống quan trọng. |
| Xóa một phần mà không kiểm tra xem ai sử dụng nó | Một phần không được sử dụng trong quy trình hiện tại sẽ được coi là lỗi thời nếu không kiểm tra công việc sau này phụ thuộc vào nó. | Ghi lại công việc, người dùng, trạng thái hiện tại và những phần thay thế của từng bộ phận. Kiểm tra những người dùng đó trước khi loại bỏ nó. |
| Trộn văn bản được tạo vào hồ sơ của một người | Lời giải thích bằng văn bản theo mô hình ngôn ngữ đã được lưu bên cạnh tài liệu của con người ở dạng mà sau này có thể bị nhầm lẫn với lời nói hoặc niềm tin của chính người đó. | Tách biệt rõ ràng tài liệu nguyên văn của con người, bản chép lại và phần diễn giải do mô hình ngôn ngữ tạo ra. Đừng bao giờ để văn bản được tạo ra âm thầm trở thành một phần hồ sơ của con người. |
| Xóa lịch sử trong quá trình dọn dẹp | Các bản ghi trước đó đã bị thay đổi hoặc xóa vì mô hình ngôn ngữ đánh giá chúng không chính xác hoặc lộn xộn. Điều đó đã phá hủy bằng chứng cần thiết để hiểu chuyện gì đã xảy ra và tại sao nó lại thay đổi. | Lưu giữ hồ sơ lịch sử. Thêm một bản sửa lỗi hoặc phát hiện sau này thay vì âm thầm viết lại quá khứ. |

## Lỗi hướng dẫn và phạm vi

| Thất bại quan sát được | Chuyện gì đã xảy ra thế | Đã thêm tính năng bảo vệ bên ngoài mô hình ngôn ngữ |
|---|---|---|
| Quy tắc bị mất trong khi thực hiện nhiệm vụ | Một mô hình ngôn ngữ có thể đọc, trình bày lại và sau đó vi phạm một quy tắc trong cùng một nhiệm vụ. | Biến các quy tắc có lỗi gây ra chi phí cao thành các điều kiện bắt buộc và kiểm tra có thể từ chối công việc. |
| Quy tắc yêu cầu bồi thường được tuân theo mà không có bằng chứng | Người mẫu tuyên bố rằng các hướng dẫn hoặc tài liệu đã được tuân theo khi kết quả cho thấy điều ngược lại. | Yêu cầu bằng chứng cho thấy việc kiểm tra liên quan đã được thực hiện và thông qua. Một mô hình ngôn ngữ nói rằng nó thành công không phải là bằng chứng. |
| Thay thế nhiệm vụ được yêu cầu | Một yêu cầu cụ thể đã được thay thế bằng khung ưu tiên của mô hình ngôn ngữ, buộc người dùng phải tranh luận lại về tác phẩm gốc. | Bảo toàn các giới hạn được yêu cầu. Từ chối một thay đổi không được yêu cầu trong khung trừ khi xung đột về an toàn hoặc quyền thực sự yêu cầu điều đó. |
| Làm thêm việc mà không được phép | Công việc liên quan được thực hiện vì nó có vẻ hữu ích, mặc dù nó không được yêu cầu. | Buộc mọi hành động vào nhiệm vụ đã khai báo. Hãy coi bất kỳ sự mở rộng nào như một quyết định mới. |
| Thay đổi điểm đến được yêu cầu | Khi vị trí được yêu cầu không thể truy cập được, kết quả sẽ được chuyển đến nơi nào đó dễ dàng hơn thay vì sửa chữa quyền truy cập. | Bảo tồn điểm đến đã chọn. Việc thay đổi nó cần có quyết định của người dùng. |
| Di chuyển qua phần chỉnh sửa được yêu cầu | Phản hồi được coi như một phương hướng để tiếp tục thay đổi công việc thay vì một sự điều chỉnh chính xác cần đạt được. | Ghi lại trạng thái cuối cùng được yêu cầu và kiểm tra kết quả sau khi thay đổi. |
| Buộc tài liệu mới vào sai vị trí | Tài liệu mới được thêm vào tài liệu hiện có mà không khớp nó vào cấu trúc, điều này làm hỏng cả hai. | Lập kế hoạch cho kết quả hoàn chỉnh, theo dõi những gì phần bổ sung thay đổi và tạo một tài liệu riêng khi nó không thuộc về. |
| Di chuyển đầu ra thay vì sửa quyền truy cập | Khi không thể truy cập được thư mục được yêu cầu, trợ lý sẽ di chuyển kết quả đến nơi dễ dàng hơn. Điều đó chia tách hồ sơ của người đó và loại bỏ hồ sơ, quyền và thói quen đã được xây dựng xung quanh vị trí ban đầu. | Sửa chữa quyền truy cập vào vị trí đã chọn. Việc thay đổi điểm đến vẫn là quyết định của người đó. |

## Bằng chứng và thất bại hoàn thành

| Thất bại quan sát được | Chuyện gì đã xảy ra thế | Đã thêm tính năng bảo vệ bên ngoài mô hình ngôn ngữ |
|---|---|---|
| Tuyên bố hoàn thành quá sớm | Việc chỉnh sửa hoặc bắt đầu một phần được báo cáo là hoàn thành trước khi tác dụng của nó được kiểm tra. | Việc hoàn thành yêu cầu bằng chứng về kết quả được yêu cầu chứ không phải một tuyên bố trạng thái được tạo ra. |
| Chấp nhận chẩn đoán mà không kiểm tra nó | Thông báo lỗi được chấp nhận mà không cần kiểm tra xem nó đến từ đâu và khi nào hoặc liệu nó có mô tả tác vụ hiện tại hay không. | Giữ bằng chứng gắn liền với việc nó được tạo ra ở đâu, khi nào và trong hoàn cảnh nào. |
| đoán hợp lý | Nguyên nhân và các bước tiếp theo được đề xuất vì chúng nghe có vẻ hợp lý chứ không phải vì bằng chứng chỉ ra chúng. | Bảo tồn những điều chưa biết. Tách riêng những gì đã được quan sát, một lời giải thích có thể, xét nghiệm và nguyên nhân được xác nhận. |
| Giả sử thay đổi mới nhất là chính xác | Những thay đổi bằng văn bản theo mô hình ngôn ngữ gần đây được cho là đúng trong khi các phần khác bị nghi ngờ trước tiên. | Kiểm tra sự thay đổi mới nhất và các giải thích cạnh tranh trước khi chỉ định nguyên nhân. |
| Coi thời gian là bằng chứng của nguyên nhân | Bộ phận hoạt động gần xảy ra lỗi bị đổ lỗi mà không so sánh hành vi bình thường hoặc các điều kiện thay đổi khác. | Làm cho vấn đề xảy ra lần nữa. So sánh các điều kiện bình thường và thay đổi, tìm kiếm bằng chứng trái ngược và tìm ra nguyên nhân. |
| Coi một bài kiểm tra nhỏ là bằng chứng về hành vi sống | Một ví dụ bắt chước, được chuẩn bị sẵn hoặc một thử nghiệm nhỏ được đưa ra làm bằng chứng cho thấy toàn bộ hệ thống hoạt động trong sử dụng thông thường. | Nêu chính xác những gì đã được thử nghiệm và không cho rằng kết quả chứng minh được nhiều hơn. |
| Kiểm tra với quyền sai | Kiểm tra đã được thông qua bằng quyền truy cập của nhà phát triển mặc dù chương trình trực tiếp chạy với các quyền khác nhau. | Kiểm tra bằng cùng một tài khoản và quyền mà chương trình trực tiếp sử dụng hoặc không chứng minh kết quả. |
| Sửa lỗi trước khi ghi | Một sai sót đã được sửa chữa trước khi nó được tiết lộ, khiến hồ sơ trông sạch sẽ hơn so với tác phẩm. | Bảo quản lỗi và sửa chữa theo thứ tự. Đừng để việc sửa chữa xóa bỏ bằng chứng. |
| Sửa đổi nhiều lần trước mặt người dùng | Một kết quả đã được sửa lại nhiều lần trước mặt người dùng vì việc lập kế hoạch bị trì hoãn cho đến sau kết quả đầu tiên. | Chọn tài liệu và lên kế hoạch cho toàn bộ kết quả trước khi yêu cầu xem xét. Trình bày một bản dự thảo giới hạn khi có thể. |
| Phá vỡ một dịch vụ trực tiếp với bản chỉnh sửa chưa hoàn chỉnh | Mô hình ngôn ngữ chỉ thay đổi một phần của tệp đang hoạt động và tiếp tục. Dịch vụ đang chạy không thể hoàn thành công việc của nó. | Hãy coi một thay đổi là chưa hoàn thành cho đến khi toàn bộ tệp hợp lệ và dịch vụ thực tế hoàn thành công việc dự kiến. |
| Thay đổi bản sao cài đặt sai | Một mô hình ngôn ngữ đã chỉnh sửa tệp cài đặt chính, khởi động lại dịch vụ, nhận được phản hồi khởi động lại thành công và báo cáo thành công. Dịch vụ đã sử dụng một bản sao được tạo khác nên cài đặt cũ vẫn hoạt động. | Xác minh kết quả hiển thị, không chỉ thông báo chỉnh sửa hoặc khởi động lại. Giữ một đường dẫn rõ ràng từ cài đặt chính đến bản sao mà dịch vụ thực sự sử dụng. |
| Sửa nhiều lần mà không khắc phục được sự cố | Bốn thay đổi đã được thực hiện cho một vấn đề. Mỗi chứng minh rằng một số mã đã chạy, nhưng không có mã nào chứng minh rằng vấn đề ban đầu đã biến mất. | Xác định kết quả phải thay đổi trước khi chỉnh sửa. Sau mỗi lần thay đổi, hãy kiểm tra trực tiếp kết quả đó. |
| Kiểm tra quyền truy cập dịch vụ trực tiếp không có | Một thư mục đã hoạt động khi được kiểm tra thông qua tài khoản của người đó nhưng dịch vụ trực tiếp đã sử dụng một tài khoản khác và vẫn không thể truy cập được. | Chạy kiểm tra trong cùng điều kiện với dịch vụ trực tiếp. |

## Thất bại về việc ai có thể nói hoặc phê duyệt những gì

| Thất bại quan sát được | Chuyện gì đã xảy ra thế | Đã thêm tính năng bảo vệ bên ngoài mô hình ngôn ngữ |
|---|---|---|
| Các công việc khác nhau được đối xử như nhau | Người quan sát, người viết, người kiểm tra, người có quyền dừng công việc và người phê duyệt phát hành đều được đối xử như nhau vì mỗi người đều chạm vào kết quả. | Mỗi bộ phận đều có một công việc nhất định và giới hạn những gì nó có thể quyết định. Một nhà văn không thể đưa ra một tuyên bố đúng. Một người quan sát không thể xuất bản. |
| Hiển thị giá trị thay thế là giá trị thực | Màn hình hiển thị các phép đo trống hoặc các giá trị thay thế hợp lý để quá trình cài đặt trông hoàn tất. | Hiển thị giá trị đo được và nguồn gốc của giá trị đó hoặc nêu rõ rằng giá trị đó không có sẵn. |
| Làm mới một trang đã phá hủy vị trí của người dùng | Việc làm mới đã thay thế toàn bộ trang và hủy tiêu điểm, lựa chọn, vị trí cuộn hoặc sao chép. | Hãy coi màn hình như một không gian làm việc của con người. Cập nhật các giá trị thay đổi mà không phá hủy vị trí của người dùng. |
| Giữ mật khẩu trong văn bản không được bảo vệ | Mật khẩu và khóa truy cập được đặt trong các tệp thông thường thay vì bộ nhớ được bảo vệ. | Giữ chúng trong bộ lưu trữ được bảo vệ và kiểm tra mọi tệp trước khi phát hành. |
| Báo cáo rằng một dịch vụ đã dừng trong khi nó vẫn tiếp tục chạy | Yêu cầu dừng được trả về thành công nhưng quá trình vẫn tiếp tục hoạt động. | Kiểm tra quy trình và hiệu quả thực sự của nó sau khi có yêu cầu kiểm soát. Không báo cáo yêu cầu như là kết quả. |

## Thất bại trong việc chú ý của con người

| Thất bại quan sát được | Chuyện gì đã xảy ra thế | Đã thêm tính năng bảo vệ bên ngoài mô hình ngôn ngữ |
|---|---|---|
| Đệm lời nói của một người | Một câu nói ngắn gọn của con người đã được mở rộng bằng tài liệu được tạo ra cho đến khi khó tìm được những từ gốc. | Lưu giữ tuyên bố ban đầu làm hồ sơ chính. Phiên dịch được tạo vẫn riêng biệt và tùy chọn. |
| Viết tròn | Câu trả lời đã được giải thích, trình bày lại, tóm tắt và kết luận sau khi đã hết nội dung hữu ích. | Dừng lại khi kết quả được yêu cầu hoàn tất. Loại bỏ các kết luận lặp đi lặp lại. |
| Chôn vùi câu trả lời | Một hoặc hai thông tin hữu ích được đặt bên trong những tài liệu mà người dùng không yêu cầu. | Đặt câu trả lời đầy đủ ngắn nhất lên đầu tiên và đưa ra những nội dung sâu hơn tùy chọn. |
| Dành sự quan tâm không được cung cấp | Lời giải thích đúng nhưng không cần thiết buộc người đọc phải mất thời gian quyết định rằng nó không cần thiết. | Tính việc đọc và chỉnh sửa là chi phí thực tế. Hãy để người đọc bắt đầu độ sâu tùy chọn. |
| Quá nhấn mạnh | Gần như mọi điểm đều được in đậm, đánh đầu hoặc đặt trong bảng nên những cảnh báo thực sự không còn nổi bật nữa. | Chỉ nhấn mạnh một vài điểm khác biệt mang tính chất quyết định hoặc gánh nặng an toàn. |

## Thất bại liên quan đến chi phí và ưu đãi của nhà cung cấp

| Thất bại quan sát được | Chuyện gì đã xảy ra thế | Đã thêm tính năng bảo vệ bên ngoài mô hình ngôn ngữ |
|---|---|---|
| Mô hình ngôn ngữ lớn phải trả phí được sử dụng theo mặc định | Công việc được gửi qua mô hình trực tuyến phải trả phí vì nó có sẵn, ngay cả khi một quy trình cố định đơn giản, kết quả đã lưu hoặc công cụ hạn chế có thể thực hiện việc đó một cách đáng tin cậy hơn. | Đo lường toàn bộ giá trị và chi phí của công việc. Chọn sự kết hợp nhỏ nhất của các công cụ mà công việc của chúng có thể được kiểm tra và chứng minh. |
| Chi phí điều chỉnh biến mất khỏi tổng số | Việc thử lại, bối cảnh lặp lại, chờ đợi và sự sửa chữa của con người được coi là miễn phí sau một kết quả tồi tệ mặc dù chúng đã sử dụng trợ cấp được trả lương và yêu cầu nhiều thời gian và sức lực của người đó hơn. | Ghi lại việc chờ đợi, thử lại, từ chối, sử dụng dịch vụ nhiều lần và sự chú ý của con người như một phần chi phí thực tế. |
| Không có hạn ngạch được trả lại cho công việc không thành công | Đầu ra không sử dụng được và số lần trao đổi cần thiết để sửa nó được tính vào hạn ngạch đã trả. Người đó không nhận được sự thay thế tự động cho khoản trợ cấp hoặc thời gian bị mất. | Ghi lại việc sử dụng không thành công và khắc phục riêng biệt. Sử dụng lại ngữ cảnh đã lưu và các kết quả bị từ chối để không mua lại lỗi tương tự. |
| Thất bại hữu ích đã bị loại bỏ | Câu trả lời bị từ chối biến mất nên công việc sau đó lặp lại sai lầm tương tự và phải trả giá lần nữa. | Giữ các kết quả bị từ chối và lý do từ chối của chúng nằm ngoài kiến ​​thức được chấp nhận. Sử dụng lại bài học mà không chấp nhận yêu cầu không được hỗ trợ. |
| Bối cảnh tương tự phải được cung cấp lại | Khi thông tin trước đó biến mất khỏi chế độ xem làm việc của mô hình ngôn ngữ, người đó phải xây dựng lại yêu cầu và gửi lại lịch sử đã được cung cấp trong phiên trả phí. | Giữ bối cảnh lâu dài bên ngoài dịch vụ. Xây dựng một gói giới hạn cho mỗi công việc và giữ lại công việc được trả lại, chỉnh sửa và từ chối để sử dụng sau này. |

## Làm thế nào những lỗi dịch vụ đó lại trở thành thiết kế của dự án này

Vấn đề quan sát được không chỉ giới hạn ở một mô hình yếu. Người trợ lý tạm thời tương tự đã được yêu cầu đóng vai trò là người ghi nhớ, nhà sử học, người lập kế hoạch, người viết, người kiểm tra và người đánh giá công việc của chính mình. Ngay cả những người mẫu được trả lương cao nhất cũng có thể thành công trong một nhiệm vụ cá nhân trong khi đánh mất lịch sử loài người đã kết nối nó với mọi thứ khác.

Robot Brain giao những công việc đó cho các bộ phận riêng biệt. Người giữ nguồn duy trì sự kiện. Độc giả địa phương tập trung kiểm tra các tính năng được xác định. Người xây dựng yêu cầu thu thập bằng chứng cho một mục đích. Một mô hình có thể đóng góp nền tảng hoặc từ ngữ. Kiểm tra độc lập và sự chấp thuận của con người quyết định những gì được chấp nhận.

Lịch sử nằm ngoài dịch vụ trả phí. Một mô hình có thể giúp thực hiện công việc đã chọn, nhưng nó không lưu giữ mạng sống của một người hoặc trở thành cách duy nhất để sử dụng công việc đã được thực hiện.

Mô hình địa phương có cùng giới hạn. Nó không được đào tạo trên hồ sơ của người đó. Nó đọc tài liệu đã chọn, trả về đề xuất ngày tháng và có thể được thay thế. Lời nói, thời gian, kinh nghiệm, quyết định, thất bại và sửa chữa của một người đều là những phần có giá trị.
