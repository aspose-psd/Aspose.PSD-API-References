---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD per riferimento API .NET
description: RasterCachedImage metodo. Ruota capovolge o ruota e capovolge limmagine.
type: docs
weight: 140
url: /it/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Ruota, capovolge o ruota e capovolge l'immagine.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Il tipo di rotazione capovolgimento. |

### Esempi

Il codice seguente mostra come ruotare l'immagine.

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

### Guarda anche

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* spazio dei nomi [Aspose.PSD](../../rastercachedimage/)
* assemblea [Aspose.PSD](../../../)


