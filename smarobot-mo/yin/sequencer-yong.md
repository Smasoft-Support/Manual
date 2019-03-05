# Sequencer調用

在流程中調用SmaROBOT視覺引導。

![SmaRobot&#x8996;&#x89BA;&#x5F15;&#x5C0E;&#x6D41;&#x7A0B;](../../.gitbook/assets/sequencer-diao-yong-1.jpg)

* 首先在變數表各自建立Target與Offset變數：

![&#x8B8A;&#x6578;&#x8868;&#x5EFA;&#x7ACB;&#x8B8A;&#x6578;](../../.gitbook/assets/sequencer-diao-yong-2.jpg)

1. 在變數表中須建立兩個陣列：

 ​        1D size=3，儲存視覺結果\(X,Y,R\)。

 ​        1D size=6，儲存手臂補償結果\(X,Y,Z,U,V,W\)。

* 調用Vision Guide步驟：

![Vision Guide &#x6B65;&#x9A5F;](../../.gitbook/assets/sequencer-diao-yong-3.jpg)

1. 流程編輯雙擊SmaRobot。
2. 在Method選項點選VisionGuide。
3. 點選鉛筆按鈕。

* GuideMove是根據視覺結果，並依據使用者選擇的校正去計算手臂需要補償的距離。

![Guide Move Setup&#x8AAA;&#x660E;](../../.gitbook/assets/sequencer-diao-yong-4.jpg)

1. 選擇先前的製作的校正。
2. 填入在變數表建立的視覺結果陣列名稱。
3. 填入在變數表建立的手臂補償結果陣列名稱。

