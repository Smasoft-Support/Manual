# Edge Detection 邊緣偵測

### 適用影像格式

| 彩色 | 灰階 | 二值 |
| :---: | :---: | :---: |
| O | O | X |

### ROI 框選方式

<table>
  <thead>
    <tr>
      <th style="text-align:center">Line
        <br />&#x76F4;&#x7DDA;</th>
      <th style="text-align:center">Rectangle
        <br />&#x65B9;&#x5F62;</th>
      <th style="text-align:center">
        <p>Rotated Rectangle</p>
        <p>&#x53EF;&#x65CB;&#x8F49;&#x65B9;&#x5F62;</p>
      </th>
      <th style="text-align:center">
        <p>Annulus</p>
        <p>&#x540C;&#x5FC3;&#x5713;</p>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">O</td>
      <td style="text-align:center">X</td>
      <td style="text-align:center">X</td>
      <td style="text-align:center">X</td>
    </tr>
  </tbody>
</table>### 基本參數調整

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

