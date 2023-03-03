---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD per riferimento API .NET
description: FillLayer metodo. Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota se lo usi su immagini senza trasparenza tutti i colori verranno sostituiti con uno solo.
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorArgb | Int32 | Nuovo valore ARGB del colore con cui sostituire i colori non trasparenti. |

### Esempi

Il codice seguente dimostra il supporto del CMYK ColorMode a 16 bit e la possibilità di disegnare utilizzando la classe Aspose.PSD.Graphics.

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

### Guarda anche

* class [FillLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* assemblea [Aspose.PSD](../../../)


