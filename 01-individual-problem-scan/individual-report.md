# Individual Problem Scan

## 1. Scan rộng các vấn đề quan sát được

Tôi bắt đầu từ trải nghiệm thực tế của bản thân và các người xung quanh, rồi chọn những vấn đề có thể vẽ workflow, có bottleneck rõ và có thể đo được bằng thời gian, số lần lặp lại hoặc rủi ro.

| STT | Lăng kính | Vấn đề quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
| :---: | :--- | :--- | :--- | :--- |
| 01 | Tốn thời gian | Tra cứu và hiểu pháp luật kinh doanh cho SME / Founder trẻ | Founder trẻ, chủ doanh nghiệp nhỏ | Mất 5–10 giờ/tuần đọc luật; tốn chi phí thuê tư vấn; dễ hiểu sai quy định. |
| 02 | Lặp lại + đau đầu từ người khác | Thủ tục hành chính kinh doanh (đăng ký GPKD, thuế, PCCC, giấy phép) | Founder, nhân viên vận hành / pháp lý | Phải đi lại 2–4 lần/thủ tục vì hồ sơ sai; mất vài tuần đến hàng tháng để được cấp phép. |
| 03 | Lặp lại + tốn thời gian | Thu thập dữ liệu, đối soát thuế và tính lợi nhuận ròng trên sàn TMĐT | Chủ gian hàng TMĐT, kế toán, vận hành đa kênh | Mất 3–5 giờ/tuần để ghép file Excel đa sàn; dễ sai sót do phí ẩn và dữ liệu phân tán. |
| 04 | Tốn thời gian + AI có thể tốt hơn | Nghiên cứu thị trường và phát hiện xu hướng mới cho solopreneur | Solo founder, marketer, nhà nghiên cứu sản phẩm | Tốn nhiều thời gian đọc tin tức; dữ liệu phân tán; quyết định còn cảm tính. |
| 05 | Tốn thời gian + khó khăn từ người khác | Tìm kiếm và đánh giá nhà cung cấp về giá, chất lượng và độ tin cậy | Chủ doanh nghiệp nhỏ, quản lý thu mua | Mất 1–2 tháng thử nghiệm; thường bị đứt gãy nguồn hàng hoặc phải đổi nhà cung cấp đột ngột. |
| 06 | Lặp lại + pain từ người khác | Theo dõi deadline, giấy tờ và các việc cần làm định kỳ cho doanh nghiệp nhỏ | Founder, nhân viên vận hành | Việc cần làm bị trôi, dễ quên context và phải nhắc lại nhiều lần. |

---

## 2. Top 3 Problem Cards

### Top 1 — Thu thập dữ liệu, pháp lý thuế và tính lợi nhuận ròng trên sàn TMĐT

**Problem 1 câu:** Mỗi tuần, chủ gian hàng TMĐT phải tự ghép dữ liệu từ nhiều sàn và file Excel để hiểu lợi nhuận thật, nhưng quá trình này kéo dài, dễ sai và có rủi ro về thuế.

**Actor:** Chủ gian hàng TMĐT, kế toán, nhân viên vận hành bán hàng đa kênh.

**Current workflow:**
1. Tải báo cáo từ Shopee / TikTok / Lazada.
2. Xuất file Excel và sắp xếp dữ liệu thủ công.
3. Đối soát doanh thu, chi phí, phí ẩn và hoàn hàng.
4. Tính lợi nhuận ròng và dự phòng thuế.
5. Gửi báo cáo cho người quản lý hoặc kế toán.

**Bottleneck:** Bước đối soát dữ liệu và tính lợi nhuận ròng là chỗ mất thời gian nhất và dễ sai sót nhất.

**Impact:** Mất 3–5 giờ/tuần; có thể dẫn đến đánh giá sai lợi nhuận, rủi ro phạt thuế hoặc quyết định kinh doanh sai.

**Success metric:** Giảm thời gian xử lý từ 3–5 giờ xuống dưới 1 giờ/tuần, đồng thời giảm lỗi đối soát.

**Non-AI alternative:** Template bảng tính chuẩn, quy trình đối soát cố định, checklist kiểm tra thủ công.

**AI hypothesis:** AI có thể hỗ trợ tự phân loại dữ liệu, phát hiện phí ẩn, gợi ý cách tính lợi nhuận ròng và tóm tắt rủi ro thuế.

**Draft current workflow:**
```text
[1] Tải dữ liệu từ nhiều sàn
→ [2] Ghép file Excel thủ công
→ [3] Đối soát doanh thu/chi phí
→ [4] Tính lợi nhuận ròng
→ [5] Review và gửi báo cáo
```

**Draft future workflow:**
```text
[1] Tự động kết nối dữ liệu từ các sàn
→ [2] AI chuẩn hóa và phân loại dữ liệu
→ [3] AI phát hiện phí ẩn và gợi ý cách tính lợi nhuận ròng
→ [4] Người dùng review và xác nhận
→ [5] Xuất báo cáo cuối cùng
```

