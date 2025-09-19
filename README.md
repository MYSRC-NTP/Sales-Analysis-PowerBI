# 📊 Sales Data Analysis

Dự án phân tích dữ liệu bán hàng bằng **Excel, Pandas, SQL và Power BI**.

---
## 1. Mục tiêu
- Làm sạch dữ liệu bán hàng (~2,000 dòng).  
- Tính toán **OrderTotal** cho mỗi đơn hàng.  
- Phân tích doanh thu theo thời gian, khách hàng, khu vực.  
- Trực quan hóa dữ liệu với Power BI.  

---

## 2. Các bước thực hiện
- **Excel**: làm sạch dữ liệu (xoá trùng, xử lý NULL, chuẩn hoá ngày).  
- **Python (Pandas)**: tính toán OrderTotal, merge dữ liệu, exploratory data analysis.  
- **SQL**: truy vấn doanh thu theo khách hàng / thành phố / tháng.  
- **Power BI**: trực quan hóa dữ liệu.  

---

**Excel**.

### 🔹 Data
![Data sales](./IMG/{48EE15CB-2A85-4556-AEA1-5B62710CDD6B}.png)

### 🔹 Tạo 3 Pivot Table
![Doanh thu theo tháng](./IMG/{05FF0B22-823B-46BB-9F2B-0EC25093C834}.png)

### 🔹 3 biểu đồ 
![Doanh thu theo sản phẩm](./IMG/{A9611EFC-6E3E-4621-968B-AC3778D3FF41}.png)



**Power BI**.

## 3. Dashboard & Kết quả

### 🔹 Doanh thu theo khu vực (Region)
![Doanh thu theo region](./IMG/{14918F66-E024-40EE-947B-2758030CB629}.png)

### 🔹 Top khách hàng
![Top khách hàng](./IMG/{C447765A-3D65-432D-A8C3-3B08148C1753}.png)

### 🔹 Xu hướng doanh thu theo tháng
![Doanh thu theo tháng](./IMG/{A24EEC37-1FD6-4D55-B87B-9D481D7FF65E}.png)

### 🔹 Doanh thu theo sản phẩm (Treemap)
![Doanh thu theo sản phẩm](./IMG/{02F4098C-D9EB-460C-9D1F-2A4DD1ED633F}.png)

---

## 4. Kết luận
- **South** là khu vực có doanh thu cao nhất.  
- Một số khách hàng (ID: CUST-2437, CUST-1401, …) chiếm phần lớn doanh thu.  
- Doanh thu có tính mùa vụ, biến động theo từng tháng.  
- Nhóm sản phẩm **Electronics** chiếm tỷ trọng doanh thu lớn nhất.  

