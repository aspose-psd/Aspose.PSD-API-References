---
title: ISmartFilterRenderer.Render
second_title: Aspose.PSD για Αναφορά API .NET
description: ISmartFilterRenderer μέθοδος. Αποδίδει το τρέχον έξυπνο φίλτρο στα δεδομένα pixel.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters.rendering/ismartfilterrenderer/render/
---
## ISmartFilterRenderer.Render method

Αποδίδει το τρέχον έξυπνο φίλτρο στα δεδομένα pixel.

```csharp
public PixelsData Render(PixelsData pixelsData)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelsData | PixelsData | Τα δεδομένα των pixels. |

### Επιστρεφόμενη Αξία

Επιστρέφει επεξεργασμένα δεδομένα pixel.

### Παραδείγματα

Ο παρακάτω κώδικας σάς δείχνει πώς να δημιουργήσετε ένα προσαρμοσμένο έξυπνο φίλτρο που διαθέτει προσαρμοσμένη απόδοση απόδοσης.

```csharp
[C#]

public void CustomSmartFilterExample(string sourceFile = "psdnet1057.psd", string outputPsd = "out_psdnet1057.psd", string outputPng = "out_psdnet1057.png")
{
    // Εκκινεί το μη υποστηριζόμενο έξυπνο φίλτρο «Crystallize» στον πίνακα εισόδου
    SmartFilter[] InitUnknownSmartFilters(SmartFilter[] smartFilters)
    {
        // το αναγνωριστικό έξυπνου φίλτρου «Crystallize».
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

        // Εφαρμογή φίλτρου στο SmartObject
        smartLayer.UpdateModifiedContent();
        smartLayer.SmartFilters.UpdateResourceValues();

        // Εφαρμογή φίλτρου σε μάσκα στρώματος
        smartFilter.ApplyToMask(maskLayer);

        //Εφαρμογή φίλτρου σε στρώμα
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
        // το αναγνωριστικό έξυπνου φίλτρου «Crystallize».
        get { return 1131574132; }
    }

    public PixelsData Render(PixelsData pixelsData)
    {
        // λήψη δομής φίλτρου
        var filterDescriptor = (DescriptorStructure) this.SourceDescriptor.Structures[6];
        // λάβετε την τιμή του Crystallize Size
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

* class [PixelsData](../../../aspose.psd/pixelsdata/)
* interface [ISmartFilterRenderer](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.Rendering](../../ismartfilterrenderer/)
* συνέλευση [Aspose.PSD](../../../)


