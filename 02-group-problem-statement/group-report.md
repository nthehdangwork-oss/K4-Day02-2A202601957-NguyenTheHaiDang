## Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1 | Đào Văn Đạt | 2A202601302 | Challenger : Phản biện các đề tài còn lại: học tập cá nhân hóa quá rộng, sức khỏe rủi ro cao, hộ kinh doanh TMĐT phụ thuộc chính sách, quản lý dự án có nhiều tool sẵn.   |
| 2 | Nguyễn Thị Kiều Trang | 2A202601961 | Note-taker / Artifact owner : Ghi lại các candidate ban đầu, bảng cluster, bảng shortlist, bảng score và lý do chọn đề tài trợ lý đề xuất lịch đăng ký học phần. |
| 3 | Trần Trọng Thịnh | 2A202601568 | Scoring & Decision owner : Dẫn nhóm chấm điểm và kết luận đề tài đăng ký học phần có actor rõ, workflow rõ, impact đo được, dễ làm MVP và so sánh được Rule / Workflow / Agent.  |
| 4 | Tống Tiến Mạnh | 2A202601614 | Cluster lead : Gom các ý tưởng thành nhóm: học tập/sinh viên, sức khỏe/an toàn, kinh doanh/vận hành, nông nghiệp. Từ đó thấy đề tài đăng ký học phần thuộc cluster học tập/sinh viên nhưng cụ thể hơn học tập cá nhân hóa. |
| 5 | Nguyễn Thế Hải Đăng | 2A202601957 |  Facilitator / Timekeeper : Giữ nhóm không đi thẳng vào giải pháp “làm AI xếp lịch”, mà quay lại hỏi actor là ai, workflow hiện tại là gì, bottleneck nằm ở đâu. |

---

# 02 — Group Problem Statement

## Đề tài nhóm chọn

**Trợ lý đề xuất lịch đăng ký học phần cho sinh viên có xét lịch trình cá nhân**

---

# Phase 3 — Group Convergence: Chọn 1 candidate problem

## 1. Danh sách candidate problems ban đầu

| # | Candidate problem | Actor | Vấn đề chính |
|---|---|---|---|
| 1 | Hệ thống hỗ trợ học tập cá nhân hóa | Người học | Người học mất thời gian tìm tài liệu, không có lộ trình rõ, khó biết mình yếu phần nào |
| 2 | Hệ thống theo dõi và chăm sóc sức khỏe cá nhân | Người bệnh, người cao tuổi | Quên uống thuốc, không theo dõi chỉ số sức khỏe đều, khó phát hiện bất thường sớm |
| 3 | Dự đoán nguy cơ thực phẩm không bán hết trước hạn | Quản lý siêu thị, cửa hàng tiện lợi | Biết ngày hết hạn nhưng khó biết sản phẩm có bán kịp trước hạn không |
| 4 | AI quản lý dự án, phân chia task và theo dõi tiến độ | Nhóm dự án, trưởng nhóm | Task phân tán, khó biết ai đang nghẽn, cập nhật tiến độ thủ công |
| 5 | Đề xuất lịch đăng ký học phần cho sinh viên | Sinh viên đại học | Sinh viên khó ghép môn học, lớp học phần và lịch cá nhân thành một lịch hợp lệ |
| 6 | AI hỗ trợ thủ tục hành chính và tính chi phí TMĐT | Hộ kinh doanh cá nhân | Khó hiểu thủ tục, thuế, phí sàn, vận chuyển, quảng cáo và lợi nhuận |
| 7 | Phát hiện sâu bệnh cây trồng qua ảnh | Nông dân | Khó phát hiện bệnh sớm, thiếu chuyên gia, dễ xử lý sai |
| 8 | Phân loại và ưu tiên yêu cầu khách hàng | Nhân viên CSKH | Nhiều yêu cầu trùng lặp, phân tán, khó ưu tiên khiếu nại gấp |
| 9 | Phát hiện tài xế buồn ngủ và mất tập trung | Tài xế, doanh nghiệp vận tải | Cần giám sát liên tục và cảnh báo thời gian thực |

---

## 2. Gom trùng / cluster

| Cluster | Candidate thuộc nhóm | Pattern chung | Nhận xét |
|---|---|---|---|
| Học tập / sinh viên | #1, #5 | Hỗ trợ người học lập kế hoạch hoặc học hiệu quả hơn | #5 cụ thể hơn, dễ vẽ workflow và dễ làm MVP hơn |
| Sức khỏe / an toàn | #2, #9 | Theo dõi trạng thái và cảnh báo rủi ro | Tác động lớn nhưng rủi ro cao, khó kiểm thử |
| Kinh doanh / vận hành | #3, #4, #6, #8 | Hỗ trợ quyết định, phân loại, tối ưu vận hành | Có nhu cầu thật nhưng dữ liệu và phạm vi dễ rộng |
| Nông nghiệp | #7 | Nhận diện vấn đề qua ảnh | Cần dữ liệu ảnh và domain chuyên môn |

---

## 3. Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Đề xuất lịch đăng ký học phần cho sinh viên | Actor rõ, workflow rõ, nhóm hiểu domain, dễ làm MVP, dễ đo before/after | Cần kiểm chứng sinh viên có thật sự mất nhiều thời gian không; cần dữ liệu chính thức |
| Hệ thống hỗ trợ học tập cá nhân hóa | Nhu cầu lớn, AI có vai trò rõ | Phạm vi rộng, khó đo cải thiện học tập trong thời gian ngắn |
| AI quản lý dự án | Dễ demo, workflow quen thuộc | Nhiều tool đã có, khó tạo khác biệt |
| Hỗ trợ hộ kinh doanh TMĐT | Nhu cầu thực tế, impact kinh tế rõ | Phụ thuộc chính sách, phí sàn và dữ liệu thay đổi |

---

## 4. Chấm điểm để đồng thuận

