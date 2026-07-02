# Day 26 Lab — Fundraising Intelligence Brief

Hướng dẫn thực hiện bài lab theo thứ tự: **tổng quan → chuẩn bị → thực hành chi tiết → kiểm tra & nộp bài**.

---

## 1. Tổng quan bài lab

### Mục tiêu học tập

1. Tìm được **1 deal fundraising AI có thật**, có số liệu, có nguồn.
2. Định vị đúng deal đó vào **Stages of Startup Equity Funding** và bảng **Venture Capital vs Private Equity**.
3. Research được **investor thật** phù hợp với idea A3 Canvas của mình, có **investment-thesis fit** rõ ràng — không phải liệt kê tên cho có.
4. Đọc được **data thị trường** trong bài chia sẻ và **tự lập luận fundability** của idea mình trong bối cảnh gọi vốn hiện tại.

### Bạn sẽ làm gì?

- Tìm 1 deal fundraising AI có thật (bất kỳ thị trường nào).
- Định vị deal đó theo framework fundraising vừa học.
- Áp cùng framework để research investor và tự lập luận fundability cho **chính idea AI product** trong A3 Canvas (từ Day 24).

### Luồng làm việc cốt lõi

```
deal thật → định vị đúng framework → investor thật → bằng chứng tài chính thật
```

### Câu nhắc cuối

Mục tiêu không phải "list tên VC cho có" hay "chọn đại 1 deal cho xong bài". Mục tiêu là tập đúng phản xạ: **credible, provable, differentiated, compelling, right investors** — áp vào chính idea của mình bằng **bằng chứng thật**, không phải cảm giác.

---

## 2. Yêu cầu nộp bài

### Repo cá nhân

- Tên repo: `Day26-Track1-MaHV-HoVaTen`
- Nộp **1 link repo cá nhân**

### Nội dung bắt buộc trong repo

| Deliverable | Mô tả |
|---|---|
| **Deal Case Brief** | 1 deal AI (không giới hạn thị trường) |
| **Bảng định vị Stage/Investor Type** | Định vị deal theo 2 framework |
| **Investor Mapping Table** | 3–5 investor thật |
| **Market Positioning Memo** | Nửa trang – 1 trang |

### Lưu ý bảo mật

- **Không** đưa API key, token, credential, hoặc dữ liệu cá nhân nhạy cảm vào repo.

---

## 3. Chuẩn bị trước khi làm — Khái niệm & tiêu chuẩn chất lượng

### 3.1. Khái niệm nhanh (đọc trước khi làm)

| Thuật ngữ | Nghĩa đơn giản |
|---|---|
| **Ticket size** | Số tiền 1 nhà đầu tư rót vào 1 vòng gọi vốn |
| **Stage / Vòng gọi vốn** | Giai đoạn công ty đang gọi vốn: Pre-Seed → Seed → Series A-B → Series C+ → IPO |
| **Investment thesis** | "Gu" đầu tư của 1 quỹ — họ thích category/market nào |
| **Due diligence** | Bước quỹ kiểm tra kỹ công ty trước khi ký term sheet |
| **Unit economics** | Tính lời/lỗ trên 1 đơn vị (1 khách hàng): Doanh thu/khách − Chi phí phục vụ/khách = Contribution margin |
| **Cash needs / Runway** | Cần bao nhiêu tiền để sống + phát triển tới cột mốc tiếp theo (thường tính theo số tháng còn "sống" được) |
| **KPI tới vòng tiếp theo** | 1–2 con số cụ thể nhà đầu tư vòng sau muốn thấy tăng (user, doanh thu, retention…) |

### 3.2. Mẫu TỐT vs CHƯA ĐẠT

Bài chấm theo **mức độ cụ thể**, không chấm theo văn phong hay hay dở. Cột "CHƯA ĐẠT" = mơ hồ, không có số, không có nguồn. Cột "TỐT" = luôn có ít nhất **1 con số + 1 lý do cụ thể**.

