## Quy trình phần mềm
*  Tổng quan 
*  Vì sao cần phải xây dựng quy trình?
*  Quy trình cổ điển

---

### Tổng quan
- Giới thiệu một số quy trình phát triển phần mềm 
- Các ưu và nhược điểm của mỗi phương pháp,
- Cách chọn quy trình phù hợp theo tính chất của dự án và đội phát triển

---
### Mục tiêu
1. Tìm hiểu về các bên liên quan và các loại tài liệu họ sử dụng để liên lạc trong quá trình phát triển phần mềm.
2. Tìm hiểu về quy trình phần mềm truyền thống, bao gồm cả phương thức thác nước và xoắn ốc.
3. Tìm hiểu về quy trình phầm mềm linh hoạt hiện đại, lập trình cực hạn, hướng phát triển thử nghiệm, và phương pháp scrum.

--- 

### Quy trình 
- Xây dựng quy trình chính là trả lời các câu hỏi:
    - Chúng ta đang cố gắng xây dựng cái gì?
    - Ai là người tham gia vào toàn bộ quá trình phát triển phần mềm?
    - Các nhóm sẽ phối hợp với nhau như thế nào? 
    - Họ sẽ thực sự xây dựng hệ thống như thế nào?
    - Khi nào tất cả sẽ được hoàn thành?

---
### Các bên liên quan
Các bên liên quan phải giao tiếp hiệu quả và có sự đồng thuận về cách xây dựng hệ thống phần mềm.

- Nhà phát triển (Developers):
    - Biến ý tưởng, tài liệu thành sản phẩm 
- Đội kiểm định chất lượng (QA team): 
    - Xác nhận sản phẩm hoạt động, đảm bảo rằng sản phẩm có thể chạy trong thực tế và có thể triển khai
- Quản lý (Management): 
    - Tham gia để giúp phối hợp giữa các nhóm khác nhau.
- Đội tiếp thị và bán hàng  (Sales and marketing team):
    - Bán sản phẩm cho khách hàng
- Người dùng (Users): 
    - Người sử dụng sản phẩm. Chúng ta hy vọng họ sẽ gửi lại những phản hồi về sản phẩm.
- Đội hỗ trợ (Support team):
    - Đội hỗ trợ người dùng liên tục, cung cấp phản hồi của người dùng cho đội kỹ thuật.

---
### Tài liệu

- Specification: tài liệu đặc tả hệ thống
- Development: tài liệu về cách phối hợp trong phát triển
- Validation: tài liệu xác nhận
- Deployment / Evolution : Các tài liệu triển khai và nâng cấp.

--- 

### Specification (Tài liệu đặc tả)
- Đưa ra nhiệm vụ, mục tiêu kinh doanh, và yêu cầu bản thân.
- Chủ yếu dành cho bên quản lý, người dùng, bán hàng ( những bên xác định hệ thống cần chức năng gì ) 

--- 
### Development (Tài liệu phát triển):
- Kế hoạch kiến trúc hệ thống, kế hoạch thiết kế, kế hoạch thực hiện
- Chủ yếu dành cho bên quản lý, đội phát triển và đội kiểm định chất lượng

---

### Validation (Tài liệu xác nhận):
- Kế hoạch kiểm tra sản phẩm, đánh giá rủi ro
- Đặc biệt quan trọng cho đội kiểm định chất lượng
   
### Deployment / Evolution (Tài liệu triển khai và nâng cấp):
- Bao gồm kế hoạch phát triển và chiến lược bảo trì

---

### Tài liệu
- Tài liệu phần mềm giúp giảm rủi ro liên quan đến việc xây dựng các sản phẩm phần mềm
- Mọi người làm việc trên cùng một kế hoạch và cùng nắm rõ những gì đang và sẽ được xây dựng
    - Nếu chỉ nói miệng không có tài liệu sẽ rất khó giải quyết khi mâu thuẫn, không nhất quán xảy ra

---

## Quy trình cổ điển
- Thác nước và 
- Xoắn ốc

