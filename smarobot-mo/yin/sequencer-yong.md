# Sequencer調用

在流程中調用SmaROBOT視覺引導。

![SmaRobot&#x8996;&#x89BA;&#x5F15;&#x5C0E;&#x6D41;&#x7A0B;](../../.gitbook/assets/sequencer-diao-yong-1.jpg)

* 首先在變數表各自建立Target與Offset變數：

![&#x8B8A;&#x6578;&#x8868;&#x5EFA;&#x7ACB;&#x8B8A;&#x6578;](../../.gitbook/assets/sequencer-diao-yong-2.jpg)

1. 在變數表中須建立兩個陣列：

   ​ 1D size=3，儲存視覺結果\(X,Y,R\)。

   ​ 1D size=6，儲存手臂補償結果\(X,Y,Z,U,V,W\)。

2. 調用Vision Guide步驟：

![&#x8A2D;&#x5B9A;Vision Guide &#x6B65;&#x9A5F;](../../.gitbook/assets/sequencer-diao-yong-3.jpg)

1. 流程編輯雙擊SmaRobot。
2. 在Method選項點選VisionGuide。
3. 點選鉛筆按鈕。
4. GuideMove是根據視覺結果，並依據使用者選擇的校正去計算手臂需要補償的距離。

![Guide Move Setup&#x8AAA;&#x660E;](../../.gitbook/assets/sequencer-diao-yong-4.jpg)

1. 選擇先前的製作的校正。
2. 填入在變數表建立的視覺結果陣列名稱。
3. 填入在變數表建立的手臂補償結果陣列名稱。
4. 調用Point步驟：

![&#x8A2D;&#x5B9A;Point&#x6B65;&#x9A5F;](../../.gitbook/assets/sequencer-diao-yong-5.jpg)

1. 流程編輯雙擊SmaRobot。
2. 在Method選項點選Points。
3. 點選鉛筆按鈕。
4. Point Setup說明：在Point指定要移動的點，並補償Vision Guide步驟所算出的補償值。

![Point Setup&#x8AAA;&#x660E;](../../.gitbook/assets/sequencer-diao-yong-6.jpg)

1. 選擇目標點：校正類型為TopCam、RobotCam，此點即為拍照點位。校正類型為DownCam，此點為放置產品的位置點位。
2. 填入在變數表建立的手臂補償陣列。