| Phần | CHƯA ĐẠT | TỐT |
|---|---|---|
| Deal Case Brief — Số liệu chính | "Startup này gọi vốn khá nhiều" | "Gọi vốn 2 triệu USD vòng Seed, dẫn dắt bởi 1 quỹ cụ thể, công bố tháng 3/2025 — có link báo" |
| AI differentiation check | "Startup này dùng AI nên chắc khác biệt" | "AI ở đây dùng để làm gì cụ thể — proprietary data, workflow riêng, hay chỉ là feature gắn thêm?" |
| Investor Mapping — Vì sao fit | "Quỹ này đầu tư công nghệ nên chắc sẽ thích idea của tôi" | "Quỹ công khai thesis tập trung early-stage AI ở Đông Nam Á, đã đầu tư ít nhất 1 startup cùng sector, ticket size khớp giai đoạn hiện tại" |
| Memo — Unit economics | "Mô hình kinh doanh này sẽ có lời" | "Ước tính: user trả X/tháng, cost phục vụ Y/tháng/user → contribution margin Z (giả định: …)" |

### 3.3. Đầu vào — Idea A3 Canvas của bạn

Trước khi research, chốt lại **1 dòng** cho mỗi ô sau. Toàn bộ lab research xoay quanh chính idea bạn đang build từ Day 24:

| Câu hỏi | Bạn điền gì |
|---|---|
| Idea AI product bạn đang build trong A3 Canvas là gì? | |
| Sector / ngành nào? | |
| Hiện đang ở giai đoạn nào? (pre-idea / prototype / MVP có traction) | |

---

## 4. Bước 1 — Tìm deal fundraising AI và định vị theo framework

### 4.1. Chọn 1 deal AI-native

- Chỉ tìm **1 deal**.
- Deal bắt buộc là **startup AI-native** — AI là phần tạo ra giá trị chính, không phải công ty chỉ "có gắn thêm chatbot".
- Không giới hạn thị trường (VN, Đông Nam Á, Mỹ, v.v.).
- Gọi vốn trong khoảng **2023–2026**.

### 4.2. Tiêu chí chọn deal

Deal phải trả lời được:

- [ ] Startup này làm gì, và AI được dùng ở đâu trong sản phẩm?
- [ ] Ai đầu tư, và đầu tư ở vòng nào?
- [ ] Ticket size là bao nhiêu (nếu công bố)?
- [ ] Sector nào?
- [ ] Có ít nhất 1 nguồn công bố (báo, press release, Crunchbase, DealStreetAsia)?

> Nếu deal thiếu số liệu hoặc chỉ có 1 nguồn mơ hồ → **đổi deal khác**.

### 4.3. AI differentiation check

Trả lời 3 câu hỏi (bám slide "Common Issues" — lỗi "Unclear differentiation"):

1. AI trong sản phẩm này giải quyết vấn đề gì cụ thể, khác gì so với làm bằng cách không dùng AI?
2. Nếu bỏ chữ "AI" đi, startup này còn lại lợi thế gì (data riêng, network, quy trình, distribution…)? Hay chỉ còn lại một cái tên?
3. Deal này có rơi vào bẫy "Unclear differentiation" không? Vì sao?

### 4.4. Điền template Deal Case Brief

| Field | Bạn điền gì |
|---|---|
| Tên startup | Tên công ty |
| Sector | Ngành hoạt động |
| Vòng gọi vốn | Pre-Seed / Seed / Series A / Series B / Series C / IPO |
| Investor(s) tham gia | Tên quỹ / nhà đầu tư |
| Ticket size | Số tiền công bố (nếu có) |
| Thời điểm | Năm hoặc tháng công bố |
| Deal này là gì? | Tóm tắt 2–3 câu, chỉ viết fact chính |
| Trích nguồn ngắn | 1 câu fact ngắn hoặc paraphrase có dẫn nguồn |
| Nguồn 1 | Tên nguồn + ngày + link hoặc citation |
| Nguồn 2 | Nguồn đối chiếu nếu có |
| Ghi chú độ tin cậy | Primary / secondary / có conflict không? |

### 4.5. Định vị deal — Framework 1: Stages Of A Startup Equity Funding

Chọn **đúng 1 giai đoạn** theo thứ tự:

