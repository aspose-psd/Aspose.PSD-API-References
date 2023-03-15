---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD for .NET API Referansı
description: FillLayer yöntem. Saydam olmayan tüm renkleri yeni renkle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not saydam olmayan görüntülerde kullanırsanız tüm renkler tek bir renkle değiştirilir.
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Saydam olmayan tüm renkleri yeni renkle değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: saydam olmayan görüntülerde kullanırsanız, tüm renkler tek bir renkle değiştirilir.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newColorArgb | Int32 | Saydam olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

### Örnekler

Aşağıdaki kod, CMYK ColorMode 16 bit desteğini ve Aspose.PSD.Graphics sınıfını kullanarak çizim yapma becerisini gösterir.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### Ayrıca bakınız

* class [FillLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* toplantı [Aspose.PSD](../../../)


