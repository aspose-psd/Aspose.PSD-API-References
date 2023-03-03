---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerGroup metode. Menambahkan grup layer.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

Menambahkan grup layer.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| groupName | String | Nama grup. |
| index | Int32 | Indeks lapisan yang akan disisipkan setelahnya. |

### Nilai Pengembalian

Membuka lapisan grup

### Contoh

Contoh berikut menunjukkan menambahkan LayerGroup ke LayerGroup lain.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// membuat hirarki layer seperti ini:
// -Grup 1
// --Lapisan 1
// --Grup 2
// ---Lapisan 2
// ---Lapisan 3
// --Lapisan 4

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

### Lihat juga

* class [LayerGroup](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* perakitan [Aspose.PSD](../../../)


