---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerGroup-Eigenschaft. Gibt zurück oder legt fest, ob der Ordner geöffnet ist; wenn auf true gesetzt, wird die Gruppe beim Start im geöffneten Zustand sein, andernfalls im minimierten Zustand."
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Liest oder setzt, ob der Ordner geöffnet ist; wenn er auf `true` gesetzt wird, ist die Gruppe beim Start geöffnet, andernfalls im minimierten Zustand.

```csharp
public bool IsOpen { get; set; }
```

## Beispiele

Der folgende Code zeigt, wie man LayerGroup (Ordner) mit der IsOpen-Eigenschaft öffnet und schließt.

```csharp
[C#]

// Beispiel für das Lesen und Schreiben der IsOpen-Eigenschaft zur Laufzeit.
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

### Siehe auch

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


