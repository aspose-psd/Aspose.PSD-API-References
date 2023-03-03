---
title: Enum InterpolationMode
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.InterpolationMode 枚举. 的InterpolationMode枚举指定缩放或旋转图像时使用的算法
type: docs
weight: 5030
url: /zh/net/aspose.psd/interpolationmode/
---
## InterpolationMode enumeration

的`InterpolationMode`枚举指定缩放或旋转图像时使用的算法。

```csharp
public enum InterpolationMode
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Invalid | `-1` | 无效插值模式。 |
| Default | `0` | 指定默认模式。 |
| Low | `1` | 指定低质量插值。 |
| High | `2` | 指定高质量插值。 |
| Bilinear | `3` | 指定双线性插值。不进行预过滤。此模式不适合将图像缩小到其原始大小的 50% 以下。 |
| Bicubic | `4` | 指定双三次插值。不进行预过滤。此模式不适合将图像缩小到其原始大小的 25% 以下。 |
| NearestNeighbor | `5` | 指定最近邻插值。 |
| HighQualityBilinear | `6` | 指定高质量的双线性插值。执行预过滤以确保高质量收缩。 |
| HighQualityBicubic | `7` | 指定高质量的双三次插值。执行预过滤以确保高质量收缩。此模式可生成最高质量的变换图像。 |

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


