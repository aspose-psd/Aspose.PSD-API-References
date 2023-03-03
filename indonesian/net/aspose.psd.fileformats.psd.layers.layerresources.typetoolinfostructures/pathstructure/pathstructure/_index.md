---
title: PathStructure.PathStructure
second_title: Aspose.PSD untuk Referensi .NET API
description: PathStructure konstruktor. Menginisialisasi instance baru dariPathStructure kelas.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Menginisialisasi instance baru dari[`PathStructure`](../) kelas.

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| keyName | ClassID | Nama kunci. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* perakitan [Aspose.PSD](../../../)