---
### Mô hình thác nước
* Đặc tả yêu cầu
* Thiết kế
* Cài đặt
* Tích hợp
* Bảo trì
---
### Mô hình thác nước
#### 1. Đặc tả yêu cầu:
- Xác định các đơn vị mà hệ thống phải cung cấp các ràng buộc trong quá trình vận hành và phát triển
- xác định mục tiêu đặt ra với hệ thống là gì qua việc bàn với khách hàng, sau đó tư liệu hóa các yêu cầu thu được trong tài liệu.

---
### Mô hình thác nước
#### 2. Thiết kế:
- Phân chia các yêu cầu cho hệ thống phần mềm, phần cứng, thiết lập nên các kiến trúc hệ thống phần mềm.
- Tiến hành thiết kế phần mềm bằng cách xây dựng và mô tả hệ thống phần mềm con cấu thành nên phầm mềm được xây dựng, và quan hệ giữa các hệ thống.

---
### Mô hình thác nước
#### 3. Cài đặt:
Chuyển bản thiết kế thành một tập hợp các chương trình hoặc các đơn vị chương trình.

---
### Mô hình thác nước
#### 4. Tích hợp:
Các đơn vị chương trình được tích hợp lại với nhau tạo thành hệ thống hoàn chỉnh.


---
### Mô hình thác nước
#### 5. Bảo trì:
Đưa phần mềm vao tiến hành sử dụng trong thực tế và tiến hành các sửa đổi cầ thiết nếu người dùng phát hiện ra khiếm khuyết.

---
### Mô hình thác nước
* Là mô hình cổ điển
* Phương pháp áp dụng một lần
* Điều khiển hiệu quả
* Phạm vi giới hạn của vòng lặp
* Vòng đời dài
---
### Mô hình thác nước
* Không thích hợp với các hệ thống không rõ ràng
* Trong mô hình thác nước, năm pha trên phải thực hiện một cách tuần tự, kết thúc pha trước rồi mới thực hiện pha tiếp theo.
* Mô hình này chỉ thích hợp khi yêu cầu đã đuợc làm rõ ràng và những thay đổi sẽ được giớ hạn một cách rõ ràng trong quá trình thiết kế.


---
### Mô hình thác nước
- Ưu điểm:
    * Phù hợp với các dự án nhỏ và có yêu cầu xác định.
    * Dễ phân công công việc.
    * kiến trúc ổn định.
- Nhược điểm:
    * Không phù hợp với dự án lớn.
    * Thời gian thực hiện lâu.

---

###  Phương pháp xoắn ốc
- Đưa ra thập niên 80 nhằm khắc phục một số nhược điểm của quy trình thác nước.
- Trong mô hình xoắn ốc, tạo ra sản phẩm nhiều lần, mỗi lần khách hàng sẽ xem và góp ý để phát triển tiếp.

--- 

###  Phương pháp xoắn ốc
- Các bước thực hiện:
 1. Lên kế hoạch: Xác định yêu cầu cho phiên bản, cho nguyên mẫu trong tương lai.
 2. Phân tích rủi ro: Tìm những rủi ro của trong phiên bản tới là gì?
 3. Xây dựng: Phát triển phần mềm và triển khai nó.
 4. Xác nhận: Kiểm tra với khách hàng để thu thập phản hồi làm cơ sở chỉnh sửa phát triển tiếp.

---

### Ưu nhược điểm
 - Ưu điểm: Giảm thiểu rủi ro bằng cách trao đổi với khách hàng sau mỗi phiên bản.

 - Nhược điểm: Chờ phản hồi của khách hàng có thể làm chậm quá trình phát triển phần mềm. 
    - Khách hàng nhiều khi không phản hồi được nhanh.

---

## Quy trình hiện đại
* Phương pháp linh hoạt (Agile Methods)
    * Lập trình cực đoan (XP)
    * Scrum

---

## Phương pháp Agile
- Xuất hiện đầu những năm 2000
- Tỏ ra hiệu quả, vượt trội so với các phương pháp phát triển truyền thống
- Cho phép người phát triển trở nên linh hoạt hơn và sớm hoàn thiện với tốc độ cao

