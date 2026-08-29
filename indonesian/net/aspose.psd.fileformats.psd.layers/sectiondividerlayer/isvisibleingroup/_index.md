---
title: "SectionDividerLayer.IsVisibleInGroup"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti SectionDividerLayer. Mendapatkan nilai yang menunjukkan apakah instance ini terlihat dalam grup. Jika layer tidak berada dalam grup, berarti grup akar"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/isvisibleingroup/
---
{{< psd/tize >}}
## SectionDividerLayer.IsVisibleInGroup property

Mendapatkan nilai yang menunjukkan apakah instance ini terlihat dalam grup (Jika lapisan tidak berada dalam grup berarti grup akar).

```csharp
public override bool IsVisibleInGroup { get; }
```

### Property Value

`true` jika instance ini terlihat dalam grup; jika tidak, `false`.

## Contoh

Kode berikut menunjukkan lapisan SectionDividerLayer dan cara mendapatkan LayerGroup yang terkait dengannya.

```csharp
[C#]

// Kode berikut menunjukkan lapisan SectionDividerLayer dan cara mendapatkan LayerGroup yang terkait dengannya.

// Hierarki lapisan
//    [0]: '</Layer group>' SectionDividerLayer untuk Grup 1
//    [1]: 'Layer 1' Lapisan Reguler
//    [2]: '</Layer group>' SectionDividerLayer untuk Grup 2
//    [3]: '</Layer group>' SectionDividerLayer untuk Grup 3
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
    // Membuat hierarki lapisan
    // Tambahkan LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Tambahkan lapisan reguler
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Tambahkan LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Tambahkan LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Mendapatkan SectionDividerLayer's
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // menggunakan metode SectionDividerLayer.GetRelatedLayerGroup(), memperoleh instance LayerGroup yang terkait.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Lihat Juga

* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


