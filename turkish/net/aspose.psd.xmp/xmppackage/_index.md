---
title: "XmpPackage sınıfı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Xmp.XmpPackage sınıfı. XMP paketinin temel soyutlamasını temsil eden XmpPackage sınıfını tanımlar"
type: docs
weight: 6800
url: /tr/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

XMP paketinin temel soyutlamasını temsil eden XmpPackage sınıfını tanımlar.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Belirtilen anahtara sahip Nesneyi alır veya ayarlar. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | XMP paketindeki anahtarları alır. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Ad alanı URI'sını alır. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Ön eki alır. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | XML ad alanını alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Değeri ekler. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Bu örneği temizler. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Belirtilen anahtarın anahtar içerip içermediğini belirler. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | XMP değerini XML temsiline dönüştürür. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Belirtilen anahtara sahip değeri kaldır. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Değeri ayarlar. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | XMP tip değerini ayarlar. |

### Ayrıca Bakınız

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


