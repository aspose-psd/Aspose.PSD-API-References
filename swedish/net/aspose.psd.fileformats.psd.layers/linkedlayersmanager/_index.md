---
title: Class LinkedLayersManager
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager klass. Manager class för länkade lager.
type: docs
weight: 3400
url: /sv/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

Manager class för länkade lager.

```csharp
public sealed class LinkedLayersManager
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Hämtar lager efter länkgrupp-id. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Hämtar länkgrupps-ID som är kopplat till lagret. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Länkar indatalagren och returnerar LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Tar bort länken till lagret.. |

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

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* hopsättning [Aspose.PSD](../../)


