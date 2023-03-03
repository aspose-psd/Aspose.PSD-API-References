---
title: SectionDividerLayer.IsVisibleInGroup
second_title: Aspose.PSD untuk Referensi .NET API
description: SectionDividerLayer Properti. Mendapat nilai yang menunjukkan apakah instance ini terlihat dalam grup Jika lapisan tidak ada dalam grup berarti grup root.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
## SectionDividerLayer.IsVisibleInGroup property

Mendapat nilai yang menunjukkan apakah instance ini terlihat dalam grup (Jika lapisan tidak ada dalam grup, berarti grup root).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Nilai properti

`BENAR` jika instance ini terlihat dalam grup; jika tidak,`PALSU` .

### Contoh

Kode berikut mendemonstrasikan layer SectionDividerLayer dan cara mendapatkan LayerGroup yang terkait dengannya.

```csharp
[C#]

// Kode berikut mendemonstrasikan layer SectionDividerLayer dan cara mendapatkan LayerGroup yang terkait dengannya.

// Hierarki layer
// [0]: '</Grup lapisan>' SectionDividerLayer untuk Grup 1
// [1]: Lapisan Reguler 'Lapisan 1'
// [2]: '</Grup lapisan>' SectionDividerLayer untuk Grup 2
// [3]: '</Grup lapisan>' SectionDividerLayer untuk Grup 3
// [4]: 'Grup 3' GroupLayer
// [5]: 'Grup 2' GroupLayer
// [6]: 'Grup 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Membuat hirarki layer
    // Tambahkan LayerGroup 'Grup 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Tambahkan lapisan biasa
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Tambahkan LayerGroup 'Grup 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Tambahkan LayerGroup 'Grup 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Mendapatkan SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // menggunakan metode SectionDividerLayer.GetRelatedLayerGroup(), dapatkan instance LayerGroup terkait.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // LayerGroup yang sama
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // LayerGroup yang sama
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // LayerGroup yang sama

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Grup 1' berisi 5 lapisan
}
```

### Lihat juga

* class [SectionDividerLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../sectiondividerlayer/)
* perakitan [Aspose.PSD](../../../)


