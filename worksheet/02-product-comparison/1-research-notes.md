---
artifact: 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Thử nghiệm + chụp ảnh + research
input: group-members.md
nop-cuoi: Không — file trung gian
---

# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

Mục tiêu của file này là ghi lại quan sát thật khi nhóm test hai sản phẩm AI với cùng một nhiệm vụ, cùng một prompt và có ảnh chụp làm bằng chứng. File này là đầu vào cho `2-comparison-table.md` và slide deck `analysis-report.pdf`.

---

## Phần A — Setup chung

- **Nhiệm vụ chung**: So sánh khả năng của ChatGPT và Perplexity khi giải thích một vấn đề pháp lý thực dụng cho startup AI tại Việt Nam, cụ thể là Nghị định 13/2023 về bảo vệ dữ liệu cá nhân.
- **Câu prompt chính xác**:

```text
Giải thích NĐ 13/2023 bảo vệ dữ liệu cá nhân của Việt Nam — áp dụng cho startup AI thế nào? Cho tôi 3 điều quan trọng nhất phải làm.
```

- **Ngành chọn**: A — Tìm kiếm
- **Sản phẩm A**: ChatGPT — https://chatgpt.com/
- **Sản phẩm B**: Perplexity — https://www.perplexity.ai/
- **Loại tài khoản dùng**:
  - Sản phẩm A: ChatGPT, giao diện web, có bật chế độ **Tìm kiếm web**. Ảnh chụp cho thấy model đang ở chế độ **Thinking**.
  - Sản phẩm B: Perplexity, giao diện web. Ảnh chụp cho thấy có thông báo **Free preview of advanced search enabled** và có lựa chọn model, nhưng ảnh không hiển thị chính xác model cụ thể.
- **Trình duyệt + thời gian test**: Trình duyệt web trên máy tính. Thời gian test không được ghi timestamp chính xác trong ảnh, nên nhóm ghi nhận theo phiên test Lab 2.

---

## Phần B — Log Sản phẩm A

**Tên sản phẩm A**: ChatGPT  
**URL**: https://chatgpt.com/  
**Model dưới mui xe**: Không hiển thị tên model cụ thể trong ảnh; giao diện cho thấy đang dùng chế độ **Thinking** và **Tìm kiếm web**.

### B.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy giao diện chat quen thuộc với câu hỏi trung tâm **“Chúng ta nên bắt đầu từ đâu?”** và ô nhập có placeholder **“Tìm kiếm web”**.

- **Trang đầu / màn hình đầu hiển thị gì?**  
  ChatGPT hiển thị một ô nhập lớn ở giữa màn hình, kèm nút `+`, tùy chọn **Tìm kiếm**, biểu tượng micro và nút gửi/voice màu đen. Bên dưới có một số gợi ý/truy vấn gần đây như “Kết Quả U17 Châu Á”, “Bùi Đình Khánh”, “Xem Bong Da Truc Tiep”, “Miu Le Bi Bat”.
- **Có hint / sample prompt sẵn không?**  
  Có các gợi ý/truy vấn gần đây, nhưng không phải sample prompt trực tiếp cho nhiệm vụ pháp lý.
- **Cần đăng nhập / paywall trước khi dùng không?**  
  Ảnh không thể hiện paywall. Giao diện cho phép nhập prompt trực tiếp.
- **Ảnh đã chụp**: `screenshots/product-chatgpt-1-entry.png`

### B.2 — Khi gõ prompt + nhận output

- **Thời gian phản hồi**: Khoảng **10 giây**, vì ảnh output hiển thị dòng **“Đã suy nghĩ trong 10s”**.
- **Có hiển thị “AI đang nghĩ...” / streaming hay đứng yên?**  
  Có. Ảnh input cho thấy ChatGPT hiển thị trạng thái đang xử lý và dòng **“Đang tìm kiếm vanban.chinhphu.vn”**.
- **Output dài bao nhiêu?**  
  Output dài, được chia thành nhiều đoạn và tiêu đề rõ ràng. Dựa trên ảnh, nội dung gồm phần giải thích tổng quan về NĐ 13/2023, phần áp dụng cho startup AI, 3 việc quan trọng nhất phải làm, ví dụ bảng data map và lưu ý riêng cho startup AI.
