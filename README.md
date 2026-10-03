# BÀI LAB DAY 17: DISCOVERING AND VALIDATING PAIN POINTS
*(Khám phá và kiểm chứng các khó khăn của người dùng)*

> **Học viên**: Nguyễn Khánh Duy  
> **Mã học viên (MHV)**: 02403  
> **Tên thư mục repo (kho lưu trữ)**: `Track1_Day17_02403_NguyenKhanhDuy`  
> **Ngày thực hiện**: 03/10/2026

---

## PHẦN 1: THÔNG TIN CÁ NHÂN VÀ NHÓM

* **Mã học viên (MHV)**: 02403
* **Họ và tên**: Nguyễn Khánh Duy
* **Tên nhóm**: [Tên nhóm của bạn - ví dụ: Nhóm 03 / Team Innovation]
* **Danh sách thành viên trong nhóm**:
  1. Nguyễn Khánh Duy (MHV: 02403)
  2. [Họ và tên thành viên 2 - MHV]
  3. [Họ và tên thành viên 3 - MHV]
* **Case (Tình huống bài toán) đã chọn**: **Case B — AI Notes: Personal Learning Notes** (Ghi chú học tập cá nhân bằng trí tuệ nhân tạo).

---

## PHẦN 2: PROBLEM HYPOTHESIS BRIEF (BẢN TÓM TẮT GIẢ THUYẾT VẤN ĐỀ)

### 1. Solution (Giải pháp) — Gỡ giải pháp khỏi hình thức cụ thể
* **Solution directive (Chỉ thị giải pháp nguyên văn)**:
  > *"Trong khi học, học viên có thể highlight (tô sáng) một đoạn nội dung, đánh dấu 'Chưa hiểu', hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu."*
* **Capability trung tính (Năng lực đáp ứng cốt lõi)**:
  > Khả năng tự động tổng hợp và cấu trúc hóa các dấu vết chú ý rời rạc của người học sau buổi học thành một tài liệu ôn tập hệ thống, giúp người học không phải tự gõ chép lại thủ công.

### 2. Change (Sự thay đổi) — Chuỗi thay đổi được kỳ vọng
* **Chuỗi mắt xích kỳ vọng**:
  $$\text{Dấu vết chú ý trong lúc học} \rightarrow \text{Bản ghi chú tổng hợp tự động} \rightarrow \text{Người học thực sự mở ra đọc lại} \rightarrow \text{Lấp lỗ hổng kiến thức} \rightarrow \text{Hiểu sâu và làm được bài tập}$$
* **3 Thay đổi được kỳ vọng**:
  1. Giảm thiểu ít nhất 70% thời gian người học phải tự sắp xếp và gõ lại ghi chú sau buổi học.
  2. Tăng tỷ lệ người học thực sự mở lại tài liệu ghi chú trong vòng 3 ngày sau buổi học.
  3. Người học chủ động ôn tập trúng các điểm nghẽn kiến thức cá nhân thay vì học lại tràn lan toàn bộ bài giảng.

### 3. Actor (Đối tượng liên quan) — Xác định các nhóm người
| Actor (Nhóm người) | Họ đang làm gì? | Pain (Khó khăn) hoặc hậu quả có thể có | Họ hưởng lợi thế nào? |
| :--- | :--- | :--- | :--- |
| **Learner (Học viên đi làm bận rộn)** | Vừa nghe giảng vừa chụp ảnh màn hình hoặc gõ nhanh vài dòng rời rạc. | Ghi chú nằm rải rác, không liên kết ngữ cảnh nên lười xem lại; lúc làm bài/thi thì quên bài. | Có ngay tài liệu ôn tập tinh gọn, đúng trọng tâm mà không tốn công chép lại. |
| **Instructor / TA (Giảng viên / Trợ giảng)** | Giảng bài và hỗ trợ giải đáp thắc mắc. | Tốn nhiều thời gian trả lời lại các câu hỏi nền tảng do học viên ghi chép sót. | Học viên tự nắm vững bài tốt hơn, câu hỏi hỏi giảng viên có chất lượng hơn. |

