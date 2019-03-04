# TCPclient與設定參數

* TCPClient功能位於SmaCOM上方處：

![SmaCOM TCPClient&#x8A2D;&#x5B9A;&#x4F4D;&#x7F6E;](../../.gitbook/assets/tcpclient-jie-mian.JPG)

* 點擊"Settings"後會出現以下視窗：

 ​   

![SmaCOM TCP Client Setup&#x4ECB;&#x9762;](../../.gitbook/assets/tcpclientsetup-jie-mian.JPG)

1. IP/Port設定欄位，預設為"127.0.0.1/6024"。
2. 接收與查看資料格式設定，預設為Standard、Buffered、CRLF與Immediate模式。

* Standard\(預設\)：等待讀取所指定的bytes到達或是Client讀取時間逾時為止，並回傳目前接收到的byte數量。若byte數量少於Client需求的數量，會回傳部分的byte並報告超時錯誤訊息。
* Buffered：等待讀取指定的bytes到達或是Client讀取時間逾時為止。若byte數量少於Client需求的數量，不會回傳任何的byte數量並報告超時錯誤訊息。
* CRLF：等待讀取所指定的bytes到達或是讀取到CR\(Carriage-Return\)與LF\(Line Feed\)換行符號與Client讀取時間逾時為止。若在字串中接收到CRLF符號，會回傳接收到的byte包含CR與LF符號。

    3. 連線逾時設定與資料 傳送/接收 讀/寫 逾時時間設定。

