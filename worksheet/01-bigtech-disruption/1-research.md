---
artifact: 1 — Tự nghiên cứu case
bai-tap: 1 — Tìm 1 case bị ảnh hưởng bởi big tech AI (cá nhân)
phase: Chọn case + tìm số liệu + nguồn
time: 15 phút
input: prompts/01-research-case.md
nop-cuoi: Không — file trung gian
---

# 1 — Tự nghiên cứu case: Course Hero bị ChatGPT commoditize use case “homework help”

## Bước 0 — Chọn case

- **Tên case**: Course Hero
- **Big tech AI tạo áp lực**: ChatGPT của OpenAI
- **Lý do chọn**: Case này khác Chegg nhưng vẫn rất rõ theo logic disruption. Course Hero có moat dữ liệu học tập và cộng đồng giáo viên/sinh viên, nhưng ChatGPT đã đổi kỳ vọng người dùng từ “tìm tài liệu phù hợp” sang “hỏi và nhận câu trả lời ngay”. Case cũng có đủ nguồn công khai để lập bằng chứng: valuation trước AI, layoff sau AI, thời điểm ra AI feature, traffic proxy giảm mạnh, và có đối thủ phản ứng nhanh hơn để so sánh là Quizlet.

## 4 nhóm số liệu cần tìm

### Nhóm 1 — Quy mô trước và sau

- Valuation trước AI shock.
- Quy mô thư viện nội dung / giáo viên tham gia.
- Giá gói trả phí.
- User proxy sau AI shock.

### Nhóm 2 — Mốc thời gian big tech AI ra tính năng tương tự

- Ngày ChatGPT public launch.
- Ngày ChatGPT Plus ra mắt.
- Giá ChatGPT Plus.

### Nhóm 3 — Phản ứng của Course Hero sau khi ChatGPT ra mắt

- Layoff / tái cấu trúc.
- Thời điểm public hóa AI Homework Help / Chat with PDF.
- Cách Course Hero kết hợp OpenAI models với thư viện nội dung và tutor.

### Nhóm 4 — Đối thủ AI thay thế / đối thủ phản ứng nhanh hơn

- ChatGPT thay thế use case nào.
- Quizlet phản ứng nhanh hơn ra sao.
- Scale của Quizlet để so sánh moat / distribution.

---

## Phần B — Bảng tổng hợp số liệu

### Bảng số liệu case Course Hero

| # | Số liệu | Giá trị | Ngày / thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
|---|---|---:|---|---|---|
| S-01 | Valuation trước AI shock | $3.6B valuation, Series C $380M | 2021-12-14 | TechCrunch - https://techcrunch.com/2021/12/15/for-course-hero-venture-capital-was-once-an-unobvious-solution/ | Có |
| S-02 | Quy mô content moat trước AI | 60M+ course-specific study resources; 70,000+ faculty | 2021-08-19 | Course Hero blog - https://www.coursehero.com/blog/cliffsnotes-quillbot/ | Có |
| S-03 | Quy mô sản phẩm hiện tại | 100M course-specific study materials | 2026-05-14 (trang hiện tại) | Course Hero Welcome - https://www.coursehero.com/welcome/ | Có |
| S-04 | Giá sản phẩm gốc | “as low as $9.95 per month” | 2026-05-14 (trang hiện tại) | Course Hero Welcome - https://www.coursehero.com/welcome/ | Có |
| S-05 | ChatGPT public launch | Research preview launch | 2022-11-30 | OpenAI - https://openai.com/index/chatgpt/ | Có |
| S-06 | ChatGPT Plus launch + pricing | $20/month | 2023-02-01 | OpenAI - https://openai.com/index/chatgpt-plus/ | Có |
| S-07 | Tác động phản ứng sớm nhất lên Course Hero | Layoff 15% staff = 42 người | 2023-03-16 | TechCrunch - https://techcrunch.com/2023/03/16/course-hero-edtech-unicorn-last-valued-at-3-6-billion-conducts-layoffs/ | Có |
| S-08 | Quy mô người dùng sau AI shock (global MAU) | “about 30 million monthly active users”; paid subscribers comparable YoY | 2023-08-30 | Forbes - https://www.forbes.com/sites/emmylucas/2023/08/30/course-hero-is-graduating-just-in-time/ | Có |
| S-09 | AI feature của Course Hero | In summer 2023, Course Hero launched AI-powered Homework Help | 2023-06-25 (được công ty công khai nhắc đến) | Course Hero College Life - https://www.coursehero.com/college-life/course-hero-vs-chatgpt-whats-the-best-ai-study-tool/ | Có |
| S-10 | AI stack của Course Hero | Kết hợp OpenAI models với library và verified tutors | 2026-05-14 (trang hiện tại) | Course Hero Responsible AI - https://www.coursehero.com/responsible-ai/ | Có |
| S-11 | User proxy 1 (DSA web MAU) | 5,236,898 approx. monthly active users | 6 tháng kết thúc 2023-06-30 | Learneo DSA report - https://assets.coursehero.com/assets/mau_report.pdf | Có |
| S-12 | User proxy 2 (DSA web MAU) | 4,043,008 approx. monthly active users | 6 tháng kết thúc 2023-12-31 | Learneo DSA report - https://assets.coursehero.com/assets/mau_report.pdf | Có |
| S-13 | User proxy 3 (DSA web MAU) | 2,792,646 approx. monthly active users | 6 tháng kết thúc 2024-06-30 | Learneo DSA report - https://assets.coursehero.com/assets/mau_report.pdf | Có |
| S-14 | User proxy 4 (DSA web MAU) | 1,220,938 approx. monthly active users | 6 tháng kết thúc 2024-12-31 | Learneo DSA report - https://assets.coursehero.com/assets/mau_report.pdf | Có |
| S-15 | Đối thủ phản ứng nhanh hơn | Quizlet launch Q-Chat, AI tutor built on ChatGPT API | 2023-03-01 | Quizlet - https://quizlet.com/blog/meet-q-chat | Có |
| S-16 | Quy mô đối thủ phản ứng nhanh hơn | 60M learners, 900M+ study sets | 2026-05-14 (trang hiện tại) | Quizlet - https://quizlet.com/mission | Có |

