# 📈 Bitcoin Price Prediction

Dự án sử dụng các kỹ thuật Machine Learning để phân tích và dự đoán giá Bitcoin theo thời gian. Đồ án cuối kỳ môn **Khai thác dữ liệu**.

## 📂 Dataset
- **Nguồn**: [Kaggle - Bitcoin data from 9th Apr 2014 to 30th Dec 2022](https://www.kaggle.com/datasets/sushilkumarinfo/bitcoin-data-from-9thapr2014-to-30thdec2022)
- Bao gồm các thông tin: Ngày, Giá mở cửa, Giá cao nhất, Giá thấp nhất, Giá đóng cửa, Volume, Market Cap,...

## 🛠️ Mô hình sử dụng
- LSTM
- BiLSTM
- ARIMA
- GRU
- SVR
- LightGBM-LSTM Stacking
- Prophet
- SARIMAX
- Transformer
- Diffusion-VAE

## 📊 Đánh giá mô hình
Các chỉ số đánh giá:
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)
- RMSE (Root Mean Square Error)

## 📁 Nội dung chính
- `Exploratory_Data_Analysis.ipynb`: Khám phá dữ liệu ban đầu
- `Model_LSTM.ipynb`: Huấn luyện và đánh giá LSTM
- `Model_ARIMA.ipynb`: Dự báo bằng ARIMA
- `Stacking_Model.ipynb`: Mô hình tổ hợp nhiều thuật toán
- ...

## ✅ Mục tiêu
- Hiểu rõ quy trình xử lý và dự báo chuỗi thời gian
- So sánh hiệu suất các mô hình học máy trong dự đoán giá Bitcoin

---

*Được thực hiện như một phần của môn học Khai thác Dữ liệu - Đại học Quốc gia TP.HCM.*

