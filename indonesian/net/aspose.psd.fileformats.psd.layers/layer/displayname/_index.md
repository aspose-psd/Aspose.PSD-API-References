---
title: "Layer.DisplayName"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti Layer. Mendapatkan atau mengatur nama tampilan lapisan"
type: docs
weight: 110
url: /id/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Mendapatkan atau mengatur nama tampilan lapisan.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Nama tampilan lapisan.

## Contoh

Contoh berikut menunjukkan kemampuan untuk mengatur nilai DisplayName, sehingga nama lapisan ditampilkan dengan benar.

```csharp
[C#]

// lakukan perubahan pada nama lapisan dan simpan
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // set nilai baru ke properti DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Lihat Juga

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


