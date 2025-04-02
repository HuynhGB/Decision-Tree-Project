# Speculation related to Machine Learning Model and Method
## Giới thiệu
- Việc áp dụng bài toán Cây quyết định vào Hệ hỗ trợ ra quyết định để dự đoán khả năng trả nợ khoản vay của khách hàng là một ứng dụng phổ biến của học máy trong lĩnh vực tài chính. Trong ngữ cảnh dự đoán khả năng trả nợ khoản vay của khách hàng, cây quyết định có thể được áp dụng để xây dựng một mô hình dự đoán dựa trên các đặc trưng của khách hàng.
- Cây quyết định hoạt động bằng cách chia tập dữ liệu thành các phần nhỏ hơn dựa trên các thuộc tính của dữ liệu. Mỗi lần chia, cây quyết định chọn thuộc tính tốt nhất để chia tập dữ liệu sao cho giảm thiểu sự không chắc chắn (uncertainty) trong việc dự đoán kết quả. Quá trình này tiếp tục cho đến khi một tiêu chí dừng được đạt đến, chẳng hạn như sự tinh tế của mô hình hoặc khi không thể chia dữ liệu thành các nhóm đồng nhất hơn.
- Trong quá trình dự đoán khả năng trả nợ, cây quyết định có thể sử dụng các thuộc tính như thu nhập, lịch sử tín dụng, tuổi, số người phụ thuộc và nhiều yếu tố khác để dự đoán xem một khách hàng có khả năng trả nợ thành công hay không. Khi mô hình đã được xây dựng, nó có thể được sử dụng để đưa ra quyết định về việc duyệt hoặc từ chối khoản vay dựa trên thông tin của khách hàng.
## Quy trình
- Đầu tiên ta mô tả dữ liệu để trình bày rõ các thuộc tính trong data.
- Sau đó sẽ thực hiện các bước về xử lý dữ liệu, chẳng hạn như xử lý giá trị bị thiếu, ngoại lai,...
- Kế đến ta đưa dữ liệu vào mô hình DecisionTreeClassifier để phân loại các nhóm khách hàng. Ngoài ra dự án còn áp dụng lần lượt 2 độ đo gini và entropy để so sánh hiệu xuất về tỉ lệ dự đoán đúng của mô hình.
