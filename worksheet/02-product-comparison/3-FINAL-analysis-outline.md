---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf`
---

# 3 — Outline 5 mục cho slide deck Analysis Report

File này là outline đầy đủ cho slide deck Lab 2. Nội dung được xây từ:

- `group-members.md`
- `1-research-notes-chatgpt-perplexity.md`
- `2-comparison-table-chatgpt-perplexity.md`
- Screenshots test ChatGPT và Perplexity
- Research nhanh về pricing, user base và business signal công khai

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**:
  - 2A202600010 — Bùi Trọng Anh
  - 2A202600404 — Nguyễn Thành Đại Khánh

- **Ngành chọn**: A — Tìm kiếm

- **Nhiệm vụ chung đã test**:  
  So sánh khả năng của ChatGPT và Perplexity khi giải thích một vấn đề pháp lý thực dụng cho startup AI tại Việt Nam: Nghị định 13/2023 về bảo vệ dữ liệu cá nhân.

- **Sản phẩm A**: ChatGPT — https://chatgpt.com/

- **Sản phẩm B**: Perplexity — https://www.perplexity.ai/

- **Câu prompt chính xác đã dùng**:

```text
Giải thích NĐ 13/2023 bảo vệ dữ liệu cá nhân của Việt Nam — áp dụng cho startup AI thế nào? Cho tôi 3 điều quan trọng nhất phải làm.
```

---

# S1 — Product Moment

Mục đích: định danh rõ 2 sản phẩm, nhiệm vụ chung, entry point và product moment chính của từng sản phẩm.

## S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A — ChatGPT | Sản phẩm B — Perplexity |
|---|---|---|
| Tên + URL | ChatGPT — https://chatgpt.com/ | Perplexity — https://www.perplexity.ai/ |
| Entry point | Giao diện chat với câu hỏi trung tâm “Chúng ta nên bắt đầu từ đâu?” và ô nhập có chế độ “Tìm kiếm web”. | Giao diện answer engine với logo “perplexity”, ô nhập “Ask anything...”, chế độ Search, nút Model và các tab Answer / Links / Images. |
| Ý định người dùng | Người dùng vào để hỏi, tìm kiếm, phân tích và nhận câu trả lời tổng hợp có thể dùng ngay. | Người dùng vào để tìm câu trả lời có nguồn, truy vết được citation và tiếp tục đào sâu bằng follow-up. |
| Surface chính | Chat interface kết hợp web search. | Answer engine / search interface kết hợp citations và follow-up. |
| Có cần đăng nhập / paywall ngay không | Ảnh test không thể hiện paywall; người dùng có thể nhập prompt trực tiếp. | Ảnh test không thể hiện paywall ngay; có thông báo “Free preview of advanced search enabled”, cho thấy một số năng lực nâng cao có thể bị giới hạn theo gói. |

## S1.2 — Bằng chứng ảnh tham chiếu

- `screenshots/product-chatgpt-1-entry.png` — ChatGPT hiển thị giao diện chat đơn giản, ô nhập “Tìm kiếm web”, phù hợp với người dùng muốn hỏi nhanh.
- `screenshots/product-chatgpt-2-input.png` — ChatGPT nhận prompt và hiển thị trạng thái đang tìm kiếm nguồn.
- `screenshots/product-perplexity-1-entry.png` — Perplexity định vị như answer engine với ô “Ask anything...” và các gợi ý tác vụ.
- `screenshots/product-perplexity-2-input.png` — Perplexity nhận prompt và hiển thị tab Answer / Links / Images cùng trạng thái Thinking.

## S1.3 — Nhận định so sánh entry point

ChatGPT tạo first impression tốt hơn với người dùng phổ thông vì giao diện chat quen thuộc, ít yếu tố gây phân tán và dễ bắt đầu ngay. Perplexity tạo first impression tốt hơn với người dùng có ý định research/search vì ngay từ entry point đã nhấn mạnh tìm kiếm, nguồn và follow-up. Với nhiệm vụ pháp lý cần kiểm chứng, Perplexity định vị đúng “search + trust” hơn; nhưng với người cần câu trả lời hành động nhanh, ChatGPT dễ tiếp cận hơn.

---

# S2 — Workflow Evidence

Mục đích: hiển thị luồng người dùng trước / trong / sau khi dùng AI và chỉ ra 3 friction areas.

## S2.1 — Luồng người dùng

```text
TRƯỚC khi gặp AI:
- Người dùng phải tự tìm văn bản NĐ 13/2023, đọc nội dung pháp lý, tìm bài phân tích phụ trợ, lọc nghĩa vụ liên quan startup AI, rồi tự chuyển thành checklist hành động.

