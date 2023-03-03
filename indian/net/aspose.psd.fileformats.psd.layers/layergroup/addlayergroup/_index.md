---
title: LayerGroup.AddLayerGroup
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: LayerGroup तरक. परत समूह जड़त है.
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

परत समूह जोड़ता है.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| groupName | String | समूह का नाम। |
| index | Int32 | बाद में डालने के लिए परत का सूचकांक। |

### प्रतिलाभ की मात्रा

समूह परत खोली जा रही है

### उदाहरण

निम्न उदाहरण एक अन्य LayerGroup में LayerGroup को जोड़ने का प्रदर्शन करता है।

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// इस तरह परतों का पदानुक्रम बनाना:
// -समूह 1
// --परत 1
// --समूह 2
// --- परत 2
// --- परत 3
// --परत 4

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

### यह सभी देखें

* class [LayerGroup](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* सभा [Aspose.PSD](../../../)


