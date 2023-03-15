---
title: LinkedLayersManager.GetLayersByLinkGroupId
second_title: Aspose.PSD für .NET-API-Referenz
description: LinkedLayersManager methode. Ruft Layer nach LinkgruppenID ab.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
## LinkedLayersManager.GetLayersByLinkGroupId method

Ruft Layer nach Linkgruppen-ID ab.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linkGroupId | Int16 | Die Linkgruppen-ID. |

### Rückgabewert

Das Layer-Array.

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* Montage [Aspose.PSD](../../../)


