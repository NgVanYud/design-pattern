[Source](https://www.codeproject.com/Tips/808058/Reasons-for-using-design-patterns "Permalink to Reasons for using design patterns")

# Những lý do sử dụng design pattern

## Giới thiệu

Tiếp theo từ bài báo trước có tiêu đề [Why design is Critical to Software Development][1], tôi muốn giải quyết một khía cạnh nâng cao hơn một chút về thiết kế phần mềm được gọi là `Design Patterns`. Như trong bài viết trước của tôi, ý tưởng xuất phát từ một cuộc thảo luận liên quan đến việc thiết kế phần mềm với một người đồng nghiệp. Trọng tâm của cuộc thảo luận là nói về ý kiến cho rằng `Design Pattern` làm mất quá nhiều thời gian khi mà sử dụng trong việc phát triển phần mềm thương mại. Mục đích của tôi ở đây là để chứng minh tại sao tôi tin rằng quan điểm đó là sai

Tôi sẽ không đi sâu chi tiết ~~về mặt cơ học~~ **lý thuyết/nguyên lý chi tiết** hay cách thực hiện của bất kỳ `Design Pattern` cụ thể nào. Có rất nhiều ~~tài liệu bổ~~ **nguồn tài liệu tuyệt vời/rõ ràng** nói về những khía cạnh khác của design pattern

## Design Pattern là gì?

Trước khi bắt đầu, hãy xem `Design Pattern` chính xác là gì? Ở đây có ~~2 định nghĩa~~ **một vài định nghĩa** (a couple of definitions) về từ khóa này:


~~Được lấy~~ **Trích/Tham khảo** (Extracted) từ [Wikipedia][2]:

> "Một design pattern trong kiến ​​trúc và khoa học máy tính là một cách giải quyết một vấn đề về thiết kế trong một lĩnh vực chuyên môn cụ thể nào đó."

Được lấy từ [Data & Object Factory][3]:

> "Design pattern ~~là các giải pháp chung trong vấn đề thiết kế phần mềm mà bạn có thể lăp đi lặp lại trong công việc phát triển phần mềm thực tế~~ **là các giải pháp định kỳ cho các vấn đề thiết kế phần mềm mà bạn tìm thấy trong phát triển ứng dụng ở thế giới thực**. Pattern nói về việc thiết kế và sự tương tác giữa các object, cũng như cung cấp một nền tảng giao tiếp rõ ràng, các giải pháp có thể tái sử dụng được trong việc giải quyết những thách thức lập trình thường gặp"

Vì thế 1 `Design Pattern` là việc khái quát hóa mục địch chung cho một vấn đề nào đó, nó có thể áp dụng cho một cách giải quyết cụ thể nào đó. Vì các nhà phát triển phần mềm thường phải giải quyết các kiểu vấn đề tương tự nhau, điều đó có nghĩa là bất kỳ các giải pháp phần mềm nào cũng có thể áp dụng những những thành phần tương tự từ những giải pháp khác. Tại sao lại cần thiết kế lại từ đầu?  
   
## Well documented and understood **Dẫn chứng tốt và dễ hiểu**

Vì `Design Patterns` được tài liệu hóa và hiểu rõ bởi các nhà phát triển, thiết kế và các kỹ sư phần mềm nên các ứng dụng của học áp dụng những giải pháp cụ thể sẽ có cách hiểu tương tự nhau.

`Design Patterns` đưa ra cho 1 nhà phát triển phần mềm một tập hợp các cách để kiểm tra và có thể thử nghiệm các vấn đề thường gặp. Do đó, bằng cách không cho phép sử dụng và thực thi các thiết kế chưa được kiểm thử trước đó, project sẽ giảm thiểu rủi ro về mặt kỹ thuật.
 
`Design Patterns` ban đầu có thể làm mất thời gian trong việc phát triển, ~~vì cần một phải học tập~~ **vì đây sẽ là một đường vòng** nếu những người trong team không quen với nó. Tuy nhiên, khi ngày càng quen dần với design pattern thì thời gian phát triển sẽ ngày càng được rút ngắn.  

## Close parallels with civil engineering **Điểm tương đồng với kỹ thuật dân dụng**

Để đưa ra một điểm chung giữa một `Design Pattern` và lĩnh vực kỹ thuật dân dụng (như tôi đã đề cập trong bài viết của mình [Why design is Critical to Software Development][1]) có những điểm tương đồng gần giống với công nghệ phần mềm, sẽ được coi là một cách để băng qua dòng sông. Đây là vấn đề thường gặp đối với các kỹ sư dân dụng, một vài giải pháp được chứng minh và hiểu rõ. Các kỹ sư dân dụng có thể xây dựng một cây cầu hoặc một đường ống.

Tại sao một kỹ sư dân dụng cố gắng giải quyết vấn đề này từ đầu trong khi đã có những giải pháp thế giới thực có thể được đề cập đến? Có sự tương đồng giữa việc kỹ sư xây dựng giải quyết vấn đề về sông và kỹ sư phần mềm giải quyết vấn đề phần mềm:

* Các giải pháp (cầu hoặc đường hầm) đều được hiểu và ghi lại tài liệu
* Các giải pháp (cầu hoặc đường hầm) giải quyết các vấn đề kỹ thuật xây dựng định kỳ
* Các giải pháp (cầu hoặc đường hầm) không xác định rõ hoặc bị quy định, nhưng lại trừu tượng và có thể được điều chỉnh cho các vấn đề cụ thể (cầu hoặc các vật liệu xây dựng đường hầm ví dụ có thể được lựa chọn để liên kết với các vấn đề cụ thể)

Từ dó, `Design Pattern` cho thấy chúng không phù hợp với mục đích thương mại do quá trình thực hiện lâu dài của chúng không giữ được. `Design Pattern` tiết kiệm thời gian (khi được tính trong suốt vòng đời của ứng dụng) bằng cách cho nhà phát triển lựa chọn các giải pháp đã được thử và kiểm nghiệm sẵn có mà họ có thể tùy chỉnh theo nhu cầu cụ thể của riêng họ.

Vấn đề duy nhất tôi đã gặp với `Design Pattern` là chúng mất thời gian để tìm hiểu. Một số loại có thể rất khó hiểu. Đây là một lý do hợp lý, vì nó đòi hỏi một nhà phát triển có tay nghề cao hơn sử dụng chúng. Điều này sau đó có thể làm tăng chi phí dự án ban đầu. Tuy nhiên, khi xem xét trong suốt thời gian sử dụng một ứng dụng, tôi sẽ hoàn toàn mong đợi những chi phí phát triển ban đầu này sẽ được bù đắp lại do chi phí bảo trì thấp hơn do sự hiểu biết cao hơn và khả năng mở rộng dễ dàng hơn (làm cho ứng dụng dễ dàng mở rộng trong tương lai để đáp ứng những tính năng mới và nổi bật khác).

`Design Pattern` làm giảm sự phức tạp, và do đó giải pháp trở nên dễ hiểu hơn


`Design Patterns` là các giải pháp đã được thử và kiểm nghiệm, nhà phát triển không cần phải bắt đầu từ đầu, và có thể chạy trên mặt đất với một giải pháp đã được chứng minh là có hiệu quả (miễn là `Design Pattern` được sử dụng giải quyết một vấn đề tương tự). Sẽ là sai khi nghĩ rằng một cây cầu để giải quyết vấn đề băng qua đại dương,chỉ vì đơn giản là nó không phù hợp.
 
## Những lợi ích của việc sử dụng Design Pattern

`Design Patterns` đem lại những lợi ích dưới đây.
* Đưa ra cho nhà phát triển sự chọn lựa các giải pháp giải quyết đã được kiểm tra và thử nghiệm
* Chúng là ngôn ngữ trung lập và do đó có thể được áp dụng cho bất kỳ ngôn ngữ nào hỗ trợ hướng đối tượng
* Chúng hỗ trợ việc giao tiếp bởi thực tế chúng được ghi chép lại và có thể được nghiên cứu nếu không phải như vậy.
* Chúng có thông tin theo dõi đã được chứng minh, vì chúng đã được sử dụng rộng rãi và do đó làm giảm nguy cơ rủi ro cho dự án
* Chúng rất linh hoạt và có thể được sử dụng trong bất kỳ loại ứng dụng hoặc tên miền nào

## Tóm tắt
`Design Patterns` mặc dù mất thời gian tìm hiểu ban đầu, nhưng là một khoản đầu tư rất đáng giá. Nó sẽ cho phép bạn thực hiện các giải pháp được thử và đã được kiểm nghiệm cho các vấn đề gặp phải, do đó tiết kiệm thời gian và nỗ lực trong suốt giai đoạn triển khai của vòng đời phát triển phần mềm. Bằng cách sử dụng các giải pháp được hiểu rõ và có tài liệu, sản phẩm cuối cùng sẽ tính bao quát cao hơn nhiều. Nếu giải pháp được dễ dàng hơn để hiểu, sau đó bằng cách mở rộng, nó cũng sẽ được dễ dàng hơn để duy trì
 
[1]: http://www.codeproject.com/Tips/806867/Why-Design-is-Critical-to-Software-Development
[2]: http://en.wikipedia.org/wiki/Design_pattern
[3]: http://www.dofactory.com/Patterns/Patterns.aspx

## Practice
- https://coderoncode.com/design-patterns/programming/php/coding/development/2014/01/19/design-patterns-php-factories.html
- https://www.binpress.com/tutorial/the-factory-design-pattern-explained-by-example/142
- https://www.codeproject.com/Articles/852232/PHP-Singleton-Pattern-A-Step-by-Step-And-Problem-s
- http://www.fluffycat.com/PHP-Design-Patterns/

**Keyword:** `how to separate code to package php`, `step by step php design pattern singleton`(change singleton to other for more result)
