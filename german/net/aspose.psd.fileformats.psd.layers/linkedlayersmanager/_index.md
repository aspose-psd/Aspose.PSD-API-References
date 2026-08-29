---
title: "Klasse LinkedLayersManager"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager Klasse. Verknüpfte Ebenen-Manager-Klasse"
type: docs
weight: 3800
url: /de/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
{{< psd/tize >}}
## LinkedLayersManager class

Klasse für die Verwaltung verknüpfter Ebenen.

```csharp
public sealed class LinkedLayersManager
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Ruft Ebenen nach Linkgruppen-ID ab. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Gibt die mit der Ebene verknüpfte Linkgruppen-ID zurück. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Verknüpft die Eingabeschichten und gibt LingGroupId zurück. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Löst die Verknüpfung der Ebene.. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie verknüpfte Ebenen in Aspose.PSD manipulieren können.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // Verknüpfen Sie alle Ebenen in einer verknüpften Gruppe
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // Ermittelt die ID für eine Ebene
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // Ermittelt alle verknüpften Ebenen anhand der Linkgruppen-ID.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // Lösen Sie jede Ebene von der Gruppe
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // Gibt NULL zurück für eine Linkgruppen-ID, die keine Ebenen in der Gruppe enthält.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


