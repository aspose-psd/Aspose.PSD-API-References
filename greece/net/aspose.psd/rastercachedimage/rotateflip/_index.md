---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD για Αναφορά API .NET
description: RasterCachedImage μέθοδος. Περιστρέφει αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.
type: docs
weight: 140
url: /el/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Ο τύπος περιστροφής αναστροφής. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να περιστρέψετε την εικόνα.

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

### Δείτε επίσης

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* χώρος ονομάτων [Aspose.PSD](../../rastercachedimage/)
* συνέλευση [Aspose.PSD](../../../)


