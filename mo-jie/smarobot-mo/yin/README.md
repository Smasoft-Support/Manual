# 視覺導引

#### 視覺導引的功能，可讓手臂配合相機取像與定位，進行更精準的 pick & place 的動作。依照應用需求，可分成RobotCam（相機掛在手臂上移動），與 DownCam（固定相機由下往上拍攝）。

### 若要建立視覺導引功能，請依照以下順序進行：

1. 建立手臂模組，新增拍照位置，並建立[視覺校正用模組](xiao-zheng-an-ding.md)
2. 使用**手臂模組的 Vision Guide Setup** 功能設定視覺導引，建立[手臂與相機的座標關係模型](pin-an-ding.md)
3. 建立用來進行**實際視覺應用**的[視覺模組](pin-an-ding.md)
4. 選擇座標關係[設定嚮導](ding/)（RobotCam / DownCam）
5. 在 **Sequencer** 中[編寫流程](sequencer-yong/)



