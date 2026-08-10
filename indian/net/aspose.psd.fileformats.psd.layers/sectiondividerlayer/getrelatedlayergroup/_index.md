---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "SectionDividerLayer method. इस SectionDividerLayer उदाहरण से संबंधित LayerGroup को प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

इस [`SectionDividerLayer`](../) उदाहरण से संबंधित [`LayerGroup`](../../layergroup/) को प्राप्त करता है।

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### रिटर्न वैल्यू

[`LayerGroup`](../../layergroup/) उदाहरण।

## उदाहरण

निम्नलिखित कोड SectionDividerLayer लेयर्स को दर्शाता है और उससे संबंधित LayerGroup को कैसे प्राप्त किया जाए।

```csharp
[C#]

// निम्नलिखित कोड SectionDividerLayer लेयर्स को दर्शाता है और उससे संबंधित LayerGroup को कैसे प्राप्त किया जाए।

// लेयर पदानुक्रम
//    [0]: '</Layer group>' Group 1 के लिए SectionDividerLayer
//    [1]: 'Layer 1' नियमित लेयर
//    [2]: '</Layer group>' Group 2 के लिए SectionDividerLayer
//    [3]: '</Layer group>' Group 3 के लिए SectionDividerLayer
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // लेयर्स पदानुक्रम बनाना
    // LayerGroup 'Group 1' जोड़ें
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // सामान्य लेयर जोड़ें
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // LayerGroup 'Group 2' जोड़ें
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // LayerGroup 'Group 3' जोड़ें
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer को प्राप्त करता है
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() मेथड का उपयोग करके, संबंधित LayerGroup इंस्टेंस प्राप्त करता है।
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### देखें भी

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


