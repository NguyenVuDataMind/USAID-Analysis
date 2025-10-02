# 🌍 USAID-Analysis  

## 📌 Giới thiệu  
Dự án **USAID Analysis** tập trung vào việc **phân tích hiệu quả và quản lý chuỗi cung ứng y tế toàn cầu của USAID**.  
Nguồn dữ liệu chính là **Supply Chain Shipment Pricing Data** do USAID cung cấp, bao gồm thông tin về vận chuyển và giá cả của các mặt hàng y tế trong giai đoạn **2007–2015**.  

Bộ dữ liệu có:  
- **10.324 dòng** và **33 cột** thông tin (sau xử lý còn **8.224 dòng, 30 cột**).  
- Các nhóm thông tin chính: mã đơn hàng, quốc gia, nhà cung cấp, loại sản phẩm, số lượng, giá trị đơn hàng, chi phí vận chuyển, thời gian giao hàng, v.v.  

---

## 🛠️ Quy trình xử lý dữ liệu  
1. **Tiền xử lý**:  
   - Chuẩn hóa dữ liệu, loại bỏ giá trị không hợp lệ.  
   - Xử lý dữ liệu thiếu (null), loại bỏ trùng lặp.  
   - Chuyển đổi định dạng ngày tháng và các biến phân loại.  

2. **Phân tích chính**:  
   - **Product Distribution**: phân tích phân bổ sản phẩm theo quốc gia, khối lượng, giá trị.  
   - **Quality Control**: đo lường tỷ lệ giao hàng trễ, số ngày trễ trung bình, chất lượng vận chuyển theo phương thức.  
   - **Cost Analysis**: đánh giá chi phí logistics (theo năm, theo phương thức vận chuyển).  
   - **Delivery Method**: so sánh chất lượng giao hàng giữa Air, Ocean, Truck, Air Charter.  
   - **Vendor Performance**: phân tích hiệu quả hoạt động của các nhà cung cấp.  

---

## 📊 Một số kết quả nổi bật  
- **Nigeria, Zambia, Mozambique** là những thị trường trọng điểm với khối lượng vận chuyển lớn.  
- Chi phí vận chuyển chênh lệch đáng kể:  
  - Guinea có chi phí cao nhất (**56,38 USD/kg**).  
  - Mozambique thấp nhất (**1,03 USD/kg**).  
- Tỷ lệ giao hàng trễ trung bình của USAID: **13,55%**, cao hơn chuẩn ngành (5–10%).  
- Chi phí logistics chiếm **6,9%** tổng giá trị hàng hóa (khoảng **103 triệu USD**).  
- Phương thức vận chuyển **Air Charter** giúp rút ngắn thời gian trễ (13 ngày trung bình) so với Ocean (32 ngày).  

---

## 🚀 Công nghệ sử dụng  
- **Python** (pandas, numpy, matplotlib, seaborn)  
- **Jupyter Notebook** cho phân tích và trực quan hóa dữ liệu  
- **Power BI** cho dashboard trực quan  
- **Canva** cho thiết kế slide báo cáo  

---

## 📂 Tài liệu liên quan  
- 📑 Slide chi tiết báo cáo: [Xem tại đây](https://www.canva.com/design/DAG0ipzdtWo/WVvXx5W4nCCuguqC9dBuqw/edit)  
- 📘 File phân tích đầy đủ: `USAID Analysis.pdf` (lưu trữ cục bộ, không push lên GitHub do dung lượng lớn).  
- 📊 Dashboard trực quan (Power BI): [Xem trực tiếp](https://app.powerbi.com/view?r=eyJrIjoiMTQ5ZGRiMzYtYjIxZi00MjYzLWJhZDUtNjhjZDllOGRjODE5IiwidCI6ImFmMWYzNzUzLTM5MjUtNGU2Zi05NDliLTk3YzAwNzMyMDgwMyIsImMiOjEwfQ%3D%3D&fbclid=IwY2xjawNGHZ9leHRuA2FlbQIxMABicmlkETFqRlIwQWM2UmxnV3R6cTF0AR7IJ_K2dLnQ0hjQsn_59ftFyts0e2wIdDhB5AEI_MyrnexoWMHLzj9wg6I8uw_aem_GklOs_earwyzABcsigod5Q)  

---

## ✨ Mục tiêu dự án  
- Đánh giá hiệu quả logistics trong chuỗi cung ứng y tế của USAID.  
- Xác định nguyên nhân gây chậm trễ và đề xuất cải tiến.  
- Đưa ra khuyến nghị để tối ưu chi phí và nâng cao chất lượng giao hàng.  

---

✍️ *Dự án thực hiện như một case study phân tích dữ liệu, kết hợp Python và Power BI để mang lại cái nhìn trực quan và thực tiễn.*
