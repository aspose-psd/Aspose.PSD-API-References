---
title: Class NameStructure
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure class. The Name structure key 0x6E616D65 which spells name in ASCII is a simple structure used to store a Unicode or Pascalstyle string representing the name of an element such as a layer path or adjustment
type: docs
weight: 3540
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

## Examples

The following code demonstrates the support of NameStructure.

```csharp
[C#]

string inputFile = "Mixer_ipad_Hand_W_crash.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(inputFile, new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    //// File is loaded successfully

    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);

    // Save the test file without changes
    psdImage.Save(outputFile);

    //// File should be opened in PS without mistakes
}

// Check that the structures of Lighting effects are saved correctly
using (var psdImage = (PsdImage)Image.Load(
           outputFile,
           new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### See Also

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


