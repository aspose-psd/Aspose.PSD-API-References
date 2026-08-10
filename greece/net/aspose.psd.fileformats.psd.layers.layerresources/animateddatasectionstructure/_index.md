---
title: "Κλάση AnimatedDataSectionStructure"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure. Η ενότητα με κινούμενα δεδομένα."
type: docs
weight: 2510
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
{{< psd/tize >}}
## AnimatedDataSectionStructure class

Η ενότητα με κινούμενα δεδομένα.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Λαμβάνει ή ορίζει τις δομές της ενότητας κινούμενων δεδομένων. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Λαμβάνει το κλειδί της δομής. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Λαμβάνει ή ορίζει το όνομα του κλειδιού. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | Λαμβάνει το μήκος σε bytes του [`OSTypeStructure`](../ostypestructure/). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Λαμβάνει το μήκος της κεφαλίδας. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Αποθηκεύει τη δομή στο καθορισμένο κοντέινερ ροής. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | Αναγνωρίζει το κλειδί δομής του AnDs. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ορίσετε/ενημερώσετε τον χρόνο καθυστέρησης στο πλαίσιο της χρονογραμμής των κινητών δεδομένων.

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

            // Δημιουργεί την εγγραφή καθυστέρησης πλαισίου με τιμή 100 εκατοδευτερόλεπτα, που ισούται με 1 δευτερόλεπτο.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Δείτε επίσης

* class [OSTypeStructure](../ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