### Ghi chú về độ so sánh dữ liệu

- `S-08` là global MAU do Forbes dẫn lại từ công ty.
- `S-11` đến `S-14` là dữ liệu monthly active users công bố theo Digital Services Act của Learneo. Đây là chuỗi dữ liệu công khai nhất quán nhất cho giai đoạn hậu AI shock, nhưng không chắc trùng định nghĩa 1:1 với global MAU trong `S-08`.
- Doanh thu, ARR, MRR, và số paid subscribers chi tiết của Course Hero không được công bố công khai theo chuỗi số liệu đầy đủ.

---

## Phần C — Kiểm chứng nguồn

### Checklist kiểm chứng

- [x] Mỗi số liệu có URL cụ thể.
- [x] URL mở được.
- [x] Các mốc ngày quan trọng đã đối chiếu giữa nguồn gốc và báo chí.
- [x] Đã ưu tiên nguồn gốc cho ngày ra mắt và pricing của ChatGPT / Course Hero / Quizlet.
- [x] Đã ghi rõ những chỗ không có nguồn công khai thay vì điền số suy đoán.

### Mức ưu tiên nguồn đã dùng

| Mức ưu tiên | Loại nguồn | Ví dụ đã dùng |
|---|---|---|
| 1 | Nguồn gốc | OpenAI, Course Hero, Learneo DSA report, Quizlet |
| 2 | Báo lớn | TechCrunch, Forbes |
| 3 | Báo cáo / tổng hợp | Không dùng để làm số liệu cốt lõi |

---

## Phần D — Phát hiện ban đầu

- Course Hero bước vào AI era với nền tảng rất mạnh: valuation $3.6B cuối năm 2021 và 60M+ study resources cùng 70K+ faculty.
- ChatGPT launch ngày `2022-11-30`, và đến `2023-02-01` đã có gói Plus $20/tháng, tạo một sản phẩm “do the work for me” rẻ hơn và tổng quát hơn rất nhiều.
- Chỉ hơn 3 tháng sau khi ChatGPT ra mắt, Course Hero đã layoff 15% nhân sự (`2023-03-16`), cho thấy cú sốc chiến lược xảy ra sớm hơn rất nhiều so với tốc độ pivot thông thường của edtech.
- Đến khi Course Hero public hóa AI Homework Help vào mùa hè 2023, đối thủ Quizlet đã tung Q-Chat từ `2023-03-01`, sớm hơn và bám sát hơn vào workflow học tập hàng ngày.
- Trên chuỗi dữ liệu web active users mà Learneo công bố, `coursehero.com` giảm từ `5.24M` (kỳ kết thúc `2023-06-30`) xuống `1.22M` (kỳ kết thúc `2024-12-31`), tương đương giảm khoảng `76.7%`.

---

## Phần E — Câu hỏi mở cho file 2-analysis.md

- Câu hỏi 1: Trước AI, Course Hero thật sự bán cái gì: tài liệu, tutor, hay khả năng “giải quyết bài tập nhanh”?
- Câu hỏi 2: Khi ChatGPT xuất hiện, shift nào của customer expectation làm Course Hero mất lợi thế nhanh nhất?
- Câu hỏi 3: Data moat 100M tài liệu của Course Hero có vì sao không đủ để bảo vệ PMF khi giao diện chat trở thành entry point mặc định?
- Câu hỏi 4: Nếu Course Hero pivot sớm hơn sang course-grounded AI + tutor verification + B2B/educator workflow, liệu họ có thể tránh được fit collapse consumer hay không?
