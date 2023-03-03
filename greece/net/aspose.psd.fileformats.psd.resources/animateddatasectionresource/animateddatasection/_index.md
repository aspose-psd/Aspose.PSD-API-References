---
title: AnimatedDataSectionResource.AnimatedDataSection
second_title: Aspose.PSD για Αναφορά API .NET
description: AnimatedDataSectionResource ιδιοκτησία. Λαμβάνει ή ορίζει τη δομή της ενότητας κινούμενων δεδομένων.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/
---
## AnimatedDataSectionResource.AnimatedDataSection property

Λαμβάνει ή ορίζει τη δομή της ενότητας κινούμενων δεδομένων.

```csharp
public AnimatedDataSectionStructure AnimatedDataSection { get; }
```

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

* class [AnimatedDataSectionStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/)
* class [AnimatedDataSectionResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Resources](../../animateddatasectionresource/)
* συνέλευση [Aspose.PSD](../../../)


