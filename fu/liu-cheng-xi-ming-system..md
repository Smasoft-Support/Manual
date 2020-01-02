# 流程編輯器之系統變數

* System.Pass
  * 紀錄本次專案執行累計的 True 次數
* System.Fail
  * 紀錄本次專案執行累計的 False 次數
* System.Iteration
  * 紀錄本次專案執行的輪迴次數
* System.Yield
  * 紀錄本次專案執行的良率。等同 System.Pass 除以 System.Fail
* System.Time
  * 紀錄本輪 Main 執行完畢的耗時。
* System.Status
  * 紀錄本輪 Main 執行完畢的最終累計結果 True / False
* System.Pause
  * 顯示目前 SmaSEQ 是否為暫停狀態。
* System.Log
  * 紀錄本輪 Main 中 SmaVISION 模組執行的細節資訊。
* Error.Action
  * 紀錄錯誤發生時的錯誤名稱。
* Error.Msg
  * 紀錄錯誤發生時的錯誤訊息。

{% hint style="info" %}
關於 Error.Action 的用法，詳見《Sequencer 流程編輯器》篇中的《Sequence - 流程》-《在 ErrorHandle 編輯專案的錯誤處理流程》
{% endhint %}



