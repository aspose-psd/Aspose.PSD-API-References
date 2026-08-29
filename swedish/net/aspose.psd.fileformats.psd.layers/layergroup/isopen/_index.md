---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerGroup egenskap. Hämtar eller anger om mappen är öppen; om den sätts till true kommer gruppen att vara i öppet läge vid start, annars i minimerat läge"
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Hämtar eller anger om mappen är öppen; om den sätts till `true` blir gruppen öppen vid start, annars minimerad.

```csharp
public bool IsOpen { get; set; }
```

## Exempel

Följande kod visar hur man öppnar och stänger LayerGroup (Folder) med hjälp av IsOpen-egenskapen.

```csharp
[C#]

// Exempel på att läsa och skriva IsOpen-egenskapen vid körning.
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

### Se även

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


