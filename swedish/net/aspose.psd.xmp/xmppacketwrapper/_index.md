---
title: "Klass XmpPacketWrapper"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Xmp.XmpPacketWrapper-klass. Innehåller serialiserat xmp-paket inklusive huvud och trailer."
type: docs
weight: 6790
url: /sv/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Innehåller serialiserat xmp-paket inklusive header och trailer.

```csharp
public class XmpPacketWrapper
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initierar en ny instans av klassen `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initierar en ny instans av klassen `XmpPacketWrapper`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Hämtar huvudets bearbetningsinstruktion. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Hämtar XMP-metadata. Valfritt. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Hämtar en array av [`XmpPackage`](../xmppackage/) i XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Hämtar antalet paket i XMP-strukturen. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Hämtar trailer‑bearbetningsinstruktionen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Lägger till paketet. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Tar bort alla [`XmpPackage`](../xmppackage/) i XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Bestämmer om paketet finns i xmp-wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Hämtar paketet efter namnrymds‑URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Tar bort XMP-paketet. |

## Anmärkningar

En wrapper bestående av ett par XML‑bearbetningsinstruktioner (PI) kan placeras runt rdf:RDF‑elementet.

### Se även

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


