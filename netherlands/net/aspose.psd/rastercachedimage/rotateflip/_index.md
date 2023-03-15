---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD voor .NET API-referentie
description: RasterCachedImage methode. Roteert spiegelt of roteert en spiegelt de afbeelding.
type: docs
weight: 140
url: /nl/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Roteert, spiegelt of roteert en spiegelt de afbeelding.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Het roteer flip-type. |

### Voorbeelden

De volgende code laat zien hoe u de afbeelding kunt roteren.

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

### Zie ook

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* naamruimte [Aspose.PSD](../../rastercachedimage/)
* montage [Aspose.PSD](../../../)


