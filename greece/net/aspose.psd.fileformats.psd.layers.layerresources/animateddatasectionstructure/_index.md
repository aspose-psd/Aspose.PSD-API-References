---
title: Class AnimatedDataSectionStructure
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure τάξη. Η ενότητα με κινούμενα δεδομένα.
type: docs
weight: 2300
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
## AnimatedDataSectionStructure class

Η ενότητα με κινούμενα δεδομένα.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Λαμβάνει ή ορίζει τις δομές της ενότητας κινούμενων δεδομένων. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Λαμβάνει το κλειδί δομής. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του κλειδιού. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | Λαμβάνει το[`OSTypeStructure`](../ostypestructure/) μήκος σε byte. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Λαμβάνει το μήκος της κεφαλίδας. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | Προσδιορίζει το κλειδί δομής των AnD. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τον τρόπο ρύθμισης/ενημέρωσης του χρόνου καθυστέρησης στο πλαίσιο της γραμμής χρόνου των κινούμενων δεδομένων.

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

            // Δημιουργεί την εγγραφή καθυστέρησης καρέ με τιμή 100 centi-second που ισούται με 1 δευτερόλεπτο.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // ορισμός χρόνου σε εκατοστά του δευτερολέπτου.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Δείτε επίσης

* class [OSTypeStructure](../ostypestructure/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


