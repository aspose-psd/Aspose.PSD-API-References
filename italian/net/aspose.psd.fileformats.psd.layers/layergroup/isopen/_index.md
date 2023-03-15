---
title: LayerGroup.IsOpen
second_title: Aspose.PSD per riferimento API .NET
description: LayerGroup proprietà. Ottiene o imposta la cartella aperta se impostata suVERO il gruppo sarà in stato aperto allavvio altrimenti in stato ridotto a icona.
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Ottiene o imposta la cartella aperta se impostata su`VERO` il gruppo sarà in stato aperto all'avvio, altrimenti in stato ridotto a icona.

```csharp
public bool IsOpen { get; set; }
```

### Esempi

Il codice seguente mostra come aprire e chiudere LayerGroup (Folder) utilizzando la proprietà IsOpen.

```csharp
[C#]

// Esempio di lettura e scrittura della proprietà IsOpen in fase di esecuzione.
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

### Guarda anche

* class [LayerGroup](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* assemblea [Aspose.PSD](../../../)


