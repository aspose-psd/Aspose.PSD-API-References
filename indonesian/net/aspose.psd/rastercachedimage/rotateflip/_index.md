---
title: RasterCachedImage.RotateFlip
second_title: Aspose.PSD untuk Referensi .NET API
description: RasterCachedImage metode. Memutar membalik atau memutar dan membalik gambar.
type: docs
weight: 140
url: /id/net/aspose.psd/rastercachedimage/rotateflip/
---
## RasterCachedImage.RotateFlip method

Memutar, membalik, atau memutar dan membalik gambar.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Jenis flip putar. |

### Contoh

Kode berikut menunjukkan cara memutar gambar.

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

### Lihat juga

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* ruang nama [Aspose.PSD](../../rastercachedimage/)
* perakitan [Aspose.PSD](../../../)


