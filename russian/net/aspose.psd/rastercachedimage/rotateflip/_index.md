---
title: "RasterCachedImage.RotateFlip"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод RasterCachedImage. Поворачивает, отражает или поворачивает и отражает изображение"
type: docs
weight: 140
url: /ru/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

Поворачивает, отражает или одновременно поворачивает и отражает изображение.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Тип поворота/отражения. |

## Примеры

Следующий код показывает, как повернуть изображение.

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

### См. также

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


