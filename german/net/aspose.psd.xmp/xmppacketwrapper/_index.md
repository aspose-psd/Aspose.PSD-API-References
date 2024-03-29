---
title: Class XmpPacketWrapper
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.Xmp.XmpPacketWrapper klas. Enthält serialisiertes xmpPaket einschließlich Header und Trailer.
type: docs
weight: 6290
url: /de/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Enthält serialisiertes xmp-Paket einschließlich Header und Trailer.

```csharp
public class XmpPacketWrapper
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initialisiert eine neue Instanz von`XmpPacketWrapper` Klasse. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initialisiert eine neue Instanz von`XmpPacketWrapper` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Ruft die Header-Verarbeitungsanweisung ab. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Ruft das XMP-Meta ab. Optional. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Ruft ein Array von ab[`XmpPackage`](../xmppackage/) innerhalb von XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Ruft die Anzahl der Pakete innerhalb der XMP-Struktur ab. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Ruft die Trailer-Verarbeitungsanweisung ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Fügt das Paket hinzu. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Entfernt alle[`XmpPackage`](../xmppackage/) innerhalb von XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Bestimmt, ob das Paket im xmp-Wrapper vorhanden ist. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Ruft Paket nach Namespace-URI ab. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Entfernt das XMP-Paket. |

### Bemerkungen

Um das rdf:RDF-Element kann ein Wrapper platziert werden, der aus zwei XML-Verarbeitungsanweisungen (PIs) besteht.

### Siehe auch

* namensraum [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* Montage [Aspose.PSD](../../)


