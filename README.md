# 🚀 Dự đoán khả năng nghỉ việc của nhân viên (HR Attrition Prediction)

![GitHub last commit](https://img.shields.io/github/last-commit/<username>/<repo-name>)
![GitHub issues](https://img.shields.io/github/issues/<username>/<repo-name>)
![GitHub pull requests](https://img.shields.io/github/issues-pr/<username>/<repo-name>)

---

## 📌 Giới thiệu
Dự án này tập trung vào việc **phân tích và dự đoán khả năng nghỉ việc (attrition)** của nhân viên dựa trên các đặc trưng nhân khẩu học và hành vi làm việc.  

🎯 **Mục tiêu chính**:
- Xác định các yếu tố quan trọng ảnh hưởng đến quyết định nghỉ việc.  
- Xây dựng mô hình Machine Learning để dự đoán khả năng nghỉ việc.  
- Đề xuất giải pháp giúp doanh nghiệp **giữ chân nhân viên**.  

---

## 🗂️ Bộ dữ liệu
- **Nguồn**: HR Analytics Dataset.  
- **Số lượng mẫu**: 1000 nhân viên.  
- **Biến quan trọng**: Tuổi, giới tính, thành phố, kinh nghiệm, học vấn, mức lương, loại hợp đồng.  
- **Nhãn dự đoán**: `Attrition` (Yes/No).  

---

## 🔧 Các bước thực hiện
1. **Khám phá dữ liệu (EDA)**  
   - Phân tích phân phối dữ liệu.  
   - Trực quan hóa mối quan hệ giữa các biến và tình trạng nghỉ việc.  

2. **Xử lý dữ liệu**  
   - Mã hóa biến phân loại (One-hot/Label Encoding).  
   - Chuẩn hóa dữ liệu.  
   - Xử lý mất cân bằng dữ liệu bằng **SMOTE**.  

3. **Xây dựng mô hình Machine Learning**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
   - LightGBM  
   - Naive Bayes  
   - SVM  

4. **Đánh giá mô hình**  
   - Các chỉ số: Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
   - So sánh hiệu năng giữa các mô hình.  

5. **Phân tích Feature Importance**  
   - Xác định những yếu tố tác động nhiều nhất đến khả năng nghỉ việc.  

---

## 📊 Kết quả
- Mô hình tốt nhất: **XGBoost** (ROC-AUC: 0.92).  
- Các yếu tố ảnh hưởng lớn nhất:  
  - Thâm niên làm việc  
  - Mức lương hiện tại  
  - Thành phố sinh sống  
  - Trình độ học vấn  
  - Loại hợp đồng  

---

## 💡 Giải pháp đề xuất
- **Chính sách giữ chân nhân viên**: tăng lương theo năng lực & thâm niên.  
- **Hỗ trợ phát triển sự nghiệp**: đào tạo, mentoring, lộ trình thăng tiến.  
- **Cân bằng công việc & cuộc sống**: linh hoạt thời gian làm việc, chế độ phúc lợi tốt hơn.  

---

## 🛠️ Công nghệ sử dụng
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-00C853?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?logo=python&logoColor=white)

---

## 📌 Cách chạy dự án

```bash
# Clone repo
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>

# Cài đặt thư viện
pip install -r requirements.txt

# Mở notebook
jupyter notebook
```

---

## 📸 Minh họa
![Attrition Distribution](images/attrition_distribution.png)  
*Biểu đồ phân phối nhân viên nghỉ việc vs không nghỉ việc.*  

---

## 👤 Tác giả
🌟 **Thông tin cá nhân**  

- Tên: Tô Huỳnh Ngọc Ngân
- Email: thnn0125@gmail.com
- LinkedIn: https://www.linkedin.com/in/moon0125/
- Portfolio: [my-portfolio.com](https://my-portfolio.com)  

---
⭐ Nếu thấy dự án hữu ích, hãy **Star** repo để ủng hộ nhé!
