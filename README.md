# coffee-shop-sales-dashboard

Dữ Liệu Bán Hàng Nói Gì? Phân Tích & Kể Chuyện bằng Power BI

<img width="634" height="356" alt="pic1" src="https://github.com/user-attachments/assets/831e8cf8-96b4-44f6-95e4-e28ad9825b7c" />

Chào mọi người, tôi xin chia sẻ một dự án cá nhân gần đây về thiết kế dashboard và phân tích dữ liệu bán hàng cho một quán cà phê, được thực hiện bằng Power BI. Mục tiêu của dự án không chỉ là trình bày các con số, mà còn là tìm ra những insight giá trị và biến chúng thành hành động cụ thể.

Dữ liệu mình filter từ ngày 1/3/2024 đến 28/2/2025
Nhìn vào biểu đồ doanh số theo tháng (Sales | By Month), tôi nhận thấy một vấn đề rõ rệt: Doanh số bán hàng giảm đáng kể từ tháng 3 đến tháng 8. Đây chính là điểm mà tôi cần đào sâu để tìm hiểu nguyên nhân.

Để tìm hiểu lý do, tôi đã chia dữ liệu thành hai nhóm:
Nhóm 1: Các tháng có doanh số cao (từ tháng 9 đến tháng 2).
Nhóm 2: Các tháng có doanh số thấp (từ tháng 3 đến tháng 8).
Tôi đã tạo các dashboard riêng biệt để so sánh hai nhóm này.

1. Phân tích nhóm doanh số cao:
<img width="635" height="358" alt="pic2_nhomDoanhSoCao" src="https://github.com/user-attachments/assets/8cc8bc84-eb50-4db0-ae4b-40ff60013669" />

Biểu đồ "Sales By Hour" của nhóm này cho thấy doanh số phân bổ khá đều trong cả ngày, không có "vùng lõm" rõ rệt. Các chỉ số cũng rất tích cực với tổng doanh số là 60,32K và 1912 giao dịch.

2. Phân tích nhóm doanh số thấp:
<img width="634" height="356" alt="pic3_nhomDoanhSoThap" src="https://github.com/user-attachments/assets/8a4ebb7b-e211-416b-973a-7c16d64185d2" />

Đây là phần thú vị. Khi phân tích nhóm tháng có doanh số thấp, tôi đã tìm ra một số insight quan trọng:
Tổng doanh số chỉ đạt 45,12K, giảm đáng kể so với nhóm 1.
Tổng số giao dịch chỉ là 1405, thấp hơn nhiều so với 1912 của nhóm cao điểm. Điều này cho thấy vấn đề cốt lõi không phải là giá trị mỗi giao dịch, mà là số lượng khách hàng đến quán giảm mạnh.
Biểu đồ "Sales By Hour" của nhóm này có một "vùng lõm" sâu vào buổi chiều (từ 11h-18h), thể hiện sự sụt giảm doanh số rõ rệt vào thời điểm này.

- Dựa trên phân tích, tôi đã đưa ra các đề xuất hành động:
Đề xuất 1 (Giải pháp chính): Tập trung vào việc thu hút khách hàng mới trong các tháng thấp điểm, thay vì chỉ giảm giá đơn thuần. Có thể triển khai các chiến dịch marketing, quảng bá trên mạng xã hội hoặc hợp tác với các đối tác để tăng lưu lượng khách.
Đề xuất 2 (Giải pháp chi tiết): Áp dụng chương trình khuyến mãi/voucher -20% vào các khung giờ thấp điểm đã xác định trên biểu đồ (11h-18h) để kích thích nhu cầu mua sắm.

Dự án này cho tôi thấy rằng một dashboard tốt không chỉ hiển thị các con số, mà còn phải kể được một câu chuyện, giúp người ra quyết định nhìn thấy vấn đề và đưa ra giải pháp hiệu quả. Hy vọng bài viết này hữu ích cho những ai đang làm về Power BI và Data Analytics.
Cảm ơn mọi người đã theo dõi! Nếu bạn có bất kỳ nhận xét hay câu hỏi nào, hãy để lại bình luận nhé.

- Data source: https://lnkd.in/g3fvR4WK