- **Output có dẫn nguồn không?**  
  Có dẫn nguồn, nhưng hiển thị dưới dạng tag nhỏ trong nội dung như **“Văn Bản Chính Ph...”**, **“LuatVietnam”**, **“LuatVietnam +1”**. Nguồn có xuất hiện nhưng không nổi bật thành một danh sách nguồn riêng ở cuối câu trả lời.
- **Có hiển thị disclaimer / cảnh báo không?**  
  Có dòng cảnh báo ở cuối giao diện: **“ChatGPT có thể mắc lỗi. Hãy kiểm tra các thông tin quan trọng.”**
- **Ảnh đã chụp**:
  - `screenshots/product-chatgpt-2-input.png`
  - `screenshots/product-chatgpt-3-output.png`
  - `screenshots/product-chatgpt-4-output.png`
  - `screenshots/product-chatgpt-5-output.png`
  - `screenshots/product-chatgpt-6-output.png`

### B.3 — Phản hồi sau khi nhận output

- **Có nút “regenerate” / “thử lại” không?**  
  Có biểu tượng làm mới/regenerate ở cuối câu trả lời.
- **Có nút copy / export ra format khác không?**  
  Có nút copy ở cuối câu trả lời. Ảnh không thể hiện export ra file riêng.
- **Có gợi ý câu hỏi tiếp theo không?**  
  Trong ảnh không thấy phần follow-up suggestion rõ ràng. ChatGPT kết thúc bằng tóm tắt và để người dùng nhập câu hỏi tiếp theo trong ô chat.
- **Có lưu lịch sử để truy lại không?**  
  Giao diện ChatGPT có cuộc hội thoại hiện tại; ảnh không thể hiện sidebar lịch sử nhưng mặc định sản phẩm có lưu cuộc trò chuyện nếu người dùng đăng nhập.
- **Có thumb up / thumb down để feedback không?**  
  Có biểu tượng like/dislike ở cuối câu trả lời.

### B.4 — Quan sát nổi

1. **ChatGPT đóng gói câu trả lời theo hướng hành động rất rõ**.  
   Trong output, ChatGPT không chỉ giải thích NĐ 13/2023 mà còn chuyển thành 3 việc startup AI cần làm: xin consent rõ ràng, làm DPIA/data map, thiết kế quyền người dùng + bảo mật + quy trình sự cố.  
   **Tham chiếu ảnh**: `screenshots/product-chatgpt-3-output.png`, `screenshots/product-chatgpt-4-output.png`, `screenshots/product-chatgpt-6-output.png`.

2. **ChatGPT đưa ví dụ rất sát với sản phẩm AI**.  
   Output có ví dụ về audio cuộc họp, transcript, prompt chat, lưu ở đâu, ai được truy cập, có gửi sang API/cloud nước ngoài không và lưu bao lâu. Điều này hữu ích cho startup AI hoặc sản phẩm AI meeting/classroom.  
   **Tham chiếu ảnh**: `screenshots/product-chatgpt-5-output.png`.

3. **Điểm yếu chính là nguồn chưa nổi bật bằng Perplexity**.  
   ChatGPT có tag nguồn như LuatVietnam hoặc Văn Bản Chính Phủ, nhưng người dùng phải tự nhìn kỹ trong dòng văn bản. Không có danh sách nguồn rõ như Perplexity.  
   **Tham chiếu ảnh**: `screenshots/product-chatgpt-3-output.png`, `screenshots/product-chatgpt-6-output.png`.

---

## Phần C — Log Sản phẩm B

**Tên sản phẩm B**: Perplexity  
**URL**: https://www.perplexity.ai/  
**Model dưới mui xe**: Không hiển thị tên model cụ thể trong ảnh. Giao diện có nút **Model** và thông báo **Free preview of advanced search enabled**.

### C.1 — Entry point + lần chạm đầu

Perplexity bắt đầu từ giao diện **answer engine** với logo “perplexity” ở giữa, ô nhập **“Ask anything...”**, lựa chọn chế độ **Search**, nút **Model**, và các gợi ý theo tác vụ như Lead generation, Create a prototype, Help me learn.