TRONG khi dùng ChatGPT:
1. Người dùng nhập prompt vào ô chat có bật Tìm kiếm web.
2. ChatGPT tìm nguồn, suy nghĩ khoảng 10 giây và trả lời theo cấu trúc: giải thích NĐ 13, áp dụng cho startup AI, 3 việc cần làm.
3. Output nhấn mạnh consent, DPIA/data map, quyền người dùng + bảo mật + xử lý sự cố.

TRONG khi dùng Perplexity:
1. Người dùng nhập cùng prompt vào ô Ask anything.
2. Perplexity trả lời theo mô hình answer engine, có citation gắn trong nội dung và chỉ báo nhiều sources.
3. Output có thêm follow-up và gợi ý triển khai 30/60/90 ngày.

SAU khi dùng AI:
- Người dùng vẫn cần kiểm chứng nguồn chính thức, đối chiếu với luật sư hoặc văn bản gốc, rồi chuyển output thành policy, data map, checklist kỹ thuật và quy trình vận hành nội bộ.
```

## S2.2 — 3 Friction Areas

| Friction | ChatGPT | Perplexity |
|---|---|---|
| **Physical load** | Giảm mạnh số tab và thao tác so với tự Google; người dùng nhập một prompt và nhận checklist hành động gần như dùng được ngay. | Cũng giảm mạnh thao tác tìm kiếm; tuy nhiên người dùng có thể cần mở thêm sources/follow-up để kiểm chứng sâu hơn. |
| **Cognitive burden** | Giảm tải nhận thức tốt cho người mới vì câu trả lời được đóng gói thành 3 việc cần làm, dễ hiểu và có ví dụ data map. | Giảm tải phần tìm kiếm nguồn, nhưng yêu cầu người dùng biết đánh giá nguồn nào đủ tin cậy cho câu hỏi pháp lý. |
| **User workarounds** | Người dùng phải tự mở và kiểm tra lại nguồn vì citation chưa nổi bật thành danh sách riêng. | Người dùng phải tự lọc nguồn, rút gọn câu trả lời dài và chuyển thành checklist nội bộ. |

## S2.3 — Bằng chứng

- `screenshots/product-chatgpt-2-input.png` — ChatGPT hiển thị trạng thái đang tìm kiếm `vanban.chinhphu.vn`.
- `screenshots/product-chatgpt-3-output.png` — ChatGPT giải thích NĐ 13/2023 và bối cảnh áp dụng cho startup AI.
- `screenshots/product-chatgpt-5-output.png` — ChatGPT đưa bảng data map với audio cuộc họp, transcript, prompt chat, nơi lưu và quyền truy cập.
- `screenshots/product-perplexity-3-output.png` — Perplexity trả lời theo dạng bullet có citation.
- `screenshots/product-perplexity-5-output.png` — Perplexity có follow-ups và gợi ý triển khai 30/60/90 ngày.

## S2.4 — Nhận định: sản phẩm nào giảm friction tốt hơn?

ChatGPT giảm friction tốt hơn ở bước biến thông tin pháp lý thành hành động cụ thể vì output ngắn gọn, có cấu trúc và dễ copy thành checklist. Perplexity giảm friction tốt hơn ở bước tìm kiếm và truy vết nguồn vì citation rõ hơn và có nhiều nguồn đi kèm. Nếu mục tiêu là “hiểu nhanh và biết làm gì”, ChatGPT nhỉnh hơn. Nếu mục tiêu là “kiểm chứng nguồn và đào sâu”, Perplexity nhỉnh hơn.

---

# S3 — Output & Trust

Mục đích: đánh giá chất lượng output và 6 tín hiệu đáng tin.

## S3.1 — Chất lượng output

### Sản phẩm A — ChatGPT

- **Output có trả lời đúng câu hỏi chính không?**  
  Có. ChatGPT trả lời đúng yêu cầu “áp dụng cho startup AI thế nào” và “3 điều quan trọng nhất phải làm”.

- **Output có bịa thông tin không?**  
  Trong phạm vi ảnh test, chưa phát hiện điểm bịa rõ ràng. Tuy nhiên, vì đây là chủ đề pháp lý, các chi tiết như nghĩa vụ thông báo, thời hạn, phạm vi áp dụng cần kiểm tra lại với văn bản gốc.

- **Output có đầy đủ hay nửa vời?**  
  Tương đối đầy đủ ở mức thực dụng. ChatGPT không chỉ tóm tắt NĐ 13 mà còn đưa ra checklist gồm consent, DPIA/data map, quyền người dùng, bảo mật, log xử lý dữ liệu và thông báo sự cố.

### Sản phẩm B — Perplexity

- **Output có trả lời đúng câu hỏi chính không?**  
  Có. Perplexity trả lời đúng theo 3 việc startup AI cần làm: minh bạch/consent, đánh giá rủi ro/ghi chép, và bảo mật/quản lý nhà cung cấp.

- **Output có bịa thông tin không?**  
  Trong phạm vi ảnh test, chưa thấy điểm bịa rõ ràng. Điểm cần kiểm chứng là chất lượng từng nguồn vì một số nguồn có thể là bài tổng hợp, không phải văn bản pháp lý gốc.

- **Output có đầy đủ hay nửa vời?**  
  Đầy đủ cho một câu trả lời nghiên cứu nhanh. Perplexity có citation, giải thích theo bullet, gợi ý bước triển khai và follow-up.

## S3.2 — 6 Tín hiệu đáng tin

| Tín hiệu | ChatGPT | Perplexity |
|---|---|---|
| 1. Dẫn nguồn | **Một phần** — có tag nguồn như LuatVietnam, Văn Bản Chính Phủ, nhưng không nổi bật thành danh sách nguồn riêng. | **Có** — citation rõ trong từng đoạn và có chỉ báo “10 sources”. |
| 2. Disclaimer khi không chắc | **Có** — giao diện có dòng “ChatGPT có thể mắc lỗi. Hãy kiểm tra các thông tin quan trọng.” | **Một phần / chưa rõ** — ảnh không thể hiện disclaimer pháp lý nổi bật. |
| 3. Fallback / dừng lại khi out-of-scope | **Chưa quan sát được** — prompt nằm trong phạm vi trả lời. | **Chưa quan sát được** — prompt nằm trong phạm vi search/research. |
| 4. Consistency | **Chưa kiểm chứng** — nhóm mới ghi nhận một lần chạy chính thức. | **Chưa kiểm chứng** — nhóm mới ghi nhận một lần chạy chính thức. |
| 5. User control | **Có** — có dừng, copy, like/dislike, regenerate. | **Có** — có follow-up, feedback, copy/share/regenerate. |
| 6. Explanation | **Một phần** — giải thích vì sao startup AI cần consent, DPIA/data map, quyền người dùng và bảo mật. | **Một phần** — giải thích kèm citation, nhưng chưa nói rõ logic xếp hạng nguồn. |

## S3.3 — Nhận định: sản phẩm nào tạo trust mạnh hơn?

Perplexity tạo trust mạnh hơn về mặt citation và truy vết nguồn vì nguồn hiển thị rõ, có chỉ báo số lượng sources và citation xuất hiện ngay trong nội dung. ChatGPT tạo trust tốt ở mặt tổng hợp và actionable output, nhưng citation hiển thị nhỏ hơn nên người dùng phải tự kiểm chứng kỹ. Với câu hỏi pháp lý, Perplexity phù hợp hơn cho bước research ban đầu có nguồn; ChatGPT phù hợp hơn cho bước biến research thành checklist thực thi.

---

# S4 — Business Signal

Mục đích: định vị hai sản phẩm trên Cost-Capability-Speed và pricing pattern.

## S4.1 — Định vị tam giác

- **ChatGPT**: **cân bằng, thiên về capability rộng** — model dưới mui xe không hiển thị cụ thể trong ảnh, nhưng giao diện có chế độ Thinking và Tìm kiếm web.  
  **Lý do**: ChatGPT có free entry, gói trả phí phổ biến và xử lý được nhiều tác vụ ngoài tìm kiếm như học tập, viết, code, phân tích, lập kế hoạch.

- **Perplexity**: **mạnh trong capability hẹp của search/research** — model dưới mui xe không hiển thị cụ thể trong ảnh, nhưng có nút Model và thông báo Free preview of advanced search enabled.  
  **Lý do**: Perplexity tập trung vào answer engine, citation, source visibility và follow-up, nên mạnh hơn trong use case tìm kiếm có nguồn.

## S4.2 — Pricing pattern

| Yếu tố | ChatGPT | Perplexity |
|---|---|---|
| Mô hình giá | Freemium + premium + business/enterprise. | Freemium + Pro + Max + enterprise. |
| Giá entry | Free plan có giới hạn lượt dùng, upload, deep research, memory/context. | Free plan có thể dùng search cơ bản; một số trải nghiệm nâng cao có giới hạn hoặc free preview. |
| Giá trả phí | ChatGPT Plus khoảng **$20/tháng**; Business/Enterprise có pricing riêng hoặc theo user. Nguồn: OpenAI Pricing. | Perplexity Pro khoảng **$20/tháng hoặc $200/năm**; Enterprise Pro khoảng **$40/seat/tháng**, Enterprise Max khoảng **$325/seat/tháng**. Nguồn: Perplexity Help Center. |
| Paywall xuất hiện ở đâu | Khi cần nhiều lượt hơn, model tốt hơn, deep research, agent mode, context/memory rộng hơn, business controls. | Khi cần Pro Search sâu hơn, model nâng cao, connector, enterprise features, usage analytics, file/internal knowledge search. |

## S4.3 — Nhận định chiến lược kinh doanh

ChatGPT đi theo chiến lược platform rộng: một assistant đa năng cho nhiều use case cá nhân, học tập, công việc và enterprise. Perplexity đi theo chiến lược niche sâu hơn: answer engine và research workflow có citation, nguồn và follow-up. Vì cùng mức giá consumer khoảng $20/tháng, khác biệt không nằm ở giá mà nằm ở value proposition: ChatGPT bán breadth, Perplexity bán trust/search UX.

---

# S5 — Product Judgment

Mục đích: ra verdict, phân tích định lượng/định tính và liên hệ với Lab 1.

## S5.1 — Verdict

- **ChatGPT**: **Strong**  
  **Lý do**: ChatGPT có độ phủ use case rộng, product quality mạnh, giao diện quen thuộc, khả năng tổng hợp tốt và lợi thế platform/distribution rất lớn.

- **Perplexity**: **Promising**  
  **Lý do**: Perplexity có niche rõ trong tìm kiếm có nguồn, citation UX tốt và phù hợp research workflow, nhưng bị áp lực từ các platform lớn nếu họ tích hợp search/citation vào assistant đa dụng.

---

## S5.2 — User base + tăng trưởng

### ChatGPT

- OpenAI công bố ChatGPT có hơn **900 triệu weekly active users** và hơn **50 triệu subscribers** trong thông báo ngày 31/03/2026.
- OpenAI cũng công bố ChatGPT đã đạt **$1B revenue trong vòng một năm sau khi launch**, đạt **$1B/quý vào cuối 2024**, và đang tạo **$2B revenue mỗi tháng** theo cùng nguồn.
- **Nguồn**: OpenAI, “OpenAI raises $122 billion to accelerate the next phase of AI”, 31/03/2026 — https://openai.com/index/accelerating-the-next-phase-ai/

### Perplexity

- Không tìm thấy số MAU/DAU/paid users chính thức đủ rõ trên trang chủ trong phạm vi bài.  
- Tín hiệu công khai có thể dùng: trang Perplexity Enterprise Customers ghi **20,000+ organizations** và nhiều case enterprise có các chỉ số như adoption rate, monthly queries, hours saved.
- **Nguồn**: Perplexity Enterprise Customers — https://www.perplexity.ai/enterprise/customers
- **Ghi chú**: MAU/DAU/paid users của Perplexity là vùng bằng chứng yếu hơn ChatGPT vì thiếu số liệu chính thức trực tiếp trong phạm vi bài.

---

## S5.3 — Doanh thu / pricing power

### ChatGPT

- **ARR/MRR công khai**: OpenAI công bố đang tạo **$2B revenue mỗi tháng** trong thông báo tháng 03/2026.
- **Pricing strategy**: Freemium → Plus/Pro → Business/Enterprise.
- **Giá consumer nổi bật**: Plus khoảng **$20/tháng**.
- **Nguồn pricing**: OpenAI Pricing — https://openai.com/pricing hoặc https://chatgpt.com/pricing/

### Perplexity

- **ARR/MRR công khai**: Không có số doanh thu chính thức đủ rõ trong phạm vi bài.
- **Pricing strategy**: Freemium → Pro/Max → Enterprise Pro/Enterprise Max.
- **Giá consumer nổi bật**:
  - Perplexity Pro: **$20/tháng hoặc $200/năm**
  - Perplexity Max: **$200/tháng hoặc $2,000/năm**
- **Enterprise pricing**:
  - Enterprise Pro: **$40/seat/tháng hoặc $400/seat/năm**
  - Enterprise Max: **$325/seat/tháng hoặc $3,250/seat/năm**
- **Nguồn**:
  - Perplexity Help Center — Using the Connector for Slack
  - Perplexity Enterprise Onboarding Guide

### Nhận định pricing power

ChatGPT có pricing power mạnh hơn vì cùng một khoản phí trả hàng tháng nhưng bao phủ nhiều use case hơn. Perplexity vẫn có pricing power trong nhóm người dùng cần research/search có citation, đặc biệt ở enterprise, nhưng cần chứng minh value đủ khác biệt khi ChatGPT/Gemini cải thiện search.

---

## S5.4 — Moat phân tích

| Moat | ChatGPT | Perplexity |
|---|---|---|
| **Data moat** | **Trung bình → mạnh** — lượng hội thoại lớn, feedback, memory, enterprise deployment tạo loop rộng; tuy nhiên dữ liệu hội thoại không phải proprietary theo nghĩa tuyệt đối. | **Trung bình** — có dữ liệu query, source click, follow-up và workflow research; nhưng moat hẹp hơn và dễ bị platform lớn mô phỏng. |
| **Network effects** | **Trung bình** — không phải network effect kiểu social network, nhưng có hiệu ứng lan truyền, GPTs, workspace, enterprise adoption. | **Yếu → trung bình** — network effect chưa rõ; giá trị chủ yếu đến từ chất lượng search/citation chứ không phải số người dùng. |
| **Switching cost** | **Trung bình** — Projects, memory, custom GPTs, history, business workspace tạo switching cost tăng dần. | **Yếu → trung bình** — Threads, Spaces, enterprise connectors tạo switching cost, nhưng người dùng cá nhân vẫn có thể chuyển sang ChatGPT/Gemini khá dễ. |
| **Brand** | **Rất mạnh** — ChatGPT gần như trở thành tên gọi đại diện cho chatbot AI phổ thông. | **Trung bình** — nổi bật trong nhóm AI search/research nhưng brand đại chúng yếu hơn ChatGPT. |
| **Distribution** | **Rất mạnh** — web, mobile, enterprise, API, partner ecosystem và độ phủ consumer rất lớn. | **Trung bình** — có web/mobile/enterprise/browser direction, nhưng distribution yếu hơn các platform lớn. |

### Nhận định moat

ChatGPT thắng lớn ở **brand + distribution + platform breadth**. Perplexity có moat tốt ở **trust UX + citation + research workflow**, nhưng moat này có nguy cơ bị copy nếu các platform lớn tích hợp citation/source UX tốt hơn. Vì vậy, Perplexity cần đào sâu workflow nghiên cứu, enterprise knowledge search và source quality để chống bị commoditize.

---

## S5.5 — Data flywheel + feedback loop

### ChatGPT

ChatGPT có flywheel rộng: nhiều người dùng → nhiều hội thoại và feedback → cải thiện sản phẩm/model/UX → nhiều use case hơn → tăng tần suất dùng → tiếp tục tạo thêm dữ liệu tương tác. Loop này có compounding mạnh vì ChatGPT không chỉ là tool search mà là assistant đa dụng cho học tập, viết, code, phân tích, công việc và enterprise.

### Perplexity

Perplexity có flywheel hẹp hơn nhưng rõ trong research/search: query → source click → follow-up → đánh giá câu trả lời → cải thiện ranking/citation/answer quality. Loop có compounding một phần, đặc biệt trong enterprise research workflow, nhưng yếu hơn ChatGPT vì phạm vi use case và distribution hẹp hơn.

### Nhận định

Compounding power: **ChatGPT > Perplexity**. Perplexity vẫn có cơ hội nếu biến source-backed research thành workflow sâu, có internal knowledge search, Spaces, connector và enterprise admin controls.

---

## S5.6 — Niche Down + AI Feature Map

### ChatGPT

- **Niche cụ thể**: General-purpose AI assistant cho người dùng cá nhân, sinh viên, nhân viên văn phòng, founder/startup và doanh nghiệp cần hỏi đáp, viết, phân tích, học tập, code, nghiên cứu nhanh.
- **AI Feature Map**:
  - **User Value: Cao** — một công cụ dùng được cho nhiều tác vụ khác nhau, từ câu hỏi pháp lý đến viết tài liệu, phân tích bảng, code và lập kế hoạch.
  - **User Alignment: Cao** — trong bài test, ChatGPT hiểu đúng ý định “áp dụng cho startup AI” và trả lời theo hướng hành động.
  - **Business Value: Cao** — market rộng, pricing nhiều tầng, dễ upsell từ free sang Plus/Pro/Business/Enterprise.

### Perplexity

- **Niche cụ thể**: Answer engine / research assistant cho người dùng cần câu trả lời có nguồn, citation rõ và follow-up phục vụ tìm kiếm/nghiên cứu.
- **AI Feature Map**:
  - **User Value: Cao trong niche search/research** — giúp người dùng nhanh chóng có câu trả lời kèm nguồn thay vì tự mở nhiều tab.
  - **User Alignment: Rất cao với câu hỏi cần nguồn** — trong bài test pháp lý, citation và sources giúp tăng cảm giác đáng tin.
  - **Business Value: Cao nhưng niche-dependent** — có giá trị với researcher, consultant, founder, legal/business team; tuy nhiên dễ bị platform lớn cạnh tranh nếu khác biệt chỉ là “AI search có nguồn”.

---

## S5.7 — Spark → Loop → System

### ChatGPT

- **Giai đoạn**: **System**
- **Lý do**: ChatGPT đã vượt qua mức Spark/Loop vì người dùng có thể dùng nó như assistant mặc định cho nhiều tác vụ hằng ngày: hỏi đáp, viết, code, phân tích, học tập, research, làm việc nhóm và enterprise.
- **Dự báo 12 tháng tới**: ChatGPT có khả năng tiếp tục mở rộng vai trò platform system, đặc biệt nếu search, projects, memory, agent mode và enterprise workspace ngày càng liền mạch.

### Perplexity

- **Giai đoạn**: **Loop → System trong niche hẹp**
- **Lý do**: Perplexity có repeat-use loop rõ trong search/research nhờ citation, follow-up và sources; tuy nhiên chưa phải default system cho mọi tác vụ của đa số người dùng.
- **Dự báo 12 tháng tới**: Perplexity có thể tiến gần System hơn trong niche research/search nếu mở rộng browser, enterprise knowledge search, internal connectors và workflow lưu trữ tri thức. Nhưng ở thị trường đại chúng, Perplexity vẫn chịu áp lực mạnh từ ChatGPT/Gemini.

---

## S5.8 — Liên hệ Lab 1

### Case Lab 1 đã phân tích

Lab 1 của nhóm đã phân tích case **Chegg bị ChatGPT/OpenAI gây áp lực**. Bài học chính: sản phẩm chỉ bán “câu trả lời” mà không sở hữu workflow sâu, distribution mạnh hoặc data flywheel riêng sẽ dễ bị big tech AI ép giá trị.

### ChatGPT có rủi ro disruption tương tự Chegg không?

ChatGPT có rủi ro thấp hơn trong bài test này vì chính ChatGPT là một trong các platform tạo ra kỳ vọng mới của người dùng. Thay vì bị big tech AI thay thế, ChatGPT hiện là sản phẩm đang mở rộng để nuốt thêm các use case như search, writing, coding, research và business workflow.

### Perplexity có rủi ro disruption tương tự Chegg không?

Perplexity có rủi ro disruption-style cao hơn ChatGPT. Nếu ChatGPT, Gemini hoặc các platform lớn tích hợp citation, source panel, follow-up và research workflow tốt hơn, khác biệt “AI search có nguồn” của Perplexity có thể bị thu hẹp. Tuy nhiên, Perplexity vẫn có cơ hội nếu đào sâu vào trust UX, enterprise search, internal knowledge và browser/workflow integration.

### Bài học rút từ Lab 1 áp dụng cho 2 sản phẩm

Bài học từ Chegg là: sản phẩm AI không nên chỉ bán output đơn lẻ. Sản phẩm sống sót tốt hơn khi kiểm soát workflow trước/trong/sau, có moat phân phối, có data flywheel và tạo switching cost rõ. Trong Lab 2, ChatGPT mạnh vì có platform breadth và distribution; Perplexity muốn tránh “Chegg hóa” thì cần biến citation/search thành một workflow nghiên cứu sâu chứ không chỉ là câu trả lời có nguồn.

---

# Bảng kiểm trước khi build slide

- [x] S1 → S4 đã điền đầy đủ.
- [x] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành.
- [x] S5.2 → S5.5 đã hoàn thành; các số liệu không có nguồn công khai đã ghi rõ.
- [x] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [x] Verdict ở S5.1 nhất quán với phân tích moat ở S5.4 và giai đoạn ở S5.7.
- [x] 2 thành viên có thể dùng outline này để build slide deck chung.

---

# Gợi ý cấu trúc slide deck từ outline

| Slide | Nội dung |
|---|---|
| 1 | Cover: Lab 2 — ChatGPT vs Perplexity |
| 2 | S1 — Product Moment |
| 3 | S2 — Workflow Evidence |
| 4 | S3 — Output & Trust |
| 5 | S4 — Business Signal |
| 6 | S5.1–S5.4 — Verdict, User base, Pricing, Moat |
| 7 | S5.5–S5.7 — Data flywheel, Niche Map, Spark→Loop→System |
| 8 | S5.8 — Liên hệ Lab 1 + Kết luận |

---

# Nguồn tham khảo public dùng cho phần S4–S5

1. OpenAI Pricing — https://openai.com/pricing hoặc https://chatgpt.com/pricing/
2. OpenAI, “OpenAI raises $122 billion to accelerate the next phase of AI”, 31/03/2026 — https://openai.com/index/accelerating-the-next-phase-ai/
3. Perplexity — https://www.perplexity.ai/
4. Perplexity Help Center — Using the Connector for Slack — thông tin Perplexity Pro, Max và Enterprise pricing.
5. Perplexity Enterprise Customers — https://www.perplexity.ai/enterprise/customers
6. Perplexity Enterprise Onboarding Guide — thông tin Enterprise Pro và Enterprise Max pricing.
