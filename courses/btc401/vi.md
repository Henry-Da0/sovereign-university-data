---
name: Bitcoin Development Accelerator
goal: Nắm vững tất cả kiến thức cơ bản để bắt đầu phát triển trên Bitcoin
objectives:
  - Hiểu rõ các khái niệm và công nghệ cốt lõi làm nền tảng cho Bitcoin.
  - Nắm vững kỹ năng thực hành về bảo mật Bitcoin, phát triển phần mềm, và quản trị mạng lưới.
  - Phát triển kỹ năng chuyên môn về Lightning Network và các giao thức liên quan.
---

Chào mừng bạn đến với các khóa học phát triển Cubo+ cho Bitcoin!

Trong 20 giờ tới, bạn sẽ đi sâu vào các giao thức Bitcoin và Lightning Network. Khóa học này được thiết kế cho các lập trình viên muốn bắt đầu làm việc trong hệ sinh thái Bitcoin và đang tìm kiếm những hiểu biết vững chắc về các lớp công nghệ khác nhau của Bitcoin và Lightning Network.

Các video được ghi hình trực tiếp trong suốt bootcamp CUBO+ 2023 tại El Salvador, nơi đã quy tụ thành công các giáo viên nổi tiếng toàn cầu. Khóa học này được cung cấp miễn phí nhờ sự hào phóng của Fulgure Venture và sự hợp tác của các giáo viên, văn phòng Bitcoin, DecouvreBitcoin, và nhiều bên liên quan khác.

Chúc bạn học tập vui vẻ!

+++

# Giới thiệu và các khóa học chuẩn bị
<partId>43a835de-c4e7-542b-9d1a-c92f049e88e6</partId>

## Giới thiệu về các khóa học CUBO+
<chapterId>dcf2d37e-b32a-5eb8-aaa3-41ac92475ba9</chapterId>

