---
title: "Sınıf XmpPacketWrapper"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Xmp.XmpPacketWrapper sınıfı. Başlık ve kuyruk dahil olmak üzere serileştirilmiş xmp paketini içerir."
type: docs
weight: 6820
url: /tr/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Başlık ve kuyruk dahil olmak üzere serileştirilmiş xmp paketini içerir.

```csharp
public class XmpPacketWrapper
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | `XmpPacketWrapper` sınıfının yeni bir örneğini başlatır. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | `XmpPacketWrapper` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Başlık işleme talimatını alır. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP meta verisini alır. İsteğe bağlı. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | XMP içinde [`XmpPackage`](../xmppackage/) dizisini alır. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP yapısı içindeki paket sayısını alır. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Kuyruk işleme talimatını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Paketi ekler. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | XMP içindeki tüm [`XmpPackage`](../xmppackage/) paketlerini kaldırır. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Paketin xmp sarmalayıcı içinde mevcut olup olmadığını belirler. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Paket'i namespace URI'sine göre alır. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP paketini kaldırır. |

## Açıklamalar

XML işleme talimatlarından (PI'lar) oluşan bir çift içeren bir sarmalayıcı, rdf:RDF öğesinin etrafına yerleştirilebilir.

### Ayrıca Bakınız

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


