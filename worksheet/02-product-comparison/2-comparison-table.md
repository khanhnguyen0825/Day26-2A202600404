---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu của file này là nén các quan sát từ `1-research-notes.md` và ảnh chụp màn hình thành bảng so sánh 5 mục, làm khung xương cho slide deck cuối.

- **Sản phẩm A**: ChatGPT
- **Sản phẩm B**: Perplexity
- **Ngành chọn**: A — Tìm kiếm
- **Prompt test chung**:

```text
Giải thích NĐ 13/2023 bảo vệ dữ liệu cá nhân của Việt Nam — áp dụng cho startup AI thế nào? Cho tôi 3 điều quan trọng nhất phải làm.
```

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A — ChatGPT | Sản phẩm B — Perplexity |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính</sup> | ChatGPT bắt đầu từ giao diện chat quen thuộc với ô **“Tìm kiếm web”**, phù hợp với người dùng muốn hỏi nhanh và nhận câu trả lời tổng hợp. Product moment chính là: nhập câu hỏi → AI tìm kiếm web → trả lời theo cấu trúc hành động. | Perplexity bắt đầu từ giao diện **answer engine** với ô **“Ask anything...”**, tab **Answer / Links / Images** và định vị rõ là công cụ tìm kiếm có nguồn. Product moment chính là: nhập câu hỏi → AI tìm kiếm → trả lời kèm citation và follow-up. |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI + friction chính</sup> | Trước AI, người dùng phải tự đọc NĐ 13/2023, tìm nguồn luật và chuyển thành checklist. Trong khi dùng, ChatGPT rút gọn workflow bằng cách đóng gói thành 3 việc cần làm: consent, DPIA/data map, quyền người dùng + bảo mật; sau đó vẫn cần kiểm tra lại nguồn pháp lý. | Trước AI, workflow thủ công giống ChatGPT. Trong khi dùng, Perplexity hỗ trợ mạnh phần tìm kiếm nguồn, citation, follow-up và gợi ý kế hoạch 30/60/90 ngày; sau đó người dùng vẫn phải tự đánh giá nguồn nào là chính thức và có đủ giá trị pháp lý. |
| **S3 — Output & Trust**<br><sup>Chất lượng output + dẫn nguồn + disclaimer + control</sup> | Output của ChatGPT mạch lạc, dễ đọc, có cấu trúc hành động rõ và có ví dụ data map sát startup AI. Điểm yếu là citation hiển thị dưới dạng tag nhỏ như “LuatVietnam”, “Văn Bản Chính Ph...” nên nguồn không nổi bật bằng Perplexity. | Output của Perplexity có citation rõ trong từng đoạn, có chỉ báo **10 sources** và gợi ý follow-up. Điểm mạnh là truy vết nguồn tốt hơn, nhưng người dùng vẫn phải tự sàng lọc chất lượng nguồn vì không phải nguồn nào cũng là văn bản pháp lý gốc. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + Cost-Capability-Speed</sup> | ChatGPT có free plan và gói Plus phổ biến khoảng **$20/tháng**, phù hợp với định vị assistant đa dụng. Trong bài test này, ChatGPT thiên về **capability rộng + tốc độ tổng hợp nhanh**, nhưng nguồn và kiểm chứng vẫn cần người dùng tự xử lý. | Perplexity có free plan và gói Pro khoảng **$20/tháng hoặc $200/năm**, thêm các tầng enterprise. Trong bài test này, Perplexity thiên về **capability hẹp nhưng sâu trong search/research**, nổi bật ở citation, source visibility và follow-up. |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng + lý do</sup> | **Strong** — ChatGPT mạnh hơn về độ rộng use case, khả năng tổng hợp, action framing và lợi thế platform. Với bài test pháp lý thực dụng, ChatGPT phù hợp khi người dùng cần biến thông tin thành checklist hành động nhanh. | **Promising** — Perplexity rất mạnh trong niche tìm kiếm có nguồn và research-style trust, nhưng bị áp lực từ các platform lớn như ChatGPT/Gemini nếu họ tích hợp search/citation tốt hơn. Perplexity cần đào sâu workflow nghiên cứu để giữ khác biệt. |

---

## Phần B — Đối chiếu 3 friction areas

- **Physical load**: Cả hai đều giảm mạnh số tab và thao tác so với tự Google/tự đọc luật; ChatGPT ít thao tác hơn nếu chỉ cần câu trả lời hành động, còn Perplexity có thêm tab nguồn/follow-up nên phù hợp khi người dùng muốn kiểm chứng sâu hơn.
- **Cognitive burden**: ChatGPT giảm tải nhận thức tốt hơn cho người mới vì câu trả lời được đóng gói thành 3 việc cần làm; Perplexity yêu cầu người dùng có khả năng đọc và đánh giá nguồn để tận dụng citation.
- **User workarounds**: Với ChatGPT, nhóm phải tự mở và kiểm tra lại nguồn vì citation chưa nổi bật; với Perplexity, nhóm phải tự lọc nguồn nào đáng tin và chuyển câu trả lời dài thành checklist nội bộ.

---

## Phần C — Đối chiếu 6 trust signals