--- 

### Tuyên ngôn Agile
Gồm 12 nguyên lý, nhưng chỉ có 4 nguyên lý trọng tâm:
- Vai trò cá nhân tương tác quan trọng hơn quy trình và công cụ
- Sản phẩm dùng được quan trọng hơn tài liệu đầy đủ
- Cộng tác với khách hàng quan trọng hơn các điều khoản hợp đồng
- Sẵn sàng thay đổi quan trọng hơn bám theo kế hoạch

---
### Ưu điểm của phương pháp Agile
- Ưu tiên thực hiện những việc thiết thực, mang lại hiệu quả trước
- Thường xuyên lấy phản hồi của khách hàng trong suốt quá trình phát triển
- Linh hoạt và sẵn sàng thay đổi vì tính chất của phần mềm thường thay đổi

---

### XP
- Là một trong những phương pháp tiên phong trong agile
- Cốt lõi là hệ thống luôn sẵn sàng triển khai ở mọi thời điểm
- Bắt đầu vào những việc nhỏ, hoàn thiện dần lên (bottom up)
    - Khác với phương pháp truyền thống là kế hoạch lớn và kế hoạch dài hạn (top down)

---

### 5 nguyên tắc chính của XP

- Giao tiếp: 
    - Khuyến khích các bên liên quan trao đổi với nhau lúc nào cũng được. 
- Đơn giản
    - Thực hiện giải pháp đơn giản nhất, khả thi nhất trước, không tính trước quá nhiều
- Phản hồi
    - Thường xuyên trao đổi với khách hàng
- Can đảm
    - Mạnh dạn làm và sai sẵn sàng bỏ đi nhưng qua đó đã rút ra được kinh nghiệm, bài học.
- Sự tôn trọng
    - Tôn trọng các ý kiến của các bên liên quan

---

### Scrum

- Scrum là phương pháp được biết đến rộng rãi trong họ phương pháp Agile
- Trong Scrum khái niệm product backlog - là danh sách theo thứ tự ưu tiên các tính năng, các công việc của dự án cần làm.
- Chia dự án thành các giai đoạn ngắn từ 1 đến 3 tuần.

---

### Đội phát triển

- Thường có 5 đến 7 người 
- Phối hợp với nhau một cách tích cực, chủ động

---
### Các khái niệm quan trọng trong Scrum

- Tồn đọng sản phẩm (Product backlog)
- Lập kế hoạch (planning)
- Tồn đọng sprint (sprint backlog)

---

### Tồn đọng sản phẩm

- Là tất cả các vấn đề cần giải quyết của toàn bộ dự án
- Được sắp xếp theo thứ tự ưu tiên

---

### Lập kế hoạch

- Cần chủ sản phẩm tham gia tích cực và đưa ra quyết định về sự thay đổi ưu tiên trong tồn đọng sản phẩm
- Phối hợp với đội phát triển, để hài hòa về mặt kỹ thuật cho các quyết định về ưu tiên. 

---

### SPRINT

- Là giai đoạn 'nước rút', diễn ra từ 1 - 3 tuần, 
- Nhằm thực hiện gọn một phần công việc của dự án, nhằm tạo ra một bản nâng cấp cho sản phẩm

---

#### Họp đứng
- Là cuộc họp nhanh, trong khoảng 15 phút, diễn ra hàng ngày
- Cả đội cập nhật tình hình cho lẫn nhau: hôm qua đã làm gì, hôm nay sẽ làm gì tiếp, có khó khăn gì
- Tuy nhiên không thảo luận về các giải pháp cho các khó khăn trong lúc họp, mà sẽ tìm giải pháp sau đó

---

#### Giai đoạn nghi thức

- Là giai đoạn mọi người nhìn lại sprint vừa thực hiện
- Có thể công bố những bổ sung, nâng cấp cho sản phẩm (nếu hoàn thành mục tiêu của sprint)
- Cũng là giai đoạn rút kinh nghiệm, chia sẻ kiến thức, kinh nghiệm, bài học cho nhau để cùng nâng cao trình độ, kinh nghiệm
