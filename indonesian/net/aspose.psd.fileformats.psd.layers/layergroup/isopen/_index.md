---
title: LayerGroup.IsOpen
second_title: Aspose.PSD untuk Referensi .NET API
description: LayerGroup Properti. Mendapat atau menyetel adalah folder yang dibuka jika disetel keBENAR daripada grup akan dalam keadaan terbuka saat start up jika tidak dalam keadaan diminimalkan.
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Mendapat atau menyetel adalah folder yang dibuka jika disetel ke`BENAR` daripada grup akan dalam keadaan terbuka saat start up, jika tidak dalam keadaan diminimalkan.

```csharp
public bool IsOpen { get; set; }
```

### Contoh

Kode berikut menunjukkan cara membuka dan menutup LayerGroup (Folder) menggunakan properti IsOpen.

```csharp
[C#]

// Contoh membaca dan menulis properti IsOpen saat runtime.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### Lihat juga

* class [LayerGroup](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* perakitan [Aspose.PSD](../../../)


