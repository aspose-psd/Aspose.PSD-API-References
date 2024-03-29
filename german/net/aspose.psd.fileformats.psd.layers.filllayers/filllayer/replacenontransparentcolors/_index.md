---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD für .NET-API-Referenz
description: FillLayer methode. Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen AlphaWert bei um glatte Kanten zu erhalten. Hinweis Wenn Sie es auf Bildern ohne Transparenz verwenden werden alle Farben durch eine einzige ersetzt.
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorArgb | Int32 | Neuer Farb-ARGB-Wert zum Ersetzen von nicht transparenten Farben. |

### Beispiele

Der folgende Code demonstriert die Unterstützung von CMYK ColorMode 16 Bit und die Fähigkeit zum Zeichnen mithilfe der Aspose.PSD.Graphics-Klasse.

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

### Siehe auch

* class [FillLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* Montage [Aspose.PSD](../../../)