| Candidate | Actor rõ | Workflow rõ | Pain có khả năng thật | Impact đo được | Làm được trong lab | So sánh Rule/Workflow/Agent được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Đề xuất lịch đăng ký học phần cho sinh viên | 5 | 5 | 4 | 5 | 5 | 5 | 5 | **34** |
| Hệ thống hỗ trợ học tập cá nhân hóa | 5 | 3 | 4 | 4 | 3 | 3 | 4 | **26** |
| AI quản lý dự án | 4 | 4 | 3 | 4 | 4 | 4 | 4 | **27** |
| Hỗ trợ hộ kinh doanh TMĐT | 5 | 4 | 4 | 5 | 3 | 4 | 2 | **27** |

## 5. Candidate nhóm chọn

```text
Trợ lý đề xuất lịch đăng ký học phần cho sinh viên có xét lịch trình cá nhân.
```

## 6. Vì sao chọn

Nhóm chọn đề tài này vì actor rõ là **sinh viên đại học chuẩn bị đăng ký học phần**. Workflow hiện tại có thể vẽ cụ thể từ bước xem chương trình đào tạo, đối chiếu bảng điểm, kiểm tra môn tiên quyết, xem lớp mở, tổng hợp lịch cá nhân, thử nhiều tổ hợp lịch đến đăng ký chính thức.

Bottleneck cũng cụ thể: sinh viên phải tự ghép nhiều nguồn dữ liệu và nhiều ràng buộc cùng lúc. Impact có thể đo bằng thời gian lập lịch, số lần thử lại, tỷ lệ lịch bị trùng, tỷ lệ vi phạm môn tiên quyết và mức độ hài lòng.

Đề tài này đủ nhỏ để làm MVP trong phạm vi một ngành và một học kỳ.

## 7. Vì sao không chọn các candidate còn lại

- Hệ thống hỗ trợ học tập cá nhân hóa: nhu cầu lớn nhưng phạm vi quá rộng, khó đo tác động học tập trong thời gian lab.
- AI quản lý dự án: workflow quen thuộc nhưng nhiều tool đã có sẵn, nhóm khó tạo điểm khác biệt trong scope nhỏ.
- Hỗ trợ hộ kinh doanh TMĐT: impact kinh tế rõ nhưng phụ thuộc chính sách, phí sàn và dữ liệu thay đổi liên tục.
- Các candidate sức khỏe/an toàn: tác động lớn nhưng rủi ro cao và khó kiểm thử an toàn trong lab.

Nếu có disagreement, nhóm xử lý bằng cách chấm điểm theo tiêu chí actor, workflow, pain, impact, khả năng làm trong lab, khả năng so sánh Rule / Workflow / Agent và mức độ hiểu domain của nhóm.

---

# Phase 4 — Quick Validation + Research giải pháp

# 1. Kiểm chứng vấn đề

## 1.1. Khó khăn này có thực sự tồn tại không?

### Giả thuyết vấn đề

Sinh viên đại học chuẩn bị đăng ký học phần thường gặp khó khăn khi phải tự tổng hợp:

- chương trình đào tạo;
- bảng điểm cá nhân;
- môn đã học;
- môn tiên quyết;
- danh sách lớp học phần được mở;
- lịch học;
- lịch thi;
- lịch làm thêm;
- lịch học thêm;
- lịch hoạt động cá nhân;
- thời gian di chuyển.

Sau đó sinh viên phải tự thử nhiều tổ hợp để tạo một lịch học hợp lệ, không trùng lịch và phù hợp với lịch trình cá nhân.

### Điều cần kiểm chứng

Hiện tại nhóm **chưa có dữ liệu thật đầy đủ**, nên chưa được khẳng định chắc chắn rằng vấn đề này nghiêm trọng. Nhóm cần kiểm chứng bằng phỏng vấn hoặc khảo sát.

Các câu hỏi cần kiểm chứng:

1. Sinh viên có thật sự mất nhiều thời gian khi đăng ký học phần không?
2. Sinh viên mất trung bình bao lâu để tạo được một lịch học phù hợp?
3. Sinh viên khó nhất ở bước nào: chọn môn, kiểm tra tiên quyết, ghép lịch, hay xử lý khi lớp hết chỗ?
4. Sinh viên có phải xét lịch cá nhân như làm thêm, học thêm, câu lạc bộ, gia đình không?
5. Sinh viên có từng đăng ký nhầm môn, trùng lịch hoặc phải đổi lịch không?
6. Vấn đề này xảy ra mỗi kỳ hay chỉ với một nhóm sinh viên đặc biệt?

---

## 1.2. Có dữ liệu thật không?

### Trạng thái hiện tại

```text
Chưa có dữ liệu thật.
```

Các số liệu đang dùng trong bản này là **ước lượng v0** để phục vụ phân tích, chưa phải bằng chứng.

### Dữ liệu cần thu thập

| Loại dữ liệu | Cách thu thập | Mục đích |
|---|---|---|
| Thời gian sinh viên tự lập lịch | Quan sát 5-10 sinh viên tự xếp lịch | Đo baseline thời gian hiện tại |
| Mức độ phổ biến của vấn đề | Survey 30-50 sinh viên | Biết bao nhiêu người gặp pain |
| Bước gây khó khăn nhất | Interview sinh viên | Xác định bottleneck thật |
| Lỗi đăng ký thường gặp | Hỏi cố vấn hoặc phòng đào tạo | Xem lỗi có lặp lại không |
| Dữ liệu chương trình đào tạo | Thu từ website/trường/CSV | Làm input cho rule engine |
| Dữ liệu lớp học phần | Thu từ danh sách lớp mở | Làm input cho optimizer |
| Lịch cá nhân | Sinh viên tự nhập thử | Kiểm tra khả năng cá nhân hóa lịch |

### Ước lượng v0 cần kiểm chứng