- **Trang đầu / màn hình đầu hiển thị gì?**  
  Trang đầu hiển thị logo Perplexity, thanh nhập chính, menu Discover/Finance/Health/Academic/Patents và khối **Try Computer** với các ví dụ tác vụ.
- **Có hint / sample prompt sẵn không?**  
  Có. Perplexity gợi ý một số tác vụ như **Find decision-makers at a company**, **Find potential integration partners**, **Build a target list of investors for my startup**.
- **Cần đăng nhập / paywall trước khi dùng không?**  
  Ảnh không thể hiện paywall trước khi nhập prompt. Tuy nhiên, trong quá trình dùng có hiện thông báo **Free preview of advanced search enabled**, cho thấy một số trải nghiệm nâng cao có thể liên quan đến gói Pro/trial.
- **Ảnh đã chụp**: `screenshots/product-perplexity-1-entry.png`

### C.2 — Khi gõ prompt + nhận output

- **Thời gian phản hồi**: Ảnh không ghi thời gian chính xác. Có trạng thái **Thinking** khi đang xử lý.
- **Có hiển thị “AI đang nghĩ...” / streaming hay đứng yên?**  
  Có. Ảnh input cho thấy Perplexity hiển thị trạng thái **Thinking**.
- **Output dài bao nhiêu?**  
  Output dài, gồm tóm tắt ngắn, 3 việc quan trọng startup AI phải làm, phần giải thích theo bullet, các điểm thực tế cần lưu ý và gợi ý bước triển khai 30/60/90 ngày.
- **Output có dẫn nguồn không?**  
  Có. Perplexity hiển thị citation trực tiếp trong từng đoạn như **baovedlcn +1**, **giaothongso.com +1**, **congtyai +1**, **cystack +1**, và cuối câu trả lời có chỉ báo **10 sources**.
- **Có hiển thị disclaimer / cảnh báo không?**  
  Không thấy disclaimer pháp lý rõ ràng trong ảnh. Output có tính chất khuyến nghị hành động, nhưng không hiển thị cảnh báo nổi bật rằng không thay thế tư vấn pháp lý.
- **Ảnh đã chụp**:
  - `screenshots/product-perplexity-2-input.png`
  - `screenshots/product-perplexity-3-output.png`
  - `screenshots/product-perplexity-4-output.png`
  - `screenshots/product-perplexity-5-output.png`

### C.3 — Phản hồi sau khi nhận output

- **Có nút “regenerate” / “thử lại” không?**  
  Có biểu tượng làm mới/regenerate ở cuối câu trả lời.
- **Có nút copy / export ra format khác không?**  
  Có các biểu tượng thao tác ở cuối output, gồm nút copy/chia sẻ/tải xuống. Ở góc trên phải giao diện còn có nút **Share** và **Download Comet**.
- **Có gợi ý câu hỏi tiếp theo không?**  
  Có. Perplexity hiển thị phần **Follow-ups**, ví dụ:
  - “3 việc startup AI ở Việt Nam hay bỏ sót khi áp dụng NĐ 13/2023 — và checklist tuân thủ để làm ngay”
  - Một gợi ý khác bắt đầu bằng “Startup AI phải...”
- **Có lưu lịch sử để truy lại không?**  
  Giao diện thể hiện thread hiện tại; ảnh không cho thấy rõ lịch sử bên sidebar.
- **Có thumb up / thumb down để feedback không?**  
  Có biểu tượng like/dislike ở cuối câu trả lời.

### C.4 — Quan sát nổi

1. **Perplexity thể hiện vai trò answer engine rõ hơn ChatGPT**.  
   Ngay từ entry point, Perplexity đặt người dùng vào bối cảnh tìm kiếm có nguồn với ô **Ask anything...**, chế độ **Search**, tab **Answer / Links / Images** và các nguồn gắn trong output.  
   **Tham chiếu ảnh**: `screenshots/product-perplexity-1-entry.png`, `screenshots/product-perplexity-2-input.png`, `screenshots/product-perplexity-3-output.png`.

