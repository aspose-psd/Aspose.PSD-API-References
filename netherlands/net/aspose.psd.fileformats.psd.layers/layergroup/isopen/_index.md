---
title: LayerGroup.IsOpen
second_title: Aspose.PSD voor .NET API-referentie
description: LayerGroup eigendom. Krijgt of stelt de map geopend indien ingesteld opWAAR dan is de groep bij het opstarten in de open status anders in de geminimaliseerde status.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Krijgt of stelt de map geopend indien ingesteld op`WAAR` dan is de groep bij het opstarten in de open status, anders in de geminimaliseerde status.

```csharp
public bool IsOpen { get; set; }
```

### Voorbeelden

De volgende code laat zien hoe u LayerGroup (Folder) opent en sluit met behulp van de eigenschap IsOpen.

```csharp
[C#]

// Voorbeeld van het lezen en schrijven van IsOpen-eigenschap tijdens runtime.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### Zie ook

* class [LayerGroup](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* montage [Aspose.PSD](../../../)


