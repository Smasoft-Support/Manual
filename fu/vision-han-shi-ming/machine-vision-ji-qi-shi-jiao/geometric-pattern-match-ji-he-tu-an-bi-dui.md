# Geometric Pattern Match 幾何圖案比對

### 適用影像格式

| 彩色 | 灰階 | 二值 |
| :---: | :---: | :---: |
| X | O | X |

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
      <td style="text-align:center">X</td>
      <td style="text-align:center">O</td>
      <td style="text-align:center">O</td>
      <td style="text-align:center">X</td>
    </tr>
  </tbody>
</table>* 依照建立的模板輪廓，在框選的影像區域中搜尋輪廓相近的目標

### 建立樣本 \(Template\)

1. 新增 / 載入 / 編輯
2. 框選樣本圖案
3. 設定座標中心點

![](../../../.gitbook/assets/tu-pian-22.png)

## 設定搜尋參數

* Rotation: 搜尋旋轉
* Scale: 搜尋縮放
* Occlusion: 封閉輪廓

![](../../../.gitbook/assets/tu-pian-21.png)

