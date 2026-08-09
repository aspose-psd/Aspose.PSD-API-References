---
title: "ILayerEffect.GetEffectBounds"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ILayerEffect Methode. Berechnet und ruft die Begrenzungen der Effektpixel basierend auf den Begrenzungen der Eingabe‑Layer‑Pixel ab"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/geteffectbounds/
---
{{< psd/tize >}}
## ILayerEffect.GetEffectBounds method

Berechnet und liest die Grenzen der Effektpixel basierend auf den Grenzen der Eingabeebenenpixel.

```csharp
public Rectangle GetEffectBounds(Rectangle layerBounds, int globalAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layerBounds | Rectangle | Die Pixelgrenzen des Layers. |
| globalAngle | Int32 | Der globale Winkel zur Berechnung des globalen Lichtwinkels. |

### Rückgabewert

Die Begrenzungen der Effektpixel basierend auf den Begrenzungen der Eingabe‑Layer‑Pixel.

## Beispiele

Zeigt, wie man die Begrenzungen eines Layers mit Effekten ermittelt und mit der korrekten Größe exportiert.

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
                                                // boundsToExport = psdImage.Bounds; // Um innerhalb der PsdImage‑Grenzen am ursprünglichen Layer‑Standort zu speichern

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

### Siehe auch

* struct [Rectangle](../../../aspose.psd/rectangle/)
* interface [ILayerEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


