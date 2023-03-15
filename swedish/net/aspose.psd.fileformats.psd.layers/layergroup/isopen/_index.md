---
title: LayerGroup.IsOpen
second_title: Aspose.PSD för .NET API-referens
description: LayerGroup fast egendom. Hämtar eller ställer är mappen opened om inställd påSann än gruppen kommer att vara i öppet tillstånd vid start annars i minimerat tillstånd.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Hämtar eller ställer är mappen opened om inställd på`Sann` än gruppen kommer att vara i öppet tillstånd vid start, annars i minimerat tillstånd.

```csharp
public bool IsOpen { get; set; }
```

### Exempel

Följande kod visar hur du öppnar och stänger LayerGroup (mapp) med hjälp av egenskapen IsOpen.

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
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* hopsättning [Aspose.PSD](../../../)