* **Actor (Đối tượng) nhóm chọn điều tra trước**: **Learner (Học viên đi làm bận rộn)**.
* **Lý do chọn**: Đây là đối tượng trực tiếp trải nghiệm khó khăn và gánh chịu hậu quả lớn nhất về kết quả học tập nếu thiếu tài liệu ôn tập hiệu quả.

### 4. Situation & Job (Bối cảnh và công việc cần làm)
* **Mô tả Situation & Job**:
  > Khi **hoàn thành một bài học trực tuyến có nhiều khái niệm phức tạp** (*situation* - bối cảnh), **học viên bận rộn** (*actor* - đối tượng) đang cố **lưu lại các điểm cốt lõi và các chỗ bản thân chưa hiểu** (*job* - việc cần làm) bằng cách **chụp ảnh màn hình điện thoại/máy tính hoặc ghi chú tạm vài gạch đầu dòng vào sổ tay / ứng dụng ghi chú** (*cách làm hiện tại*).
* **JTBD Hypothesis (Giả thuyết việc cốt lõi cần hoàn thành)**:
  > Khi **kết thúc một bài học có dung lượng kiến thức lớn**, tôi muốn **nhanh chóng có một bản tổng hợp rõ ràng về các điểm mình còn vướng mắc**, để có thể **ôn tập trọng tâm trong thời gian ngắn nhất mà không phải tốn hàng giờ xem lại toàn bộ video bài giảng**.

### 5. Pain (Khó khăn) — Hai cách giải thích cạnh tranh
* **Pain Hypothesis A (Giả thuyết A - Trọng tâm ở khâu lưu trữ & ôn tập sau buổi học)**:
  > Khi hoàn thành bài học, người học gặp khó khăn trong việc ôn tập vì **các ghi chú và ảnh chụp màn hình nằm rải rác, thiếu ngữ cảnh liên kết** (*barrier* - rào cản), dẫn đến **họ lười mở lại xem và quên sạch kiến thức chỉ sau vài ngày** (*consequence* - hậu quả).
* **Pain Hypothesis B (Giả thuyết B - Trọng tâm ở khâu tiếp thu trong buổi học)**:
  > Trong khi nghe giảng, người học gặp khó khăn trong việc tiếp thu vì **việc vừa phải hiểu bài vừa phải cúi xuống chép bài gây quá tải nhận thức** (*barrier* - rào cản), dẫn đến **họ bị lỡ mất những giải thích quan trọng tiếp theo của giảng viên** (*consequence* - hậu quả).
* **Giả thuyết nhóm chọn điều tra trước**: **Pain Hypothesis A**.
* **Lý do chọn**: Vì tính năng *AI Notes* được kích hoạt chủ yếu sau khi bài học kết thúc (khi người học cần tổng hợp để ôn tập), giải quyết trực tiếp rào cản về việc kết nối các ghi chú rời rạc thành kiến thức hệ thống.

### 6. Evidence Map (Bản đồ bằng chứng) — Xác định điều cần tìm trước khi viết câu hỏi
| Yếu tố cần kiểm tra | Evidence (Bằng chứng) làm nhóm tin hơn | Evidence (Bằng chứng) khiến nhóm nghi ngờ / bác bỏ |
| :--- | :--- | :--- |
| **Situation có thật** | Người được hỏi kể vanh vách một bài học gần đây mà họ đã từng chụp màn hình hoặc ghi chú. | Tuần qua người học chỉ nghe thụ động, không hề ghi chép hay lưu lại bất kỳ thứ gì. |
| **Pain có ý nghĩa** | Kể lại sự bất lực, bực bội khi mở lại ghi chú cũ mà không hiểu mình từng viết tắt điều gì. | Cảm thấy cách ghi chép hiện tại rất tiện, dễ hiểu và không có bất kỳ trở ngại nào. |
| **Workaround (Cách tạm bợ) tồn tại** | Đã từng thử dùng Notion, mở song song 2 màn hình, hoặc gõ lại vào Word để lưu trữ. | Chưa bao giờ tìm cách gom ghi chép, chấp nhận quên và không bận tâm. |
| **Consequence (Hậu quả) tồn tại** | Bị điểm kém ở bài kiểm tra, hoặc lúc làm bài tập thực hành phải tốn gấp đôi thời gian mò lại bài giảng. | Không để lại hậu quả gì; bài tập vẫn làm tốt và điểm thi vẫn cao dù không đọc lại ghi chú. |
| **Pattern (Quy luật) có lặp lại** | Tình trạng chụp màn hình rồi bỏ xó đã diễn ra lặp đi lặp lại ở nhiều khóa học khác nhau. | Đây chỉ là trường hợp cá biệt ở một môn học duy nhất, các môn khác không bị. |

