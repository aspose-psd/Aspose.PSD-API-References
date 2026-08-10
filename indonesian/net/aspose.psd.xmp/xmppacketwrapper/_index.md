---
title: "Kelas XmpPacketWrapper"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.Xmp.XmpPacketWrapper. Berisi paket xmp yang diserialkan termasuk header dan trailer."
type: docs
weight: 6790
url: /id/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Berisi paket xmp yang diserialisasi termasuk header dan trailer.

```csharp
public class XmpPacketWrapper
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Menginisialisasi instance baru dari kelas `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Menginisialisasi instance baru dari kelas `XmpPacketWrapper`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Mendapatkan instruksi pemrosesan header. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Mendapatkan meta XMP. Opsional. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Mendapatkan array [`XmpPackage`](../xmppackage/) di dalam XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Mendapatkan jumlah paket di dalam struktur XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Mendapatkan instruksi pemrosesan trailer. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Menambahkan paket. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Menghapus semua [`XmpPackage`](../xmppackage/) di dalam XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Menentukan apakah paket ada dalam pembungkus xmp. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Mendapatkan paket berdasarkan URI namespace. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Menghapus paket XMP. |

## Catatan

Sebuah pembungkus yang terdiri dari sepasang instruksi pemrosesan XML (PIs) dapat ditempatkan di sekitar elemen rdf:RDF.

### Lihat Juga

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


