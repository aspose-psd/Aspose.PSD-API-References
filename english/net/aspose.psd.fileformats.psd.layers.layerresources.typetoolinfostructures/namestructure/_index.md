---
title: Class NameStructure
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure class. The Name structure key 0x6E616D65 which spells name in ASCII is a simple structure used to store a Unicode or Pascalstyle string representing the name of an element such as a layer path or adjustment
type: docs
weight: 3530
url: /net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/
---
{{< psd/tize >}}
## NameStructure class

The Name structure (key: 0x6E616D65, which spells "name" in ASCII) is a simple structure used to store a Unicode or Pascal-style string representing the name of an element, such as a layer, path, or adjustment.

```csharp
public sealed class NameStructure : OSTypeStructure
```

## Constructors

| Name | Description |
| --- | --- |
| [NameStructure](namestructure/)(ClassID) | Initializes a new instance of the `NameStructure` class. |

## Properties

| Name | Description |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/key/) { get; } | Gets the key. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Gets or sets the key name. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/length/) { get; } | Gets the [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/value/) { get; set; } | Gets or sets the value of a Name structure. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Gets the header length. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Saves the structure to the specified stream container. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Saves the structure to the specified stream container. |

## Fields

| Name | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/structurekey/) | The Name structure key. |

### See Also

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