### 7. Chốt Problem Hypothesis & Solution Parking Lot
* **Problem Hypothesis (Giả thuyết vấn đề) chốt mang sang Chặng 2**:
  > *"Người học trực tuyến có thói quen ghi chú ngắn và chụp ảnh màn hình trong lúc học, nhưng họ hiếm khi mở ra xem lại vì các mảnh thông tin này bị rời rạc và thiếu ngữ cảnh bài giảng, dẫn đến việc họ phải tốn rất nhiều thời gian học lại từ đầu khi cần ôn tập."*
* **Điều gì phải đúng để giả thuyết đứng vững**: Người học có mở lại ghi chép nhưng thấy rối rắm, mất phương hướng và thực tế đã chịu hậu quả vì việc quên kiến thức.
* **Điều gì khiến nhóm hủy bỏ giả thuyết**: Người học chỉ cần nghe giảng là nhớ, hoặc việc ghi chép vài từ khóa đơn giản trên sổ tay đã hoàn toàn đủ cho nhu cầu của họ.
* **Solution Parking Lot (5 Hướng giải quyết tạm gác lại, có ít nhất 1 hướng KHÔNG dùng AI)**:
  1. *Hướng 1*: **AI** tự động liên kết các đoạn tô sáng và câu hỏi với mốc thời gian trong video để tạo bản tóm tắt bài giảng (Có dùng AI).
  2. *Hướng 2*: Cung cấp mẫu *template* (khung định dạng sẵn) ghi chú chia cột theo phương pháp Cornell để người học tự điền trong lúc học (**KHÔNG dùng AI**).
  3. *Hướng 3*: Cuối bài học, giảng viên đính kèm một trang tóm tắt kiến thức cốt lõi (*cheat sheet*) để người học tải về đối chiếu (**KHÔNG dùng AI**).
  4. *Hướng 4*: **AI** tự động tạo 3 câu trắc nghiệm nhanh dựa trên các điểm người học đánh dấu *"Chưa hiểu"* để họ tự kiểm tra độ nhớ (Có dùng AI).
  5. *Hướng 5*: Hệ thống tự động lưu các ảnh chụp màn hình vào một thư mục riêng theo từng chương học (**KHÔNG dùng AI**).

---

## PHẦN 3: CONVERSATION GUIDE (BẢN HƯỚNG DẪN PHỎNG VẤN PHIÊN BẢN CUỐI)

> **Phương pháp áp dụng**: **The Mom Test** (nghệ thuật đặt câu hỏi khai thác sự thật quá khứ, tuyệt đối không giới thiệu tính năng giải pháp).

### 1. Tiêu chí tuyển người & Recruitment Check (Sàng lọc nhanh)
* **Tiêu chí**: Chúng tôi cần nói chuyện với người học trực tuyến **đã từng ghi chú, tô sáng hoặc chụp màn hình lưu tài liệu học tập trong vòng 7 ngày gần đây**.
* **Câu hỏi sàng lọc (Recruitment check)**:
  > *"Trong vòng 7 ngày qua, bạn có tham gia buổi học trực tuyến hoặc xem video bài giảng nào mà bạn có ghi chép lại hoặc chụp màn hình bài giảng không?"*
  *(Nếu có $\rightarrow$ Phù hợp để phỏng vấn; Nếu không $\rightarrow$ Báo giảng viên để ghép với người khác).*

### 2. Lời mở đầu (Opening)
> *"Chào bạn, cảm ơn bạn đã dành thời gian trò chuyện cùng mình. Hôm nay mình đang làm một nghiên cứu nhỏ về thói quen học tập và cách mọi người quản lý thông tin trong các khóa học trực tuyến. Buổi nói chuyện chỉ là để lắng nghe trải nghiệm thực tế của bạn, hoàn toàn không có câu trả lời đúng hay sai. Mình xin phép ghi âm lại cuộc trò chuyện này để phục vụ ghi chép bài học và cam kết bảo mật, không chia sẻ công khai nhé."*

