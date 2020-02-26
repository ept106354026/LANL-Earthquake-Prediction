# LANL-Earthquake-Prediction
kaggle LANL Earthquake Prediction

嘗試方向分為兩種

- 使用 cnn 或是 lstm 
  - 原始訊號
  - 對信號進行fft(快速傅立葉轉換)後，得到頻譜進行建模
  
- 進行特徵工程，使用 xgboost 或其他樹類模型進行預測，特徵
  - quantile  of moving mean/std(train_feature.csv) 
  - frequency spectrum feature(X/X_1/X_2.csv)
  

 
