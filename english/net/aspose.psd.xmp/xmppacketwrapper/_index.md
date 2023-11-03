---
title: Class XmpPacketWrapper
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.Xmp.XmpPacketWrapper class. Contains serialized xmp package including header and trailer
type: docs
weight: 6510
url: /net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Contains serialized xmp package including header and trailer.

```csharp
public class XmpPacketWrapper
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Initializes a new instance of the `XmpPacketWrapper` class. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Initializes a new instance of the `XmpPacketWrapper` class. |

## Properties

| Name | Description |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Gets the header processing instruction. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Gets the XMP meta. Optional. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Gets array of [`XmpPackage`](../xmppackage/) inside XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Gets amount of packages inside XMP structure. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Gets the trailer processing instruction. |

## Methods

| Name | Description |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Adds the package. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Removes all [`XmpPackage`](../xmppackage/) inside XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Determines whethere package is exist in xmp wrapper. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Gets package by namespace URI. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Removes the XMP package. |

## Remarks

A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.

### See Also

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


