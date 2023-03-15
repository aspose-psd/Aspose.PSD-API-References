---
title: Class LinkedLayersManager
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager klas. Beheerklasse gekoppelde lagen.
type: docs
weight: 3400
url: /nl/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

Beheerklasse gekoppelde lagen.

```csharp
public sealed class LinkedLayersManager
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Haalt lagen op door link group id. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Haalt de koppelingsgroep-ID op die is gekoppeld aan de laag. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Koppelt de invoerlagen en retourneert LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Ontkoppelt de laag.. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u gekoppelde lagen kunt manipuleren in Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // koppel alle lagen in één gekoppelde groep
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // krijgt id voor één laag
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // haalt alle gelinkte lagen op door link group id.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // ontkoppel elke laag van de groep
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // haalt NULL op voor een koppelingsgroep-ID die geen lagen in de groep heeft.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* montage [Aspose.PSD](../../)