2. **Nguồn và citation nổi bật hơn**.  
   Output có citation gắn sau từng luận điểm và cuối câu trả lời có chỉ báo **10 sources**. Điều này làm người dùng dễ truy vết hơn khi câu hỏi liên quan đến pháp lý.  
   **Tham chiếu ảnh**: `screenshots/product-perplexity-3-output.png`, `screenshots/product-perplexity-5-output.png`.

3. **Perplexity có follow-up tốt cho workflow nghiên cứu**.  
   Sau khi trả lời, Perplexity tự gợi ý các câu hỏi tiếp theo và đề xuất bước triển khai 30/60/90 ngày. Điều này giúp người dùng tiếp tục đào sâu thay vì dừng ở câu trả lời đầu tiên.  
   **Tham chiếu ảnh**: `screenshots/product-perplexity-5-output.png`.

---

## Phần D — First impressions

### 1. Sản phẩm nào “cảm giác” dễ dùng hơn lần đầu? Tại sao?

**ChatGPT dễ dùng hơn với người dùng phổ thông** vì giao diện chat quen thuộc, ít yếu tố gây phân tán và câu trả lời được trình bày theo hướng tóm gọn, dễ copy thành checklist hành động. Ảnh ChatGPT cho thấy người dùng chỉ cần nhập prompt vào ô chat, hệ thống tự tìm kiếm và trả lời theo cấu trúc rõ.

Tuy nhiên, **Perplexity dễ dùng hơn nếu mục tiêu là tìm kiếm có nguồn**, vì giao diện ngay từ đầu đã định vị như một answer engine, có tab Answer/Links/Images, có sources và follow-ups rõ ràng.

### 2. Sản phẩm nào “cảm giác” cho output đáng tin hơn? Tại sao?

**Perplexity tạo cảm giác đáng tin hơn về mặt truy vết nguồn**, vì citation hiển thị rõ trong từng đoạn, có chỉ báo **10 sources**, và người dùng thấy ngay sản phẩm đang dựa trên nhiều nguồn web.

**ChatGPT tạo cảm giác đáng tin ở mặt tổng hợp và hành động**, vì output có cấu trúc rõ, giải thích dễ hiểu và đưa ví dụ data map sát với startup AI. Tuy nhiên, nguồn của ChatGPT ít nổi bật hơn nên cần người dùng tự kiểm tra lại kỹ hơn.

### 3. Câu hỏi mà nhóm chưa trả lời được sau 20 phút test

- Nguồn nào trong output của từng sản phẩm là nguồn chính thức nhất và có nên ưu tiên văn bản gốc từ Chính phủ/Bộ Công an hơn các bài tổng hợp hay không?
- Nếu startup AI xử lý transcript/audio/prompt của người dùng Việt Nam nhưng dùng API hoặc cloud nước ngoài, nghĩa vụ chuyển dữ liệu ra nước ngoài theo NĐ 13/2023 cần thực hiện cụ thể đến mức nào?
- Số liệu business như MAU, DAU, paid users và doanh thu chính thức của Perplexity chưa có đủ nguồn công khai rõ ràng trong phiên test ngắn.

---

## Bảng kiểm trước khi sang Bước 2

- [x] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [x] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm.
- [x] Mỗi quan sát có ảnh/log tham chiếu.
- [x] First impressions ghi rõ lý do, không chỉ nói chung chung “tốt hơn”.
- [x] Đã trả lời trách nhiệm nhóm trong `group-members.md`.

---

## Danh sách ảnh tham chiếu

### ChatGPT

- `screenshots/product-chatgpt-1-entry.png`
- `screenshots/product-chatgpt-2-input.png`
- `screenshots/product-chatgpt-3-output.png`
- `screenshots/product-chatgpt-4-output.png`
- `screenshots/product-chatgpt-5-output.png`
- `screenshots/product-chatgpt-6-output.png`

### Perplexity

- `screenshots/product-perplexity-1-entry.png`
- `screenshots/product-perplexity-2-input.png`
- `screenshots/product-perplexity-3-output.png`
- `screenshots/product-perplexity-4-output.png`
- `screenshots/product-perplexity-5-output.png`
