---
title: Class XmpPacketWrapper
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.Xmp.XmpPacketWrapper kelas. Berisi paket xmp serial termasuk header dan trailer.
type: docs
weight: 6290
url: /id/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Berisi paket xmp serial termasuk header dan trailer.

```csharp
public class XmpPacketWrapper
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Menginisialisasi instance baru dari`XmpPacketWrapper` kelas. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Menginisialisasi instance baru dari`XmpPacketWrapper` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Mendapat instruksi pemrosesan tajuk. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Mendapat meta XMP. Opsional. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Mendapat berbagai[`XmpPackage`](../xmppackage/) di dalam XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Mendapat jumlah paket di dalam struktur XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Mendapat instruksi pemrosesan trailer. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Menambahkan paket. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Menghapus semua[`XmpPackage`](../xmppackage/) di dalam XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Menentukan apakah paket ada di xmp wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Mendapat paket dengan namespace URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Menghapus paket XMP. |

### Perkataan

Pembungkus yang terdiri dari sepasang instruksi pemrosesan XML (PI) dapat ditempatkan di sekitar elemen rdf:RDF.

### Lihat juga

* ruang nama [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* perakitan [Aspose.PSD](../../)


