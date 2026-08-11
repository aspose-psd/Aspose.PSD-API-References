---
title: "ILayerEffect.GetEffectBounds"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo ILayerEffect. Calcola e restituisce i limiti dei pixel di effetto basati sui limiti dei pixel del livello di input"
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Calcola e restituisce i limiti dei pixel di effetto basati sui limiti dei pixel del livello di input.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layerBounds | Rettangolo | I limiti dei pixel del livello. |
| globalAngle | Int32 | L'angolo globale per calcolare l'angolo della luce globale. |

### Valore di ritorno

I limiti dei pixel di effetto basati sui limiti dei pixel del livello di input.

## Esempi

Dimostra come ottenere i limiti di un livello con effetti e esportarli con la dimensione corretta.

```csharp
[C#]

string srcFile = "1958.psd";
string outputFile = "out_1958.png";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    var layer1 = psdImage.Layers[1];

    var layerBoudns = layer1.Bounds;
    foreach (var effect in layer1.BlendingOptions.Effects)
    {
        layerBoudns = Rectangle.Union(
            layerBoudns,
            effect.GetEffectBounds(layer1.Bounds, psdImage.GlobalAngle));
    }

    Rectangle boundsToExport = Rectangle.Empty; // The default value is to save only the layer with effects.
                                                // boundsToExport = psdImage.Bounds; // Per salvare entro i limiti di PsdImage nella posizione originale del livello

    layer1.Save(
        outputFile,
        new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha },
        boundsToExport);

    using (var imgStream = new FileStream(outputFile, FileMode.Open))
    {
        var loadedLayer = new Layer(imgStream);
        if (loadedLayer.Size == layerBoudns.Size)
        {
            System.Console.WriteLine("The size is calculated correctly.");
        }
    }
}
```

### Vedi anche

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


