---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD för .NET API-referens
description: RasterCachedImage metod. Roterar vänder eller roterar och vänder bilden.
type: docs
weight: 140
url: /sv/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Roterar, vänder eller roterar och vänder bilden.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Den roterande fliptypen. |

### Exempel

Följande kod visar hur du roterar bilden.

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

### Se även

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namnutrymme [Aspose.PSD](../../rastercachedimage/)
* hopsättning [Aspose.PSD](../../../)