```
Pre-Seed Funding (Startup Owners, Friends & Family)
  → Seed Funding (Angel investors, Friends & Family, Crowdfunding)
  → Series A to Series B (Venture Capitalists)
  → Series C (Late Stage VCs, Private Equity Firms)
  → IPO (Public)
```

### 4.6. Định vị deal — Framework 2: Venture Capital vs Private Equity

| Field | Bạn điền cho deal của mình |
|---|---|
| Stage of Investment | Angel / Seed / Growth / Crossover / Late-Stage-Buyout |
| Investment Size (US$) tương ứng | Angel: $10K–250K · Seed: $250K–2M · Growth: $10M–50M · Crossover: $50M–100M · Late Stage: triệu tới tỷ |
| Investor Type khớp deal | Individuals/group · First institutional check · Series A through C · Series C through IPO · Majority control-debt financed |
| Vì sao bạn xếp deal vào ô này? | Giải thích 1–2 câu dựa trên ticket size + investor type thực tế |

---

## 5. Bước 2 — Research Investor Mapping cho idea của bạn

### 5.1. Cách tìm investor

Dùng đúng các cách trong bài chia sẻ ("How to find good investors"):

| Cách | Yêu cầu |
|---|---|
| **1. Lists** | **Bắt buộc** — dùng database công khai (Crunchbase, Tracxn, DealStreetAsia), lọc: Headquarters Location + Investor Type = Venture Capital + Operating Status = Active. Bắt đầu với: **Techstars**, **Antler**, **500 Global** |
| **2. Events, workshops** | Tùy chọn — note thêm nếu biết event/cộng đồng có investor |
| **3. Referrals** | Tùy chọn — chỉ dùng nếu thật sự có mentor/network; không giả vờ |
| **4. Be famous** | Bỏ qua — không áp dụng cho bài tập |

> **Lists là đủ** để hoàn thành bài. Không cần làm đủ cả 4 cách.

### 5.2. Điền template Investor Mapping Table

- Tối thiểu **3 investor**, tối đa **5 investor**.

| Investor / Quỹ | Loại investor (Angel/Seed/Growth VC/…) | Sector & stage họ tập trung | Ticket size điển hình | Vì sao fit với idea của bạn? | Nguồn (portfolio page / Crunchbase / DealStreetAsia) |
|---|---|---|---|---|---|
| (1) | | | | | |
| (2) | | | | | |
| (3) | | | | | |

### 5.3. Câu hỏi cần trả lời cho mỗi investor

Theo checklist "What to know before/after an investor meeting":

- [ ] **Investment thesis** của họ là gì — category/market nào họ quan tâm?
- [ ] Họ đã đầu tư công ty nào trong **cùng space** chưa? Đó có phải competitive investment với idea của bạn không?
- [ ] **Typical ticket size** của họ là bao nhiêu?
- [ ] **Investment criteria** họ công bố là gì (team, market, stage, % equity requirement…)?
- [ ] **Vì sao họ nên đầu tư vào bạn** — hoặc vì sao có thể họ sẽ không?

---

## 6. Bước 3 — Viết Market Positioning Memo

### 6.1. Data thị trường cần tham chiếu (từ bài chia sẻ)

- Vietnam VC deal value và deal count giảm liên tục, ~30% vào cuối 2025 so với đỉnh 2021
- Check size trung bình co lại đáng kể (2023 → 2025)
- Sector heatmap: Ecommerce, Edtech, Climate Tech nhiều deal nhất; **AI agent funding tăng mạnh** (162 deal, $3.8B tới 2024)
- Xu hướng YC "Request for Startups": AI-Native Service Companies, AI + Hardware, AI + Deeptech, Software for Agents

### 6.2. Câu hỏi trung tâm của memo

Viết memo ngắn (**nửa trang – 1 trang**) trả lời:

> *"Idea của tôi có fundable trong bối cảnh gọi vốn hiện tại không, và tôi cần bằng chứng gì để chứng minh điều đó?"*

### 6.3. Nội dung bắt buộc — tránh lỗi "Unclear financials"

Memo **phải** trả lời được:

