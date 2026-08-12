---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "ILayerEffect method. Berekent en haalt de grenzen van effectpixels op basis van de grenzen van de invoerlaagpixels"
type: docs
weight: 50
url: /nl/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Berekent en haalt de grenzen van effectpixels op basis van de grenzen van de invoerlaagpixels.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerBounds | Rechthoek | De grenzen van de laagpixels. |
| globalAngle | Int32 | De globale hoek om de globale lichthoek te berekenen. |

### Retourwaarde

De grenzen van effectpixels op basis van de grenzen van de invoerlaagpixels.

## Voorbeelden

Toont hoe je de grenzen van een laag met effecten kunt verkrijgen en deze kunt exporteren met de juiste grootte.

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
                                                // boundsToExport = psdImage.Bounds; // Om op te slaan binnen de PsdImage-grenzen op de oorspronkelijke laaglocatie

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

### Zie ook

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


