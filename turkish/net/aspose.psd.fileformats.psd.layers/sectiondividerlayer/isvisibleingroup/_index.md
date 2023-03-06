---
title: SectionDividerLayer.IsVisibleInGroup
second_title: Aspose.PSD for .NET API Referansı
description: SectionDividerLayer mülk. Bu örneğin grupta görünüp görünmediğini gösteren bir değer alır katman grupta değilse kök grup anlamına gelir.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

Bu örneğin grupta görünüp görünmediğini gösteren bir değer alır (katman grupta değilse, kök grup anlamına gelir).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Mülk değeri

`doğru` bu örnek grupta görünür durumdaysa; aksi takdirde,`YANLIŞ` .

### Örnekler

Aşağıdaki kod, SectionDividerLayer katmanlarını ve bununla ilgili LayerGroup'un nasıl alınacağını gösterir.

```csharp
[C#]

// Aşağıdaki kod, SectionDividerLayer katmanlarını ve bununla ilgili LayerGroup'un nasıl alınacağını gösterir.

// Katmanlar hiyerarşisi
// [0]: '</Katman grubu>' Grup 1 için SectionDividerLayer
// [1]: 'Katman 1' Normal Katman
// [2]: '</Katman grubu>' Grup 2 için SectionDividerLayer
// [3]: '</Katman grubu>' Grup 3 için SectionDividerLayer
// [4]: 'Grup 3' Grup Katmanı
// [5]: 'Grup 2' Grup Katmanı
// [6]: 'Grup 1' Grup Katmanı

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
    // LayerGroup 'Group 1'i ekleyin
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Normal katman ekle
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // LayerGroup 'Group 2'yi ekleyin
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // LayerGroup 'Group 3'ü ekleyin
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // SectionDividerLayer'ı alır
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // SectionDividerLayer.GetRelatedLayerGroup() yöntemini kullanarak ilgili LayerGroup örneğini alır.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // aynı Katman Grubu
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // aynı Katman Grubu
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // aynı Katman Grubu

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Grup 1' 5 katman içeriyor
}
```

### Ayrıca bakınız

* class [SectionDividerLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* toplantı [Aspose.PSD](../../../)


