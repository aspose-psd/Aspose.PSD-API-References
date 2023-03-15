---
title: LinkedLayersManager.GetLinkGroupId
second_title: Aspose.PSD för .NET API-referens
description: LinkedLayersManager metod. Hämtar länkgruppsID som är kopplat till lagret.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
## LinkedLayersManager.GetLinkGroupId method

Hämtar länkgrupps-ID som är kopplat till lagret.

```csharp
public short GetLinkGroupId(Layer layer)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layer | Layer | Lagret. |

### Returvärde

Länkgrupps-id.

### Exempel

Följande exempel visar hur du kan manipulera länkade lager i Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // länka alla lager i en länkad grupp
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // får id för ett lager
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // hämtar alla länkade lager efter länkgrupp-id.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // ta bort länken mellan varje lager från gruppen
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // hämtar NULL för ett länkgrupps-ID som inte har några lager i gruppen.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Se även

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* hopsättning [Aspose.PSD](../../../)


