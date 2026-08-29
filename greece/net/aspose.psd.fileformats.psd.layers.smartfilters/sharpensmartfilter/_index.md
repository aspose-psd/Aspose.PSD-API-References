---
title: "Κλάση SharpenSmartFilter"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.SharpenSmartFilter class. Το φίλτρο Sharpen"
type: docs
weight: 3870
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/
---
{{< psd/tize >}}
## SharpenSmartFilter class

Το έξυπνο φίλτρο Sharpen.

```csharp
public sealed class SharpenSmartFilter : SmartFilter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SharpenSmartFilter](sharpensmartfilter/#constructor)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `SharpenSmartFilter`. |
| [SharpenSmartFilter](sharpensmartfilter/#constructor_1)(DescriptorStructure) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `SharpenSmartFilter`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filterid/) { get; } | Λαμβάνει το αναγνωριστικό τύπου του έξυπνου φίλτρου. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Λαμβάνει ή ορίζει την κατάσταση ενεργοποίησης του έξυπνου φίλτρου. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/name/) { get; } | Λαμβάνει το όνομα του έξυπνου φίλτρου. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Η δομή περιγραφέα πηγής με δεδομένα έξυπνου φίλτρου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο εικόνας [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Εφαρμόζει το τρέχον φίλτρο στα δεδομένα μάσκας της εισόδου [`Layer`](../../aspose.psd.fileformats.psd.layers/layer/). |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Δημιουργεί το κλώνο μέλους της τρέχουσας εμφάνισης του τύπου. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/sharpensmartfilter/filtertype/) | Το αναγνωριστικό του τρέχοντος έξυπνου φίλτρου. |

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

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


