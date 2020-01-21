# FAQ

## 為什麼 Sequencer 中， SmaROBOT、SmaMOTION 要將 &lt;CheckDone&gt; 獨立做成一個步驟？

#### 保持流程編寫的彈性

當流程執行到 &lt;CheckDone&gt; 步驟時，會等待上個手臂或馬達的運行指令完成，再繼續下一個步驟。將 &lt;CheckDone&gt; 獨立出來，是為了保持流程編寫的彈性，讓我們在下達運行指令後，等待手臂、馬達運行的同時，安排其他步驟在 &lt;CheckDone&gt; 之前，提高運作效率。

![CheckDone](.gitbook/assets/checkdone_marked.PNG)

## SmaROBOT 可以一次操作兩隻手臂嗎?

#### 同廠牌可以。

目前的 SmaROBOT 中，使用者可以建立多個手臂模組，操控多隻同廠牌手臂。



