README
 Phân Tích & Dự Báo Giá Cổ Phiếu Coca-Cola (KO) 1980–2026
Môn học: Phân tích và Dự báo Chuỗi Thời gian (127109)
Nhóm: Nhóm 4
Trường: Đại học Kinh tế TP.HCM (UEH)
 Cấu trúc Repository
📁 NHOM4_PHAN-TICH-CHUOI-THOI-GIAN-VA-DU-BAO/
├── KO_Stock_Price_Forecasting_Complete.ipynb   # Notebook chính (toàn bộ pipeline)
├── KO_CocaCola_Stock_Prices_1980_2026.csv      # Dữ liệu gốc
├── KO_Train_Processed.csv                      # Tập huấn luyện (sau tiền xử lý)
├── KO_Test_Processed.csv                       # Tập kiểm tra (sau tiền xử lý)
├── Preds_File2_Classical.csv                   # Kết quả dự báo ARIMA/Holt-Winters
├── Preds_File3.csv                             # Kết quả dự báo XGBoost
├── Preds_GARCH_Vol.csv                         # Kết quả dự báo phương sai GARCH
└── README.md
​
 Mô tả Dữ liệu
Thuộc tính
Chi tiết
Nguồn
Yahoo Finance (cổ phiếu KO – The Coca-Cola Company)
Thời gian
01/01/1980 – 2026
Tần suất
Ngày giao dịch (Daily)
Các cột chính
Date, Open, High, Low, Close, Volume, RSI_14, MACD, MA_20
 Hướng dẫn Chạy Notebook
Mở file KO_Stock_Price_Forecasting_Complete.ipynb trên Google Colab
Bấm Runtime → Run All
Notebook sẽ tự động tải dữ liệu từ GitHub — không cần cấu hình thêm gì
 Không cần Google Drive. Không cần tải file thủ công.
 Nội dung Phân tích
Phần
Nội dung
Phần 1
Tiền xử lý, EDA tài chính, trích xuất đặc trưng (RSI, MACD), phân tích tính dừng
Phần 2
Baseline thống kê: Naive Forecast, ARIMA, Holt-Winters; chẩn đoán nhiễu trắng
Phần 3
Machine Learning: Sliding Window, XGBoost, Random Forest, SHAP
Phần 4.1
ARIMA-GARCH: mô hình hóa phương sai có điều kiện
Phần 4.2
Deep Learning: LSTM dự báo phi tuyến
Phần 5
Đánh giá chéo, backtesting chiến lược giao dịch, tổng hợp báo cáo
 Thành viên Nhóm
Tên
Vai trò
Nhiệm vụ
Tỷ trọng
Lê Thị Cẩm Vân
Data Engineer & EDA
Tiền xử lý, trích xuất đặc trưng tài chính (RSI, MACD), phân tích tính dừng (Phần 1)
16.6%
Đặng Nhựt Hùng
Classical Quant
Xây dựng Baseline thống kê (Naive, ARIMA, Holt-Winters), chẩn đoán nhiễu trắng (Phần 2)
16.6%
Tô Thanh Phong
ML Engineer
Tái cấu trúc Sliding Window, huấn luyện XGBoost/Random Forest, SHAP (Phần 3)
16.6%
Quãng Trọng Sỹ Nghi
Financial Modeler
Mô hình hóa phương sai với ARIMA-GARCH (Phần 4.1)
16.6%
Trần Hoàng Thiện
DL Researcher
Dự báo phi tuyến với Deep Learning LSTM (Phần 4.2)
16.6%
Phạm Xuân Huỳnh
Strategist & QA
Đánh giá chéo, backtesting chiến lược giao dịch, tổng hợp Report (Phần 5)
17.0%
