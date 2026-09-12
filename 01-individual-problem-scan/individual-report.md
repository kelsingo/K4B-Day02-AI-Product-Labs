# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Ngô Hoàng Thụy Khuê 
- Mã học viên: 2A202603017
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên vừa tốt nghiệp ngành Khoa học Máy tính 
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Đọc bài báo khoa học 
    - 

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Tìm quán ăn phù hợp tại một nơi mới | Khách du lịch, người nhập cư từ xa | 2 tiếng/1 bữa ăn |
| 2 | Tốn thời gian/AI có thể tốt hơn | Thuê nhà tại thành phố mới | Người đi làm/Sinh viên công tác xa nhà | 1-3 tháng |
| 3 | Pain từ người khác | Không có giờ giấc làm việc và nghỉ ngơi tại nhà hợp lý | người làm việc/học tập tại nhà | Làm việc qua đêm mỗi ngày (3-5 ngày/tuần) |
| 4 | Lặp lại | Trả lời câu hỏi từ khách hàng về chính sách công ty | Nhân viên chăm sóc khách hàng| 15-20 lần/ngày |
| 5 | Lặp lại/AI có thể tốt hơn | Soạn hồ sơ, văn bản hành chính | Chuyên viên hành chính nhân sự, thư ký, chuyên viên pháp chế | 4–6 tiếng/bộ hồ sơ; 70–80% nội dung sử dụng lại mẫu cố định nhưng vẫn dễ sai sót do nhập tay (lỗi chính tả, sai mã/số liệu) |
| 6 | Tốn thời gian | Lên danh sách và chuẩn bị thức ăn | Người nấu ăn cho gia đình | 2-3 tiếng |
| 7 | AI có thể tốt hơn | Đọc bài báo khoa học phức tạp về toán | Sinh viên ngoài ngành toán | 1 tuần/bài báo|
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Thuê nhà tại thành phố mới | Actor cụ thể: sinh viên hoặc người đi làm chuyển đến thành phố mới. Workflow gồm tìm kiếm → lọc theo tiêu chí → liên hệ → xem/kiểm tra → lựa chọn, và pain kéo dài **1–3 tháng**, cho thấy tác động đáng kể. | Bài toán khá rộng và phụ thuộc nhiều yếu tố ngoài AI như giá, vị trí, hợp đồng và tình trạng phòng; cần thu hẹp phạm vi để có bottleneck duy nhất và pilot khả thi. |
| 2 | Tìm quán ăn phù hợp tại một nơi mới | Actor cụ thể: khách du lịch/người mới đến một thành phố. Workflow có thể vẽ rõ từ xác định nhu cầu → tìm kiếm → lọc địa điểm → so sánh → chọn quán; bottleneck nằm ở bước tìm kiếm và tổng hợp thông tin, với pain đáng kể là khoảng 2 tiếng cho một bữa ăn | Cần xác định rõ nguồn thông tin và tiêu chí đánh giá phù hợp (giá, khẩu vị, khoảng cách, đánh giá, thời gian mở cửa). |
| 3 | Không có giờ giấc làm việc và nghỉ ngơi tại nhà hợp lý | Actor cụ thể:  người làm việc/học tập tại nhà. Workflow có thể gồm ghi nhận lịch → xác định thời gian làm việc/nghỉ → lập lịch → nhắc nhở → điều chỉnh, trong đó AI có thể hỗ trợ cá nhân hóa lịch. | Chưa có evidence định lượng rõ về thời gian mất mát hoặc mức độ ảnh hưởng. |


### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu: Tốn nhiều thời gian để tìm và lựa chọn nơi ở phù hợp khi chuyển đến một thành phố mới.

Actor: Sinh viên hoặc người đi làm chuyển đến thành phố mới.

Thời điểm / bối cảnh: Khi chuẩn bị chuyển đến thành phố mới và cần tìm chỗ ở trong thời gian ngắn hoặc trung hạn.

Current workflow 3-7 bước:
1. Xác định ngân sách, vị trí mong muốn và các tiêu chí về phòng. 
2. Tìm kiếm phòng trên các nền tảng và mạng xã hội. 
3. Lọc các phòng theo giá, vị trí và tiện nghi. 
4. Liên hệ chủ nhà/môi giới để hỏi thông tin và tình trạng phòng. 
5. Xem phòng, kiểm tra điều kiện và hợp đồng. 
6. So sánh các lựa chọn và quyết định thuê.

