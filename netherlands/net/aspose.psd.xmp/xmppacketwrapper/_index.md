---
title: Class XmpPacketWrapper
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Xmp.XmpPacketWrapper klas. Bevat geserialiseerd xmppakket inclusief header en trailer.
type: docs
weight: 6290
url: /nl/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Bevat geserialiseerd xmp-pakket inclusief header en trailer.

```csharp
public class XmpPacketWrapper
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initialiseert een nieuw exemplaar van het`XmpPacketWrapper` klasse. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initialiseert een nieuw exemplaar van het`XmpPacketWrapper` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Haalt de headerverwerkingsinstructie op. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Haalt de XMP-meta op. Optioneel. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Krijgt een reeks van[`XmpPackage`](../xmppackage/) binnen XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Krijgt het aantal pakketten binnen de XMP-structuur. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Haalt de instructie voor het verwerken van de trailer op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Voegt het pakket toe. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Verwijdert alles[`XmpPackage`](../xmppackage/) binnen XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Bepaalt of het pakket aanwezig is in de xmp-wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Krijgt pakket op naamruimte-URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Verwijdert het XMP-pakket. |

### Opmerkingen

Een wrapper bestaande uit een paar XML-verwerkingsinstructies (PI's) kan rond het rdf:RDF-element worden geplaatst.

### Zie ook

* naamruimte [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* montage [Aspose.PSD](../../)


