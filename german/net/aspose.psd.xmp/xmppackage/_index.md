---
title: "Klasse XmpPackage"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Xmp.XmpPackage Klasse. Definiert die Klasse XmpPackage, die die Basisabstraktion für ein XMP-Paket darstellt."
type: docs
weight: 6770
url: /de/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

Definiert die Klasse XmpPackage, die die Grundabstraktion für ein XMP‑Paket darstellt.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Liest die Schlüssel im XMP-Paket. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Liest die Namespace-URI. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Liest das Präfix. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Liest den XML-Namespace. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Fügt den Wert hinzu. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Löscht diese Instanz. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Bestimmt, ob der angegebene Schlüssel enthalten ist. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Konvertiert den XMP-Wert in die XML-Darstellung. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Legt den Wert fest. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Legt den XMP-Typwert fest. |

### Siehe auch

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


