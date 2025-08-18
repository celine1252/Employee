# Employee

# 🚀 Dự đoán khả năng nghỉ việc của nhân viên (HR Attrition Prediction)

![GitHub Repo stars](https://img.shields.io/github/stars/<username>/<repo-name>?style=social)
![GitHub forks](https://img.shields.io/github/forks/<username>/<repo-name>?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/<username>/<repo-name>)
![GitHub issues](https://img.shields.io/github/issues/<username>/<repo-name>)
![GitHub pull requests](https://img.shields.io/github/issues-pr/<username>/<repo-name>)

---

## 📑 Mục lục
- [📌 Giới thiệu](#-giới-thiệu)
- [🗂️ Bộ dữ liệu](#️-bộ-dữ-liệu)
- [🔧 Các bước thực hiện](#-các-bước-thực-hiện)
- [📊 Kết quả](#-kết-quả)
- [💡 Giải pháp đề xuất](#-giải-pháp-đề-xuất)
- [🛠️ Công nghệ sử dụng](#️-công-nghệ-sử-dụng)
- [📌 Cách chạy dự án](#-cách-chạy-dự-án)
- [📸 Minh họa](#-minh-họa)
- [👤 Tác giả](#-tác-giả)

---

## 📌 Giới thiệu
Dự án này tập trung vào việc **phân tích và dự đoán khả năng nghỉ việc (attrition)** của nhân viên dựa trên các đặc trưng nhân khẩu học và hành vi làm việc.  

🎯 **Mục tiêu chính:**
- Xác định các yếu tố quan trọng ảnh hưởng đến quyết định nghỉ việc.
- Xây dựng mô hình Machine Learning để dự đoán khả năng nghỉ việc.
- Đề xuất giải pháp giúp doanh nghiệp **giữ chân nhân viên**.

---

## 🗂️ Bộ dữ liệu
- **Nguồn:** HR Analytics Dataset.  
- **Số lượng mẫu:** ~XXXX nhân viên.  
- **Biến quan trọng:** Tuổi, giới tính, thành phố, kinh nghiệm, học vấn, mức lương, loại hợp đồng.  
- **Nhãn dự đoán:** `Attrition` (Yes/No).  

---

## 🔧 Các bước thực hiện
1. **EDA**: phân tích dữ liệu, trực quan hóa.  
2. **Xử lý dữ liệu**: mã hóa biến phân loại, chuẩn hóa, SMOTE.  
3. **Xây dựng mô hình**: Logistic Regression, Random Forest, XGBoost, LightGBM, Naive Bayes, SVM.  
4. **Đánh giá mô hình**: Accuracy, Precision, Recall, F1, ROC-AUC.  
5. **Feature Importance**: xác định yếu tố tác động lớn nhất.  

---

## 📊 Kết quả
- 📈 Mô hình tốt nhất: **XGBoost** (ROC-AUC: 0.92).  
- 🔑 Yếu tố ảnh hưởng chính: Thâm niên, mức lương, thành phố, học vấn, loại hợp đồng.  

---

## 💡 Giải pháp đề xuất
- Tăng lương & phúc lợi theo thâm niên.  
- Đào tạo & mentoring cho nhân viên.  
- Chính sách linh hoạt về thời gian & phúc lợi.  

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
---

## 📸 Minh họa
Phân phối nhân viên nghỉ việc vs không nghỉ việc.

## 👤 Tác giả
🌟 Thông tin cá nhân

Tên: Nguyễn Văn A

Email: nguyenvana@example.com

LinkedIn: linkedin.com/in/nguyenvana

Portfolio: my-portfolio.com
