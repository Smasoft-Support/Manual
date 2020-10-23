# Color Pattern Match 彩色圖案比對

### 適用影像格式

| 彩色 | 灰階 | 二值 |
| :---: | :---: | :---: |
| O | X | X |

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
      <td style="text-align:center">O (Multi)</td>
      <td style="text-align:center">X</td>
      <td style="text-align:center">X</td>
    </tr>
  </tbody>
</table>

* Create Template: 創建比對樣本
* Minimum Score: 分數門檻
* Numbers to Find: ROI內搜尋數量
* Search for Rotation: 搜尋旋轉圖案 
* Angle: 角度範圍 \(+/-\) 
* Mirror Angle: 鏡像角度
* Color Score Weight: 顏色比重
* Color Sensitivity: 顏色解析精細度 
* Search Strategy: 搜尋嚴謹程度

![](../../../.gitbook/assets/tu-pian-9.png)

