---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Aspose.PSD for .NET API Referansı"
description: "SectionDividerLayer yöntemi. Bu SectionDividerLayer örneğiyle ilişkili LayerGroup'ı alır."
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

Bu [`SectionDividerLayer`](../) örneğiyle ilişkili [`LayerGroup`](../../layergroup/) alır.

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### Dönüş Değeri

`[`LayerGroup`](../../layergroup/)` örneği.

## Örnekler

Aşağıdaki kod, SectionDividerLayer katmanlarını ve ona ilişkili LayerGroup'un nasıl alınacağını gösterir.

```csharp
[C#]

// Aşağıdaki kod, SectionDividerLayer katmanlarını ve ona ilişkili LayerGroup'un nasıl alınacağını gösterir.

// Katmanlar hiyerarşisi
//    [0]: '</Layer group>' Group 1 için SectionDividerLayer
//    [1]: 'Layer 1' Normal Katman
//    [2]: '</Layer group>' Group 2 için SectionDividerLayer
//    [3]: '</Layer group>' Group 3 için SectionDividerLayer
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
    // Katman hiyerarşisi oluşturma
    // LayerGroup 'Group 1' ekleyin
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Normal katman ekleyin
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // LayerGroup 'Group 2' ekleyin
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // LayerGroup 'Group 3' ekleyin
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer'ın öğesini alır
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() metodunu kullanarak, ilgili LayerGroup örneğini elde eder.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Ayrıca Bakınız

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


