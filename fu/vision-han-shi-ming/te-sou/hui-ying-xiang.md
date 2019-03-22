# 灰階影像

## 灰階影像

### Edge Detection: 邊緣偵測

### 基本參數調整

* Process: 搜尋目標種類
  * Get First Edge: 第一個
  * Get First Edge + Last Edge: 第一個與最後一個
  * Get All Edges: 所有邊
  * Get Best Edges: 強度最大者
* Edge Polarity: 邊緣類型
  * Rising Edges: 由暗到亮者
  * Falling Edges: 由亮到暗者
  * All Edges: 所有邊
* Min Edge Strength: 最小強度門檻。
  * 隨著數值增加，僅會搜尋達門檻強度之邊
* Expected Number 預期數量
  * 達預期數量以上會輸出 Pass，反之則 NG

### 進階參數調整

* Interpolation Type: 演算方式
* Kernel Size: 搜尋之核心大小 \(預設為 3\*3\)
* Width: 搜尋間隔

![](../../../.gitbook/assets/tu-pian-16.jpg)

### ROI 工具:

| Line | Rectangle | Rotated Rectangle | Annulus |
| :---: | :---: | :---: | :---: |
| 單一 | - | - | - |

<<<<<<< HEAD
### Find Straight Line 找直線
=======
## Find Straight Line 找直線
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

* 搜尋框選的影像區域中的直線， 並回傳該直線起始點與終點的像素座標值

![](../../../.gitbook/assets/tu-pian-24.jpg)

<<<<<<< HEAD
&lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

## Find Circle: 找圓

#### ROI 工具:
=======
### ROI 工具:
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

| Line | Rectangle | Rotated Rectangle | Annulus |
| :---: | :---: | :---: | :---: |
| - | 單一 | - | - |

<<<<<<< HEAD
### Find Circle: 找圓

> > > > > > > SmaVISION
=======
## Find Circle: 找圓
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

* 在框選的影像區域中，搜尋圓形輪廓的目標，並輸出該圓形的圓心像素座標、半徑與真圓度

![](../../../.gitbook/assets/tu-pian-17.jpg)

### ROI 工具:

| Line | Rectangle | Rotated Rectangle | Annulus |
| :---: | :---: | :---: | :---: |
| - | - | - | 單一 |

<<<<<<< HEAD
### Shape Detection: 形狀偵測
=======
## Shape Detection: 形狀偵測
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

* 搜尋影像中的基本幾何圖案

![](../../../.gitbook/assets/tu-pian-18.png)

### ROI 工具:

| Line | Rectangle | Rotated Rectangle | Annulus |
| :---: | :---: | :---: | :---: |
| - | - | - | - |

<<<<<<< HEAD
### Pattern Match: 圖像比對

#### 建立樣本\( Template \)
=======
## Pattern Match: 圖像比對

### 建立樣本\( Template \)
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

1. 新增 / 載入 / 編輯
2. 框選樣本圖案
3. 設定座標中心點

![](../../../.gitbook/assets/tu-pian-20.png)

### 設定搜尋參數

* Algorithm: 演算法\(快速→嚴謹\)
  * 通常使用 Low Discrepancy Sampling 即可，偶會使用 Grayscale Value Pyramid
* Score: 分數門檻 
  * 僅顯示達到此門檻之結果
* Number to Find: 搜尋數量
  * 每個 ROI 中，要搜尋多少圖案。
* Search for Rotation: 搜尋旋轉圖案 
* Angle: 欲搜尋圖案之旋轉角度範圍 \(+/-\) 
* Mirror Angle: 鏡像角度

![](../../../.gitbook/assets/tu-pian-19.png)

### ROI 工具:

| Line | Rectangle | Rotated Rectangle | Annulus |
| :---: | :---: | :---: | :---: |
| - | 單一 / 多個 | 單一 / 多個 | - |

<<<<<<< HEAD
### Geometric Pattern Match: 幾何圖像比對
=======
## Geometric Pattern Match: 幾何圖像比對
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

* 依照建立的模板輪廓，在框選的影像區域中搜尋輪廓相近的目標

### 建立樣本 \(Template\)

1. 新增 / 載入 / 編輯
2. 框選樣本圖案
3. 設定座標中心點

![](../../../.gitbook/assets/tu-pian-22.png)

<<<<<<< HEAD
## &lt;&lt;&lt;&lt;&lt;&lt;&lt; HEAD

#### 設定搜尋參數
=======
### 設定搜尋參數
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75

* Rotation: 搜尋旋轉
* Scale: 搜尋縮放
* Occlusion: 封閉輪廓

![](../../../.gitbook/assets/tu-pian-21.png)

### ROI 工具:

| Line | Rectangle | Rotated Rectangle | Annulus |
| :---: | :---: | :---: | :---: |
| - | 單一 | - | - |

<<<<<<< HEAD
> > > > > > > SmaVISION

=======
>>>>>>> 1c9e3559cb27f2f92443627fc7d98f3e59876b75
