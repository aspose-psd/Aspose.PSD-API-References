---
title: Class ObjectArrayStructure
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.ObjectArrayStructure class. Defines the ObjectArrayStructure class that usually holds UnitArrayStructure array. It is used in the PSD file resources such as PlLd Resource and SoLd Resource
type: docs
weight: 3390
url: /net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---
{{< psd/tize >}}
## ObjectArrayStructure class

Defines the ObjectArrayStructure class that usually holds [`UnitArrayStructure`](../unitarraystructure/) array. It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

```csharp
public sealed class ObjectArrayStructure : OSTypeStructure
```

## Constructors

| Name | Description |
| --- | --- |
| [ObjectArrayStructure](objectarraystructure/#constructor_1)(string, string, OSTypeStructure[]) | Initializes a new instance of the `ObjectArrayStructure` class. |
| [ObjectArrayStructure](objectarraystructure/#constructor)(int, ClassID, ClassID, string, OSTypeStructure[]) | Initializes a new instance of the `ObjectArrayStructure` class. |

## Properties

| Name | Description |
| --- | --- |
| [ClassID](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classid/) { get; set; } | Gets or sets the object array class ID. |
| [ClassName](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/classname/) { get; set; } | Gets or sets the object array class name. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/key/) { get; } | Gets the object array structure key. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Gets or sets the key name. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/length/) { get; } | Gets the [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes. |
| [StructureCount](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurecount/) { get; } | Gets the object array substructure count. |
| [Structures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structures/) { get; set; } | Gets or sets a copy of an array of structures. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Gets the header length. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Saves the structure to the specified stream container. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Saves the structure to the specified stream container. |

## Fields

| Name | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/structurekey/) | Identifies the 'ObAr' structure key. |

## Examples

The following code demonstrates the support of the ObAr and UnFl signatures.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

var sourceFilePath = "LayeredSmartObjects8bit2.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    UnitArrayStructure verticalStructure = null;
    foreach (Layer imageLayer in image.Layers)
    {
        foreach (var imageResource in imageLayer.Resources)
        {
            var resource = imageResource as PlLdResource;
            if (resource != null && resource.IsCustom)
            {
                foreach (OSTypeStructure structure in resource.Items)
                {
                    if (structure.KeyName.ClassName == "customEnvelopeWarp")
                    {
                        AssertAreEqual(typeof(DescriptorStructure), structure.GetType());
                        var custom = (DescriptorStructure)structure;
                        AssertAreEqual(custom.Structures.Length, 1);
                        var mesh = custom.Structures[0];
                        AssertAreEqual(typeof(ObjectArrayStructure), mesh.GetType());
                        var meshObjectArray = (ObjectArrayStructure)mesh;
                        AssertAreEqual(meshObjectArray.Structures.Length, 2);
                        var vertical = meshObjectArray.Structures[1];
                        AssertAreEqual(typeof(UnitArrayStructure), vertical.GetType());
                        verticalStructure = (UnitArrayStructure)vertical;
                        AssertAreEqual(verticalStructure.UnitType, UnitTypes.Pixels);
                        AssertAreEqual(verticalStructure.ValueCount, 16);

                        break;
                    }
                }
            }
        }
    }

    AssertAreEqual(true, verticalStructure != null);
}
```

### See Also

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


