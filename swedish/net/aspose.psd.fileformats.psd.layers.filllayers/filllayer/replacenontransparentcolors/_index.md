---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD för .NET API‑referens"
description: "FillLayer-metoden. Ersätter alla icke-transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Observera att om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda."
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorArgb | Int32 | Nytt färg‑ARGB‑värde att ersätta icke‑transparenta färger med. |

## Exempel

Följande kod demonstrerar stöd för CMYK ColorMode 16‑bit och möjligheten att rita med hjälp av Aspose.PSD.Graphics‑klassen.

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

### Se även

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


