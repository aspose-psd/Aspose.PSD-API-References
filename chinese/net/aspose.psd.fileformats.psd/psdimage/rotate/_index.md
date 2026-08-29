---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 方法。 将图像围绕中心旋转"
type: docs
weight: 670
url: /zh/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

围绕中心旋转图像。

```csharp
public override void Rotate(float angle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 单精度 | 旋转角度（单位：度）。正值将顺时针旋转。 |

## 示例

以下代码演示了按特定角度值旋转图像的功能。

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// 整个图像旋转
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// 图层旋转
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### 另请参阅

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

围绕中心旋转图像。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 单精度 | 旋转角度（单位：度）。正值将顺时针旋转。 |
| resizeProportionally | 布尔 | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则，尺寸保持不变，仅内部图像内容被旋转。 |
| backgroundColor | 颜色 | 背景颜色。 |

### 另请参阅

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


