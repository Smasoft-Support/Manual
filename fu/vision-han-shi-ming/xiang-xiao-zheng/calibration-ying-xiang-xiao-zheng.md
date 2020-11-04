# Calibration 影像校正

### 影像扭曲校正、Scale計算、座標轉換

* Launch Calibration: 啟動校正應用程式 
  * 程式路徑: “C:\Program Files \(x86\)\National Instruments\Vision \Utility\Calibration Training Interface \NI Calibration Training.exe“ 
  * 依照指示完成校正後，將校正結果儲存下來\(.png檔\)
* Calibrated File Path
  * 經過NICalibration Training.exe校正後，將存出來的圖片載入，SmaSEQ 會將校正參數導入視覺專案中。
  * 若未經過NI Calibration Training，亦可載入一張相機拍攝的原始圖片，並使用 Edit Step手動給予 Scale值。
* Edit Step: 可手動編輯Scale

![](../../../.gitbook/assets/tu-pian-3.png)



