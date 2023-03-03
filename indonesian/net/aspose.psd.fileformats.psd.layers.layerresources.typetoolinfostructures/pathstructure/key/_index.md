---
title: PathStructure.Key
second_title: Aspose.PSD untuk Referensi .NET API
description: PathStructure Properti. Mendapat kunci struktur.
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Mendapat kunci struktur.

```csharp
public override int Key { get; }
```

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