| Nội dung | Yêu cầu |
|---|---|
| **Unit economics sơ bộ** | Ước tính: Doanh thu/khách − Chi phí phục vụ/khách. Ghi rõ nếu là estimate + giả định |
| **Cash needs** | Cần bao nhiêu tiền để đi tới milestone tiếp theo? |
| **KPI tới vòng tiếp theo** | Con số cụ thể cần đạt trước khi gọi vòng kế tiếp |

> Không được để trống hoặc viết mơ hồ kiểu "sẽ tốt", "rất tiềm năng". 1 phép trừ đơn giản với số ước tính hợp lý là đủ — không cần mô hình tài chính phức tạp.

---

## 7. Nguồn, AI search & kiểm tra chất lượng

### 7.1. Thứ tự ưu tiên nguồn

1. **Primary source** — company announcement, press release, official filing, investor's portfolio page
2. **High-quality secondary** — DealStreetAsia, TechCrunch, VnExpress International, báo cáo Inventures/CB Insights
3. **Nguồn phụ đối chiếu** — blog tổng hợp, newsletter, explainer article

### 7.2. Gợi ý prompt AI search

Thay `[SECTOR]`, `[TÊN STARTUP]`, `[STAGE]` bằng nội dung thực tế:

```
Tìm cho tôi 3-5 deal fundraising AI có thật (bất kỳ thị trường nào),
công bố trong 2023-2026. Startup phải có AI là sản phẩm cốt lõi, không
phải chỉ gắn thêm chatbot. Chỉ giữ deal có ít nhất 1 nguồn công bố
ticket size hoặc investor rõ ràng.
```

```
Với deal [TÊN STARTUP], giúp tôi tóm tắt: AI được dùng để làm gì,
stage, investor tham gia, ticket size, sector, thời điểm, và nguồn nào
nên đọc trước.
```

```
Tìm cho tôi 5-8 investor (VC/quỹ) có khả năng quan tâm tới sector
[SECTOR] ở stage [STAGE] tại Đông Nam Á/Việt Nam. Ưu tiên investor có
public portfolio hoặc investment thesis công khai rõ ràng.
```

> **Không copy thẳng output AI vào bài.** Luôn tự mở nguồn và kiểm lại fact.

### 7.3. Checklist kiểm nguồn

Trước khi chốt deal hoặc investor:

- [ ] Đã mở nguồn thật chưa?
- [ ] Số liệu nằm ở đâu trong nguồn?
- [ ] Mốc thời gian có đúng không?
- [ ] Đây là nguồn gốc hay nguồn trích lại?
- [ ] Nếu có 2 nguồn, chúng có mâu thuẫn nhau không?

> **Không được** ghi ChatGPT, Claude, Gemini, Perplexity làm nguồn của deal hoặc investor.

---

## 8. Checklist tự kiểm trước khi nộp

- [ ] Đã chọn 1 deal AI-native có thật, có số liệu, có nguồn (không giới hạn thị trường)
- [ ] Đã định vị deal đúng vào **Stages of Startup Equity Funding** và bảng **VC vs Private Equity**
- [ ] Đã trả lời câu hỏi **AI differentiation check** — deal có rơi vào bẫy "Unclear differentiation" không
- [ ] Đã research **3–5 investor thật**, không phải investor tưởng tượng
- [ ] Đã trả lời được **investment thesis fit** cho từng investor, không chỉ liệt kê tên
- [ ] Memo có chạm vào **unit economics**, **cash needs**, và **KPI tới vòng tiếp theo**
- [ ] Đã mở nguồn gốc hoặc nguồn chất lượng cao, không chỉ tin vào AI summary
- [ ] Không ghi AI chatbot làm nguồn của deal hoặc investor

---

## 9. Thứ tự thực hiện đề xuất

```
1. Đọc khái niệm nhanh + mẫu TỐT vs CHƯA ĐẠT
2. Chốt idea A3 Canvas (3 câu hỏi đầu vào)
3. Bước 1: Tìm deal → Deal Case Brief → AI differentiation check → Định vị 2 framework
4. Bước 2: Research investor qua Lists → Investor Mapping Table (3–5 investor)
5. Bước 3: Viết Market Positioning Memo (fundability + unit economics + cash needs + KPI)
6. Kiểm nguồn + checklist tự kiểm
7. Nộp repo
```