| Giả định | Giá trị v0 | Cần kiểm chứng bằng |
|---|---:|---|
| Thời gian trung vị để tự tạo lịch | 75 phút | Quan sát thực tế |
| Số lần thử tổ hợp lịch | 5 lần | Log thao tác hoặc phỏng vấn |
| Tỷ lệ lịch nháp bị xung đột với lịch cá nhân | 20% | So sánh lịch nháp với lịch cá nhân |
| Tỷ lệ sinh viên tìm được lịch phù hợp nhanh | 60% | Survey hoặc test task |
| Điểm hài lòng hiện tại | 3/5 | Survey |

---

# 2. Research giải pháp đã có

## 2.1. Người khác xử lý thế nào?

| Giải pháp / tool / pattern | Link | Họ xử lý phần nào? | Cấp độ | Điểm mạnh | Điểm yếu / khoảng trống |
|---|---|---|---|---|---|
| Excel / Google Sheet tự xếp lịch | https://www.google.com/sheets/about/ | Sinh viên tự nhập lớp học, tự kiểm tra trùng giờ | Rule thủ công | Dễ dùng, không cần AI | Không tự hiểu môn tiên quyết, không tự tối ưu, dễ sai |
| Website trường | Hệ thống đăng ký học phần của từng trường | Cho sinh viên xem lớp mở và đăng ký chính thức | Workflow | Dữ liệu chính thức, dùng được cho đăng ký thật | Thường chỉ kiểm tra sau khi sinh viên chọn, chưa chủ động đề xuất nhiều lịch |
| Google Calendar | https://support.google.com/calendar/answer/2465776 | Quản lý lịch cá nhân | Workflow | Tốt cho lịch làm thêm, học thêm, hoạt động cá nhân | Không hiểu môn học, tín chỉ, tiên quyết |
| Coursicle Course Planner | https://www.coursicle.com/course-planner/ | Hỗ trợ tìm lớp và tạo thời khóa biểu | Workflow / Rule | Trực quan, sinh viên dễ thử lịch | Chưa chắc phù hợp CTĐT và quy định từng trường Việt Nam |
| Degree Works / Degree Audit | https://www.ellucian.com/products/student/student-success | Theo dõi tiến độ tốt nghiệp và môn còn thiếu | Workflow | Mạnh về kiểm tra chương trình đào tạo | Không tập trung vào tối ưu lịch học với lịch cá nhân từng kỳ |
| Stellic Academic Planning | https://www.stellic.com/ | Lập kế hoạch học tập, degree audit, advising workflow | Workflow nâng cao | Bao phủ nhiều nghiệp vụ học vụ | Quá lớn cho MVP, cần tích hợp dữ liệu trường |
| AI academic advisor | Pattern tư vấn học vụ có AI | Tư vấn môn học dựa trên hồ sơ học tập | Workflow có AI | Có thể hiểu nhu cầu tự nhiên và giải thích | Rủi ro nếu AI tự suy luận sai quy định học vụ |
| Agent tự đăng ký học phần | Pattern agent tự động hóa | Tự chọn môn, theo dõi lớp, đăng ký thay sinh viên | Agent | Tự động hóa cao | Rủi ro cao, cần quyền truy cập hệ thống trường, dễ gây hậu quả nếu sai |

---

## 2.2. Họ làm ở cấp độ nào?

| Cấp độ | Mô tả | Ví dụ trong bài toán này |
|---|---|---|
| Rule | Điều kiện rõ ràng, đúng/sai kiểm tra được | Trùng giờ, số tín chỉ, môn tiên quyết, lịch cá nhân bị xung đột |
| Workflow | Nhiều bước nối tiếp, có công cụ hỗ trợ từng bước | Nhập dữ liệu → lọc môn → sinh lịch → kiểm tra → hiển thị |
| Agent | AI tự lập kế hoạch, gọi công cụ, thay đổi bước tiếp theo | Tự theo dõi lớp còn chỗ, tự đổi phương án, tự đăng ký |

---

## 2.3. Điểm yếu của giải pháp hiện có

Các giải pháp hiện có thường gặp các điểm yếu sau:

1. **Chỉ kiểm tra sau khi sinh viên đã chọn**, chưa chủ động đề xuất nhiều phương án lịch phù hợp.
2. **Chưa kết hợp tốt lịch cá nhân**, ví dụ lịch làm thêm, học thêm, câu lạc bộ, gia đình, thời gian di chuyển.
3. **Chưa giải thích trade-off**, ví dụ vì sao lịch A tốt hơn lịch B, hoặc phải đánh đổi điều kiện nào.
4. **Không xử lý tốt yêu cầu tự nhiên**, ví dụ "em muốn lịch đừng quá dày nhưng vẫn đủ tín chỉ".
5. **Phụ thuộc dữ liệu chính thức**, nếu dữ liệu lớp mở, tiên quyết hoặc lịch thi không cập nhật thì lịch đề xuất có thể sai.
6. **Agent tự động đăng ký có rủi ro cao**, vì nếu đăng ký sai có thể ảnh hưởng trực tiếp đến quyền lợi và tiến độ học tập của sinh viên.

---

# 3. Sáu câu hỏi khai thác bài toán

## Câu 1. Quy trình hiện tại thế nào?

Quy trình hiện tại của sinh viên:

```text
Xác định mục tiêu học kỳ
→ Xem chương trình đào tạo
→ Đối chiếu bảng điểm
→ Kiểm tra môn tiên quyết
→ Xem lớp học phần được mở
→ Tổng hợp lịch trình cá nhân
→ Tự ghép lịch học với lịch cá nhân
→ Kiểm tra trùng lịch, tín chỉ, lịch thi và thời gian di chuyển
→ Hỏi cố vấn nếu có ngoại lệ
→ Đăng ký chính thức
→ Lập lại phương án nếu lớp hết chỗ hoặc lịch thay đổi
```

