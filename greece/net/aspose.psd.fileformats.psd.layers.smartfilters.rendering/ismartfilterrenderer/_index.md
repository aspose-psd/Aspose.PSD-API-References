---
title: "Διεπαφή ISmartFilterRenderer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Διεπαφή Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering.ISmartFilterRenderer. Η διεπαφή για έναν συγκεκριμένο renderer έξυπνου φίλτρου."
type: docs
weight: 3860
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/
---
{{< psd/tize >}}
## ISmartFilterRenderer interface

Η διεπαφή για έναν συγκεκριμένο renderer έξυπνου φίλτρου.

```csharp
public interface ISmartFilterRenderer
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Render](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/)(PixelsData) | Αποδίδει το τρέχον έξυπνο φίλτρο στα δεδομένα εικονοστοιχείων. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα προσαρμοσμένο έξυπνο φίλτρο με προσαρμοσμένο renderer.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Αρχικοποιεί το μη υποστηριζόμενο έξυπνο φίλτρο 'Crystallize' στον πίνακα εισόδου.
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // το αναγνωριστικό (ID) του έξυπνου φίλτρου 'Crystallize'.
        int id = 1131574132;

        for (int i = 0; i < smartFilters.Length; i++)
        {
            var smartFilter = smartFilters[i];
            if (smartFilter is UnknownSmartFilter && smartFilter.FilterId == id)
            {
                var customSmartFilterInstance = new CustomSmartFilterWithRenderer();
                customSmartFilterInstance.SourceDescriptor.Structures = smartFilter.SourceDescriptor.Structures;
                smartFilters[i] = customSmartFilterInstance;
            }
        }

        return smartFilters;
    }

    using (var image = (PsdImage) Image.Load(sourceFile))
    {
        SmartObjectLayer smartLayer = (SmartObjectLayer) image.Layers[1];
        Layer maskLayer = image.Layers[2];
        Layer regularLayer = image.Layers[3];

        smartLayer.SmartFilters.Filters = InitUnknownSmartFilters(smartLayer.SmartFilters.Filters);
        var smartFilter = smartLayer.SmartFilters.Filters[0];

        // Εφαρμόστε φίλτρο στο SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Εφαρμόστε φίλτρο στη μάσκα στρώσης
        smartFilter.ApplyToMask(maskLayer);

        //Εφαρμόστε φίλτρο στη στρώση
        smartFilter.Apply(regularLayer);

        image.Save(outputPsd);
        image.Save(outputPng, new PngOptions());
    }
}

public sealed class CustomSmartFilterWithRenderer : SmartFilter, ISmartFilterRenderer
{
    public override string Name
    {
        get { return "Custom 'Crystallize' smart filter\0"; }
    }

    public override int FilterId
    {
        // το αναγνωριστικό (ID) του έξυπνου φίλτρου 'Crystallize'.
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // λάβετε τη δομή του φίλτρου
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // λάβετε την τιμή του μεγέθους Crystallize
        var valueStructure = (IntegerStructure) filterDescriptor.Structures[0];

        for (int i = 0; i < pixelsData.Pixels.Length; i++)
        {
            if (i % valueStructure.Value == 0)
            {
                pixelsData.Pixels[i] = 0;
            }
        }

        return pixelsData;
    }
}
```

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../aspose.psd.fileformats.psd.layers.smartfilters.rendering/)
* assembly [Aspose.PSD](../../)


