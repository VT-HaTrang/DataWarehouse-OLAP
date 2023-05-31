# Xây dựng và Phân tích Kho dữ liệu bằng OLAP

Sử dụng các kiến thức về kho dữ liệu và OLAP để xây dựng và phân tích kho dữ liệu cho bộ dữ liệu Supplemental Homicide Report, bao gồm các quy trình chính như: Tiền xử lý dữ liệu và tạo lược đồ hình sao, Tích hợp dữ liệu (SSIS), phân tích dữ liệu và báo cáo (SSAS (kéo thả) + MDX + POWER BI + EXCEL), Data Mining. </br>

## 1. Bộ dữ liệu
</br>
Bộ dữ liệu Supplemental Homicide Report là bộ dữ liệu chứa thông tin về các vụ án giết người và tội phạm liên quan đến sát hại trong nhiều quận và bang tại Hoa Kỳ. Dữ liệu bao gồm hơn 28.000 vụ giết người mà MAP thu được thông qua Đạo luật Tự do Thông tin đối với các vụ giết người không được báo cáo cho Bộ Tư pháp. </br>
Bộ dữ liệu này cung cấp thông tin đa dạng về các vụ án giết người, bao gồm thông tin về nạn nhân, đối tượng, quan hệ giữa họ, vũ khí được sử dụng và các tình huống xảy ra trong các vụ án. Nó cung cấp cái nhìn tổng quan về tình hình tội phạm giết người và mối liên quan giữa các yếu tố khác nhau trong các vụ án. </br>
Dataset có 769.754 dòng khảo sát và 32 thuộc tính. (tính đến tháng 12 năm 2023). </br>
Link nguồn dữ liệu: [Supplemental Homicide Reports](https://data.world/murder-accountability-project/supplemental-homicide-report)

## 2. Lược đồ ngôi sao
</br>
![image](https://github.com/VT-HaTrang/DataWarehouse-OLAP/assets/88712945/049cc981-4a2b-488e-a12f-ea2208b36dce)
