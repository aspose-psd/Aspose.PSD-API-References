---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "LayerGroup मेथड। लेयर समूह को जोड़ता है"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

लेयर समूह को जोड़ता है।

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| groupName | String | समूह का नाम। |
| index | Int32 | लेयर को उसके बाद सम्मिलित करने के लिए इंडेक्स। |

### रिटर्न वैल्यू

ग्रुप लेयर खोलना

## उदाहरण

निम्न उदाहरण दर्शाता है कि एक LayerGroup को दूसरे LayerGroup में कैसे जोड़ा जाए।

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// लेयर्स की पदानुक्रम इस प्रकार बनाना:
// -समूह 1
// --लेयर 1
// --समूह 2
// ---लेयर 2
// ---लेयर 3
// --लेयर 4

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

### देखें भी

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


