---
artifact: group-members — Danh sách thành viên nhóm Lab 2
bai-tap: 2 — Phân tích sản phẩm AI (nhóm)
phase: Khai báo nhóm
nop-cuoi: Có — bắt buộc (nộp kèm analysis-report.pdf)
---

# Thành viên nhóm Lab 2

Lab 2 làm theo nhóm 2 học viên. Mỗi học viên có 1 repo riêng (`Day26-MãHọcViên`), nhưng nội dung Lab 2 (slide deck + screenshots + research notes) là sản phẩm chung — mỗi học viên copy bản chung về repo cá nhân của mình.

File này khai báo 2 thành viên trong nhóm + phân công thực hiện.

---

## Danh sách thành viên

| # | Mã học viên | Họ tên đầy đủ | Phân công chính |
|---|---|---|---|
| 1 | 2A202600010 | Bùi Trọng Anh | Test ChatGPT, chụp ảnh giao diện/input/output ChatGPT, tổng hợp nhận định về workflow và action framing |
| 2 | 2A202600404 | Nguyễn Thành Đại Khánh | Test Perplexity, chụp ảnh giao diện/input/output Perplexity, tổng hợp nhận định về nguồn, citation và trust signal |

---

## Nhiệm vụ thử nghiệm chung

Nhóm sử dụng cùng một prompt để kiểm tra khả năng của hai sản phẩm AI trong việc giải thích một vấn đề pháp lý thực dụng liên quan đến Nghị định 13/2023 về bảo vệ dữ liệu cá nhân tại Việt Nam. Mục tiêu là so sánh cách ChatGPT và Perplexity hỗ trợ startup AI hiểu nghĩa vụ tuân thủ, xác định rủi ro và chuyển hóa thông tin thành các việc cần làm ngay.

**Prompt sử dụng chung**:

```text
Giải thích NĐ 13/2023 bảo vệ dữ liệu cá nhân của Việt Nam — áp dụng cho startup AI thế nào? Cho tôi 3 điều quan trọng nhất phải làm.
```

**Ngành chọn**: A — Tìm kiếm

**Sản phẩm A**: ChatGPT — https://chatgpt.com/

**Sản phẩm B**: Perplexity — https://www.perplexity.ai/

---

## Phân chia screenshot

- Sản phẩm A → Bùi Trọng Anh — 2A202600010 phụ trách chụp ChatGPT
- Sản phẩm B → Nguyễn Thành Đại Khánh — 2A202600404 phụ trách chụp Perplexity

---

## Ghi chú

- Mỗi thành viên copy folder `02-product-comparison/` đã hoàn thiện vào repo cá nhân của mình.
- Slide deck `analysis-report.pdf` là sản phẩm chung — 2 thành viên cùng tên trong credits của slide deck.
- Nhóm không dùng Google Slides công khai, nên không bắt buộc có `analysis-report-link.md`. Nếu sau này upload deck lên Google Slides, nhóm sẽ bổ sung file `analysis-report-link.md`.
- File `group-members.md` này phải giống nhau ở cả 2 repo cá nhân, cùng nội dung và cùng 2 mã học viên.

---

## Cấu trúc Analysis Report — S5 mở rộng

Slide deck Analysis Report có 5 mục bắt buộc từ S1 đến S5. Mục S5, Product Judgment, được mở rộng thành 8 mục con để bám sát phân tích định lượng và định tính đã học.

- **S5.1 Verdict** — ChatGPT được đánh giá **Strong** vì có độ phủ tác vụ rộng, khả năng tổng hợp tốt và lợi thế platform. Perplexity được đánh giá **Promising** vì mạnh về tìm kiếm có nguồn và citation UX, nhưng chịu áp lực lớn từ các platform AI đa năng.
- **S5.2 User base + tăng trưởng** — ChatGPT có tín hiệu tăng trưởng công khai mạnh hơn, gồm số liệu weekly active users và subscribers từ nguồn OpenAI. Perplexity có tín hiệu mở rộng enterprise, nhưng không có đầy đủ số liệu MAU/DAU công khai trong phạm vi bài.
- **S5.3 Doanh thu / pricing power** — cả hai đều có free plan và consumer paid plan quanh mức 20 USD/tháng. ChatGPT có lợi thế monetization đa use case, còn Perplexity có pricing power rõ hơn trong nhóm người dùng cần research/search workflow.
- **S5.4 Moat phân tích** — ChatGPT mạnh ở brand và distribution; Perplexity có moat ở trust UX, citation và workflow tìm kiếm, nhưng distribution yếu hơn.
- **S5.5 Data flywheel + feedback loop** — ChatGPT có flywheel rộng từ lượng hội thoại lớn, feedback, memory và enterprise deployment. Perplexity có loop hẹp hơn từ query, source click, follow-up và workflow nghiên cứu.
- **S5.6 Niche Down + AI Feature Map** — ChatGPT là general-purpose AI assistant; Perplexity là answer engine/research assistant cho các câu hỏi cần nguồn rõ.
- **S5.7 Spark → Loop → System** — ChatGPT đang ở giai đoạn **System** vì đã trở thành assistant mặc định cho nhiều tác vụ. Perplexity nằm giữa **Loop** và **System**, mạnh trong search/research nhưng chưa phải default assistant cho đa số người dùng.
- **S5.8 Liên hệ Lab 1 case** — bài học từ case Chegg cho thấy sản phẩm chỉ bán “câu trả lời” mà thiếu workflow sâu, moat phân phối và data flywheel sẽ dễ bị big tech AI thay thế. Trong bài test này, Perplexity cần tiếp tục đào sâu trust UX và research workflow để tránh bị các platform lớn tích hợp search/citation và làm mờ khác biệt.

Nhóm đã hoàn thành các mục bắt buộc gồm S5.1, S5.6, S5.7 và S5.8. Các mục S5.2–S5.5 cũng đã được bổ sung ở mức phù hợp với nguồn công khai tìm được; những số liệu không có nguồn công khai được ghi rõ trong slide thay vì tự ước đoán.
