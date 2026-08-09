---
title: "LinkedLayersManager.LinkLayers"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LinkedLayersManager-Methode. Verknüpft die Eingabelayer und gibt LingGroupId zurück"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
{{< psd/tize >}}
## LinkedLayersManager.LinkLayers method

Verknüpft die Eingabeschichten und gibt LingGroupId zurück.

```csharp
public short LinkLayers(Layer[] layers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Layer | Layer[] | Die Layer. |

### Rückgabewert

Die Linkgruppen-ID.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Die Layer sind null. |
| ArgumentException | Die Anzahl der Layer muss größer als 1 sein. |
| ArgumentException | Der Container jedes Layers sollte derselbe sein wie das aktuelle PsdImage. |

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


