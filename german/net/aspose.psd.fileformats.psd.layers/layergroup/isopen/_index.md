---
title: LayerGroup.IsOpen
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerGroup eigendom. Ruft ab oder legt fest ob der Ordner geöffnet ist  wenn auf eingestelltWAHR Diese Gruppe befindet sich beim Start im geöffneten Zustand ansonsten im minimierten Zustand.
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Ruft ab oder legt fest, ob der Ordner geöffnet ist , wenn auf eingestellt`WAHR` Diese Gruppe befindet sich beim Start im geöffneten Zustand, ansonsten im minimierten Zustand.

```csharp
public bool IsOpen { get; set; }
```

### Beispiele

Der folgende Code zeigt, wie LayerGroup (Folder) mithilfe der IsOpen-Eigenschaft geöffnet und geschlossen wird.

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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* Montage [Aspose.PSD](../../../)


