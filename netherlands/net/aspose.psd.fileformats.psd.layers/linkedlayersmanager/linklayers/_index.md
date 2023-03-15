---
title: LinkedLayersManager.LinkLayers
second_title: Aspose.PSD voor .NET API-referentie
description: LinkedLayersManager methode. Koppelt de invoerlagen en retourneert LingGroupId.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
## LinkedLayersManager.LinkLayers method

Koppelt de invoerlagen en retourneert LingGroupId.

```csharp
public short LinkLayers(Layer[] layers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layers | Layer[] | De lagen. |

### Winstwaarde

De koppelingsgroep-id.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | De lagen zijn nul. |
| ArgumentException | Het aantal lagen moet groter zijn dan 1. |
| ArgumentException | De container van elke laag moet hetzelfde zijn als de huidige PsdImage. |

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* montage [Aspose.PSD](../../../)


