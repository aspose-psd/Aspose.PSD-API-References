---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ILayerEffect metod. Beräknar och hämtar gränserna för effektpixlar baserat på indata lagerpixelers gränser"
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Beräknar och hämtar gränserna för effektpixlar baserat på indata lagrets pixelgränser.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerBounds | Rectangle | Lagrets pixelgränser. |
| globalAngle | Int32 | Den globala vinkeln för att beräkna den globala ljusvinkeln. |

### Returvärde

Gränserna för effektpixlar baserat på indata lagerpixelers gränser.

## Exempel

Visar hur man får ett lagers gränser med effekter och exporterar det med korrekt storlek.

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
                                                // boundsToExport = psdImage.Bounds; // För att spara inom PsdImage-gränserna på den ursprungliga lagerplatsen

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

### Se även

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


