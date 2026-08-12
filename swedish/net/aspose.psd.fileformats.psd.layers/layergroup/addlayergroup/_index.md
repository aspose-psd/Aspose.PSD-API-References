---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerGroup‑metod. Lägger till lagergruppen."
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

Lägger till lagergruppen.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| groupName | String | Gruppens namn. |
| index | Int32 | Indexet för lagret att infoga efter. |

### Returvärde

Öppnar grupplager

## Exempel

Följande exempel visar hur du lägger till LayerGroup i en annan LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// skapa lagerhierarki så här:
// -Grupp 1
// --Lager 1
// --Grupp 2
// ---Lager 2
// ---Lager 3
// --Lager 4

var createOptions = new PsdOptions();
createOptions.Source = new FileCreateSource(sourceFileName, false);
createOptions.Palette = new PsdColorPalette(new Color[] { Color.Green });

using (var psdImage = (PsdImage)Image.Create(createOptions, 500, 500))
{
    LayerGroup group1 = psdImage.AddLayerGroup("Group 1", 0, false);

    Layer layer1 = new Layer(psdImage);
    layer1.Name = "Layer 1";
    group1.AddLayer(layer1);

    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);

    Layer layer2 = new Layer(psdImage);
    layer2.Name = "Layer 2";
    group2.AddLayer(layer2);

    Layer layer3 = new Layer(psdImage);
    layer3.Name = "Layer 3";
    group2.AddLayer(layer3);

    Layer layer4 = new Layer(psdImage);
    layer4.Name = "Layer 4";
    group1.AddLayer(layer4);

    psdImage.Save();
}
```

### Se även

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


