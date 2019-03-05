# Sequencer調用

在流程中調用SmaROBOT視覺引導。

![SmaRobot&#x8996;&#x89BA;&#x5F15;&#x5C0E;&#x6D41;&#x7A0B;](../../.gitbook/assets/sequencer-diao-yong-1.jpg)

* 首先在變數表各自建立Target與Offset變數：

![&#x8B8A;&#x6578;&#x8868;&#x5EFA;&#x7ACB;&#x8B8A;&#x6578;](../../.gitbook/assets/sequencer-diao-yong-2.jpg)

1. 在變數表中須建立兩個陣列：

 ​        1D size=3，儲存視覺結果\(X,Y,R\)。

 ​        1D size=6，儲存手臂補償結果\(X,Y,Z,U,V,W\)。