---

## Câu 2. Nút thắt ở đâu?

Nút thắt chính nằm ở bước:

```text
Tự ghép lịch học với lịch cá nhân và kiểm tra tính khả thi.
```

Lý do:

- Sinh viên phải xử lý nhiều nguồn dữ liệu cùng lúc.
- Sinh viên phải kiểm tra nhiều ràng buộc cứng: tiên quyết, tín chỉ, trùng lịch, lịch thi.
- Sinh viên phải cân bằng nhiều mong muốn mềm: nghỉ ngày nào, không học quá dày, có thời gian đi làm thêm.
- Số tổ hợp lớp có thể nhiều.
- Nếu lớp hết chỗ, sinh viên phải lập lại phương án.

---

## Câu 3. Hao phí hiện tại bao nhiêu?

### Hao phí thời gian

Ước lượng v0:

```text
Một sinh viên có thể mất khoảng 75-150 phút để tạo và sửa lịch học phù hợp.
```

Công thức ước lượng:

```text
Tổng hao phí = số sinh viên × thời gian trung bình lập lịch
```

Ví dụ giả định:

```text
500 sinh viên × 75 phút = 37.500 phút
= 625 giờ mỗi kỳ
```

### Hao phí khác

- Thời gian cố vấn trả lời câu hỏi lặp lại.
- Thời gian sinh viên sửa lịch khi lớp hết chỗ.
- Rủi ro đăng ký sai môn hoặc sai điều kiện.
- Rủi ro lịch học quá dày, ảnh hưởng kết quả học tập.
- Rủi ro chậm tiến độ tốt nghiệp nếu chọn sai môn quan trọng.

---

## Câu 4. Tiêu chí thành công đo bằng gì?

| Chỉ số | Baseline v0 | Target MVP | Cách đo |
|---|---:|---:|---|
| Thời gian trung vị để tạo lịch phù hợp | 75 phút | ≤ 10 phút | Quan sát sinh viên thực hiện cùng một task trước/sau |
| Tỷ lệ lịch vượt qua toàn bộ ràng buộc cứng | Chưa có | 100% | Validator tự động kiểm tra |
| Tỷ lệ sinh viên tìm được ít nhất một lịch chấp nhận được | 60% giả định | ≥ 80% | Survey sau khi dùng thử |
| Tỷ lệ AI hiểu đúng ràng buộc cứng/mềm | Chưa có | ≥ 90% | Test set yêu cầu tự nhiên đã gán nhãn |
| Tỷ lệ yêu cầu mơ hồ được hỏi lại | Chưa có | ≥ 95% | Test các câu thiếu thông tin hoặc xung đột |
| Điểm hài lòng tổng thể | 3/5 giả định | ≥ 4/5 | Survey Likert 1-5 |

---

## Câu 5. Hậu quả khi AI sai là gì?

| Lỗi AI | Hậu quả | Cách kiểm soát |
|---|---|---|
| AI hiểu sai lịch cá nhân | Đề xuất lịch trùng với lịch làm thêm/học thêm | Sinh viên phải xác nhận ràng buộc trước khi sinh lịch |
| AI phân loại sai ràng buộc cứng/mềm | Bỏ qua điều kiện bắt buộc hoặc quá ưu tiên điều kiện không quan trọng | Hiển thị lại điều kiện để sinh viên sửa |
| AI giải thích sai quy định | Sinh viên hiểu sai và chọn lịch không phù hợp | Dẫn nguồn quy định, trường hợp quan trọng chuyển cố vấn |
| AI đề xuất lịch quá dày | Sinh viên quá tải, ảnh hưởng học tập/sức khỏe | Cho phép đặt giới hạn số tiết/ngày và thời gian nghỉ |
| AI làm lộ lịch cá nhân | Ảnh hưởng riêng tư | Chỉ dùng lịch khi sinh viên cấp quyền, lưu tối thiểu, cho phép xóa |
| AI tự đăng ký sai | Ảnh hưởng trực tiếp quyền lợi sinh viên | MVP không cho AI tự đăng ký |

---

## Câu 6. Có giải pháp phi AI đơn giản không?

Có.

Các giải pháp phi AI gồm:

- Excel template để tự xếp lịch;
- checklist môn tiên quyết;
- website lọc môn đủ điều kiện;
- rule kiểm tra trùng lịch;
- form chọn điều kiện bằng checkbox;
- công cụ sinh thời khóa biểu bằng thuật toán;
- cố vấn học tập hỗ trợ thủ công.

### Khi nào phi AI là đủ?

Phi AI có thể đủ nếu:

- mỗi môn chỉ có một lớp;
- sinh viên không có nhiều lịch cá nhân;
- quy định đơn giản;
- sinh viên chỉ cần kiểm tra trùng giờ;
- form checkbox đã đủ diễn đạt nhu cầu.

### Vì sao vẫn cân nhắc AI?

AI có giá trị khi sinh viên diễn đạt nhu cầu tự nhiên như:

```text
Em muốn học khoảng 18 tín chỉ, tránh sáng thứ Hai, vẫn đi làm thêm tối thứ Ba và thứ Năm, lịch đừng quá dày, ưu tiên học môn cần cho đồ án.
```

AI có thể hỗ trợ:

- hiểu yêu cầu tự nhiên;
- chuyển thành ràng buộc cứng/mềm;
- hỏi lại khi mơ hồ;
- giải thích trade-off giữa các lịch.

---

# Phase 5 — Workflow + Problem Statement

# 1. Current workflow chi tiết