| Tín hiệu đáng tin | Sản phẩm A — ChatGPT | Sản phẩm B — Perplexity |
|---|---|---|
| 1. Dẫn nguồn (citation) — link mở được, đúng nội dung | **Một phần** — có tag nguồn như LuatVietnam, Văn Bản Chính Phủ, nhưng hiển thị nhỏ và không nổi bật thành danh sách nguồn riêng. | **Có** — citation hiển thị rõ trong từng đoạn và cuối câu trả lời có chỉ báo **10 sources**. |
| 2. Disclaimer khi không chắc (“không tìm được”, “có thể sai”) | **Có** — giao diện có dòng “ChatGPT có thể mắc lỗi. Hãy kiểm tra các thông tin quan trọng.” | **Một phần / chưa rõ** — ảnh không thể hiện disclaimer pháp lý nổi bật; output vẫn cần người dùng tự hiểu rằng đây không thay thế tư vấn luật. |
| 3. Fallback / dừng lại khi out-of-scope | **Chưa quan sát được** — prompt nằm trong phạm vi trả lời nên không thấy trường hợp ChatGPT từ chối hoặc dừng lại. | **Chưa quan sát được** — prompt nằm trong phạm vi tìm kiếm nên không thấy trường hợp Perplexity fallback hoặc dừng lại. |
| 4. Consistency — chạy 2 lần cùng prompt, output có giống không | **Chưa kiểm chứng** — nhóm mới ghi nhận một lần chạy chính thức trong ảnh. | **Chưa kiểm chứng** — nhóm mới ghi nhận một lần chạy chính thức trong ảnh. |
| 5. User control — sửa lại, dừng, regenerate, undo | **Có** — ảnh cho thấy có nút dừng khi đang thinking, nút copy, like/dislike và biểu tượng regenerate ở cuối output. | **Có** — ảnh cho thấy có ô follow-up, nút chia sẻ, biểu tượng feedback, regenerate/copy và nút điều khiển ở cuối câu trả lời. |
| 6. Explanation — giải thích “tại sao AI nói thế” | **Một phần** — ChatGPT giải thích lý do startup AI phải làm consent, DPIA/data map, quyền người dùng và bảo mật, nhưng không giải thích chi tiết quy trình chọn nguồn. | **Một phần** — Perplexity giải thích theo bullet và citation, nhưng vẫn chưa giải thích rõ cách xếp hạng/chọn nguồn nào mạnh hơn. |

---

## Phần D — Định vị 2 sản phẩm trên Cost-Capability-Speed

- **Sản phẩm A — ChatGPT nghiêng về**: **cân bằng, thiên về capability rộng**.  
  **Lý do**: ChatGPT có free entry, gói Plus phổ biến $20/tháng và xử lý được nhiều loại tác vụ ngoài tìm kiếm như viết, phân tích, học tập, code, lập kế hoạch; trong bài test này tốc độ tổng hợp và action framing rất tốt.

- **Sản phẩm B — Perplexity nghiêng về**: **mạnh trong capability hẹp của search/research**.  
  **Lý do**: Perplexity cũng có free entry và gói Pro quanh $20/tháng, nhưng giá trị chính nằm ở trải nghiệm answer engine, citation rõ, nguồn dễ truy vết và follow-up tốt cho workflow nghiên cứu.

---

## Phần E — Verdict sơ bộ

- **Sản phẩm A — verdict sơ bộ**: **Strong**
  - **Lý do**: ChatGPT có lợi thế platform, giao diện quen thuộc, khả năng tổng hợp tốt và biến câu hỏi pháp lý thành checklist hành động rõ ràng cho startup AI.

- **Sản phẩm B — verdict sơ bộ**: **Promising**
  - **Lý do**: Perplexity có niche rõ trong tìm kiếm có nguồn và tạo cảm giác đáng tin hơn khi cần citation, nhưng chịu áp lực cạnh tranh lớn nếu các assistant đa dụng tích hợp search/citation tốt hơn.

---

## Phần F — Ô còn thiếu bằng chứng / cần đào thêm

| Mục còn thiếu | Trạng thái | Ghi chú |
|---|---|---|
| Consistency khi chạy lại cùng prompt | Thiếu bằng chứng | Nhóm chưa chạy lại prompt lần 2 cho cả hai sản phẩm, nên chưa kết luận được độ ổn định output. |
| Thời gian phản hồi chính xác của Perplexity | Thiếu bằng chứng | Ảnh chỉ cho thấy trạng thái Thinking, không có số giây cụ thể. |
| Model cụ thể của từng sản phẩm | Thiếu một phần | Ảnh ChatGPT chỉ thấy chế độ Thinking; Perplexity có nút Model nhưng không hiển thị model được chọn. |
| Chất lượng từng nguồn pháp lý | Cần kiểm chứng thêm | Cần mở từng nguồn, ưu tiên văn bản chính thức như văn bản Chính phủ/Bộ Công an nếu muốn kết luận pháp lý chắc hơn. |
| Số liệu business của Perplexity | Thiếu một phần | Có thể dùng tín hiệu enterprise/pricing công khai, nhưng MAU/DAU/paid users chính thức không đủ rõ trong phạm vi test. |

---

## Bảng kiểm trước khi sang Bước 3

- [x] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [x] Mỗi nhận định đều có thể chỉ về ảnh/log trong `1-research-notes.md` làm bằng chứng.
- [x] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [x] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [x] Ô còn thiếu bằng chứng đã được đánh dấu để Phase 3 đào thêm.

---

## Kết luận chuyển sang Bước 3

Bảng so sánh hiện đã đủ để dựng outline slide deck. Trọng tâm khi sang `3-FINAL-analysis-outline.md` là mở rộng S5 theo 8 mục con: verdict, user base/growth, pricing power, moat, data flywheel, niche map, Spark→Loop→System và liên hệ Lab 1 case Chegg.
