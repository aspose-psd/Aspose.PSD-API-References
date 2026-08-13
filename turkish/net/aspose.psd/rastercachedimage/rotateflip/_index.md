---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.PSD for .NET API Referansı"
description: "RasterCachedImage yöntemi. Görüntüyü döndürür, çevirir veya döndürüp çevirir."
type: docs
weight: 140
url: /tr/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Döndürme/çevirme türü. |

## Örnekler

Aşağıdaki kod, görüntünün nasıl döndürüleceğini gösterir.

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

### Ayrıca Bakınız

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


