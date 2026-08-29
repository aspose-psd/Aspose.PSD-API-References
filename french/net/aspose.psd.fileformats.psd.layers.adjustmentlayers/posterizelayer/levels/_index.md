---
title: "PosterizeLayer.Levels"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PosterizeLayer. Niveaux du calque Posterize"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/levels/
---
{{< psd/tize >}}
## PosterizeLayer.Levels property

Niveaux du calque Posterize.

```csharp
public short Levels { get; set; }
```

## Exemples

Le code suivant démontre la prise en charge de PosterizeLayer.

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

### Voir aussi

* class [PosterizeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


