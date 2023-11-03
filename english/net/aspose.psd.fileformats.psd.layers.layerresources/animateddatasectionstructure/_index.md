---
title: Class AnimatedDataSectionStructure
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure class. The section with animated data
type: docs
weight: 2400
url: /net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure class

The section with animated data.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Properties

| Name | Description |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Gets or sets the animated data section structures. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Gets the structure key. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Gets or sets the key name. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | Gets the [`OSTypeStructure`](../ostypestructure/) length in bytes. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Gets the header length. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Saves the structure to the specified stream container. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Saves the structure to the specified stream container. |

## Fields

| Name | Description |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | Identifies the structure key of AnDs. |

## Examples

The following code demonstrates how to set/update delay time in the timeline frame of animated data.

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // Creates the frame delay record with value 100 centi-second that is equal to 1 second.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### See Also

* class [OSTypeStructure](../ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


