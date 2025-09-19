# 📊 Sales Data Analysis (Excel & Power BI)

## 1. Mục tiêu dự án
Phân tích dữ liệu bán hàng (~2,000 dòng) nhằm:
- Làm sạch dữ liệu: xoá trùng, xử lý null, chuẩn hoá ngày tháng.
- Tạo cột tính toán `OrderTotal` (nếu có `revenue` thì dùng `revenue`, nếu không thì tính `unit_price * quantity * (1 - discount)`).
- Phân tích & trực quan hóa doanh thu theo tháng, khách hàng, thành phố, và sản phẩm.

## 2. Công cụ sử dụng
- **Excel / Pandas**: Làm sạch dữ liệu.
- **SQL**: Tính tổng doanh thu theo khách hàng / thành phố / tháng.
- **Power BI**: Xây dựng dashboard trực quan.

## 3. Dashboard & Phân tích

### 🔹 Doanh thu theo khu vực (Region)
![Doanh thu theo region](./{14918F66-E024-40EE-947B-2758030CB629}.png)

### 🔹 Top khách hàng
![Top khách hàng](./{C447765A-3D65-432D-A8C3-3B08148C1753}.png)

### 🔹 Xu hướng doanh thu theo tháng
![Doanh thu theo tháng](./{A24EEC37-1FD6-4D55-B87B-9D481D7FF65E}.png)

### 🔹 Doanh thu theo sản phẩm (Treemap)
![Doanh thu theo sản phẩm](./{02F4098C-D9EB-460C-9D1F-2A4DD1ED633F}.png)

## 4. Kết quả
- **Khu vực South** có doanh thu cao nhất.
- Xác định được **Top khách hàng** đóng góp lớn.
- Doanh thu biến động theo tháng → có thể dùng cho dự báo.
- Nhóm sản phẩm **Electronics** chiếm tỷ trọng lớn nhất.