![Video](https://youtu.be/4VuI9we_XYM)

Filippo và Mario giới thiệu về CUBO+, mở đầu cho hành trình học tập toàn diện phía trước. Họ thảo luận về cấu trúc của các khóa học, kết quả mong đợi, và cách mà những kiến thức này sẽ giúp các sinh viên đạt được thành công trong lĩnh vực phát triển Bitcoin.

### Mục tiêu

Khóa học nhằm trang bị cho người học nền tảng hiểu biết sâu sắc về các nguyên tắc cơ bản của Bitcoin, kỹ năng phát triển thực tế, và khả năng khám phá và đóng góp hiệu quả vào hệ sinh thái Bitcoin. Thông qua sự kết hợp của kiến thức lý thuyết và bài tập thực hành, sinh viên sẽ nắm vững những kiến thức cơ bản về bảo mật Bitcoin, sự phức tạp về các tầng của phần mềm và cơ chế quản trị Bitcoin.

### Yêu cầu đầu vào

Học viên cần có tinh thần tò mò, ham học hỏi ở cấp độ chuyên nghiệp và một số kiến thức cơ bản về lập trình. Mặc dù không yêu cầu một nền tảng kiến thức chi tiết về Bitcoin, nhưng học viên cần một hiểu biết cơ bản về nguyên tắc lập trình và sự cởi mở để tiếp cận với các khái niệm kỹ thuật phức tạp để tận dụng tối đa khóa học này.

#### Công cụ hỗ trợ
Trong suốt khóa học, học viên sẽ sử dụng các công cụ quan trọng để nâng cao hiểu biết và trải nghiệm học tập của mình. Việc sử dụng Linux, giao diện dòng lệnh, GitHub và Docker sẽ rất quan trọng để có thể thực hành phát triển Bitcoin. Các công cụ này sẽ hỗ trợ người học trong quá trình làm việc với bộ phần mềm của Bitcoin, quản lý môi trường phát triển, và cộng tác trong các dự án thực tế.

## Tại sao lại là Bitcoin
<chapterId>89a0aa8b-90bd-58b2-82b3-bc5e1f82eaeb</chapterId>

### Tại sao El Salvador cần Bitcoin

![video](https://youtu.be/VExfKFrGuYw)

Chào mừng bạn đến với bài giảng đầu tiên của **Cubo+**. Hôm nay, chúng ta sẽ khám phá thế giới Bitcoin dưới sự dẫn dắt của Ricky, người sáng lập **Bitcoin Italia Podcast**. Ricky là một nhà hoạt động nhân quyền đầy nhiệt huyết, sử dụng Bitcoin như một công cụ để bảo vệ và thúc đẩy nhân quyền. Với hơn sáu năm kinh nghiệm, Ricky đã đi khắp nơi để ghi lại sự chấp nhận Bitcoin ở các thị trường mới nổi như El Salvador và Guatemala. Công việc của anh không chỉ dừng lại ở việc sản xuất podcast, mà còn bao gồm các hoạt động trên YouTube (Bitcoin Explorers) và Twitter (BTC Explorer, Ricky6). Cam kết của Ricky với Bitcoin xuất phát từ niềm tin rằng nó mang đến tự do tài chính và quyền riêng tư, thách thức các hệ thống ngân hàng tập trung truyền thống.

![Unbanked Population](assets/en/1/1.webp)
_Dân số toàn cầu không có ngân hàng_

### Bitcoin: Tự do tài chính và tác động của nó tại El Salvador

Bài giảng **‘Tại sao El Salvador cần Bitcoin’** cung cấp một cái nhìn tổng quan về: **giao thức Bitcoin** và nguồn gốc của nó, **phong trào cypherpunk**, và tầm quan trọng của Bitcoin như một công cụ cho tự do (**tiền không bị kiểm duyệt, sự bao gồm về tài chính**, và các chủ đề liên quan khác).
> **Định nghĩa:**
>
> - _Giao thức Bitcoin:_ Các quy tắc và cấu trúc điều chỉnh cách Bitcoin hoạt động như một loại tiền kỹ thuật số phi tập trung.
> - _Phong trào Cypherpunk:_ Nhóm người ủng hộ việc sử dụng mật mã học để đảm bảo quyền riêng tư và tự do trong không gian kỹ thuật số.
> - _Sự bao gồm về tài chính:_ Việc cung cấp quyền truy cập vào các dịch vụ tài chính cho những người bị loại trừ khỏi hệ thống ngân hàng truyền thống, thường được gọi là "không có ngân hàng - unbanked."
> - _Đồng tiền không bị kiểm duyệt:_ Đồng tiền mà chính phủ hoặc các tổ chức tài chính không thể kiểm soát hoặc hạn chế.

#### Nền tảng và hoạt động của Ricky

Hành trình của Ricky đến với Bitcoin bắt nguồn từ việc anh là một nhà hoạt động nhân quyền. Anh tin rằng Bitcoin có thể mang đến cho các cá nhân quyền kiểm soát về tài chính, bảo vệ quyền riêng tư và tránh những hạn chế từ các ngân hàng tập trung. Khám phá của Ricky về việc áp dụng Bitcoin tại các quốc gia như El Salvador cho thấy công nghệ này có thể giúp người dân ở các thị trường mới nổi đạt được độc lập tài chính.

### Ý nghĩa toàn cầu và thách thức của Bitcoin

Bitcoin không chỉ là một loại tiền kỹ thuật số. Nó còn là một công cụ để bảo vệ quyền riêng tư và đảm bảo tự do tài chính. Bằng cách sử dụng **khóa riêng tư**, hoạt động như mật khẩu chính, người dùng có thể quản lý Bitcoin của mình một cách an toàn, và nắm toàn quyền kiểm soát tài sản của bản thân.

Trong các chế độ độc tài, nơi có sự đàn áp tài chính, đặc tính **kháng kiểm duyệt** của Bitcoin cho phép mọi người giao dịch mà không sợ bị đóng băng tài khoản hoặc tịch thu tài sản. Đặc tính **mã nguồn mở** của Bitcoin khuyến khích sự tham gia toàn cầu, tạo ra một cộng đồng không ngừng cải tiến mạng lưới.

![Image](assets/en/1/4.webp)

Mặc dù có tiềm năng lớn, Bitcoin cũng phải đối mặt với nhiều thách thức. Tại một số nơi như Châu Phi và Ấn Độ, cơ sở hạ tầng cơ bản như điện và internet còn thiếu, làm hạn chế khả năng tiếp cận. Hơn nữa, **sự bao gồm về mặt kỹ thuật số** — đảm bảo rằng mọi người ở mọi độ tuổi và trình độ học vấn đều có thể sử dụng công nghệ — vẫn là một trở ngại lớn.

> **Định nghĩa:**
>
> - _Khoá riêng tư:_ Mã bí mật cho phép truy cập vào Bitcoin của người dùng.
> - _Mã nguồn mở:_ Phần mềm mà bất kỳ ai cũng có thể kiểm tra, sửa đổi và cải thiện.

### Trường hợp của El Salvador

Quyết định chấp nhận Bitcoin làm tiền tệ hợp pháp của El Salvador cho thấy tiềm năng chuyển đổi của nó. Bằng cách sử dụng Bitcoin, quốc gia này kỳ vọng thu hút được đầu tư nước ngoài và thúc đẩy ổn định tài chính. Các dự án như **Bitcoin Beach** cho thấy các nền kinh tế địa phương có thể phát triển khi áp dụng Bitcoin làm phương tiện trao đổi.

Tuy nhiên, việc áp dụng Bitcoin trên phạm vi toàn cầu gặp nhiều trở ngại như sự thiếu hiểu biết, kháng cự với công nghệ mới, và thách thức về cơ sở hạ tầng. Con đường đạt đến một hệ thống tài chính bao gồm hơn — nơi Bitcoin có thể giúp nâng tầm các quốc gia đang phát triển — còn dài nhưng đầy hứa hẹn. Đặc tính phi tập trung và mã nguồn mở của Bitcoin mang đến hy vọng cho một tương lai nơi mà mọi người có thể tiếp cận được sự công bằng về mặt tài chính.

#### Kết luận

Tóm lại, Bitcoin mang lại tiềm năng lớn cho sự trao quyền và bao gồm về mặt tài chính, nhưng vẫn còn nhiều thách thức lớn phía trước. Duy trì sự gắn kết với cộng đồng Bitcoin, học hỏi và đặt câu hỏi sẽ là chìa khóa để hiện thực hoá một tương lai tài chính phi tập trung. Thông qua sự hợp tác và ủng hộ, tầm nhìn về một hệ thống tài chính công bằng hơn cho tất cả mọi người có thể trở thành hiện thực.

### Phong trào Cypherpunk và trường phái kinh tế học Áo

![video](https://youtube.com/live/KIaC31YQLBA)

#### Phong trào Cypherpunk

**Phong trào Cypherpunk** nổi lên vào cuối thế kỷ 20, với mục tiêu thúc đẩy quyền riêng tư và tự do thông qua mật mã học. Những người tiên phong như **Eric Hughes** và **Tim May** tin rằng mã hóa mạnh là điều cần thiết để bảo vệ tự do cá nhân trong thế giới kỹ thuật số. Các ý tưởng của họ có ảnh hưởng lớn đến sự ra đời của Bitcoin.

> **Định nghĩa:**
>
> - _Cypherpunk:_  Một phong trào thúc đẩy quyền riêng tư và tự do bằng cách sử dụng mật mã học.

#### Trường phái kinh tế học Áo

Đồng thời, **trường phái kinh tế học Áo** đã cung cấp nền tảng cho các nguyên tắc tiền tệ của Bitcoin. Các nhà kinh tế học như **Ludwig von Mises** và **Friedrich Hayek** cho rằng một đồng tiền tốt nên là đồng tiền khan hiếm, bền vững và có thể lưu trữ giá trị tốt — những nguyên tắc cốt lõi đã định hình nên thiết kế của Bitcoin.

> **Định nghĩa:**
>
> - _Sự khan hiếm:_ Sự giới hạn về nguồn cung, tạo ra giá trị thông qua nhu cầu được phân bổ cẩn thận.

### Sự ra đời của Bitcoin

**Satoshi Nakamoto** đã kết hợp các ý tưởng này để tạo ra Bitcoin vào năm 2008, một loại tiền kỹ thuật số phi tập trung và có khả năng kháng kiểm duyệt. Bằng cách kết hợp lý tưởng về quyền riêng tư của Cypherpunk với các nguyên tắc về tiền tệ tốt của trường phái kinh tế học Áo, Bitcoin mang đến một hệ thống tài chính mới, thách thức các ngân hàng truyền thống và sự kiểm soát của chính phủ.

> **Định nghĩa:**
>
> - _Kháng kiểm duyệt:_ Đồng tiền không thể bị kiểm soát hoặc ngăn chặn bởi các thế lực bên ngoài.

#### Nguyên lý kinh tế chính

- **Sự khan hiếm:** Nguồn cung cố định của Bitcoin đảm bảo giá trị của nó theo thời gian.
- **Sự ưa thích theo thời gian:** Khuyến khích tiết kiệm cho tương lai thay vì chi tiêu ngay lập tức.
- **Tiết kiệm:** Lưu trữ giá trị cho các nhu cầu trong tương lai, dẫn đến đầu tư và đổi mới.

> **Định nghĩa:**
>
> - _Sự ưa thích theo thời gian:_ Đánh giá cao các hàng hóa ở hiện tại hơn các hàng hóa trong tương lai.
> - _Tiết kiệm:_ Lưu trữ giá trị để sử dụng trong tương lai.

### Bitcoin tại El Salvador

Việc El Salvador chấp nhận Bitcoin phản ánh tiềm năng của nó như một công cụ tự do tài chính, phù hợp với **Kinh tế học Áo** khi thúc đẩy sự tự nguyện chấp nhận và phi tập trung. Động thái này thách thức các hệ thống tài chính truyền thống bằng cách giải quyết những vấn đề then chốt: cạnh tranh, độc quyền và tịch thu tài sản.

![Image](assets/en/1/5.webp)

- **Cạnh tranh**: Bitcoin tạo ra sự cạnh tranh trong lĩnh vực tài chính bằng cách cung cấp một giải pháp thay thế cho ngân hàng truyền thống, cho phép người dân Salvador bỏ qua các rào cản tài chính và chọn các dịch vụ phù hợp hơn với nhu cầu của họ.

- **Độc quyền**: Bằng cách phi tập trung hoá quyền tiếp cận tài chính, Bitcoin phá vỡ độc quyền của các ngân hàng và đồng tiền do chính phủ phát hành, giảm sự phụ thuộc vào các tổ chức tập trung và thúc đẩy sự bao gồm về mặt tài chính.

- **Tịch thu**: Khả năng chống lại sự tịch thu tuỳ ý của Bitcoin cho phép người dân Salvador kiểm soát tài sản của họ, bảo vệ tài sản khỏi việc bị thu giữ từ bên ngoài và tăng cường chủ quyền tài chính của bản thân.

Việc El Salvador chấp nhận Bitcoin thúc đẩy một hệ thống tài chính bao gồm hơn, cạnh tranh hơn và an toàn hơn, thách thức những hạn chế của tài chính truyền thống.

#### Kết luận

Nền tảng của Bitcoin trong **phong trào Cypherpunk** và **Kinh tế học Áo** đã tạo nên một dạng tiền tệ độc đáo và mang tính cách mạng. Hiểu rõ các nguyên tắc này giúp chúng ta nắm bắt được lý do tại sao Bitcoin được tạo ra và cách thức hoạt động của nó. Để tìm hiểu thêm, bạn có thể đọc **The Bitcoin Standard** của **Saifedean Ammous**.

Cảm ơn bạn đã theo dõi tài liệu này!

## Hiểu về Bitcoin
<chapterId>d800970a-0d8e-5557-810a-7aef845d4a34</chapterId>

### Nền tảng công nghệ của Bitcoin

![video](https://youtu.be/5UkjQomJsHU)
Trong bài giảng đầu tiên của phần học 'Hiểu về Bitcoin', chúng ta đã bắt đầu khám phá nền tảng công nghệ hỗ trợ mạng lưới Bitcoin. Chúng ta đã đề cập đến một loạt các chủ đề, bao gồm **Hashcash, giao dịch, blockchain, Lightning Network** và các thành phần chính khác của giao thức Bitcoin.
### Nền tảng công Nghệ của Bitcoin - Phần 2

![video](https://youtu.be/UkwbPVhLeIk)
Trong bài giảng thứ hai của 'Hiểu về Bitcoin', chúng ta đã đi sâu hơn vào nền tảng công nghệ của Bitcoin.

### Cấu trúc của Bitcoin

Nguồn gốc của Bitcoin dựa trên một số đổi mới quan trọng, bắt đầu từ **Hashcash của Adam Back**, một hệ thống bằng chứng công việc (PoW) được thiết kế để ngăn chặn thư rác và các cuộc tấn công từ chối dịch vụ bằng cách yêu cầu người gửi thực hiện các nhiệm vụ tính toán. Khái niệm PoW này trở thành nền tảng của bảo mật Bitcoin.

Bitcoin sử dụng **chữ ký số** với mật mã **đường cong e-líp** để bảo vệ và xác minh các giao dịch. **Thuật toán chữ ký số đường cong e-líp (ECDSA)** đảm bảo chỉ chủ sở hữu hợp pháp mới có thể thực hiện giao dịch mà không tiết lộ khóa riêng của họ.

**Satoshi Nakamoto**, người sáng lập ẩn danh của Bitcoin, đã mở rộng những ý tưởng này bằng cách chuyển đổi mô hình PoW sang một **blockchain** phi tập trung. Điều này cho phép một mạng lưới các nút phân tán xác thực và ghi lại các giao dịch mà không cần một thực thể tập trung, đánh dấu một bước tiến lớn so với các thử nghiệm tiền kỹ thuật số trước đó.

> **Định nghĩa:**
>
> - _Bằng chứng công việc - Proof-of-Work (PoW):_ Hệ thống trong đó các thành viên phải giải các câu đố tính toán để xác thực giao dịch và bảo vệ mạng lưới.
> - _Mã hoá đường cong e-líp:_ Phương pháp mã hóa cho phép tạo chữ ký số an toàn và hiệu quả.

### Cơ chế hoạt động của blockchain và xác thực giao dịch

Các giao dịch Bitcoin được xác thực và thêm vào các khối bởi các **thợ đào**, những người cạnh tranh với nhau để giải câu đố mật mã thông qua thuật toán PoW. Điều này bao gồm việc tìm kiếm một giá trị băm được bắt đầu với một số lượng số không nhất định bằng cách điều chỉnh giá trị **nonce** cho đến khi tìm thấy mã băm phù hợp.

Mỗi khối trong blockchain bao gồm một **header** (chứa dữ liệu như băm của khối trước đó) và danh sách các giao dịch. Khối đầu tiên, được gọi là **Khối Khởi Nguyên (Genesis Block)**, là độc nhất vì nó không gắn vào một khối nào trước đó cả.

![Image](assets/en/1/6.webp)

Trước khi các giao dịch được đưa vào một khối, chúng tồn tại trong **mempool**, nơi chúng chờ được xác nhận. Sau khi được xác nhận, các giao dịch này sẽ được thêm vào khối mới được đào và do đó là được thêm vào blockchain.

> **Định nghĩa:**
>
> - _Đào:_ Quá trình giải các câu đố mật mã để thêm các khối mới vào blockchain.
> - _Nonce:_ Giá trị được sử dụng để tìm mã băm chính xác trong quá trình đào.
> - _Mempool:_ Khu vực chờ cho các giao dịch chưa được xác nhận trước khi được thêm vào một khối.

### Khả năng mở rộng, quyền riêng tư, và phát triển trong Bitcoin

Bitcoin đối mặt với các thách thức liên quan đến khả năng mở rộng và quyền riêng tư. Khả năng xử lý giao dịch giới hạn của chuỗi khối gây khó khăn trong việc xử lý khối lượng giao dịch lớn. Các giải pháp như **Lightning Network** giải quyết vấn đề này bằng cách cho phép thực hiện các giao dịch ngoài chuỗi thông qua các kênh thanh toán, giúp tăng tốc độ và bảo vệ quyền riêng tư.

Chạy một **nút đầy đủ (full-node)** là lựa chọn rất quan trọng để đảm bảo tính phi tập trung và bảo mật, nhưng các nút **Xác minh thanh toán đơn giản (SPV)** cho phép chúng ta tham gia dễ dàng hơn nhưng mất đi một phần bảo mật.

Sự phát triển của Bitcoin nhằm cải thiện hiệu suất và bảo mật. Các nâng cấp chính bao gồm **Segregated Witness (SegWit)**, giải quyết khả năng sửa đổi giao dịch và tăng kích thước khối hiệu quả, và **Taproot**, cải thiện quyền riêng tư và cho phép các hợp đồng phức tạp hơn thông qua **Cây cú pháp trừu tượng dạng Merkle (MAST)**.

> **Định nghĩa:**
>
> - _SegWit:_  Là một bản nâng cấp của Bitcoin nhằm tách dữ liệu chữ ký khỏi dữ liệu giao dịch, nâng cao hiệu quả của mạng lưới.
> - _Taproot:_ Là một bản nâng cấp nhằm tăng cường quyền riêng tư và khả năng mở rộng của Bitcoin bằng cách cho phép các hợp đồng thông minh phức tạp hơn.
> - _Lightning Network:_ Là một giải pháp lớp thứ hai cho phép thực hiện các giao dịch Bitcoin nhanh hơn, rẻ hơn thông qua các kênh thanh toán.

#### Kết luận

Cấu trúc và sự phát triển liên tục của Bitcoin thể hiện sự đổi mới và khả năng thích ứng của công nghệ này. Từ **Hashcash** đến một blockchain phi tập trung, từ **SegWit** đến **Taproot**, Bitcoin tiếp tục giải quyết những thách thức về khả năng mở rộng, quyền riêng tư và bảo mật. Những nỗ lực không ngừng của cộng đồng đảm bảo rằng Bitcoin vẫn bền vững và phi tập trung trong khi được phát triển để đáp ứng nhu cầu của tương lai.

## Phản biện về Bitcoin
<chapterId>171ec71d-3028-5820-9b4f-36682113fc81</chapterId>

### Phản biện về Bitcoin

![video](https://youtu.be/f0Pf0u1y5F4)

Trong bài giảng này, chúng ta sẽ phản biện các quan niệm sai lầm phổ biến xung quanh **Bitcoin, blockchain và tiền mã hóa**. Chúng ta sẽ làm rõ các hiểu lầm về tiêu thụ năng lượng của Bitcoin, việc sử dụng Bitcoin cho mục đích phạm pháp và những thông tin gây "FUD" (sợ hãi, bất an, nghi ngờ) xung quanh công nghệ này.

### Bitcoin và Blockchain

Một hiểu lầm phổ biến là Bitcoin và chuỗi khối là một. Trong khi Bitcoin là một loại tiền kỹ thuật số, chuỗi khối là công nghệ nền tảng của nó. Chuỗi khối cung cấp một bản ghi giao dịch được xác minh, nhưng đi kèm với các hạn chế như tốc độ chậm hơn và chi phí cao hơn mà các giải pháp như Lightning Network có thể giải quyết.
A frequent misconception is that **Bitcoin** and **blockchain** are the same. While Bitcoin is a digital currency, **blockchain** is the technology that powers it. Blockchains provide a verified record of transactions but come with trade-offs like slower speeds and higher costs, which solutions like the **Lightning Network** address.

> **Definitions:**
>
> - _Blockchain:_ The underlying technology used to record transactions in a decentralized, immutable ledger.
> - _Lightning Network:_ A second-layer solution that improves Bitcoin's transaction efficiency by enabling off-chain transactions.

### Bitcoin vs. Crypto

Another key distinction is that **Bitcoin** was created with the sole purpose of providing a decentralized, censorship-resistant form of money, free from control by any company or government. In contrast, cryptocurrencies **shitcoins** are often designed with centralized control, primarily existing to enrich the companies behind them through predatory practices, pump-and-dump schemes, or outright scams. These tokens typically serve no genuine purpose beyond making a quick profit for their creators at the expense of uninformed investors. Bitcoin, however, stands alone as the only truly decentralized digital currency with a proven track record of security and resilience.

> **Definitions:**
>
> - _Shitcoins:_ Shitcoins are low-value or questionable quality cryptocurrencies that lack real utility. They are often highly speculative and are sometimes created for fraudulent purposes or without a clear purpose, taking advantage of the cryptocurrency market boom.

![Image](assets/en/1/2.webp)

### Energy Consumption and Environmental Impact

One of the most common criticisms of Bitcoin is its **energy consumption**. While Bitcoin mining does use energy, it accounts for less than 1% of global electricity consumption and less than 3% of wasted energy. Moreover, **Bitcoin mining** often taps into unused or renewable energy sources, making it greener than often portrayed.

> **Definitions:**
>
> - _Bitcoin Mining:_ The process of validating transactions and securing the network by solving cryptographic puzzles, which requires computational power.

### Cắt Bỏ FUD

![video](https://youtu.be/f0Pf0u1y5F4)

Phá bỏ blockchain và shitcoin và Phá bỏ những hiểu lầm và quan niệm sai lầm về việc lãng phí năng lượng của Bitcoin, và việc sử dụng cho mục đích tội phạm

## Vận Hành Bitcoin
<chapterId>5f638ec9-a6c1-5716-b27f-d837ab896eb1</chapterId>

### Cài Đặt Bitcoin Core

![Video](https://youtu.be/fIUU2sRCEj0)

Trong bài giảng đầu tiên của mô-đun thứ 4, chúng tôi đã khám phá kiến trúc của Bitcoin và cài đặt một nút Bitcoin Core

### Cài Đặt C-lightning

![video](https://youtu.be/zrB1Kc4BqvY)

Trong bài giảng thứ hai, chúng tôi đã đi sâu vào quá trình cài đặt c-lightning

### Bảo Mật và Thiết Bị Phần Cứng

![video](https://youtu.be/oVaI9WuLkgk)

Trong bài giảng thứ ba, chúng tôi đã đề cập đến các chủ đề liên quan đến bảo mật, thiết bị phần cứng, và cấu hình của Specter

## Cải Thiện Bitcoin
<chapterId>4fdd032f-2b05-5f24-a094-297d64f939de</chapterId>

### Vấn Đề Mở trong Hệ Sinh Thái Bitcoin

![video](https://youtu.be/Vlm2ZdxcidA)
Các bạn ơi, đây là link cho bài giảng cuối cùng của giai đoạn chuẩn bị về các vấn đề của Bitcoin và các giải pháp tiềm năng

# Cơ Bản về Bitcoin
<partId>6c0a3691-3ce4-5309-8ad7-e16e4b63c734</partId>

## Tư Duy Bảo Mật trong Bitcoin
<chapterId>0b97af0c-015a-54e3-a7f0-0f62ceb96c07</chapterId>

![Video](https://youtu.be/2f_rK74MB3U)

Peter Todd đi sâu vào các vấn đề bảo mật đặc thù của Bitcoin, dạy các nhà phát triển cách áp dụng tư duy bảo mật từ đầu. Bài giảng nhằm mục đích xây dựng một nền tảng vững chắc trong việc nhận diện và giảm thiểu các mối đe dọa tiềm tàng trong phát triển Bitcoin dựa trên bài tập thực hành giải thích Mô Hình Đe Dọa của phần mềm dùng để đánh dấu thời gian cho bầu cử.

## Phần Mềm Tự Do và Mã Nguồn Mở (FLOSS) trong Bitcoin
<chapterId>2c59d609-f1ef-53f4-9575-df62e4d066e9</chapterId>

![Video](https://youtu.be/ln-FYziKqNY)

Việc sử dụng Phần Mềm Tự Do và Mã Nguồn Mở (FLOSS) là rất quan trọng trong hệ sinh thái Bitcoin. Peter Todd khám phá tầm quan trọng của FLOSS đối với Bitcoin, tìm hiểu lịch sử của FLOSS và xem xét cách Github cho phép chúng ta cùng nhau xây dựng phần mềm mã nguồn mở như Bitcoin.

## Mật Mã học trong Bitcoin
<chapterId>71867dd2-912c-55ad-b59c-9dbca8a39469</chapterId>

![Video](https://youtu.be/QcK-Cl8B9QU)

Adam Gibson đưa người tham gia qua các nền tảng mật mã học của Bitcoin từ góc độ toán học. Phiên bản này bao gồm các chức năng mật mã học thiết yếu có mặt trong Bitcoin, như hash và bảo mật của chúng, cây merkle, giao thức danh tính và chữ ký, log rời rạc và đường cong elliptic.

## Mô Hình Quản Trị của Bitcoin
<chapterId>a30ec3e7-b290-5145-a9a9-042224ab20d2</chapterId>

![Video](https://youtu.be/g_BcT5YkZUQ)

Peter Todd thảo luận về mô hình quản trị của Bitcoin, cung cấp cái nhìn sâu sắc về cách các quyết định được đưa ra trong cộng đồng Bitcoin và cách tiếp cận phân quyền này ảnh hưởng đến sự phát triển và ổn định của giao thức. Đáng chú ý, ông khám phá cách các loại thay đổi có thể dẫn đến Soft hoặc Hard Forks, sự khác biệt trong quản trị giữa thay đổi chính sách và quy tắc đồng thuận, và trò chơi chính trị của sự thay đổi trong Bitcoin.

# Các Khái Niệm Tầng Một
<partId>5300855f-e5e4-5bca-9afe-2397f7c76260</partId>

## Các Thành Phần Nút trong Bitcoin
<chapterId>75ea1d88-ee6f-5f98-af90-e4758c55e606</chapterId>

![Video](https://youtu.be/hGS8Cuj5Zb4)
Adam Gibson phân tích các thành phần khác nhau của một nút Bitcoin. Chương này tập trung vào vai trò của mỗi thành phần trong việc duy trì chức năng và tính toàn vẹn của mạng. Đặc biệt, ông tập trung vào lý do tại sao chúng ta nên chạy một nút bitcoin, nút bitcoin làm gì, và các thành phần khác nhau của một nút bitcoin hoạt động như thế nào.

## Cấu Trúc Dữ Liệu của Bitcoin
<chapterId>5ed314b1-8293-567d-bf03-730e8c9c774b</chapterId>

![video](https://youtu.be/okvV9hqDOtM)

Alekos Filini trình bày cái nhìn sâu sắc về cấu trúc dữ liệu của Bitcoin. Điều này bao gồm tổ chức dữ liệu trong blockchain và cách nó tạo điều kiện cho sự vững chắc và hiệu quả của mạng.

## Bitcoin L1 Software Stack
<chapterId>96d64781-fc27-5209-88d8-2acf00d05ea8</chapterId>

![Video](https://youtu.be/xOdz9GEiShM)

Daniela Brozzoni cung cấp cái nhìn tổng quan về Bitcoin Layer 1 software stack, giải thích các lớp tạo nên nền tảng của giao thức Bitcoin (tức là nút Bitcoin và ví Bitcoin) và cách xây dựng phần mềm Bitcoin với giới thiệu về thư viện Bitcoin và một cái nhìn sâu về Bitcoin Development Kit (BDK).

# Lightning Network
<partId>d7ac2ad7-a4b3-564f-8a8d-cfec5297b3a5</partId>

## Lịch Sử của Payment Channels
<chapterId>a0b11c6e-c0ff-5e65-b809-b2ab9a2fc37b</chapterId>

![Video](https://youtu.be/VtpbCspK5T4)

Gabriel Comte cung cấp một góc nhìn lịch sử về sự phát triển của payment channels, là cơ sở của Lightning Network. Chương này khám phá sự tiến hóa của payment channels và tầm quan trọng của chúng trong việc mở rộng giao dịch Bitcoin, từ payment channels của Satoshi đến giải pháp payment channel hai chiều như Duplex Micropayment Channels hoặc Lightning payment channels.

## Lịch Sử của Atomic Routing
<chapterId>28be7b31-e6b2-5eea-a5ed-62ce0a154b6e</chapterId>

![Video](https://youtu.be/5OUgGHH6jPY)

Gabriel Comte kể lại lịch sử của atomic routing, chi tiết về một số kỹ thuật đã là nền tảng của lớp định tuyến của lightning network như mô hình Hub-and-Spokes, mô hình Ripple và Hashed TimeLocked Contracts (HTLCs). Lịch sử này đã rất quan trọng trong việc kích hoạt giao dịch an toàn, không cần tin cậy trên Lightning Network.

## Đánh Giá BOLT
<chapterId>ba4b09ae-81de-53f2-8c15-316f037aaea9</chapterId>

![Video](https://youtu.be/1aIuKBkPlkg)

asi0 đánh giá BOLT, cơ sở của Lightning Technology, giải thích các thông số kỹ thuật mà bất kỳ Lightning Network nào cũng phải tuân thủ. Đây sẽ là cái nhìn sâu rộng đầu tiên vào các lớp khác nhau của Lightning Network.

## Các LN Clients Chính
<chapterId>a2ad8db4-aea2-5231-927c-616c53db31bf</chapterId>

![Video](https://youtu.be/a0Q_5dzpqKw)

asi0 giới thiệu các Lightning Network (LN) clients chính, cung cấp phân tích về các tính năng, điểm mạnh dựa trên ma trận 2x2 đánh giá mức độ quản lý quyền sở hữu và quản lý thanh khoản mà người dùng có với LN clients.

# Thách Thức của LN
<partId>ca58c9d7-ba7e-5392-8488-6a21a9850e6a</partId>

## Thách Thức Thực Tế đối với LN
<chapterId>014c7c40-aef7-58ac-b51f-33784463f482</chapterId>

(video sẽ sớm được cung cấp)

asi0 đề cập đến những thách thức thực tế khi làm việc với Lightning Network. Điều này bao gồm thảo luận về các hạn chế hiện tại và những nỗ lực đang diễn ra để vượt qua chúng dựa trên 4 thách thức chính (quản lý thanh khoản, trừu tượng hóa L1/L2, nhận offline và quản lý sao lưu) được khám phá từ quan điểm của người dùng và từ quan điểm của nhà phát triển

## Sự Tiến Hóa Tương Lai của LN
<chapterId>c06763dd-bb26-5fec-8ac4-3e446e9517cd</chapterId>

![Video](https://youtu.be/VXMON_nD650)

Gabriel Comte suy đoán về sự tiến hóa tương lai của Lightning Network, xem xét các phát triển tiềm năng - như dual-funded channels, eltoo, BOLT 12, PTLCs, Watchtowers và tiêu chuẩn LSP - và cách chúng có thể biến đổi cảnh quan giao dịch Bitcoin.

## Các Giao Thức trên LN
<chapterId>f4d147bb-f146-5b36-a994-b9b70da83744</chapterId>

![Video](https://youtu.be/KqBfPaXqU2U)

Alekos Filini xem xét các giao thức được xây dựng trên Lightning Network, giải thích cách chúng đóng góp vào khả năng mở rộng và chức năng của Bitcoin.

# Phần Thưởng
<partId>4c5c74d7-40a9-5292-9b82-e3f3d79875e1</partId>
## Cơ Bản về Đào Bitcoin
<chapterId>a4eacfc3-7b37-5fa3-abd1-b1fc48b645f0</chapterId>
![Video](https://youtu.be/W3Ra0cdG02I)

Ajelex tập trung vào khía cạnh kinh doanh của việc đào Bitcoin, xem xét các chiến lược để duy trì lợi nhuận trong một thị trường cạnh tranh. Cuộc thảo luận bao gồm phân tích về chi phí hoạt động, các biện pháp hiệu quả và kinh tế học điều khiển ngành công nghiệp đào mỏ.

## Hiểu về Joinmarket
<chapterId>f109f64f-9b73-5fbf-8870-5d34d5b69df8</chapterId>

![Video](https://youtu.be/VFjccozVwc8)

Adam Gibson cung cấp cái nhìn sâu sắc về Joinmarket, chi tiết về cách thực hiện CoinJoin này tăng cường quyền riêng tư và khả năng thay thế của Bitcoin. Ông thảo luận về cách Joinmarket tạo điều kiện cho các giao dịch hợp tác, không cần tin cậy và ẩn danh trong hệ sinh thái Bitcoin. Sau đó, trong phần thứ hai, ông hướng dẫn cách chạy Joinmarket trên Signet.

## Hackathon Năm Đầu Tiên của Cubo+
<chapterId>3faf7daa-ea42-5b68-bcaf-04b70b2e02dd</chapterId>

### Nhóm 1 Hackathon - Di Sản của Satoshi

![Video](https://youtu.be/NiaahH57N1w)

Nhóm Di Sản của Satoshi trình bày công việc của họ về việc xây dựng một trang thương mại điện tử Lightning với Shopify, React JS và Hydrogen cùng cổng thanh toán IBEX.

### Nhóm 2 Hackathon - Honey Badger

![Video](https://youtu.be/dds0-SV8ltE)

Nhóm Honey Badger trình bày giải pháp của họ cho một blog với Micropayments được hỗ trợ bởi Lightning thông qua việc sử dụng LnBits và Next.js, Node.js và Hydrogen.

### Nhóm 3 Hackathon

![Video](https://youtu.be/2YjrrDMGU9c)

Nhóm thứ ba trình bày một Bảng Điều Khiển Node Mạng Lightning thông qua một API tùy chỉnh, LND, vue.js, node.js, Bootstrap.

### Nhóm 4 Hackathon - Học Bổng Satoshi

![Video](https://youtu.be/mxLKiHa0mes#)

Nhóm Học Bổng của Satoshi trình bày một ứng dụng trò chơi LN sử dụng LnBits và MongoDB, Poetry, Node.js.

### Nhóm 5 Hackathon - Lighting Walker

![Video](https://youtu.be/IiY5PmkGNVo)

Nhóm Lightning Walker trình bày giải pháp của họ cho Dịch Vụ Chuyển Tiền sử dụng MySQL, JavaScript và API của ZDB.



## Đánh giá khóa học
<chapterId>7f4f46e2-de71-5387-8609-9785fb9e5946</chapterId>
<isCourseReview>true</isCourseReview>

## Lời Cảm Ơn
<chapterId>33cb95cf-91d1-555b-a33b-0e3bd6745c33</chapterId>

Chúng tôi muốn ghi nhận sự đóng góp của các giáo viên của chúng tôi:

- Peter Todd
- Adam Gibson
- Alekos Filini
- Daniela Brozzoni
- Ajelex
- asi0
- Gabriel Comte

Chuyên môn của họ đã vô cùng quý báu cho sự thành công của khóa học này. Đây đã là khóa học đầu tiên dựa trên ấn bản đầu tiên của sáng kiến Cubo+, được tổ chức vào tháng 7 năm 2023. Cảm ơn tất cả các thành viên và giáo viên đã tham gia vào hành trình giáo dục tiên phong này. Điều này đánh dấu sự bắt đầu của những gì chúng tôi hy vọng sẽ là một hành trình dài và quảng đại vào thế giới phát triển Bitcoin. Là lớp đầu tiên, sự tham gia của các bạn đã thiết lập tiêu chuẩn cho các lớp học tương lai.
Hãy tiếp tục khám phá, học hỏi và đóng góp cho hệ sinh thái Bitcoin. Kiến thức thu được ở đây chỉ là điểm khởi đầu. Tiếp tục đào sâu vào hố thỏ, và bạn sẽ khám phá ra một thế giới cơ hội ngày càng mở rộng.
