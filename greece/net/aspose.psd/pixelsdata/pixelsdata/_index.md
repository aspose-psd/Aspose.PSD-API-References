---
title: "PixelsData.PixelsData"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής PixelsData. Δημιουργεί ένα νέο στιγμιότυπο της κλάσης PixelsData"
type: docs
weight: 10
url: /el/net/aspose.psd/pixelsdata/pixelsdata/
---
{{< psd/tize >}}
## PixelsData() {#constructor}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`PixelsData`](../).

```csharp
public PixelsData()
```

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

* class [PixelsData](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## PixelsData(int[], Rectangle) {#constructor_1}

Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [`PixelsData`](../).

```csharp
public PixelsData(int[] pixels, Rectangle bounds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | Int32[] | Τα δεδομένα εικονοστοιχείων. |
| όρια | Rectangle | Το ορθογώνιο των ορίων των εικονοστοιχείων. |

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

* struct [Rectangle](../../rectangle/)
* class [PixelsData](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


