---
title: Class PathStructure
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure kelas. Struktur jalur.
type: docs
weight: 3220
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
## PathStructure class

Struktur jalur.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | Menginisialisasi instance baru dari`PathStructure` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Mendapat kunci struktur. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Mendapat atau menyetel nama kunci. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | Mendapatkan[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) panjang dalam byte. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Mendapat atau menyetel jalur. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Mendapat atau menyetel awalan jalur. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Mendapatkan panjang tajuk. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Menyimpan struktur ke wadah aliran yang ditentukan. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Menyimpan struktur ke wadah aliran yang ditentukan. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Mengidentifikasi kunci struktur. |

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

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* perakitan [Aspose.PSD](../../)


