---
title: Layer.IsVisible
second_title: Aspose.PSD untuk Referensi .NET API
description: Layer Properti. Mendapat atau menyetel nilai yang menunjukkan apakah layer terlihat
type: docs
weight: 170
url: /id/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Mendapat atau menyetel nilai yang menunjukkan apakah layer terlihat

```csharp
public bool IsVisible { get; set; }
```

### Nilai properti

`BENAR` jika contoh ini terlihat; jika tidak,`PALSU` .

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat mengubah visibilitas LayerGroup di Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// buat perubahan pada nama layer dan simpan
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Matikan semua yang ada di dalam grup
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [Layer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* perakitan [Aspose.PSD](../../../)


