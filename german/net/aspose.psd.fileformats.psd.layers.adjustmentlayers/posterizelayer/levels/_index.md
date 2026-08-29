---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PosterizeLayer-Eigenschaft. Stufen des Posterize-Layers."
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Stufen der Posterize Ebene.

```csharp
public short Levels { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung von PosterizeLayer.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    foreach (Layer layer in image.Layers)
    {
        if (layer is PosterizeLayer)
        {
            ((PosterizeLayer)layer).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### Siehe auch

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


