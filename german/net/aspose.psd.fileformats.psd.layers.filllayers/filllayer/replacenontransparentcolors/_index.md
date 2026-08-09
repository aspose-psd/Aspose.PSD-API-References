---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FillLayer-Methode. Ersetzt alle nichttransparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie sie bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt."
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie dies bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorArgb | Int32 | Neuer ARGB-Farbwert, mit dem nichttransparente Farben ersetzt werden. |

## Beispiele

Der folgende Code demonstriert die Unterstützung des CMYK-Farbmodus mit 16 Bit und die Möglichkeit, mit der Klasse Aspose.PSD.Graphics zu zeichnen.

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

### Siehe auch

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


