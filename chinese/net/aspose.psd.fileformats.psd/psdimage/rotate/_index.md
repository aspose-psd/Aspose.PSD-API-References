---
title: PsdImage.Rotate
second_title: Aspose.PSD for .NET API 参考
description: PsdImage 方法. 围绕中心旋转图像
type: docs
weight: 610
url: /zh/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
## Rotate(float) {#rotate}

围绕中心旋转图像。

```csharp
public override void Rotate(float angle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| angle | Single | 以度为单位的旋转角度。正值将顺时针旋转。 |

### 例子

以下代码演示了按特定角度值旋转图像的能力。

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

//图层旋转
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

### 也可以看看

* class [PsdImage](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 部件 [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

围绕中心旋转图像。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| angle | Single | 以度为单位的旋转角度。正值将顺时针旋转。 |
| resizeProportionally | Boolean | 如果设置为`真的`您将根据旋转的矩形（角点）投影更改图像大小，在其他情况下保持尺寸不变并且仅旋转内部图像内容。 |
| backgroundColor | Color | 背景的颜色。 |

### 也可以看看

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 部件 [Aspose.PSD](../../../)


