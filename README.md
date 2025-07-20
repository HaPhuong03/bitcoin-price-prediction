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
- LightGBM-LSTM Stacking
- SVR
- RNN
- Prophet
- SARIMAX
- SARIMAX + LSTM
- Diffusion-VAE

## 📊 Đánh giá mô hình
Các chỉ số đánh giá:
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)
- RMSE (Root Mean Square Error)

## 📁 Nội dung chính
- `Data_Visualization.ipynb`: Khám phá dữ liệu ban đầu
- `LSTM.ipynb`, `BiLSTM.ipynb`, `ARIMA.ipynb`, `GRU.ipynb`, `LightGBM-LSTM_Stacking.ipynb`,`SVR.ipynb`,`RNN.ipynb`,`Prophet.ipynb`,`SARIMAX.ipynb`, `SARIMAX-LSTM.ipynb`, `Diffusion_VAE.ipynb` : Huấn luyện, dự báo và đánh giá hiệu suất các mô hình học máy
- `BaoCaoKetQua.pdf`: Bài báo tổng hợp kết quả nghiên cứu, bao gồm:  
  1. Giới thiệu đề tài  
  2. Nghiên cứu liên quan  
  3. Các thuật toán sử dụng  
  4. Kết quả thực nghiệm *(So sánh hiệu suất các mô hình dự đoán giá Bitcoin)*  
  5. Kết luận  
  → Được trình bày theo định dạng bài báo khoa học chuẩn của **Springer**


## ✅ Mục tiêu
- Hiểu rõ quy trình xử lý và dự báo chuỗi thời gian
- So sánh hiệu suất các mô hình học máy trong dự đoán giá Bitcoin

---

*Được thực hiện như một phần của môn học Khai thác Dữ liệu - Trường Đại học Công nghệ Thông tin - Đại học Quốc gia TP.HCM.*

