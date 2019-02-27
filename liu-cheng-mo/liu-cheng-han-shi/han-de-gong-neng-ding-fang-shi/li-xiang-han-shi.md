# 錯誤處理相關函式

## \# 錯誤\(Error\)

當流程執行到此步驟時直接觸發錯誤程序，暫停所有線程並且進入ErrorHandle，錯誤名稱會記錄到Error.Action的系統變數，而錯誤訊息則是記錄到Error.Msg的系統店數當中，兩者一併傳到ErrorHandle裡面進行錯誤處理。

| 設定參數 | 參數說明 |
| :--- | :--- |
| 名稱\(Name\) | 步驟名稱，可自訂 |
| 錯誤名稱\(Error Action\) | 錯誤的名稱，可自訂 |
| 錯誤訊息\(Error Message\) | 錯誤訊息，用於告知操作員錯誤原因 |

![](../../../.gitbook/assets/errorfunction.jpg)

## \# 行為\(Action\) \[限ErrorHandle使用\]

在ErrorHandle中完成錯誤處理程序後，需指定流程的下一步該如何繼續運行，其中Goto的使用方式請參考\[[流程中的錯誤處理\(ErrorHandle\)](../../liu-cheng-zhong-de-li-errorhandle.md)\]。

<table>
  <thead>
    <tr>
      <th style="text-align:left">設定參數</th>
      <th style="text-align:left">參數說明</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">名稱(Name)</td>
      <td style="text-align:left">步驟名稱，可自訂</td>
    </tr>
    <tr>
      <td style="text-align:left">行為(Action)</td>
      <td style="text-align:left">
        <p>下一步的流程動作</p>
        <p>。Continue : 從暫停的狀態繼續運行</p>
        <p>。Pause : 暫停線程</p>
        <p>。Goto : 指定繼續運行的下一個步驟</p>
        <p>。Cleanup : 進入Cleanup流程</p>
        <p>。Abort : 終止所有線程</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">線程(Sequence)</td>
      <td style="text-align:left">指定要Goto的線程</td>
    </tr>
    <tr>
      <td style="text-align:left">目錄(Index)</td>
      <td style="text-align:left">指定要Goto的步驟編號</td>
    </tr>
  </tbody>
</table>