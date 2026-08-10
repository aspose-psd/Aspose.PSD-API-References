---
title: "AnimatedDataSectionStructure.Items"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "AnimatedDataSectionStructure प्रॉपर्टी। एनिमेटेड डेटा सेक्शन संरचनाओं को प्राप्त या सेट करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure.Items property

एनिमेटेड डेटा सेक्शन संरचनाओं को प्राप्त करता है या सेट करता है।

```csharp
public OSTypeStructure[] Items { get; }
```

## उदाहरण

निम्नलिखित कोड दर्शाता है कि एनिमेटेड डेटा की टाइमलाइन फ्रेम में देरी समय को कैसे सेट/अपडेट किया जाए।

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

            // फ़्रेम देरी रिकॉर्ड बनाता है जिसका मान 100 सेंटी-सेकंड है, जो 1 सेकंड के बराबर है।
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### देखें भी

* class [OSTypeStructure](../../ostypestructure/)
* class [AnimatedDataSectionStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


