---
title: AnimatedDataSectionResource.AnimatedDataSection
second_title: Aspose.PSD för .NET API-referens
description: AnimatedDataSectionResource fast egendom. Hämtar eller ställer in den animerade datasektionsstrukturen.
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/
---
## AnimatedDataSectionResource.AnimatedDataSection property

Hämtar eller ställer in den animerade datasektionsstrukturen.

```csharp
public AnimatedDataSectionStructure AnimatedDataSection { get; }
```

### Exempel

Följande kod visar hur man ställer in/uppdaterar fördröjningstid i tidslinjeramen för animerade data.

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

            // Skapar ramfördröjningsposten med värdet 100 centi-sekund som är lika med 1 sekund.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // ställ in tiden i centi-sekunder.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Se även

* class [AnimatedDataSectionStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/)
* class [AnimatedDataSectionResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../animateddatasectionresource/)
* hopsättning [Aspose.PSD](../../../)


