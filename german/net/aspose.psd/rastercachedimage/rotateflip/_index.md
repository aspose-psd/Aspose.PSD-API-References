---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD für .NET-API-Referenz
description: RasterCachedImage methode. Dreht kippt oder dreht und kippt das Bild.
type: docs
weight: 140
url: /de/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Dreht, kippt oder dreht und kippt das Bild.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Der Rotations-Flip-Typ. |

### Beispiele

Der folgende Code zeigt, wie das Bild gedreht wird.

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

### Siehe auch

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namensraum [Aspose.PSD](../../rastercachedimage/)
* Montage [Aspose.PSD](../../../)