### 3. Story Opener (Câu hỏi mở màn câu chuyện thực tế)
> *"Bạn có thể kể cho mình nghe về lần gần nhất bạn tham gia một buổi học trực tuyến mà bạn cảm thấy có nhiều kiến thức phức tạp cần phải ghi lại không?"*

### 4. Big 3 Questions (3 Câu hỏi cốt lõi tương ứng 3 điều cần học)
| Điều cần học | Câu hỏi phỏng vấn sẽ dùng |
| :--- | :--- |
| **1. Hành vi ghi chép thực tế lúc học** | *"Lúc nghe giảng đến đoạn khó hiểu đó, bạn đã thực sự làm những thao tác gì để lưu lại nội dung?"* |
| **2. Thực tế khâu xem lại ghi chú (Câu hỏi đáng sợ)** | *"Sau khi buổi học đó kết thúc, bạn có mở lại những phần mình đã ghi chép hay ảnh chụp màn hình đó không? Cụ thể bạn đã xem lại nó vào lúc nào?"* |
| **3. Khó khăn, cách giải quyết tạm bợ và hậu quả** | *"Khi mở lại để xem hoặc lúc làm bài tập, điều gì khiến bạn gặp khó khăn nhất? Bạn đã giải quyết lúc đó ra sao và mất bao nhiêu thời gian?"* |

### 5. Probe Bank (Ngân hàng câu hỏi đào sâu)
* *"Lúc đó chuyện gì xảy ra tiếp theo?"*
* *"Bạn đã xử lý việc đó như thế nào?"*
* *"Vì sao bạn lại chọn làm theo cách đó mà không làm cách khác?"*
* *"Phần nào trong quá trình đó làm bạn thấy tốn thời gian hoặc bực mình nhất?"*
* *"Việc đó dẫn đến hậu quả gì cho bài tập hoặc kỳ thi sau đó của bạn không?"*
* *"Lần gần nhất trước đó mà bạn gặp tình trạng tương tự là khi nào?"*

### 6. Ba phản xạ xử lý tình huống lệch hướng dữ liệu
* **Khi người dùng đưa ra lời khen**: Áp dụng **Deflect** (đánh lạc hướng khéo léo) $\rightarrow$ Cảm ơn ngắn gọn và quay lại ngay câu chuyện hành vi: *"Cảm ơn bạn! Nhưng quay lại lần học gần nhất tối hôm trước, lúc đó bạn đã thao tác cụ thể thế nào?"*
* **Khi người dùng nói chung chung hoặc hứa hẹn tương lai**: Áp dụng **Anchor** (neo giữ vào mốc thời gian) $\rightarrow$ *"Đó là dự định, còn lần gần nhất chuyện đó xảy ra trên thực tế là vào ngày nào?"*
* **Khi người dùng đòi hỏi tính năng mới**: Áp dụng **Dig** (đào sâu vào bản chất) $\rightarrow$ *"Tính năng đó sẽ giúp bạn giải quyết được việc cụ thể gì? Hiện tại chưa có nó thì bạn đang tự xoay xở bằng cách nào?"*

### 7. Điểm cải tiến của Guide sau buổi luyện tập thực tế
* Bỏ câu hỏi: *"Bạn có thường xuyên xem lại ghi chú không?"* (vì câu này mang tính suy đoán chung chung) $\rightarrow$ Đổi thành câu hỏi neo mốc: *"Lần gần nhất bạn mở lại ghi chú bài học là khi nào?"*.
* Bổ sung thêm câu hỏi đào sâu về **công cụ thay thế tạm thời** (*workaround*): *"Lúc mở ghi chú ra thấy thiếu ý, bạn đã tra cứu lại bằng cách nào và mất bao nhiêu phút?"*.

---

## PHẦN 4: PRACTICE REFLECTION (ĐÚC KẾT KINH NGHIỆM SAU PHỎNG VẤN)

*(Dựa trên trải nghiệm thực tế 15 phút làm người phỏng vấn của học viên Nguyễn Khánh Duy)*

