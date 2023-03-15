---
title: Class AnimatedDataSectionResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Resources.AnimatedDataSectionResource klass. Pluginresursen för Animated Data Section.
type: docs
weight: 3630
url: /sv/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---
## AnimatedDataSectionResource class

Plug-in-resursen för Animated Data Section.

```csharp
public class AnimatedDataSectionResource : ResourceBlock
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AnimatedDataSection](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/) { get; } | Hämtar eller ställer in den animerade datasektionsstrukturen. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/datasize/) { get; } | Hämtar resursdatastorleken i byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Hämtar eller ställer in den unika identifieraren för resursen. |
| [KeyName](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/keyname/) { get; } | Resursnyckelns namn. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/minimalversion/) { get; } | Får den minsta nödvändiga PSD-versionen. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Hämtar eller ställer in resursnamnet. Pascal-sträng, vadderad för att göra storleken jämn (ett nollnamn består av två byte på 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Hämtar resurssignaturen. Bör alltid vara '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Hämtar resursblockstorleken i byte inklusive dess data. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Sparar resursblocket till den angivna strömmen. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validerar resursvärdena. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* hopsättning [Aspose.PSD](../../)