| Bước | Actor | Input | Hoạt động | Output | Thời gian/tần suất | Handoff | Bottleneck |
|---|---|---|---|---|---|---|---|
| 1 | Sinh viên | Mục tiêu tín chỉ, tiến độ học tập | Xác định học kỳ này muốn học bao nhiêu tín chỉ, môn nào cần ưu tiên | Nhu cầu ban đầu | 5-10 phút / mỗi kỳ | Chuyển sang xem CTĐT | Sinh viên chưa chắc biết môn nào quan trọng |
| 2 | Sinh viên | Chương trình đào tạo, quy định học vụ | Tìm môn bắt buộc, tự chọn, môn còn thiếu | Danh sách môn cần học | 10-20 phút / mỗi kỳ | Chuyển sang bảng điểm | Tài liệu dài, nhiều phiên bản |
| 3 | Sinh viên | Bảng điểm, môn đã học | Đối chiếu môn đã qua, chưa đạt, cần học lại | Danh sách môn còn phải học | 5-15 phút / mỗi kỳ | Chuyển sang kiểm tra điều kiện | Mã môn/tên môn có thể không đồng nhất |
| 4 | Sinh viên | Môn còn thiếu, quy định tiên quyết | Kiểm tra môn đủ điều kiện đăng ký | Danh sách môn đủ điều kiện | 10-20 phút / mỗi kỳ | Chuyển sang xem lớp mở | Dễ bỏ sót tiên quyết, học trước, song hành |
| 5 | Sinh viên, hệ thống trường | Danh sách lớp mở | Xem giờ học, giảng viên, địa điểm, sĩ số | Danh sách lớp có thể chọn | 5-15 phút / mỗi kỳ | Chuyển sang lịch cá nhân | Dữ liệu thay đổi, lớp có thể hết chỗ |
| 6 | Sinh viên | Lịch làm thêm, học thêm, CLB, gia đình, di chuyển | Tổng hợp khung giờ bận và ưu tiên cá nhân | Lịch cá nhân | 10-20 phút / mỗi kỳ | Chuyển sang ghép lịch | Lịch nằm nhiều nơi, dễ thiếu |
| 7 | Sinh viên | Lớp học phần, lịch cá nhân | Thử nhiều tổ hợp lớp để tránh xung đột | Lịch nháp | 20-45 phút / mỗi kỳ | Chuyển sang kiểm tra | Phải thử thủ công nhiều tổ hợp |
| 8 | Sinh viên | Lịch nháp, lịch thi, tín chỉ, tiên quyết | Kiểm tra tính khả thi của lịch | Lịch phù hợp hoặc danh sách lỗi | 10-20 phút / mỗi phương án | Nếu sai quay lại bước 7 | Dễ bỏ sót xung đột |
| 9 | Sinh viên, cố vấn | Câu hỏi hoặc ngoại lệ | Hỏi cố vấn/phòng đào tạo | Hướng dẫn điều chỉnh | 10-30 phút, chưa tính chờ | Trả lại sinh viên | Handoff chậm |
| 10 | Sinh viên, hệ thống trường | Lịch đã chọn | Đăng ký chính thức | Thành công hoặc lỗi | 5-15 phút / mỗi kỳ | Nếu lỗi quay lại bước 5 hoặc 7 | Lớp hết chỗ, hệ thống nghẽn |
| 11 | Sinh viên | Lớp hết chỗ, lớp hủy, lịch đổi | Lập phương án khác | Lịch mới | 10-30 phút / mỗi lần | Quay lại đăng ký | Lặp lại nhiều bước |

## Bottleneck chính

```text
Sinh viên phải kết hợp nhiều nguồn dữ liệu và nhiều loại ràng buộc cùng lúc: chương trình đào tạo, bảng điểm, môn tiên quyết, lớp mở, lịch thi, lịch trình cá nhân và thời gian di chuyển. Việc thử tổ hợp thủ công mất thời gian, dễ bỏ sót xung đột và khó xác định phương án cân bằng nhất.
```

---

# 2. Future workflow chi tiết

| Bước | Actor | Input | Hoạt động | Output | Thời gian mục tiêu | Handoff | Bottleneck / rủi ro còn lại |
|---|---|---|---|---|---|---|---|
| 1 | Sinh viên | Ngành, khóa, bảng điểm, môn đã học | Nhập hoặc tải hồ sơ học tập | Hồ sơ học tập có cấu trúc | 1-3 phút | Chuyển cho kiểm tra dữ liệu | Dữ liệu có thể thiếu |
| 2 | Sinh viên | Lịch làm thêm, học thêm, CLB, gia đình, di chuyển | Nhập hoặc đồng bộ lịch cá nhân | Khung giờ bận và ưu tiên | 2-5 phút | Chuyển cho AI | Lịch cá nhân thay đổi thường xuyên |
| 3 | Sinh viên | Số tín chỉ, môn ưu tiên, ngày muốn nghỉ, tải học | Nhập mục tiêu bằng form hoặc ngôn ngữ tự nhiên | Yêu cầu ban đầu | 1-2 phút | Chuyển cho AI | Yêu cầu có thể mơ hồ |
| 4 | AI + sinh viên | Yêu cầu tự nhiên, lịch cá nhân | AI chuyển thành ràng buộc cứng/mềm, sinh viên xác nhận | Bộ điều kiện đã xác nhận | Dưới 1 phút | Chuyển cho rule engine | AI có thể hiểu sai |
| 5 | Rule engine | Hồ sơ học tập, CTĐT, tiên quyết | Lọc môn đủ điều kiện | Danh sách môn hợp lệ | Dưới 5 giây | Chuyển cho optimizer | Phụ thuộc dữ liệu chính thức |
| 6 | Optimizer | Lớp học phần, lịch cá nhân, thời gian di chuyển, ưu tiên | Sinh 3-5 lịch không xung đột | Lịch đề xuất | 5-30 giây | Chuyển cho validator | Số tổ hợp có thể lớn |
| 7 | Validator | Các lịch đề xuất | Kiểm tra tín chỉ, tiên quyết, lịch học, lịch thi, lịch cá nhân, di chuyển | Lịch hợp lệ | Dưới 5 giây | Chuyển cho AI giải thích | Phụ thuộc chất lượng dữ liệu |
| 8 | AI | Lịch hợp lệ và ưu tiên của sinh viên | Giải thích ưu/nhược điểm và trade-off | Bản so sánh lịch | Dưới 10 giây | Chuyển cho sinh viên | Giải thích có thể dài hoặc lệch trọng tâm |
| 9 | Sinh viên | Các lịch đề xuất | Chọn lịch hoặc điều chỉnh ưu tiên | Lịch được chọn | 2-5 phút | Đăng ký hoặc chuyển cố vấn | Người dùng vẫn quyết định |
| 10 | Cố vấn | Hồ sơ, lịch, ngoại lệ | Review học vượt, học lại, chuyển ngành hoặc ngoại lệ | Phê duyệt/hướng dẫn | 5-10 phút khi cần | Trả lại sinh viên | Không tự động hóa toàn bộ |
| 11 | Sinh viên, hệ thống trường | Lịch được chọn | Đăng ký chính thức | Thành công hoặc lỗi | 5-10 phút | Nếu lỗi chuyển dự phòng | Phụ thuộc hệ thống trường |
| 12 | Hệ thống | Lớp hết chỗ, lịch cá nhân hiện tại | Tạo lịch dự phòng | Lịch thay thế | Dưới 30 giây | Quay lại bước so sánh | Cần dữ liệu lớp cập nhật |

