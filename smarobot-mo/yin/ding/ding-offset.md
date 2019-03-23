# 設定Offset

設定Offset目的是為了解決RobotCam視覺引導點非抓取點的應用。

**注意 : 先移動手臂到拍照點再執行以下程序。**

### Step 1:

![&#x521D;&#x59CB;&#x5316;&#x8A2D;&#x5B9A;](../../../.gitbook/assets/jian-li-offset1.jpg)

1. 右鍵點擊先前建立的SmaRobot模組，選擇Vision Guide Setup。
2. 從先前建立的RobotCam校正右鍵點擊Set Offset。
3. 從彈出的視窗中填寫名稱與要使用的專案名稱與要使用的Tool。

此處選擇的Tool會影響手臂到視覺引導點的位置。例如，若先前已設定一Tool偏移法蘭面中心X:50, Y:30，則在導引時，是以該Tool點位置到達視覺導引點正上方。選擇Tool0，則是法蘭面中心會到視覺引導點正上方。

若在流程中是要以Tool點導引，則此處需選擇相對應的Tool設定Offset。

### Step 2 :

![&#x8A2D;&#x5B9A;&#x6A19;&#x6E96;&#x503C;\(Golden Sample\)](../../../.gitbook/assets/offset-set-golden.png)

按下Next設定此樣品的位置及角度為標準值，之後的視覺導引便會以新取像到的樣品位置做比較，並引導手臂。

### Step 3：

![&#x5C0E;&#x5F15;&#x624B;&#x81C2;&#x5230;Pattern&#x6B63;&#x4E0A;&#x65B9;](../../../.gitbook/assets/jian-li-offset2.jpg)

相機取像並定位，準備好急停按鈕，確認周遭設備不會有碰撞疑慮後，點擊Next會將法蘭面中心或選用的Tool中心移動到定位Pattern的正上方。

### Step 4：

![&#x64CD;&#x4F5C;&#x624B;&#x81C2;&#x79FB;&#x52D5;&#x81F3;&#x9700;&#x8981;&#x7684;&#x6293;&#x53D6;&#x9EDE;](../../../.gitbook/assets/jian-li-offset3.jpg)

此時法蘭面或是Tool中心應在Pattern的正上方，操作左下方的操作盤，來使Tool移動到需要的抓取點。若移動完畢，請點選Next。

### Step 5：

![Offset&#x8A2D;&#x5B9A;&#x5B8C;&#x6210;](../../../.gitbook/assets/jian-li-offset4.jpg)

Offset設定完成，準備好急停按鈕，確認周遭設備不會有碰撞疑慮後，請點擊Next使手臂回到回到起始位置。

### Step 6：

![&#x96A8;&#x610F;&#x79FB;&#x52D5;&#x6A23;&#x54C1;](../../../.gitbook/assets/jian-li-offset5.jpg)

在相機能拍到的範圍內，將要抓取的元件隨意移動並旋轉，準備好急停按鈕，確認周遭設備不會有碰撞疑慮後，並按下Next來將Tool點移動到抓取點。

### Step 7：

![&#x79FB;&#x52D5;&#x5230;&#x6293;&#x53D6;&#x9EDE;](../../../.gitbook/assets/jian-li-offset6.jpg)

若Offset設定正確無誤，此時Tool需在抓取點位置，接著準備好急停按鈕，確認周遭設備不會有碰撞疑慮後，按下Next回到初始位置。

### Step 8 :

![&#x5EFA;&#x7ACB;Offset&#x5C0E;&#x5F15;&#x7D50;&#x675F;](../../../.gitbook/assets/jian-li-offset7.jpg)

設定Offset導引過程結束。

### Step 9 :

![Manage Calibration&#x65B0;&#x589E;Offset&#x5B8C;&#x6210;](../../../.gitbook/assets/jian-li-offset8.jpg)

若成功建立，Manage Calibration視窗會多一項Offset。

