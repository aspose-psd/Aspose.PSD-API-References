---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD for .NET API Reference
description: LayerGroup method. Adds the layer group
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

Adds the layer group.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| groupName | String | Name of the group. |
| index | Int32 | The index of the layer to insert after. |

### Return Value

Opening group layer

## Examples

The following example demonstrates adding LayerGroup into another LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// making layers hierarchy like this:
// -Group 1
// --Layer 1
// --Group 2
// ---Layer 2
// ---Layer 3
// --Layer 4

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

### See Also

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* assembly [Aspose.PSD](../../../)