---

# 3. Before / After impact

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước chính | 10-11 bước | 7-8 bước lõi | Chưa tính đăng ký chính thức |
| Tổng thời gian lập lịch | 75-150 phút | 5-10 phút | Baseline cần kiểm chứng |
| Số bước thủ công | 8-9 bước | 3-4 bước | Sinh viên vẫn nhập dữ liệu, xác nhận và chọn lịch |
| Số lần thử lại tổ hợp lịch | 5 lần | ≤ 2 lần | Ghi log thao tác |
| Tỷ lệ lịch xung đột ràng buộc cứng | Chưa đo | 0% | Validator kiểm tra |
| Risk mới | Không có AI nhưng dễ sai thủ công | AI hiểu sai, dữ liệu cũ, lộ lịch cá nhân | Cần xác nhận người dùng và validator |

---

# 4. Problem Statement v0 — 6 field

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học chuẩn bị đăng ký học phần, đặc biệt là sinh viên có lịch làm thêm, học thêm, tham gia câu lạc bộ, có trách nhiệm gia đình, phải di chuyển giữa nhiều cơ sở, học lại, học vượt hoặc không theo hoàn toàn lớp hành chính. |
| **Workflow** | Trước mỗi kỳ, sinh viên phải xem chương trình đào tạo, đối chiếu bảng điểm, kiểm tra môn tiên quyết, xem lớp được mở, tổng hợp lịch cá nhân, tự thử nhiều tổ hợp lớp, kiểm tra trùng giờ/lịch thi/tín chỉ/thời gian di chuyển, hỏi cố vấn nếu có ngoại lệ và lập lại lịch nếu lớp hết chỗ. |
| **Bottleneck** | Sinh viên phải kết hợp nhiều nguồn dữ liệu và nhiều loại ràng buộc cùng lúc. Việc thử tổ hợp thủ công mất thời gian, dễ bỏ sót xung đột và khó xác định phương án cân bằng nhất giữa tiến độ học tập và lịch trình cá nhân. |
| **Impact** | Sinh viên mất nhiều thời gian lập và sửa lịch; có thể chọn lịch trùng công việc hoặc hoạt động cá nhân; lịch học quá dày hoặc thiếu thời gian tự học; phải bỏ môn hoặc đổi lớp sau khi đăng ký; tăng số câu hỏi gửi cố vấn/phòng đào tạo; lựa chọn sai có thể làm chậm tiến độ tốt nghiệp. |
| **Success Metric** | Giảm thời gian trung vị để tạo lịch từ khoảng 75 phút xuống dưới 10 phút; 100% lịch đề xuất không xung đột với ràng buộc cứng đã xác nhận; ít nhất 80% sinh viên tìm được một phương án phù hợp; ít nhất 70% dùng nguyên lịch hoặc chỉ sửa một điều kiện nhỏ; giảm ít nhất 30% số lần sinh viên phải tự lập lại lịch; điểm hài lòng trung bình đạt ít nhất 4/5. |
| **Boundary** | MVP chỉ phục vụ một ngành và một học kỳ; chỉ sử dụng lịch cá nhân do sinh viên tự nhập hoặc chủ động đồng bộ; không tự truy cập lịch cá nhân nếu chưa được cho phép; không tự đăng ký học phần; không bảo đảm lớp còn chỗ nếu thiếu dữ liệu thời gian thực; không thay thế cố vấn; không tự quyết định sự kiện cá nhân nào phải bị hủy; không dùng LLM để xác nhận tính hợp lệ của lịch. |

---

# Phase 6 — Rule / Workflow / Agent + Decision

# 1. Ma trận độ mơ hồ × độ phức tạp

## Vị trí bài toán

```text
Độ mơ hồ trung bình × độ phức tạp cao.
```

## Vì sao độ mơ hồ trung bình?

Các điều kiện sau có đúng/sai rõ ràng:

- trùng giờ;
- số tín chỉ;
- môn tiên quyết;
- môn đã học;
- lịch thi;
- thời gian di chuyển;
- xung đột với lịch cá nhân.

Nhưng các mong muốn sau có thể mơ hồ:

- lịch nhẹ;
- không quá dày;
- ưu tiên nghỉ thứ Sáu;
- vẫn đi làm thêm được;
- có thời gian tự học;
- học đủ môn quan trọng nhưng không quá tải.

## Vì sao độ phức tạp cao?

Bài toán phải phối hợp nhiều nguồn dữ liệu:

