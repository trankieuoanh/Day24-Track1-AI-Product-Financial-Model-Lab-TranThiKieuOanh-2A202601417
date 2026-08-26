> **Brief (Triết lý bài học):** Một sản phẩm AI có RAG/Agent chạy mượt ở Day 23 mới chỉ là thành công về kỹ thuật. Để sản phẩm sống sót và tăng trưởng thương mại, PM/Founder bắt buộc phải giải bài toán tài chính: Tính đúng chi phí biến đổi COGS (đặc biệt là AI Hidden Costs), làm chủ Unit Economics (CAC, LTV, Gross Margin), và thực hiện stress-test dòng tiền 3 kịch bản (Optimistic, Base, Pessimistic) để chứng minh khả năng sinh tồn (Runway ≥ 12 tháng).

---


| Mục | Nội dung |
|---|---|
| **Họ và tên** | Trần Thị Kiều Oanh |
| **MSSV** | 202601417 |
| **Tên dự án** | AI Study Assistant — Trợ lý học tập AI cho sinh viên Việt Nam (cá nhân) |
| **Mô hình pricing** | Hybrid: gói Premium cố định + phí usage khi vượt quota |
| **File Excel nộp bài** | `202601417_TranThiKieuOanh_Day24.xlsx` |

## 📝 Decision Note (bảo vệ mô hình tài chính trước hội đồng đầu tư)

Khách hàng mục tiêu của dự án là sinh viên đại học Việt Nam cần công cụ ôn tập và hỏi đáp kiến thức cá nhân hóa. ARPU Base được chốt ở mức 159.000đ/tháng theo mô hình Hybrid — gói Premium cố định cộng phí usage khi vượt quota — dựa trên benchmark các app học tập tại Việt Nam đang định giá 99.000–250.000đ/tháng. Mức này đủ cao để giữ Gross Margin 68,6% nhưng vẫn nằm trong ngưỡng chi tiêu của sinh viên. Adoption rate Base 0,2%/tháng trên TAM 400.000 khách (suy luận top-down từ ~2 triệu sinh viên đại học, chỉ tính phân khúc chủ động tự học trả phí) tương thích với quy mô ngân sách marketing lean của giai đoạn pre-seed.

CAC Base 300.000đ được suy ra từ chi phí quảng cáo Facebook/TikTok ngành edtech (khoảng 50–150k/install, tỉ lệ chuyển đổi sang khách trả phí 5–15%). Với GP/khách 109.000đ và churn 4%/tháng, mô hình đạt LTV/CAC ≈ 9x và CAC Payback 2,8 tháng — vượt chuẩn vàng 3x của nhà đầu tư — tức còn dư địa an toàn khi gặp biến cố.

Về AI Hidden Costs, nhóm giữ mức 36–43% API cost ở cả ba kịch bản, phản ánh chi phí labeling bộ câu hỏi theo giáo trình, retraining dữ liệu mới ~20%/năm và human QA duyệt chất lượng nội dung — khoản mục thường bị startup AI bỏ qua dẫn tới chết yểu.

Stress-test 24 tháng cho thấy Base đạt NPV ~7,3 tỷ đồng, IRR vượt xa WACC 22%; kịch bản Pessimistic với shock 1,5x Churn (6%) và CAC (450.000đ) vẫn duy trì Runway 13 tháng nhờ vòng vốn pre-seed 4 tỷ đồng. Plan B: nếu churn vượt 6% hoặc CAC tăng thêm, đội sẽ siết fixed cost về ~135tr/tháng, chuyển chiến lược sang retention-first và xem xét lại cấu trúc pricing usage trước khi raise vòng tiếp theo.
