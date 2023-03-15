---
title: Class XmpPackage
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Xmp.XmpPackage klass. Definierar XmpPackageklassen som representerar basabstraktion för XMPpaket.
type: docs
weight: 6270
url: /sv/net/aspose.psd.xmp/xmppackage/
---
## XmpPackage class

Definierar XmpPackage-klassen som representerar basabstraktion för XMP-paket.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Hämtar eller ställer inObject med den angivna nyckeln. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Hämtar nycklarna i XMP-paketet. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Hämtar namnutrymmets URI. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Får prefixet. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Hämtar XML-namnutrymmet. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Lägger till värdet. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Rensar denna instans. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Bestämmer om den angivna nyckeln innehåller nyckel. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Returnerar en uppräkning som itererar genom samlingen. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Konverterar XMP-värdet till XML-representationen. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Ta bort värdet med den angivna nyckeln. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Anger värdet. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Ställer in XMP-typvärdet. |

### Se även

* interface [IXmlValue](../ixmlvalue/)
* namnutrymme [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* hopsättning [Aspose.PSD](../../)