---

### Top 2 — Tra cứu và hiểu pháp luật kinh doanh cho SME / Founder trẻ

**Problem 1 câu:** Founder trẻ thường mất rất nhiều thời gian để tra cứu và hiểu các quy định pháp luật liên quan đến hoạt động kinh doanh, nhưng ngôn ngữ pháp lý rườm rà khiến họ dễ hiểu sai hoặc trì hoãn.

**Actor:** Founder trẻ lần đầu khởi nghiệp, chủ doanh nghiệp nhỏ, solopreneur.

**Current workflow:**
1. Tìm thông tin trên Google hoặc các website tra cứu luật.
2. Đọc nhiều tài liệu dài và rời rạc.
3. Câu hỏi lại nhiều lần về nghĩa vụ pháp lý.
4. Dựa vào phán đoán cá nhân hoặc thuê tư vấn khi cần.

**Bottleneck:** Tìm đúng nội dung phù hợp và hiểu đúng quy định trong bối cảnh doanh nghiệp cụ thể là bước khó nhất.

**Impact:** Mất 5–10 giờ/tuần; có thể đưa ra quyết định sai, bị phạt hoặc phải chi tiền cho tư vấn không cần thiết.

**Success metric:** Giảm thời gian tra cứu và hiểu quy định, đồng thời tăng độ tin cậy khi trả lời các câu hỏi pháp lý cơ bản.

**Non-AI alternative:** Sổ tay quy định, checklist pháp lý, tư vấn từ chuyên gia khi cần.

**AI hypothesis:** AI có thể giúp chuyển luật thành câu hỏi/đáp ngắn gọn, tóm tắt quy định theo từng loại hình kinh doanh và cảnh báo thay đổi mới.

**Draft current workflow:**
```text
[1] Tìm tài liệu pháp luật
→ [2] Đọc và đối chiếu nhiều nguồn
→ [3] Tự suy luận nghĩa vụ
→ [4] Xác nhận bằng tư vấn hoặc phán đoán riêng
```

**Draft future workflow:**
```text
[1] Người dùng đặt câu hỏi theo ngữ cảnh
→ [2] AI tóm tắt quy định và giải thích bằng ngôn ngữ đơn giản
→ [3] AI đề xuất checklist cần làm theo loại hình doanh nghiệp
→ [4] Người dùng kiểm tra và quyết định cuối cùng
```

---

### Top 3 — Hoàn thành thủ tục và quy trình hành chính kinh doanh

**Problem 1 câu:** Người làm thủ tục doanh nghiệp thường phải đi lại nhiều lần vì hồ sơ chưa chuẩn, khiến thời gian cấp phép bị kéo dài và làm chậm tiến độ ra mắt sản phẩm.

**Actor:** Founder, chủ doanh nghiệp, nhân viên pháp lý và vận hành.

**Current workflow:**
1. Xác định loại thủ tục cần làm.
2. Tìm tài liệu hướng dẫn và checklist.
3. Chuẩn bị hồ sơ.
4. Nộp hồ sơ và chờ phản hồi.
5. Nếu sai, phải sửa lại và đi lại nhiều lần.

**Bottleneck:** Thiếu checklist chuẩn và việc kiểm tra hồ sơ trước khi nộp là điểm gây lãng phí lớn nhất.

**Impact:** Mất vài tuần đến hàng tháng; làm chậm ngày ra mắt, tăng stress và tốn thêm chi phí di chuyển.

**Success metric:** Giảm số lần nộp sai hồ sơ và rút ngắn thời gian hoàn tất thủ tục.

**Non-AI alternative:** Checklist giấy, mẫu hồ sơ chuẩn, hướng dẫn thủ công từ cơ quan liên quan.

**AI hypothesis:** AI có thể hỗ trợ sinh checklist hồ sơ, rà soát lỗi nhập liệu và gợi ý các giấy tờ còn thiếu trước khi nộp.

**Draft current workflow:**
```text
[1] Xác định thủ tục cần làm
→ [2] Tìm hướng dẫn thủ công
→ [3] Chuẩn bị hồ sơ
→ [4] Nộp hồ sơ và chờ phản hồi
→ [5] Sửa lại nếu sai
```

**Draft future workflow:**
```text
[1] Người dùng nhập mô hình doanh nghiệp và loại thủ tục
→ [2] AI sinh checklist hồ sơ và các bước cần làm
→ [3] AI rà soát lỗi trước khi nộp
→ [4] Người dùng nộp hồ sơ
→ [5] Hệ thống ghi nhận và nhắc bước tiếp theo
```

---

## 3. Vì sao 3 bài này được chọn

- Có actor rõ ràng và workflow có thể vẽ được.
- Có bottleneck cụ thể, không chỉ là vấn đề chung chung.
- Có thể đo bằng thời gian, số lần lặp lại hoặc rủi ro.
- Có thể so sánh giữa giải pháp không dùng AI, dùng rule/workflow và dùng agent/AI.