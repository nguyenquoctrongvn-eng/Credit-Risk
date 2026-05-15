# Credit-Risk Analyst
### MỤC TIÊU DỰ ÁN

Mục tiêu chính của dự án này là xây dựng một hệ thống phân tích và dự báo rủi ro tín dụng toàn diện dựa trên dữ liệu khách hàng vay vốn. Các mục tiêu cụ thể bao gồm:

  - **Khám phá dữ liệu (EDA):**  
    Nhận diện các đặc điểm quan trọng ảnh hưởng đến khả năng hoàn trả khoản vay như thu nhập, mục đích vay và tình trạng sở hữu nhà ở.

  - **Xử lý và chuẩn hóa dữ liệu:**  
    Áp dụng các kỹ thuật tiên tiến (như Yeo-Johnson Transformation và Scaling) để nắn chỉnh các biến số bị lệch, giúp tối ưu hóa hiệu suất cho các mô hình máy học.

  - **Phân khúc khách hàng (Clustering):**  
    Sử dụng thuật toán K-Means để chia nhóm khách hàng dựa trên sự tương đồng về đặc điểm định tính và mức độ rủi ro, từ đó hỗ trợ doanh nghiệp xây dựng chiến lược quản lý rủi ro phù hợp cho từng nhóm.

  - **Xây dựng mô hình dự báo (Classification):**  
    Thử nghiệm và so sánh nhiều thuật toán khác nhau (Logistic Regression, Random Forest, XGBoost...) để tìm ra mô hình có khả năng phân loại nợ xấu chính xác nhất.

### CÔNG CỤ VÀ THƯ VIỆN SỬ DỤNG
- Ngôn ngữ lập trình: Python

- Xử lý dữ liệu: Pandas, NumPy
  
- Trực quan hóa dữ liệu:   Power BI, Matplotlib, Seaborn
  
- Xây dựng mô hình: Scikit-learn ( K-Means, Logistic Regression, Decision Tree, Random Forest), 

### ĐẶC ĐIỂM BỘ DỮ LIỆU
- Quy mô: 32,581 dòng và 11 biến số.

- Biến mục tiêu (`loan_status`): 0 (Non Default - Không nợ xấu) và 1 (Default - Nợ xấu).

- Các nhóm biến chính:

  * Thông tin khách hàng: `person_age`,`person_home_ownership`.

  * Tài chính & Việc làm: `person_income`, `person_emp_length`.

  * Thông tin khoản vay: `loan_amnt`, `loan_int_rate`, `loan_grade`, `loan_intent`, `loan_percent_income`

  * Lịch sử tín dụng: `cb_person_cred_hist_length`, `cb_person_default_on_file`.
 

### DASHBOARD POWER BI
Theo dõi tổng quan danh mục khách hàng vay vốn:

- Tổng số khách hàng
- Tổng thu nhập
- Tổng khoản vay
- Tỷ lệ nợ xấu
  
Phân tích tỷ lệ nợ xấu theo:

- Mục đích vay 
- Tình trạng sở hữu nhà 
- Lịch sử nợ xấu 
- Xếp hạng khoản vay
- Độ tuổi khách hàng
  
### TÁC GIẢ 
Nguyễn Quốc Trọng
