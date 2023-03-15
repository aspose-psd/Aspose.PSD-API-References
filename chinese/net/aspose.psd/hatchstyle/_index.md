---
title: Enum HatchStyle
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.HatchStyle 枚举. 指定可用于的不同模式HatchBrush对象.
type: docs
weight: 4340
url: /zh/net/aspose.psd/hatchstyle/
---
## HatchStyle enumeration

指定可用于的不同模式[`HatchBrush`](../../aspose.psd.brushes/hatchbrush/)对象.

```csharp
public enum HatchStyle
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Horizontal | `0` | 水平线图案。 |
| Min | `0` | 指定填充样式水平。 |
| Vertical | `1` | 垂直线的图案。 |
| ForwardDiagonal | `2` | 从左上角到右下角的对角线图案。 |
| BackwardDiagonal | `3` | 从右上角到左下角的对角线图案。 |
| Cross | `4` | 指定交叉的水平线和垂直线。 |
| LargeGrid | `4` | 指定剖面线样式 Cross. |
| Max | `4` | 指定填充样式 SolidDiamond. |
| DiagonalCross | `5` | 交叉对角线的图案。 |
| Percent05 | `6` | 指定 5% 的影线。前景色与背景色的比例为5:95. |
| Percent10 | `7` | 指定 10% 的影线。前景色与背景色的比例为10:90. |
| Percent20 | `8` | 指定 20% 的影线。前景色与背景色的比例为20:80. |
| Percent25 | `9` | 指定 25% 的影线。前景色与背景色的比例为25:75. |
| Percent30 | `10` | 指定 30% 的影线。前景色与背景色的比例为30:70. |
| Percent40 | `11` | 指定 40% 的填充。前景色与背景色的比例为40:60. |
| Percent50 | `12` | 指定 50% 填充。前景色与背景色的比例为50:50. |
| Percent60 | `13` | 指定 60% 的填充。前景色与背景色的比例为60:40. |
| Percent70 | `14` | 指定 70% 填充。前景色与背景色的比例为70:30. |
| Percent75 | `15` | 指定 75% 的剖面线。前景色与背景色的比例为75:25. |
| Percent80 | `16` | 指定 80% 的填充。前景色与背景色的比例为80:100. |
| Percent90 | `17` | 指定 90% 填充。前景色与背景色的比例为90:10. |
| LightDownwardDiagonal | `18` | 指定从顶部点到底部点向右倾斜的对角线，并且间距比 ForwardDiagonal 更近 50%，但不抗锯齿。 |
| LightUpwardDiagonal | `19` | 指定从顶部点到底部点向左倾斜并且间距比 BackwardDiagonal 更近 50% 的对角线，但它们没有抗锯齿。 |
| DarkDownwardDiagonal | `20` | 指定从顶部点到底部点向右倾斜的对角线，间距比 ForwardDiagonal 的宽度小 50%，并且是 ForwardDiagonal 的两倍。此填充图案未抗锯齿。 |
| DarkUpwardDiagonal | `21` | 指定从顶部点到底部点向左倾斜的对角线，间距比 BackwardDiagonal 更近 50%，并且是其宽度的两倍，但这些线没有抗锯齿。 |
| WideDownwardDiagonal | `22` | 指定从顶部点到底部点向右倾斜的对角线，具有与填充样式 ForwardDiagonal 相同的间距，并且是其宽度的三倍，但不抗锯齿。 |
| WideUpwardDiagonal | `23` | 指定从顶部点到底部点向左倾斜的对角线，具有与填充样式 BackwardDiagonal 相同的间距，并且是其宽度的三倍，但不抗锯齿。 |
| LightVertical | `24` | 指定垂直线的间距比 Vertical. 小 50% |
| LightHorizontal | `25` | 指定比 Horizontal. 间距小 50% 的水平线 |
| NarrowVertical | `26` | 指定垂直线的间距比填充样式 Vertical 的间距小 75%（或比 LightVertical 的间距小 25%）。 |
| NarrowHorizontal | `27` | 指定比填充样式水平间距小 75%（或比 LightHorizontal 间距小 25%）的水平线。 |
| DarkVertical | `28` | 指定垂直线的间距比 Vertical 小 50%，并且是其宽度的两倍。 |
| DarkHorizontal | `29` | 指定水平线的间距比 Horizontal 小 50%，宽度是 Horizontal. 的两倍 |
| DashedDownwardDiagonal | `30` | 指定从顶部点到底部点向右倾斜的虚线对角线。 |
| DashedUpwardDiagonal | `31` | 指定虚线对角线，从顶部点到底部点向左倾斜。 |
| DashedHorizontal | `32` | 指定水平虚线。 |
| DashedVertical | `33` | 指定垂直虚线。 |
| SmallConfetti | `34` | 指定具有五彩纸屑外观的图案填充。 |
| LargeConfetti | `35` | 指定具有五彩纸屑外观的图案填充，并且由比 SmallConfetti 更大的块组成。 |
| ZigZag | `36` | 指定由锯齿形组成的水平线。 |
| Wave | `37` | 指定由波浪号组成的水平线。 |
| DiagonalBrick | `38` | 指定具有分层砖外观的填充，从顶部点到底部点向左倾斜。 |
| HorizontalBrick | `39` | 指定具有水平分层砖块外观的舱口。 |
| Weave | `40` | 指定具有编织材料外观的舱口。 |
| Plaid | `41` | 指定具有格子材料外观的影线。 |
| Divot | `42` | 指定具有草皮外观的图案填充。 |
| DottedGrid | `43` | 指定水平和垂直线，每条线都由点组成，交叉。 |
| DottedDiamond | `44` | 指定向前对角线和向后对角线，每条线都由点组成，交叉。 |
| Shingle | `45` | 指定具有从顶部点到底部点向右倾斜的对角线分层带状疱疹外观的舱口。 |
| Trellis | `46` | 指定具有网格外观的图案填充。 |
| Sphere | `47` | 指定一个具有彼此相邻放置的球体外观的舱口。 |
| SmallGrid | `48` | 指定交叉的水平线和垂直线，它们之间的间距比剖面线样式 Cross. 的间距小 50% |
| SmallCheckerBoard | `49` | 指定具有棋盘外观的舱口。 |
| LargeCheckerBoard | `50` | 指定具有棋盘外观的图案填充，其正方形的大小是 SmallCheckerBoard. 的两倍 |
| OutlinedDiamond | `51` | 指定交叉但不抗锯齿的前向对角线和后向对角线。 |
| SolidDiamond | `52` | 指定具有对角放置的棋盘外观的填充。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


