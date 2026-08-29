---
title: "Layer.IsVisible"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti Layer. Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan terlihat."
type: docs
weight: 180
url: /id/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan terlihat

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` jika instance ini terlihat; jika tidak, `false`.

## Contoh

Contoh berikut menunjukkan cara Anda dapat mengubah visibilitas LayerGroup di Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// lakukan perubahan pada nama lapisan dan simpan
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Matikan semua di dalam grup
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Lihat Juga

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


