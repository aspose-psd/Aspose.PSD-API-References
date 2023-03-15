---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD per riferimento API .NET
description: IGradientFillSettings proprietà. Ottiene o imposta la scala.
type: docs
weight: 100
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

Ottiene o imposta la scala.

```csharp
public int Scale { get; set; }
```

### Valore della proprietà

La bilancia.

### Esempi

Nell'esempio seguente viene illustrato come utilizzare la proprietà Scale per ridimensionare FillLayer con gradiente.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // ottenere un livello di riempimento
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // aggiorna il valore della scala
    settings.Scale = 200;
    fillLayer.Update(); // Aggiorna i dati dei pixel

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Guarda anche

* interface [IGradientFillSettings](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* assemblea [Aspose.PSD](../../../)


