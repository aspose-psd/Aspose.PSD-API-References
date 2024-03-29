---
title: Class XmpPackage
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Xmp.XmpPackage klas. Definiert die XmpPackageKlasse die die Basisabstraktion für das XMPPaket darstellt.
type: docs
weight: 6270
url: /de/net/aspose.psd.xmp/xmppackage/
---
## XmpPackage class

Definiert die XmpPackage-Klasse, die die Basisabstraktion für das XMP-Paket darstellt.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Ruft ab oder setzt dieObject mit dem angegebenen Schlüssel. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Ruft die Schlüssel im XMP-Paket ab. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Ruft den Namespace-URI ab. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Ruft das Präfix ab. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Ruft den XML-Namespace ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Fügt den Wert hinzu. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Löscht diese Instanz. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Bestimmt, ob der angegebene Schlüssel Schlüssel enthält. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Konvertiert den XMP-Wert in die XML-Darstellung. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Legt den Wert fest. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Legt den XMP-Typwert fest. |

### Siehe auch

* interface [IXmlValue](../ixmlvalue/)
* namensraum [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* Montage [Aspose.PSD](../../)


