# Basel III – Rủi ro tín dụng & Stress Testing (Mini Project)

## Tổng quan dự án
Dự án này mô phỏng việc áp dụng khung Basel III trong quản trị rủi ro tín dụng
tại một ngân hàng thương mại. Thông qua một danh mục tín dụng giả lập,
dự án thực hiện tính toán Tổn thất kỳ vọng (Expected Loss – EL),
Tài sản có rủi ro (Risk-Weighted Assets – RWA) và
Tỷ lệ an toàn vốn (Capital Adequacy Ratio – CAR),
đồng thời đánh giá khả năng chịu đựng vốn của ngân hàng
dưới các kịch bản stress rủi ro tín dụng.

Dự án được thực hiện với mục tiêu học tập và ứng tuyển,
nhằm thể hiện hiểu biết thực tiễn về Basel III và quản trị rủi ro ngân hàng.

---

## Mục tiêu
- Xây dựng danh mục tín dụng giả lập theo phân khúc khách hàng
- Định lượng rủi ro tín dụng thông qua Expected Loss (EL)
- Tính toán Risk-Weighted Assets (RWA) và Capital Adequacy Ratio (CAR)
- Thực hiện stress test bằng cách điều chỉnh PD và LGD
- Đánh giá tác động của rủi ro tín dụng lên vốn ngân hàng

---

## Mô tả dữ liệu
- **Dữ liệu**: Danh mục tín dụng giả lập (50 khách hàng)
- **Phân khúc khách hàng**:
  - Retail (Khách hàng cá nhân)
  - SME (Doanh nghiệp vừa và nhỏ)
  - Corporate (Doanh nghiệp lớn)
- **Các biến chính**:
  - EAD (Exposure at Default)
  - PD (Probability of Default)
  - LGD (Loss Given Default)

Do hạn chế về bảo mật dữ liệu ngân hàng,
dữ liệu trong dự án là dữ liệu giả lập nhưng được xây dựng
trong khoảng giá trị phù hợp với thực tế.

---

## Phương pháp thực hiện

### Tổn thất kỳ vọng (Expected Loss)
- EL = PD × LGD × EAD

### Tài sản có rủi ro (RWA)
- RWA = EAD × Trọng số rủi ro (theo phân khúc)

### Tỷ lệ an toàn vốn (CAR)
- CAR = Vốn / Tổng RWA


### Stress Testing
- Áp dụng kịch bản stress ở mức độ vừa phải (Moderate)
- PD được điều chỉnh tăng theo hệ số
- LGD được điều chỉnh tăng theo mức cộng thêm
- Vốn sau stress được điều chỉnh theo phần tăng của Expected Loss

---

## Kết quả chính
- CAR tại kịch bản cơ sở: khoảng **10%**
- Expected Loss tăng đáng kể dưới kịch bản stress
- CAR sau stress giảm xuống khoảng **9,21%**
- CAR vẫn cao hơn mức tối thiểu **8%** theo quy định Basel III

---

## Công cụ & kỹ năng sử dụng
- Microsoft Excel
- Phân tích rủi ro tín dụng
- Basel III
- Stress Testing
- Quản trị rủi ro ngân hàng

---

## Lưu ý
Dự án được thực hiện cho mục đích học tập và minh họa.
Toàn bộ dữ liệu sử dụng là dữ liệu giả lập và không đại diện
cho bất kỳ ngân hàng hay khách hàng thực tế nào.

---

## Tác giả
**Huỳnh Minh Luận**  



