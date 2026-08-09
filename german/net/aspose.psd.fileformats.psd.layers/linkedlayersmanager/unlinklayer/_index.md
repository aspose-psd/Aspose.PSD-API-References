---
title: "LinkedLayersManager.UnlinkLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LinkedLayersManager-Methode. Trennt den Layer."
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/
---
{{< psd/tize >}}
## LinkedLayersManager.UnlinkLayer method

Löst die Verknüpfung der Ebene..

```csharp
public void UnlinkLayer(Layer layer)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ebene | Ebene | Die Ebene. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Der Layer ist null. |
| ArgumentException | Der Container des Layers sollte derselbe sein wie das aktuelle PsdImage. |

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


