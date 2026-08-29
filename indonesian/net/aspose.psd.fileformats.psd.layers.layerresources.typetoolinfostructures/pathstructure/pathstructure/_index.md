---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor PathStructure. Menginisialisasi sebuah instance baru dari kelas PathStructure"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Menginisialisasi sebuah instance baru dari kelas [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keyName | ClassID | Nama kunci. |

## Contoh

Kode berikut menunjukkan kemampuan memuat file dengan struktur PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Lihat Juga

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


