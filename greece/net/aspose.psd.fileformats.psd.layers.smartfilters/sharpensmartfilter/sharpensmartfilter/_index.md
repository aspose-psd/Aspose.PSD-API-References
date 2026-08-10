---
title: "SharpenSmartFilter.SharpenSmartFilter"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής SharpenSmartFilter. Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SharpenSmartFilter"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter() {#constructor}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter()
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του SharpenSmartFilter.

```csharp
[C#]

string sourceFile = "sharpen_source.psd";
string outputPsd = "sharpen_output.psd";
string outputPng = "sharpen_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFile))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // επεξεργασία έξυπνων φίλτρων
    SharpenSmartFilter sharpen = (SharpenSmartFilter)smartObj.SmartFilters.Filters[0];

    // έλεγχος τιμών φίλτρου
    AssertAreEqual(BlendMode.Normal, sharpen.BlendMode);
    AssertAreEqual(100d, sharpen.Opacity);
    AssertAreEqual(true, sharpen.IsEnabled);

    // ενημέρωση τιμών φίλτρου
    sharpen.BlendMode = BlendMode.Divide;
    sharpen.Opacity = 75;
    sharpen.IsEnabled = false;

    // προσθήκη νέων στοιχείων φίλτρου
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new SharpenSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // εφαρμογή αλλαγών
    smartObj.SmartFilters.UpdateResourceValues();
    smartObj.UpdateModifiedContent();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Δείτε επίσης

* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)

---

## SharpenSmartFilter(DescriptorStructure) {#constructor_1}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`SharpenSmartFilter`](../).

```csharp
public SharpenSmartFilter(DescriptorStructure sourceDescriptor)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceDescriptor | DescriptorStructure | Η δομή περιγραφέα με πληροφορίες έξυπνου φίλτρου. |

### Δείτε επίσης

* class [DescriptorStructure](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/)
* class [SharpenSmartFilter](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../../)


