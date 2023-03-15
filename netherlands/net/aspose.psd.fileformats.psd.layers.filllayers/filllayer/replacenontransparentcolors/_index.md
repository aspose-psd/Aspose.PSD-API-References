---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD voor .NET API-referentie
description: FillLayer methode. Vervangt alle niettransparante kleuren door nieuwe kleuren en behoudt de oorspronkelijke alfawaarde om vloeiende randen te besparen. Opmerking als u het gebruikt op afbeeldingen zonder transparantie worden alle kleuren vervangen door een enkele kleur.
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Vervangt alle niet-transparante kleuren door nieuwe kleuren en behoudt de oorspronkelijke alfawaarde om vloeiende randen te besparen. Opmerking: als u het gebruikt op afbeeldingen zonder transparantie, worden alle kleuren vervangen door een enkele kleur.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newColorArgb | Int32 | Nieuwe kleur ARGB-waarde om niet-transparante kleuren mee te vervangen. |

### Voorbeelden

De volgende code demonstreert de ondersteuning van de CMYK ColorMode 16-bits en de mogelijkheid om te tekenen met de klasse Aspose.PSD.Graphics.

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

### Zie ook

* class [FillLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* montage [Aspose.PSD](../../../)


