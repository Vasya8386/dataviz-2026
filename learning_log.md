# Learning Log - Titanic Data Exploration

## 1. Quá trình gặp lỗi và cách giải quyết

### Vấn đề 1: VS Code không nhận đúng Python kernel

- Mô tả:
Khi mở file .ipynb trong VS Code, em không thấy environment dataviz.

- Nguyên nhân:
Environment chưa được register với Jupyter kernel.

- Cách giải quyết:
Sử dụng lệnh:

python -m ipykernel install --user --name dataviz

sau đó restart VS Code.

- Kết quả:
VS Code đã nhận đúng environment và notebook chạy bình thường.

---

### Vấn đề 2: Chưa hiểu cách sử dụng Markdown và Code cell

- Mô tả:
Ban đầu em chưa biết khi nào nên dùng Markdown cell và khi nào nên dùng Code cell.

- Cách giải quyết:
Tìm hiểu thêm về cấu trúc notebook và xem ví dụ từ các notebook mẫu.

- Kết quả:
Em hiểu cách trình bày notebook rõ ràng hơn và biết cách giải thích kết quả phân tích.

---

# 2. Điều tự học thêm ngoài bài giảng

## Tìm hiểu thêm về trực quan hóa dữ liệu với Seaborn

Ngoài nội dung trên lớp, em đã tự tìm hiểu thêm về thư viện Seaborn để trực quan hóa dữ liệu hiệu quả hơn trong quá trình exploratory data analysis (EDA).

### Những kiến thức đã học thêm:

- Cách sử dụng `barplot()` để so sánh giá trị trung bình giữa các nhóm dữ liệu.
- Cách sử dụng `histplot()` để quan sát phân phối dữ liệu số như tuổi hoặc giá vé.
- Cách sử dụng `boxplot()` để phát hiện outliers và so sánh phân bố dữ liệu giữa các nhóm.
- Cách kết hợp Seaborn với Matplotlib để:
  - thêm tiêu đề biểu đồ
  - chỉnh kích thước figure
  - xoay label
  - tùy chỉnh màu sắc
- Hiểu sự khác nhau giữa:
  - dữ liệu categorical
  - dữ liệu numerical
  - và cách chọn biểu đồ phù hợp cho từng loại dữ liệu.

### Ví dụ kiến thức áp dụng:

Em đã áp dụng `barplot()` để so sánh tỷ lệ sống sót giữa:
- nam và nữ
- các hạng vé khác nhau

Ngoài ra, em sử dụng `histplot()` để quan sát phân bố độ tuổi của hành khách Titanic.

### Tóm tắt kiến thức học được

Qua quá trình tự học, em hiểu rằng trực quan hóa dữ liệu không chỉ giúp biểu đồ đẹp hơn mà còn giúp:
- phát hiện xu hướng dữ liệu
- tìm outliers
- so sánh giữa các nhóm
- hỗ trợ đưa ra kết luận nhanh hơn trong phân tích dữ liệu.

Em cũng nhận ra rằng Seaborn phù hợp cho data analysis hơn Matplotlib trong nhiều trường hợp vì cú pháp ngắn gọn và biểu đồ trực quan hơn.

---

# 3. Reflection Cá Nhân

## Điều khó nhất

Điều khó nhất là hiểu cách phân tích dữ liệu và đặt câu hỏi từ dataset thay vì chỉ chạy code.

---

## Điều thú vị nhất

Điều thú vị nhất là khám phá tỷ lệ sống sót của hành khách Titanic và tìm ra sự khác biệt giữa nam và nữ.

---

## Câu hỏi còn chưa có câu trả lời

Liệu có thể dự đoán chính xác khả năng sống sót của hành khách chỉ bằng một vài đặc điểm cơ bản không?

---

# 4. Tài nguyên tự học

## Video YouTube đã xem

### Video:
Python Pandas Tutorial by freeCodeCamp

### Điều học được:
Em học được cách sử dụng groupby(), filtering và xử lý missing values trong Pandas.

---

# 5. Bonus

## Kaggle

### Kaggle account: 
https://www.kaggle.com/vasilu

### Notebook đã đọc:
Titanic Data Science Solutions

### Hai kỹ thuật mới học được:
1. Feature engineering
2. Handling missing values bằng median

---

## Người theo dõi trên LinkedIn

### Tên:
Andrew Ng

### Lý do chọn:
Vì em đã biết Andrew Ng qua các khóa học vào các kỳ trước trên Coursera, và vì tài khoản này chia sẻ nhiều kiến thức về AI, machine learning và data science rất hữu ích cho người mới học.