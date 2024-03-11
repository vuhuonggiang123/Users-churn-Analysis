# Users-churn-Analysis
## **Sử dụng PowerBI tạo ra dashboard giúp stakeholder thấy được tình hình churn và nhận diện nhóm users churn**
### **1. Giới thiệu về dataset**
- Dataset là bảng dữ liệu cung cấp thông tin về users của một công ty mạng viễn thông
- Bao gồm các trường thông tin về nhân khẩu học, các dịch vụ users sử dụng và thông tin liên quan đến churn của users (định nghĩa churn ở đây là một user đang sử dụng sản phẩm/dịch vụ của công ty sau đó họ ngừng sử dụng)
    - Thông tin về users churn: Churn category, churn reason, Churn label
    - Các cột khách là thông tin về nhân khẩu học của khách hàng theo customer ID và các gói dịch vụ mà khách hàng sử dụng
### **2. Giới thiệu về dashboard**
- Sheet Customer Overview:
    - Đưa ra cái nhìn tổng quan về tình hình churn của users cũng như các đặc điểm nổi bật của user churn bằng cách so sánh profile của toàn bộ tập khách hàng với profile của tập customer churn
    - Nhận diện insight và level từ team leader trở lên của team sales/CSM thấy được toàn cảnh tình hình churn và đặc điểm của users churn
- Sheet Customer Detail:
    - Dùng để tra cứu
    - Thường dùng cho stakeholder là cấp member của team tra cứu từng khách hàng để có thông tin liên lạc, nhân khẩu học, gói dịch vụ khách hàng sử dụng, từ đó các member có phương thức tác động, chăm sóc khách hàng phù hợp để giảm tỷ lệ churn
- Sheet Churn Reason:
    - Phân tích nguyên nhân rời bỏ của khách hàng
- Sheet Ask a question:
    - Nhập keyword sẽ có thông tin hiện ra theo câu hỏi mình nhập
### **3. Insight and Recommendation**
_**Tổng quan về khách hàng của công ty:**_
- Tổng số khách hàng của công ty là 6687 khách hàng, với tỷ lệ nam là 50.58% và nữ là 49.42%. Tỷ lệ khách hàng trên 30 tuổi chiếm đa số với tỷ lệ 81%. Khách hàng của công ty chủ yếu là khách hàng mới có account được lập chưa đến 10 tháng, tỷ lệ nhóm khách hàng này chiếm 26%
- Khách hàng đăng ký cuộc gọi quốc tế không nhiều, chỉ chiếm 38.45%, khách hàng sử dụng gói dịch vụ dữ liệu không giới hạn chiếm phần lớn với tỷ lệ 67.21%, khách hàng đăng lý sử dụng dịch vụ theo nhóm chỉ chiếm 22.75% và khách hàng có sử dụng dịch vụ an ninh thông tin và lưu trữ online chiếm 34.31%
- Khách hàng chủ yếu ký hợp đồng với công ty theo từng tháng với tỷ lệ 51%, phương thức thanh toán chủ yếu là Direct debit với tỷ lệ trên 55%. Chi phí trung bình khách hàng phải trả mỗi tháng là 31.03$, tổng chi phí trung bình của mỗi khách hàng là 1.08k$
_**Tình hình và đặc điểm churned users:**_
- Tỷ lệ churned user chiếm gần 27% so với tổng khách hàng, số lượng 1796 khách hàng với tỷ lệ nam nữ ngang nhau. Khách hàng churn chủ yếu trên 30 tuổi với tỷ lệ 84% và chủ yếu là khách hàng mới có account được lập chưa đến 10 tháng, tỷ lệ 49%
- Một nửa lượng khách hàng churn đăng ký cuộc gọi quốc tế, chiếm 49.11%. Khách hàng sử dụng gói dịch vụ dữ liệu không giới hạn chiếm phần lớn với tỷ lệ 80.35%, khách hàng đăng lý sử dụng dịch vụ theo nhóm chỉ chiếm 5.51% và khách hàng có sử dụng dịch vụ an ninh thông tin và lưu trữ online chiếm 29.4%
- Khách hàng chủ yếu ký hợp đồng với công ty theo từng tháng với tỷ lệ 87.92%, phương thức thanh toán chủ yếu là Direct debit với tỷ lệ 71%. Chi phí trung bình khách hàng phải trả mỗi tháng là 36.8$, tổng chi phí trung bình của mỗi khách hàng là 761.42$
- Khách hàng churn chủ yếu do chuyển sang đối thủ cạnh tranh với tỷ lệ 45.51%. Lý do là công ty đối thủ đã offer họ gói dịch vụ tốt hơn và có dịch vụ tốt hơn
- Nhóm khách hàng không hài lòng với thái độ và sản phẩm của công ty chiếm khoảng 32%. Nguyên nhân chủ yếu là do thái độ của nhân viên hỗ trợ
_**Recommendation:**_
- Tìm hiểu và sản phẩm của đối thủ cạnh tranh và phân tích ưu nhược điểm với sản phẩm của công ty và thuyết phục khách hàng
- Offer những khách hàng churn gói dịch vụ ưu đãi hơn so với đối thủ cạnh tranh
- Tổ chức những buổi training về việc hỗ trợ khách hàng, có kế hoạch trừ KPI đối với những nhân viên có thái độ không tốt với khách hàng
