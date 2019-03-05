# 手臂與相機關係建立

建立相機與手臂之間的座標轉換關係：\(RobotCam & DownCam\)

* 前置準備：取得欲校正相機的解析度\(可從NI Max查看\)
* RobotCam與DownCam校正須確定手臂拍照位於U軸可以自由旋轉180度與-180度。

![&#x5EFA;&#x7ACB;&#x624B;&#x81C2;&#x6A21;&#x7D44;](../../../.gitbook/assets/jian-li-shou-bi-mo-zu.jpg)

1. 右鍵點擊SmaRobot，選擇Create New。
2. 為本手臂模組命名。

* 設定手臂連線模組：

![&#x624B;&#x81C2;&#x9023;&#x7DDA;&#x6A21;&#x7D44;](../../../.gitbook/assets/she-ding-shou-bi-lian-xian-mo-zu.jpg)

1. 點擊Setting設定手臂連線設定。
2. 點擊Connect連線。
3. 移動手臂至拍照位置，並記錄手臂的點位\(此點位的Z軸高度即為之後導引的取像高度\)。
4. 若校正為DownCam，拍照點的U軸角度必須為0。

