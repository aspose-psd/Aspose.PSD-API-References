---
title: Enum ResizeType
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.ResizeType 枚举. 指定调整大小类型
type: docs
weight: 5370
url: /zh/net/aspose.psd/resizetype/
---
## ResizeType enumeration

指定调整大小类型。

```csharp
public enum ResizeType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 在调整大小操作期间不保留像素。 |
| LeftTopToLeftTop | `1` | 新图像的左上点将与原始图像的左上点重合。如果需要，将进行裁剪。 |
| RightTopToRightTop | `2` | 新图像的右上点将与原始图像的右上点重合。如果需要，将进行裁剪。 |
| RightBottomToRightBottom | `3` | 新图像的右下点将与原始图像的右下点重合。如果需要，将进行裁剪。 |
| LeftBottomToLeftBottom | `4` | 新图像的左下点将与原始图像的左下点重合。如果需要，将进行裁剪。 |
| CenterToCenter | `5` | 新图像的中心将与原始图像的中心重合。如果需要，将进行裁剪。 |
| LanczosResample | `6` | 使用 a=3. 的 lanczos 算法重新采样 |
| NearestNeighbourResample | `7` | 使用最近邻算法重新采样。 |
| AdaptiveResample | `8` | 使用基于加权和混合有理函数和 lanczos3 插值算法的自适应算法重新采样。 |
| BilinearResample | `9` | 使用双线性插值重新采样。允许图像预过滤以在需要时在重新采样之前去除噪声 |
| HighQualityResample | `10` | 高质量重采样 |
| CatmullRom | `11` | Catmull-Rom 三次插值法。 |
| CubicConvolution | `12` | 三次卷积插值法 |
| CubicBSpline | `13` | CubicBSpline三次插值法 |
| Mitchell | `14` | 米切尔三次插值法 |
| SinC | `15` | Sinc(Lanczos3)三次插值法 |
| Bell | `16` | 贝尔插值法 |

### 例子

以下代码演示了如何使用新的 SinC 调整大小类型调整图像大小。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

以下代码演示了如何使用新的 Bell 调整类型调整图像大小。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

以下代码演示了如何使用新的 Mitchell 调整大小类型调整图像大小。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

以下代码演示了如何使用新的 CatmullRom 调整类型调整图像大小。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

以下代码演示了如何使用新的 CubicBSpline 调整类型调整图像大小。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

以下代码演示了如何使用新的 CubicConvolution 调整大小类型调整图像大小。

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### 也可以看看

* 命名空间 [Aspose.PSD](../../aspose.psd/)
* 部件 [Aspose.PSD](../../)