- chương trình đào tạo;
- bảng điểm;
- môn tiên quyết;
- danh sách lớp mở;
- lịch học;
- lịch thi;
- lịch cá nhân;
- thời gian di chuyển;
- mục tiêu tín chỉ;
- ưu tiên cá nhân.

Ngoài ra, số tổ hợp lớp có thể lớn và bước sau phụ thuộc bước trước.

---

# 2. So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Sinh viên chọn môn và điều kiện bằng form/checkbox. Hệ thống kiểm tra trùng giờ, tín chỉ, tiên quyết, lịch cá nhân. | Đủ nếu yêu cầu đơn giản, ít mơ hồ và sinh viên chỉ cần lịch không trùng | Form dài, không hiểu câu tự nhiên, khó giải thích trade-off | Không chọn làm mức chính, nhưng dùng cho lõi kiểm tra |
| **Workflow** | AI hiểu nhu cầu; rule lọc môn; optimizer sinh lịch; validator kiểm tra; AI giải thích; sinh viên xác nhận | Phù hợp khi các bước rõ ràng nhưng cần AI hỗ trợ hiểu nhu cầu và giải thích | Cần schema rõ; AI có thể hiểu sai nên phải xác nhận | **Chọn** |
| **Agent** | Agent tự đọc dữ liệu, chọn môn, theo dõi lớp, đổi phương án, có thể đăng ký thay sinh viên | Chỉ phù hợp nếu cần tự động hóa nhiều bước và có API ổn định | Quyền truy cập lớn, khó kiểm soát, dễ hành động sai | Không chọn |

---

## Mức chọn

```text
Workflow có AI hỗ trợ.
```

## Vì sao chọn Workflow?

Bài toán có nhiều bước rõ ràng nên không cần agent tự chủ. Tuy nhiên, rule-only chưa đủ vì sinh viên thường diễn đạt nhu cầu bằng ngôn ngữ tự nhiên và có nhiều mong muốn mềm cần giải thích trade-off.

Workflow có AI hỗ trợ cho phép:

- dùng AI để hiểu yêu cầu;
- dùng AI để phân biệt ràng buộc cứng/mềm;
- dùng AI để hỏi lại khi mơ hồ;
- dùng AI để giải thích trade-off;
- dùng rule/validator cho các phần cần đúng tuyệt đối.

---

## Vì sao không chọn mức đơn giản hơn?

Không chọn rule-only vì Problem Statement có các yếu tố:

```text
"lịch trình cá nhân"
"mong muốn về số tín chỉ và khối lượng học"
"khó xác định phương án cân bằng nhất"
```

Những yếu tố này không phải lúc nào cũng được diễn đạt thành checkbox rõ ràng. Ví dụ:

```text
Em muốn học khoảng 18 tín chỉ, tránh sáng thứ Hai, vẫn đi làm thêm tối thứ Ba và thứ Năm, lịch đừng quá dày, ưu tiên học môn cần cho đồ án.
```

Rule-only buộc sinh viên tự dịch câu trên thành nhiều tham số. AI có thể hỗ trợ chuyển câu tự nhiên thành ràng buộc cứng/mềm và hỏi lại khi thiếu thông tin.

---

## Vì sao không chọn Agent?

Không chọn Agent vì boundary của MVP đã nêu rõ:

```text
Không tự đăng ký học phần.
Không thay thế cố vấn.
Không tự quyết định sự kiện cá nhân nào phải bị hủy.
Không dùng LLM để xác nhận tính hợp lệ của lịch.
```

Agent tự chủ nhiều bước làm tăng rủi ro nhưng chưa cần thiết cho MVP.

---

# 3. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên đại học chuẩn bị đăng ký học phần, đặc biệt là sinh viên có lịch làm thêm, học thêm, hoạt động ngoại khóa, trách nhiệm gia đình, phải di chuyển giữa nhiều cơ sở hoặc có lộ trình học không theo lớp hành chính. |
| **Workflow** | Sinh viên cung cấp hồ sơ học tập, danh sách môn đã hoàn thành, mục tiêu số tín chỉ, lịch trình cá nhân và mong muốn về ngày học, thời gian nghỉ, khối lượng học. AI chuyển yêu cầu tự nhiên thành ràng buộc có cấu trúc. Sinh viên xác nhận lại các ràng buộc. Rule engine lọc môn đủ điều kiện. Optimizer sinh lịch. Validator kiểm tra toàn bộ điều kiện cứng. AI giải thích trade-off giữa các lịch hợp lệ. Sinh viên chọn phương án cuối. Cố vấn xử lý trường hợp ngoại lệ. |
| **Bottleneck** | Sinh viên phải kết hợp dữ liệu học vụ và lịch cá nhân từ nhiều nguồn, đồng thời xử lý ràng buộc cứng, mong muốn mềm, điều kiện có thể xung đột và số lượng tổ hợp lớp lớn. Rule đơn thuần xử lý tốt điều kiện cứng nhưng chưa hỗ trợ tốt việc hiểu yêu cầu tự nhiên và giải thích đánh đổi giữa các phương án. |
| **Impact** | Nếu hoạt động tốt, hệ thống giảm thời gian lập lịch, giảm số lần thử thủ công, giảm xung đột giữa lịch học và lịch cá nhân, giúp sinh viên hiểu trade-off và giảm câu hỏi cơ bản gửi cố vấn. Nếu hoạt động sai, hệ thống có thể hiểu sai điều kiện cá nhân, đề xuất lịch không phù hợp, giải thích sai quy định, làm sinh viên tin nhầm vào kế hoạch hoặc làm lộ lịch trình cá nhân. |
| **Success Metric** | Thời gian trung vị để tạo lịch chấp nhận được ≤ 10 phút; 100% lịch đề xuất vượt validator; AI hiểu đúng ràng buộc cứng/mềm ≥ 90%; yêu cầu mơ hồ được hỏi lại ≥ 95%; ít nhất 80% sinh viên tìm được lịch chấp nhận được; ít nhất 70% dùng nguyên lịch hoặc chỉ sửa một điều kiện; điểm hài lòng ≥ 4/5; không có sự cố lộ lịch cá nhân trong pilot. |
| **Boundary** | Chỉ phục vụ một ngành và một học kỳ trong MVP; chỉ dùng dữ liệu chính thức được xác định phiên bản; lịch cá nhân chỉ được sử dụng khi sinh viên chủ động nhập hoặc cấp quyền; không tự đăng ký học phần; không tự thay đổi sự kiện cá nhân; không tự xử lý trường hợp học vụ ngoại lệ; không dùng LLM để kiểm tra tính hợp lệ; mọi lịch phải qua validator; mọi yêu cầu do AI trích xuất phải được sinh viên xác nhận. |
| **AI intervention point** | AI chỉ can thiệp tại 3 điểm: chuẩn hóa yêu cầu tự nhiên thành ràng buộc cứng/mềm; hỏi lại khi thông tin thiếu, mơ hồ hoặc mâu thuẫn; giải thích ưu/nhược điểm và trade-off của các lịch đã được validator xác nhận. |
| **Mức chọn** | Workflow có AI hỗ trợ. |
| **Rủi ro & người thật kiểm tra** | Mức rủi ro tổng thể: Trung bình. Sinh viên review phần AI hiểu lịch cá nhân và mong muốn. Validator review tính hợp lệ về giờ, tín chỉ, tiên quyết, lịch thi và thời gian di chuyển. Cố vấn review trường hợp học vượt, học lại, chuyển ngành hoặc ngoại lệ. Phòng đào tạo hoặc dữ liệu chính thức review quy định học vụ và phiên bản chương trình. |

