---
title: SectionDividerLayer.IsVisibleInGroup
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: SectionDividerLayer संपत्त. यह इंगत करने वल मन प्रप्त करत है क क्य यह उदहरण समूह में दखई दे रह है यद परत समूह में नहं है त इसक अर्थ रूट समूह है
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

यह इंगित करने वाला मान प्राप्त करता है कि क्या यह उदाहरण समूह में दिखाई दे रहा है (यदि परत समूह में नहीं है तो इसका अर्थ रूट समूह है)।

```csharp
public override bool IsVisibleInGroup { get; }
```

### संपत्ति मूल्य

`सत्य` यदि यह उदाहरण समूह में दिखाई दे रहा है; अन्यथा,`असत्य` .

### उदाहरण

निम्नलिखित कोड सेक्शनडिवाइडरलेयर परतों को प्रदर्शित करता है और इससे संबंधित लेयरग्रुप कैसे प्राप्त करें।

```csharp
[C#]

// निम्न कोड सेक्शनडिवाइडरलेयर परतों को प्रदर्शित करता है और इससे संबंधित लेयरग्रुप कैसे प्राप्त करें।

// परतें पदानुक्रम
// [0]: '</परत समूह>' ग्रुप 1 के लिए सेक्शन डिवाइडर लेयर
// [1]: 'परत 1' नियमित परत
// [2]: '</परत समूह>' ग्रुप 2 के लिए सेक्शन डिवाइडर लेयर
// [3]: '</परत समूह>' ग्रुप 3 के लिए सेक्शन डिवाइडर लेयर
// [4]: 'समूह 3' GroupLayer
// [5]: 'ग्रुप 2' ग्रुपलेयर
// [6]: 'ग्रुप 1' ग्रुपलेयर

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // परतें पदानुक्रम बनाना
    // लेयरग्रुप 'ग्रुप 1' जोड़ें
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // नियमित परत जोड़ें
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // लेयरग्रुप 'ग्रुप 2' जोड़ें
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // लेयरग्रुप 'ग्रुप 3' जोड़ें
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // सेक्शनडिवाइडरलेयर का हो जाता है
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup () पद्धति का उपयोग करके, संबंधित LayerGroup उदाहरण प्राप्त करता है।
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // वही लेयरग्रुप
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // वही लेयरग्रुप
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // वही लेयरग्रुप

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'समूह 1' में 5 परतें हैं
}
```

### यह सभी देखें

* class [SectionDividerLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* सभा [Aspose.PSD](../../../)


