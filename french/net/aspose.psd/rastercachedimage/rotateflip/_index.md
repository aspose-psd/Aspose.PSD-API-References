---
title: RasterCachedImage.RotateFlip
second_title: Référence de l'API Aspose.PSD pour .NET
description: RasterCachedImage méthode. Fait pivoter retourne ou fait pivoter et retourne limage.
type: docs
weight: 140
url: /fr/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Fait pivoter, retourne ou fait pivoter et retourne l'image.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Le type de retournement de rotation. |

### Exemples

Le code suivant montre comment faire pivoter l'image.

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

### Voir également

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* espace de noms [Aspose.PSD](../../rastercachedimage/)
* Assemblée [Aspose.PSD](../../../)


