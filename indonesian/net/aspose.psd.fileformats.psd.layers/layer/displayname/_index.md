---
title: Layer.DisplayName
second_title: Aspose.PSD untuk Referensi .NET API
description: Layer Properti. Mendapat atau menyetel nama tampilan layer.
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Mendapat atau menyetel nama tampilan layer.

```csharp
public string DisplayName { get; set; }
```

### Nilai properti

Nama tampilan layer.

### Contoh

Contoh berikut mendemonstrasikan kemampuan untuk mengatur nilai DisplayName, di mana nama layer ditampilkan dengan benar.

```csharp
[C#]

// buat perubahan pada nama layer dan simpan
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // tetapkan nilai baru ke dalam properti DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Lihat juga

* class [Layer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* perakitan [Aspose.PSD](../../../)


