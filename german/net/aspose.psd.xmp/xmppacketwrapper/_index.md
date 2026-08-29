---
title: "Klasse XmpPacketWrapper"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Xmp.XmpPacketWrapper class. Enthält ein serialisiertes XMP-Paket inklusive Header und Trailer"
type: docs
weight: 6790
url: /de/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Enthält ein serialisiertes XMP‑Paket einschließlich Header und Trailer.

```csharp
public class XmpPacketWrapper
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initialisiert eine neue Instanz der `XmpPacketWrapper`-Klasse. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initialisiert eine neue Instanz der `XmpPacketWrapper`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Liefert die Header-Verarbeitungsanweisung. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Liefert die XMP-Metadaten. Optional. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Liefert ein Array von [`XmpPackage`](../xmppackage/) innerhalb von XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Liefert die Anzahl der Pakete innerhalb der XMP-Struktur. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Liefert die Trailer-Verarbeitungsanweisung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Fügt das Paket hinzu. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Entfernt alle [`XmpPackage`](../xmppackage/) innerhalb von XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Bestimmt, ob ein Paket im XMP-Wrapper existiert. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Liefert das Paket nach Namespace-URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Entfernt das XMP-Paket. |

## Hinweise

Ein Wrapper, der aus einem Paar XML-Verarbeitungsanweisungen (PIs) besteht, kann um das rdf:RDF-Element herum platziert werden.

### Siehe auch

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


