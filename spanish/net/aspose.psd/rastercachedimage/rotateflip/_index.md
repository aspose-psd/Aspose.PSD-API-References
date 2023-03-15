---
title: RasterCachedImage.RotateFlip
second_title: Referencia de API de Aspose.PSD para .NET
description: RasterCachedImage método. Gira voltea o gira y voltea la imagen.
type: docs
weight: 140
url: /es/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Gira, voltea o gira y voltea la imagen.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | El tipo rotar voltear. |

### Ejemplos

El siguiente código muestra cómo rotar la imagen.

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

### Ver también

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* espacio de nombres [Aspose.PSD](../../rastercachedimage/)
* asamblea [Aspose.PSD](../../../)


