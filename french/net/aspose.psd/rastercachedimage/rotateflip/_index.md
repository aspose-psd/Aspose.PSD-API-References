---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RasterCachedImage. Effectue une rotation, un retournement ou une rotation et un retournement de l'image"
type: docs
weight: 140
url: /fr/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

Fait pivoter, retourner ou pivoter et retourner l'image.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Le type de rotation/retournement. |

## Exemples

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

### Voir aussi

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


