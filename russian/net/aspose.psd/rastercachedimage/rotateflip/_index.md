---
title: RasterCachedImage.RotateFlip
second_title: Справочник по Aspose.PSD для .NET API
description: RasterCachedImage метод. Вращает переворачивает или поворачивает и переворачивает изображение.
type: docs
weight: 140
url: /ru/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Вращает, переворачивает или поворачивает и переворачивает изображение.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Тип вращения флип. |

### Примеры

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

### Смотрите также

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* пространство имен [Aspose.PSD](../../rastercachedimage/)
* сборка [Aspose.PSD](../../../)


