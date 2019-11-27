# TCPClient 與設定參數

* 使用 TCPClient 連線方式時，點擊「Settings」可調整以下設定：

![SmaCOM TCP Client Setup&#x4ECB;&#x9762;](../../../.gitbook/assets/tcpclientsetup-jie-mian.JPG)

* IP/Port 
  * 填入 TCP Server 的 IP位址與 Port 號
* Mode
  * 接收與傳送資料結尾設定。
    * Standard
      * 等待讀取所指定的 byte 數達到要求，或讀取時間逾時為止，並回傳截止前接收到的 bytes。若 byte 數量少於要求的數量，則會回傳目前有的 bytes，並產生超時錯誤訊息。
    * Buffered
      * 等待讀取所指定的 byte 數達到要求，或讀取時間逾時為止。若 byte 數量少於要求的數量，則不會回傳任何 bytes ，並產生超時錯誤訊息。
    * CRLF

      * 等待讀取所指定的 byte 數達到要求，或是讀取到 CR（Carriage-Return）與 LF

      （Line Feed）換行符號，或讀取時間逾時為止。若在字串中接收到 CRLF 符號，則直接回傳接收到的bytes，包含 CR 與 LF 符號。

    * Immediate
      * 等待讀取所指定的任何 bytes 到達，直到沒有資料而讀取時間逾時為止，並回傳接收到的 bytes。若期間沒有收到 byte，則回傳超時錯誤訊息。
* Open Timeout
  * 與 Server 連線逾時設定
* R/W Timeout
  * 資料傳送/接收（讀/寫）逾時設定。

