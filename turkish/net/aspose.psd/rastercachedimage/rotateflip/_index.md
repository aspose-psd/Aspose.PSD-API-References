---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD for .NET API Referansı
description: RasterCachedImage yöntem. Görüntüyü döndürür çevirir veya döndürür ve çevirir.
type: docs
weight: 140
url: /tr/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Görüntüyü döndürür, çevirir veya döndürür ve çevirir.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Döndürme çevirme türü. |

### Örnekler

Aşağıdaki kod görüntünün nasıl döndürüleceğini gösterir.

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

### Ayrıca bakınız

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* ad alanı [Aspose.PSD](../../rastercachedimage/)
* toplantı [Aspose.PSD](../../../)