Bottleneck: Tìm kiếm, lọc và xác minh nhiều lựa chọn, thông tin về giá, vị trí, tình trạng phòng và điều kiện thuê thường nằm ở nhiều nguồn khác nhau. Thông tin về uy tín của chủ nhà/môi giới thường khó xác minh. 

Impact: Quá trình tìm nhà có thể kéo dài 1–3 tháng, đồng thời đòi hỏi nhiều lần tìm kiếm, liên hệ và kiểm tra trước khi quyết định.

Success metric: Giảm thời gian tìm được một shortlist phù hợp, giảm số listing phải tự kiểm tra/liên hệ, giảm số lần phải lặp lại việc tìm kiếm. 

Non-AI alternative: Dùng bộ tiêu chí cố định, bộ lọc trên các nền tảng cho thuê nhà và Google Sheet để lưu, chấm điểm và so sánh các listing. Dùng các mạng xã hội để đánh giá uy tín

AI hypothesis: Agent nhận các ràng buộc về ngân sách, vị trí, diện tích và tiện nghi, sau đó tìm kiếm, tổng hợp đánh giá, lọc và đưa ra một shortlist các lựa chọn phù hợp để người dùng tiếp tục xác minh. 

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — kéo dài 1-3 tháng

[1 Xác định tiêu chí: 30'] → [2 Search nhiều nền tảng: nhiều giờ/ngày/tuần] <-- bottleneck → [3 Lọc + mở listing: nhiều giờ] → [4 Liên hệ + xác minh: nhiều ngày] → [5 Xem phòng + so sánh: nhiều ngày] 

FUTURE STATE — giảm đáng kể thời gian tìm shortlist

[1 Nhập tiêu chí: 10'] → [2 Agent tìm + lọc + tổng hợp shortlist: 30-60'] → [3 Người dùng kiểm tra listing + quyết định: 30-60']  <-- human boundary

Fallback: nếu listing không còn phòng, thông tin không chính xác hoặc AI đưa ra lựa chọn không tốt, người dùng tiếp tục search thủ công hoặc điều chỉnh tiêu chí.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu: Tốn thời gian để tìm quán ăn phù hợp tại một nơi mới.

Actor: Khách du lịch, sinh viên, người đi làm xa nhà 

Thời điểm / bối cảnh: Khi đến một thành phố/khu vực mới và cần tìm một quán ăn đáp ứng nhiều tiêu chí cá nhân hoặc nhóm.

Current workflow 3-7 bước:
1. Tìm kiếm quán trên Google/Google Maps/mạng xã hội. 
2. Lên list nhiều quán ăn. 
3. So sánh giá, đánh giá, vị trí, menu và giờ mở cửa. 
4. Chọn quán.

Bottleneck: Tốn nhiều thời gian để tìm kiếm và tổng hợp thông tin từ nhiều nguồn; phải mở và so sánh nhiều lựa chọn để xác định quán phù hợp.

Impact: Có thể mất đến 2 giờ để tìm một lựa chọn phù hợp cho một bữa ăn.

Success metric: Giảm thời gian từ lúc bắt đầu tìm kiếm đến lúc chọn được quán, giảm số địa điểm phải tự mở và so sánh, đảm bảo quán ăn hài lòng với người dùng.

Non-AI alternative: Dùng Google Sheet/template tiêu chí và checklist để tự so sánh các quán. 

AI hypothesis: Agent nhận yêu cầu bằng ngôn ngữ tự nhiên, tổng hợp nhiều lựa chọn theo tiêu chí và đưa ra 2-3 quán phù hợp kèm lý do để người dùng kiểm tra và lựa chọn. Đồng thời kiểm tra tình trạng hiện tại của quán (quán có mở cửa không, đánh giá gần nhất).

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~120 phút 
[1 Xác định nhu cầu: 10'] → [2 Search nhiều nguồn: 40'] → [3 Xem thông tin từng quán: 40'] → [4 So sánh + kiểm tra lại: 30'] <-- bottleneck 

FUTURE STATE — ~25-35 phút 
[1 Nhập nhu cầu: 5'] → [2 Agent tìm + tổng hợp 2-3 lựa chọn: 15-20'] → [3 Người dùng review + chọn: 5-10'] <-- human boundary 

Fallback: nếu AI thiếu/sai thông tin hoặc đề xuất không phù hợp, người dùng kiểm tra lại nguồn và tự tìm thêm lựa chọn khác.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu: Người làm việc/học tập tại nhà khó duy trì lịch làm việc và nghỉ ngơi hợp lý.

Actor: Người làm việc hoặc học tập tại nhà.

Thời điểm / bối cảnh: Trong những ngày làm việc/học tập tại nhà, đặc biệt khi lịch trình không cố định và không có ranh giới rõ giữa thời gian làm việc và nghỉ ngơi.

Current workflow 3-7 bước:
1. Xác định các công việc/học tập cần hoàn thành trong ngày. 
2. Tự ước lượng thời gian cần thiết cho từng việc. 
3. Tự sắp xếp thời gian làm việc và nghỉ ngơi. 
4. Thực hiện công việc theo lịch đã đặt. 
5. Điều chỉnh lịch khi phát sinh việc hoặc bị trễ tiến độ.

Bottleneck: Tự lập và điều chỉnh lịch khi có nhiều công việc với thời lượng và mức độ ưu tiên khác nhau, dễ bỏ qua thời gian nghỉ hoặc kéo dài thời gian làm việc.

Impact: Lịch làm việc/nghỉ ngơi thiếu ổn định, khó duy trì thói quen và có thể dẫn đến việc phải điều chỉnh lịch nhiều lần trong ngày.

Success metric: Giảm thời gian lập lịch và số lần phải điều chỉnh thủ công, tăng tỷ lệ hoàn thành công việc theo lịch và duy trì các khoảng nghỉ đã đặt.

Non-AI alternative: Dùng Google Calendar/to-do list, time-blocking template và reminder cố định. 

AI hypothesis: Agent nhận danh sách công việc, deadline và thời gian rảnh, sau đó đề xuất lịch làm việc/nghỉ cá nhân hóa và tự điều chỉnh khi người dùng cập nhật tiến độ.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~70-100 phút/ngày cho việc lập + điều chỉnh lịch

[1 Liệt kê công việc: 10'] → [2 Ước lượng thời gian: 10'] → [3 Tự lập lịch: 20'] → [4 Theo dõi + điều chỉnh: 30-60']  <-- bottleneck

FUTURE STATE — ~10-20 phút/ngày

[1 Nhập công việc + thời gian rảnh: 5'] → [2 Agent đề xuất lịch + reminder: 5-10'] → [3 Người dùng review + điều chỉnh: 5']  <-- human boundary

Fallback: nếu lịch AI đề xuất không phù hợp hoặc quá tải, người dùng chỉnh lại thời gian/ưu tiên và agent tạo lịch mới.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Card #1 có workflow khá rõ: xác định tiêu chí → tìm kiếm → lọc → liên hệ/xác minh → xem và so sánh → quyết định thuê. Pain có thể đo được bằng thời gian tìm nhà, số listing phải xem/liên hệ và số lần lặp lại việc tìm kiếm; hiện tại quá trình có thể kéo dài 1–3 tháng. AI có thể giúp tìm, lọc và tổng hợp shortlist theo nhiều tiêu chí, từ đó giảm đáng kể thời gian và công sức tìm kiếm.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Liệu bài toán này có quá rộng và phụ thuộc quá nhiều vào các yếu tố thực tế như tình trạng phòng, hợp đồng và việc xem nhà trực tiếp không? Bottleneck thực sự có nằm ở việc tìm và lọc listing hay nằm ở bước xác minh/đàm phán với chủ nhà?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:Problem còn khá rộng, đặc biệt vì “thuê nhà” bao gồm nhiều bước mà AI khó tự động hóa hoàn toàn; evidence 1–3 tháng cũng chưa cho biết chính xác bao nhiêu thời gian là do việc tìm kiếm.
- Tôi sửa gì: Thu hẹp problem vào bước tìm kiếm và shortlist, thay vì toàn bộ quá trình thuê nhà. Cần đo riêng thời gian tìm kiếm, số listing được xem và số listing phù hợp được tìm thấy để xác định bottleneck và đánh giá chính xác lợi ích của AI.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
