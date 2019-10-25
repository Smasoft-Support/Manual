# 運行過程按下急停

* 若在移動過程中按下急停或是Point中的offset功能，則當下位置不會出現在點位表中。自動路徑規劃會找尋上一次移動路徑的歷史路徑，並從中找尋最近與Tool相同的點位來做路徑規劃。

![&#x8DEF;&#x5F91;&#x898F;&#x5283;&#x904B;&#x884C;&#x904E;&#x7A0B;&#x6025;&#x505C;](../../../.gitbook/assets/lu-jing-gui-hua-ji-ting-1.jpg)

* 若在移動過程中按下急停或是Point中的offset功能，則當下位置不會出現在點位表中。自動路徑規劃會找尋上一次移動路徑的歷史路徑，並從中找尋最近與Tool相同的點位來做路徑規劃。

![&#x9078;&#x64C7;D&#x9EDE;&#x4F4D;&#x7684;&#x81EA;&#x52D5;&#x8DEF;&#x5F91;&#x898F;&#x5283;](../../../.gitbook/assets/lu-jing-gui-hua-ji-ting-2-1.jpg)

* 解除急停後，使用者點選A點位，找尋歷史點位中的\(B-&gt;C-&gt;D\)中，選離目前最近的C點，則自動路徑規劃為：當前位置-&gt;C-&gt;B-&gt;A。

![&#x9078;&#x64C7;A&#x9EDE;&#x4F4D;&#x7684;&#x81EA;&#x52D5;&#x8DEF;&#x5F91;&#x898F;&#x5283;](../../../.gitbook/assets/lu-jing-gui-hua-ji-ting-3-1.jpg)

