---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD for .NET API 参考
description: RasterCachedImage 方法. 旋转翻转或旋转并翻转图像
type: docs
weight: 140
url: /zh/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

旋转、翻转或旋转并翻转图像。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

### 例子

以下代码显示了如何旋转图像。

```csharp
[C#]

var sourceFile = "1.psd";
var pngPath = "RotateFlipTest2617.png";
var psdPath = "RotateFlipTest2617.psd";
var flipType = RotateFlipType.Rotate270FlipXY;
using (var im = (PsdImage)(Image.Load(sourceFile)))
{
    im.RotateFlip(flipType);
    im.Save(pngPath, new PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
    im.Save(psdPath);
}
```

### 也可以看看

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* 命名空间 [Aspose.PSD](../../rastercachedimage/)
* 部件 [Aspose.PSD](../../../)


