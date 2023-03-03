---
title: PathStructure.Length
second_title: Aspose.PSD untuk Referensi .NET API
description: PathStructure Properti. MendapatkanOSTypeStructure panjang dalam byte.
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Mendapatkan[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) panjang dalam byte.

```csharp
public override int Length { get; }
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


