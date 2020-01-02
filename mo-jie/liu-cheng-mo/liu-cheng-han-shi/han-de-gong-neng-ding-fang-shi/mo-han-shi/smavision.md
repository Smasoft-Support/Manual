# 命令機器視覺模組【SmaVISION】

### 命令指定的 SmaVISION Module 執行動作指令。

| 參數 | 說明 |
| :--- | :--- |
| Module | 選擇要命令的模組。 |
| Method | 選擇動作指令。 |
| Error Action | 命名錯誤名稱。當此步驟發生錯誤時，將紀錄此名稱。 |
| Update Result | 填入指令語法 |

{% hint style="info" %}
有關 Error Action 欄位名稱的具體功能，請參考《在 ErrorHandle 編輯專案的錯誤處理流程》
{% endhint %}

## Method 動作指令與語法

###  ****&lt; **Start** &gt; **，開始運作**

* 無須設定其他參數

![SmaVISION - Start](../../../../../.gitbook/assets/smavision-start.PNG)

### &lt; **Result** &gt; **，等待視覺模組完成動作**

* **Update Result 參數**
  * 指派變數，負責接收結果數值
  * 設定：
    * SmaVISION 預設輸出值
      * Source（原圖），數值型態為 Image（影像）
      * Image（影像成果圖），數值型態為 Image（影像）
      * Overlay（原圖+標記），數值型態為 Image（影像）
      * Log 紀錄了全部影像步驟的數值資訊、執行時間等，數值型態為 。
      * Result 顯示模組執行後的結果，數值型態為 Boolean
      * `OI.Monitor=Source`，將影像原圖寫至操作員介面上名為「Monitor」的影像空間變數。
        * 可用的圖層：
      * `OI.Pass=Result`，將結果 \(Pass / Fail\) 寫至操作員介面上名為「Pass」的 Boolean 變數。
      * `Local.Number=Count`，可將視覺模組中的化名為 Count 的值，寫至名為 Number 的 Local 數值變數中。

![SmaVISION - Result](../../../../../.gitbook/assets/smavision-result2.PNG)

![SmaVISION - Edit result step](../../../../../.gitbook/assets/smavision-result.PNG)

{% hint style="info" %}
有關化名的介紹與操作方式，詳見《SmaVISION模組 - 結果數據處理》
{% endhint %}

### &lt; **Save** &gt; **，將視覺影像輸出成圖**

* **Update Result 參數**
  * 指定存放圖片的路徑。若有需要，可再指定層、縮放比例。
  * 語法：
    * 可點擊 Save 方法旁邊的「...」按鈕，直接指定路徑並給予名稱及副檔名，如

      `"C:\Users\ChaoMin\Desktop\SSProject\123.png"`。

    * \(Option\) 若要指定圖層或縮放比例，請在路徑後補上指令，並以「;」分隔，如`"C:\Users\ChaoMin\Desktop\SSProject\123.png";Image;50`，表示指定「Image」圖層，且圖片縮放為原本的 50%。
      * 可指定的圖層：
        * Source（原圖）
        * Image（影像成果圖）
        * Overlay（原圖+標記）

![SmaVISION - Save](../../../../../.gitbook/assets/smavision-save.PNG)