---

# 4. Go / Not Yet / No-Go

## Bảng quyết định

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | Yes | Actor là sinh viên chuẩn bị đăng ký học phần; workflow đã vẽ before/after |
| Baseline và success metric đã đo được chưa? | Not Yet | Baseline hiện là ước lượng v0, cần quan sát và khảo sát thật |
| Có data/input đủ dùng chưa? | Not Yet | Cần dữ liệu CTĐT, bảng điểm, môn tiên quyết, lớp mở, lịch thi và lịch cá nhân |
| Nếu AI sai, hậu quả có chấp nhận được không? | Yes, nếu có kiểm soát | MVP không tự đăng ký; mọi lịch qua validator; sinh viên xác nhận yêu cầu |
| Có người review/owner vận hành không? | Not Yet | Cần xác định cố vấn/phòng đào tạo có tham gia review ngoại lệ không |
| Có cách non-AI đơn giản hơn không? | Yes | Excel/checklist/rule-based có thể giải quyết một phần, cần so sánh baseline |

## Decision

```text
Not Yet
```

## Lý do trích trực tiếp từ PS

1. PS có ghi:

```text
Các số liệu baseline trong file này là ước lượng v0.
```

→ Vì vậy chưa biết sinh viên thực sự mất nhiều thời gian hay không.

2. PS có ghi:

```text
Chỉ dùng dữ liệu chính thức được xác định phiên bản.
```

→ Vì vậy nếu chưa lấy được dữ liệu chính thức, chưa nên xây AI.

3. PS có ghi:

```text
Không bảo đảm lớp còn chỗ nếu thiếu dữ liệu thời gian thực.
```

→ Nếu pain chính là lớp hết chỗ, sản phẩm chưa giải quyết gốc vấn đề.

4. PS có ghi:

```text
Lịch cá nhân chỉ được sử dụng khi sinh viên chủ động nhập hoặc cấp quyền.
```

→ Cần kiểm chứng sinh viên có sẵn sàng nhập hoặc cấp quyền lịch cá nhân không.

5. PS có ghi:

```text
Mọi yêu cầu do AI trích xuất phải được sinh viên xác nhận.
```

→ Điều này cho thấy AI có thể hiểu sai, nên cần test trước khi pilot.

---

## Nếu Go, pilot nhỏ nhất là gì?

```text
Pilot cho một ngành trong một học kỳ.
Dữ liệu đầu vào là CSV/Excel gồm chương trình đào tạo, môn tiên quyết, lớp mở, lịch học và lịch thi.
Sinh viên nhập lịch cá nhân thủ công.
Hệ thống sinh 3-5 lịch hợp lệ, có giải thích trade-off.
Không tự đăng ký.
Test với 10-20 sinh viên.
```

---

## Nếu Not Yet, cần validate gì trước?

```text
1. Phỏng vấn 5-10 sinh viên để đo thời gian lập lịch, bước đau nhất và workaround hiện tại.
2. Survey 30-50 sinh viên để kiểm tra mức độ phổ biến của pain.
3. Hỏi 1-2 cố vấn hoặc cán bộ đào tạo về lỗi đăng ký lặp lại.
4. Xác nhận có thể lấy dữ liệu chính thức của ít nhất một ngành.
5. Làm baseline phi AI bằng Excel/rule để xem có giải quyết đủ tốt không.
6. Test AI trên bộ câu yêu cầu tự nhiên để đo khả năng phân biệt ràng buộc cứng/mềm.
```

---

## Nếu No-Go, nên làm gì thay AI?

```text
Nếu sinh viên không gặp pain đủ lớn, hoặc rule-based đã giải quyết gần như toàn bộ nhu cầu, nhóm nên làm một công cụ phi AI đơn giản hơn: checklist môn đủ điều kiện, bảng lọc lớp, kiểm tra trùng lịch và file Excel/website tạo thời khóa biểu.

Nếu pain chính là lớp hết chỗ, nhóm nên chuyển hướng sang hệ thống cảnh báo lớp còn chỗ và tạo phương án dự phòng.
```
