# Phân Cụm và Dự Đoán Loài Thực Vật USDA (USDA Plant Species Clustering & Prediction)  

## 1. Tổng Quan Dự Án  
- <b> Mục tiêu: </b> Phân tích và phân cụm phân bố các loài thực vật trên toàn nước Mỹ nhằm hỗ trợ quy hoạch môi trường và ra quyết định trong nông nghiệp.
- <b> Bộ dữ liệu: </b> USDA Plant Dataset (34.781 mẫu, 70 đặc trưng).
- <b> Các bên liên quan: </b> Cơ quan môi trường, nhà quy hoạch nông nghiệp, và các nhà nghiên cứu.

## 2. Nhu Cầu và Mục Tiêu Kinh Doanh  
- Xác định các mô hình phân bố theo khu vực của các loài thực vật.
- Phát hiện các điểm bất thường trong phân cụm để hỗ trợ chiến lược bảo tồn.
- Cung cấp các thông tin dựa trên dữ liệu để phục vụ quy hoạch nông nghiệp và quản lý đa dạng sinh học.

## 3. Chuẩn Bị Dữ Liệu và Phương Pháp Phân Tích  
- <b> Làm sạch dữ liệu: </b> Xử lý giá trị thiếu, mã hóa biến phân loại, chuẩn hóa các đặc trưng.
- <b> Phân tích khám phá dữ liệu (EDA): </b> Trực quan hóa sự phân bố của các loài theo bang và vùng sinh thái.
- <b> Các mô hình phân cụm được thử nghiệm: </b> K-Means, DBSCAN, Agglomerative Clustering, và phân cụm dựa trên Autoencoder.
- <b> Chỉ số đánh giá: </b> Silhouette Score, WCSS (Phương pháp Elbow).

## 4. Kết Quả Chính  
- Heatmaps và dashboards trực quan thể hiện sự phân bố của các loài thực vật.
- Biểu đồ so sánh các mô hình phân cụm cùng điểm đánh giá.
- Tài liệu hóa quy trình, phương pháp và kết quả gửi đến các bên liên quan.

## 5. Phát Hiện và Nhận Định  
- DBSCAN đạt hiệu suất cao nhất (Silhouette Score ≈ 0.57).
- Một số loài có xu hướng tập trung theo vùng, trong khi những loài khác phân bố rộng rãi trên toàn quốc.
- Kết quả giúp hỗ trợ công tác bảo vệ môi trường, quy hoạch cây trồng, và chiến lược đa dạng sinh học.

## 6. Kỹ Năng Ứng Dụng  
Làm sạch dữ liệu, phân tích EDA, phân cụm dữ liệu, trực quan hóa, đánh giá thống kê, và truyền đạt kết quả phân tích dưới dạng thông tin hỗ trợ ra quyết định.  

## 7. Phản Hồi và Tự Đánh Giá  
Dự án này giúp tôi nâng cao khả năng xử lý tập dữ liệu lớn, đánh giá nhiều mô hình khác nhau và chuyển đổi kết quả kỹ thuật thành các thông tin có giá trị thực tiễn cho nhà quản lý và các bên liên quan.
