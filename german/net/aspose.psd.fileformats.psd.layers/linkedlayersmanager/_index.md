---
title: Class LinkedLayersManager
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager klas. Managerklasse für verknüpfte Ebenen.
type: docs
weight: 3400
url: /de/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

Managerklasse für verknüpfte Ebenen.

```csharp
public sealed class LinkedLayersManager
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Ruft Layer nach Linkgruppen-ID ab. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Ruft die der Ebene zugeordnete Linkgruppen-ID ab. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Verknüpft die Eingabeschichten und gibt LingGroupId zurück. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Hebt die Verknüpfung der Ebene auf.. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie verknüpfte Ebenen in Aspose.PSD manipulieren können

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // Alle Ebenen in einer verknüpften Gruppe verknüpfen
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // Ruft die ID für eine Ebene ab
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // Ruft alle verknüpften Layer nach Linkgruppen-ID ab.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // Jede Ebene von der Gruppe trennen
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // ruft NULL für eine Link-Gruppen-ID ab, die keine Layer in der Gruppe hat.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Montage [Aspose.PSD](../../)


