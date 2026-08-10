---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti LayerGroup. Mendapatkan atau mengatur apakah folder terbuka; jika diset ke true maka grup akan berada dalam keadaan terbuka saat memulai, jika tidak maka dalam keadaan diminimalkan"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Mendapatkan atau mengatur apakah folder terbuka; jika diset ke `true` maka grup akan berada dalam keadaan terbuka saat memulai, jika tidak dalam keadaan diminimalkan.

```csharp
public bool IsOpen { get; set; }
```

## Contoh

Kode berikut menunjukkan cara membuka dan menutup LayerGroup (Folder) menggunakan properti IsOpen.

```csharp
[C#]

// Contoh membaca dan menulis properti IsOpen pada waktu berjalan.
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

### Lihat Juga

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


