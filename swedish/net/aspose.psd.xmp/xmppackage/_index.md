---
title: "Klass XmpPackage"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Xmp.XmpPackage-klass. Definierar XmpPackage-klassen som representerar en grundläggande abstraktion för XMP-paket"
type: docs
weight: 6770
url: /sv/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

Definierar XmpPackage-klassen som representerar en grundläggande abstraktion för XMP-paket.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Hämtar eller anger objektet med den angivna nyckeln. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Hämtar nycklarna i XMP-paketet. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Hämtar namnrymdens URI. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Hämtar prefixet. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Hämtar XML-namnrymden. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Lägger till värdet. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Rensar denna instans. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Avgör om den angivna nyckeln innehåller nyckeln. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Konverterar XMP-värde till XML-representationen. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Ta bort värdet med den angivna nyckeln. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Ställer in värdet. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Ställer in XMP-typvärdet. |

### Se även

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


