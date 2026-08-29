---
title: "RasterCachedImage.RotateFlip"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode RasterCachedImage. Memutar, membalik, atau memutar dan membalik gambar"
type: docs
weight: 140
url: /id/net/aspose.psd/rastercachedimage/rotateflip/
---
{{< psd/tize >}}
## RasterCachedImage.RotateFlip method

Memutar, membalik, atau memutar dan membalik gambar.

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Tipe rotasi balik. |

## Contoh

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

### Lihat Juga

* enum [RotateFlipType](../../rotatefliptype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


