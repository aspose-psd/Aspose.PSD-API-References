---
title: Class AnimatedDataSectionStructure
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure classe. La sezione con i dati animati.
type: docs
weight: 2300
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
## AnimatedDataSectionStructure class

La sezione con i dati animati.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Ottiene o imposta le strutture animate della sezione dati. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Ottiene la chiave della struttura. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Ottiene o imposta il nome della chiave. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | Ottiene il[`OSTypeStructure`](../ostypestructure/) lunghezza in byte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Ottiene la lunghezza dell'intestazione. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Salva la struttura nel contenitore del flusso specificato. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Salva la struttura nel contenitore del flusso specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | Identifica la chiave di struttura di AnDs. |

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

* class [OSTypeStructure](../ostypestructure/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


