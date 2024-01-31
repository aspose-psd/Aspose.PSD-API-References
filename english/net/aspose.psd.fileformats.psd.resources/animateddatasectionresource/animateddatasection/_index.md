---
title: AnimatedDataSectionResource.AnimatedDataSection
second_title: Aspose.PSD for .NET API Reference
description: AnimatedDataSectionResource property. Gets or sets the animated data section structure
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/
---
{{< psd/tize >}}
## AnimatedDataSectionResource.AnimatedDataSection property

Gets or sets the animated data section structure.

```csharp
public AnimatedDataSectionStructure AnimatedDataSection { get; }
```

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

* class [AnimatedDataSectionStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/)
* class [AnimatedDataSectionResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


