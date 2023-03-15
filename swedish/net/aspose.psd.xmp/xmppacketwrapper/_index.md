---
title: Class XmpPacketWrapper
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Xmp.XmpPacketWrapper klass. Innehåller serialiserat xmppaket inklusive header och trailer.
type: docs
weight: 6290
url: /sv/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Innehåller serialiserat xmp-paket inklusive header och trailer.

```csharp
public class XmpPacketWrapper
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initierar en ny instans av`XmpPacketWrapper` class. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initierar en ny instans av`XmpPacketWrapper` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Hämtar bearbetningsinstruktionen för rubriken. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Hämtar XMP-meta. Valfritt. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Får array av[`XmpPackage`](../xmppackage/) inuti XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Får mängden paket i XMP-strukturen. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Får bearbetningsinstruktionen för trailern. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Lägger till paketet. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Tar bort alla[`XmpPackage`](../xmppackage/) inuti XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Avgör om paketet finns i xmp wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Hämtar paket med namnutrymmes-URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Tar bort XMP-paketet. |

### Anmärkningar

Ett omslag som består av ett par XML-bearbetningsinstruktioner (PI:er) kan placeras runt rdf:RDF-elementet.

### Se även

* namnutrymme [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* hopsättning [Aspose.PSD](../../)