### 1. Câu hỏi nào đã giúp người dùng cởi mở chia sẻ một tình huống cụ thể?
> Câu hỏi: *"Kể cho mình nghe về lần gần nhất bạn tham gia một buổi học trực tuyến có nhiều công thức phức tạp và bạn cần lưu lại?"* đã giúp người được phỏng vấn lập tức nhớ lại phiên học cụ thể vào tối thứ Tư. Nhờ neo vào sự kiện quá khứ cụ thể, họ bắt đầu mô tả chi tiết từ tư thế ngồi học, việc mở hai màn hình song song, đến việc chụp hơn chục bức ảnh màn hình rồi lưu vào ứng dụng ghi chú.

### 2. Điểm nào bản thân cần làm tốt hơn ở lần phỏng vấn thật tiếp theo?
> Bản thân nhận thấy trong 5 phút đầu vẫn còn phản xạ nói quá nhiều và suýt nữa đã gợi ý giải pháp khi người được phỏng vấn than phiền về việc ảnh chụp màn hình bị lộn xộn. Ở lần phỏng vấn thật ngoài thực địa, mình cần rèn luyện phản xạ im lặng lắng nghe nhiều hơn, tuyệt đối không ngắt lời người kể và kiên nhẫn dùng các câu hỏi ngắn trong *Probe Bank* để họ tự nói ra hết hành vi của mình.

### 3. Sau khi luyện tập, nhóm đã sửa đổi Conversation Guide ở đâu và vì sao?
> Nhóm đã quyết định sửa đổi 2 điểm quan trọng:
> 1. Thêm câu hỏi bắt buộc về thời gian hao phí: *"Bạn mất bao nhiêu phút để tìm lại kiến thức khi ghi chú bị thiếu?"* để đo lường định lượng được mức độ nghiêm trọng của hậu quả (*consequence*).
> 2. Đưa phản xạ **Deflect** (né lời khen) vào vị trí dễ nhìn nhất trong tài liệu, vì trong lúc phỏng vấn thử, người trả lời rất hay khen ngợi *"ước gì có công cụ tự gom bài giúp mình"*, khiến người hỏi suýt nữa bị cuốn vào việc giới thiệu tính năng giải pháp.

---

## PHẦN 5: AI SUPPORT LOG (NHẬT KÝ SỬ DỤNG TRÍ TUỆ NHÂN TẠO)

* **Những phần việc AI đã hỗ trợ**:
  1. Hỗ trợ bóc tách và phân tích các khung hình từ video đề bài của trường để trích xuất đầy đủ 4 chặng và 6 luật của bài lab.
  2. Gợi ý cấu trúc chuỗi mắt xích tư duy từ *Solution* về *Evidence Map* cho Case B.
  3. Đề xuất các câu hỏi phản xạ chuẩn theo phương pháp *The Mom Test*.
* **Những điểm AI làm sai hoặc còn hời hợt**:
  * Ban đầu, khi được yêu cầu gợi ý câu hỏi phỏng vấn, **AI** đưa ra các câu hỏi dạng mời mọc đánh giá giải pháp như: *"Bạn có thích một công cụ tự động tổng hợp bài học bằng AI không?"* hoặc *"Bạn có nghĩ tính năng này sẽ tiết kiệm thời gian không?"*. Những câu hỏi này vi phạm nghiêm trọng Luật số 1 và Luật số 2 của bài lab.
  * Các câu giả thuyết ban đầu của **AI** còn chung chung, mang nặng tính mô tả giao diện thay vì phân tích rào cản hành vi của người học.
* **Cách học viên đã tự tay can thiệp và sửa đổi**:
  * Xóa bỏ hoàn toàn các câu hỏi xin ý kiến tương lai, viết lại thành các câu hỏi tập trung vào hành vi và mốc thời gian quá khứ (*"Lần gần nhất...", "Bạn đã làm gì..."*).
  * Viết thêm 2 giả thuyết cạnh tranh (*Pain Hypothesis A* và *B*) với các rào cản (*barrier*) cụ thể để bảo đảm bài làm có thể bị bác bỏ nếu dữ liệu thực tế không ủng hộ.
  * Tự bổ sung các giải pháp không sử dụng công nghệ trong *Solution Parking Lot* (như phương pháp ghi chép Cornell và tài liệu tóm tắt một trang của giảng viên) để bảo đảm tư duy không bị phụ thuộc vào AI.
