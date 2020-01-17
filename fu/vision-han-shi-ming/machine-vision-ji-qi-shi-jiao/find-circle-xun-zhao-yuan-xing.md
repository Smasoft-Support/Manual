# Find Circle 尋找圓形

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
      <td style="text-align:center">X</td>
      <td style="text-align:center">X</td>
      <td style="text-align:center">O</td>
    </tr>
  </tbody>
</table>* 在框選的影像區域中，搜尋圓形輪廓的目標，並輸出該圓形的圓心像素座標、半徑與真圓度

![](../../../.gitbook/assets/tu-pian-17.jpg)

