---
title: AnimatedDataSectionStructure.Items
second_title: Aspose.PSD für .NET-API-Referenz
description: AnimatedDataSectionStructure eigendom. Ruft die animierten Datenabschnittsstrukturen ab oder legt sie fest.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/
---
## AnimatedDataSectionStructure.Items property

Ruft die animierten Datenabschnittsstrukturen ab oder legt sie fest.

```csharp
public OSTypeStructure[] Items { get; }
```

### Beispiele

Der folgende Code zeigt, wie die Verzögerungszeit im Zeitachsenrahmen von animierten Daten festgelegt/aktualisiert wird.

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

            // Erstellt den Frame-Delay-Record mit dem Wert 100 Zenti-Sekunde, was 1 Sekunde entspricht.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // Zeit in Centisekunden einstellen.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Siehe auch

* class [OSTypeStructure](../../ostypestructure/)
* class [AnimatedDataSectionStructure](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../animateddatasectionstructure/)
* Montage [Aspose.PSD](../../../)


