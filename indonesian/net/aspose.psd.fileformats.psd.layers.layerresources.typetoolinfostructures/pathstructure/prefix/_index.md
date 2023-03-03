---
title: PathStructure.Prefix
second_title: Aspose.PSD untuk Referensi .NET API
description: PathStructure Properti. Mendapat atau menyetel awalan jalur.
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
## PathStructure.Prefix property

Mendapat atau menyetel awalan jalur.

```csharp
public string Prefix { get; set; }
```

### Nilai properti

Jalur lengkap.

### Contoh

Kode berikut menunjukkan kemampuan untuk memuat file dengan struktur PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Lihat juga

* class [PathStructure](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* perakitan [Aspose.PSD](../../../)


