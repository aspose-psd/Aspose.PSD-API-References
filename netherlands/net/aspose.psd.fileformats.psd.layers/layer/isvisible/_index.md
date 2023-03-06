---
title: Layer.IsVisible
second_title: Aspose.PSD voor .NET API-referentie
description: Layer eigendom. Haalt of stelt een waarde in die aangeeft of de laag zichtbaar is
type: docs
weight: 170
url: /nl/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Haalt of stelt een waarde in die aangeeft of de laag zichtbaar is

```csharp
public bool IsVisible { get; set; }
```

### Eigendoms-waarde

`WAAR` of deze instantie zichtbaar is; anders,`vals` .

### Voorbeelden

Het volgende voorbeeld laat zien hoe u de zichtbaarheid van LayerGroup in Aspose.PSD kunt wijzigen

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// breng wijzigingen aan in de laagnamen en sla deze op
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Schakel alles binnen een groep uit
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Zie ook

* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)


