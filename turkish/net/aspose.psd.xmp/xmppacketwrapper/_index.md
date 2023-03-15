---
title: Class XmpPacketWrapper
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Xmp.XmpPacketWrapper sınıf. Başlık ve fragman dahil olmak üzere seri hale getirilmiş xmp paketini içerir.
type: docs
weight: 6290
url: /tr/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Başlık ve fragman dahil olmak üzere seri hale getirilmiş xmp paketini içerir.

```csharp
public class XmpPacketWrapper
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Yeni bir örneğini başlatır.`XmpPacketWrapper` sınıf. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Yeni bir örneğini başlatır.`XmpPacketWrapper` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Başlık işleme talimatını alır. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP metasını alır. İsteğe bağlı. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | dizisini alır[`XmpPackage`](../xmppackage/) XMP. içinde |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP yapısı içindeki paket miktarını alır. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Fragman işleme talimatını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Paketi ekler. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Tümünü kaldırır[`XmpPackage`](../xmppackage/) XMP. içinde |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Paketin xmp sarıcıda olup olmadığını belirler. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Paketi ad alanı URI'sine göre alır. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP paketini kaldırır. |

### Notlar

rdf:RDF öğesinin etrafına bir çift XML işleme talimatından (PI) oluşan bir sarmalayıcı yerleştirilebilir.

### Ayrıca bakınız

* ad alanı [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* toplantı [Aspose.PSD](../../)


