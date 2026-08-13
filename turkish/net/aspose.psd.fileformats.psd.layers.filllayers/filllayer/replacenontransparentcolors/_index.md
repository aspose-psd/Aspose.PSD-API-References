---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD for .NET API Referansı"
description: "FillLayer yöntemi. Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur. Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir."
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Tüm saydam olmayan renkleri yeni renk ile değiştirir ve düzgün kenarları korumak için orijinal alfa değerini korur. Not: Saydamlığı olmayan görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newColorArgb | Int32 | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

## Örnekler

Aşağıdaki kod, CMYK ColorMode 16 bit desteğini ve Aspose.PSD.Graphics sınıfı kullanılarak çizim yapabilme yeteneğini gösterir.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Ayrıca Bakınız

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


