---
title: AnimatedDataSectionStructure.Items
second_title: Aspose.PSD per riferimento API .NET
description: AnimatedDataSectionStructure proprietà. Ottiene o imposta le strutture animate della sezione dati.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/
---
## AnimatedDataSectionStructure.Items property

Ottiene o imposta le strutture animate della sezione dati.

```csharp
public OSTypeStructure[] Items { get; }
```

### Esempi

Il codice seguente mostra come impostare/aggiornare il tempo di ritardo nel frame della sequenza temporale dei dati animati.

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

            // Crea il record di ritardo del fotogramma con valore 100 centisecondi che è uguale a 1 secondo.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // imposta il tempo in centisecondi.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Guarda anche

* class [OSTypeStructure](../../ostypestructure/)
* class [AnimatedDataSectionStructure](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../animateddatasectionstructure/)
* assemblea [Aspose.PSD](../../../)


