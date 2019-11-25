# 運行中斷與賦歸

#### 若在移動過程中按下急停，或是【SmaROBOT】步驟的 &lt; Point &gt; 指令有帶入 Offset，則手臂可能會存在於路徑點以外的位置。自動路徑規劃會找尋上一次移動的歷史路徑，並從中挑選最近的路徑點，進行移動路徑規劃。

![&#x8DEF;&#x5F91;&#x898F;&#x5283;&#x904B;&#x884C;&#x904E;&#x7A0B;&#x6025;&#x505C;](../../../.gitbook/assets/lu-jing-gui-hua-ji-ting-1.jpg)

### 停止後重啟

* 若目標為 D 點，手臂會找到最近的 C 點，並以 C 點進行路徑規畫至 D 點。

![&#x9078;&#x64C7;D&#x9EDE;&#x4F4D;&#x7684;&#x81EA;&#x52D5;&#x8DEF;&#x5F91;&#x898F;&#x5283;](../../../.gitbook/assets/lu-jing-gui-hua-ji-ting-2-1.jpg)

* 若目標為 A 點，手臂亦會找到最近的 C 點，再以 C 點進行路徑規畫運行 -&gt;C-&gt;B-&gt;A

![&#x9078;&#x64C7;A&#x9EDE;&#x4F4D;&#x7684;&#x81EA;&#x52D5;&#x8DEF;&#x5F91;&#x898F;&#x5283;](../../../.gitbook/assets/lu-jing-gui-hua-ji-ting-3-1.jpg)

