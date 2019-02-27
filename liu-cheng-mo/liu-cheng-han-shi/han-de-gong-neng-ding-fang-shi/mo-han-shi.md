# 模組函式

### \# SmaCOM

呼叫SmaCOM模組進行通訊連線。

<table>
  <thead>
    <tr>
      <th style="text-align:left">設定參數</th>
      <th style="text-align:left">參數說明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">模組(Module)</td>
      <td style="text-align:left">選擇要執行的模組專案</td>
    </tr>
    <tr>
      <td style="text-align:left">方法(Method)</td>
      <td style="text-align:left">
        <p>模組要執行的功能</p>
        <p>。Read : 接收資訊
          <br />。Write : 寫入資訊
          <br />。Reconnect : 嘗試重新連線</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">錯誤名稱(Error Action)</td>
      <td style="text-align:left">當模組運錯錯誤時所要回傳的錯誤名稱</td>
    </tr>
    <tr>
      <td style="text-align:left">資料(Data)</td>
      <td style="text-align:left">接收資料的變數或寫入的資料內容</td>
    </tr>
  </tbody>
</table>![](../../../.gitbook/assets/smacomfunction.jpg)

* 讀取資料 : 當要接收外部設備傳來的資料時，直接在Data欄位輸入用來接收資料的變數名稱，變數的資料型態必須為字串變數。
* 寫入資料 : 當要寫入資料到外部設備時，參考下面的範例於Data欄位輸入適當的格式。
  * 直接寫入 : "寫入的文字內容"
  * 透過變數 : Local.變數名稱 \(必須是字串變數\)

### \# SmaMOTION

呼叫SmaMOTION模組進行運動控制。

### \# SmaROBOT

呼叫SmaROBOT模組執行手臂控制。

### \# SmaVISION

呼叫SmaVISION模組執行影像處理。

<table>
  <thead>
    <tr>
      <th style="text-align:left">設定參數</th>
      <th style="text-align:left">參數說明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">模組(Module)</td>
      <td style="text-align:left">選擇要執行的模組專案</td>
    </tr>
    <tr>
      <td style="text-align:left">方法(Method)</td>
      <td style="text-align:left">
        <p>模組要執行的功能</p>
        <p>。Start : 開始執行影像處理
          <br />。Result : 讀取影像處理完成後的結果
          <br />。Save : 將結果影像進行存檔</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">錯誤名稱(Error Action)</td>
      <td style="text-align:left">當模組運錯錯誤時所要回傳的錯誤名稱</td>
    </tr>
    <tr>
      <td style="text-align:left">更新結果(Update Result)</td>
      <td style="text-align:left">指派變數去接收影像處理後的結果，
        <br />或是輸入影像的儲存路徑</td>
    </tr>
  </tbody>
</table>![](../../../.gitbook/assets/smavisionfunction.jpg)

### \# SmaDIO

呼叫SmaDIO模組執行擴充IO的功能。

<table>
  <thead>
    <tr>
      <th style="text-align:left">設定參數</th>
      <th style="text-align:left">參數說明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">模組(Module)</td>
      <td style="text-align:left">選擇要執行的模組專案</td>
    </tr>
    <tr>
      <td style="text-align:left">方法(Method)</td>
      <td style="text-align:left">
        <p>模組要執行的功能</p>
        <p>。WriteDO : 編輯輸出腳位的狀態
          <br />。ReadDI : 讀取輸入腳位的狀態
          <br />。WaitUntil : 等待輸入腳位到達特定狀態</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">錯誤名稱(Error Action)</td>
      <td style="text-align:left">當模組運錯錯誤時所要回傳的錯誤名稱</td>
    </tr>
    <tr>
      <td style="text-align:left">逾時(Timeout)</td>
      <td style="text-align:left">設定等待時間，超過時間會進入錯誤處
        <br />理程序</td>
    </tr>
    <tr>
      <td style="text-align:left">命令(Command)</td>
      <td style="text-align:left">SmaDIO模組執行的動作，直接點擊右側
        <br />的編輯標籤進行設定</td>
    </tr>
  </tbody>
</table>![](../../../.gitbook/assets/smadiofunction.jpg)

