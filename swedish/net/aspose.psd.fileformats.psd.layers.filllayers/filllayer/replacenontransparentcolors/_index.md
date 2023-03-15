---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD för .NET API-referens
description: FillLayer metod. Ersätter alla icketransparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Ersätter alla icke-transparenta färger med ny färg och bevarar det ursprungliga alfavärdet för att spara jämna kanter. Obs: om du använder det på bilder utan genomskinlighet kommer alla färger att ersättas med en enda.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorArgb | Int32 | Nytt ARGB-värde för färg att ersätta icke-transparenta färger med. |

### Exempel

Följande kod visar stödet för CMYK ColorMode 16-bitars och förmågan att rita genom att använda klassen Aspose.PSD.Graphics.

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

### Se även

* class [FillLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* hopsättning [Aspose.PSD](../../../)


