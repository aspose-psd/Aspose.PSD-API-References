---
title: "Κλάση AddNoiseSmartFilter"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.AddNoiseSmartFilter κλάση. Το έξυπνο φίλτρο AddNoise"
type: docs
weight: 3830
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/
---
{{< psd/tize >}}
## AddNoiseSmartFilter class

Το έξυπνο φίλτρο AddNoise.

```csharp
public sealed class AddNoiseSmartFilter : SmartFilter
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [AddNoiseSmartFilter](addnoisesmartfilter/)() | Αρχικοποιεί μια νέα εμφάνιση της κλάσης `AddNoiseSmartFilter`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AmountNoise](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/amountnoise/) { get; set; } | Λαμβάνει ή ορίζει την ποσότητα της τιμής θορύβου. |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης. |
| [Distribution](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution/) { get; set; } | Λαμβάνει ή ορίζει την κατανομή του φίλτρου θορύβου. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filterid/) { get; } | Λαμβάνει το αναγνωριστικό τύπου του έξυπνου φίλτρου. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Λαμβάνει ή ορίζει την κατάσταση ενεργοποίησης του έξυπνου φίλτρου. |
| [IsMonochromatic](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/ismonochromatic/) { get; set; } | Λαμβάνει ή ορίζει την τιμή του μονοχρωματικού. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/name/) { get; } | Λαμβάνει το όνομα του έξυπνου φίλτρου. |
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
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/filtertype/) | Το αναγνωριστικό του τρέχοντος έξυπνου φίλτρου. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει την υποστήριξη της διεπαφής έξυπνων φίλτρων.

```csharp
[C#]

string sourceFilte = "r2_SmartFilters.psd";
string outputPsd = "out_r2_SmartFilters.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (var image = (PsdImage)Image.Load(sourceFilte))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    // επεξεργασία έξυπνων φίλτρων
    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // έλεγχος τιμών φίλτρου
    AssertAreEqual(3.1, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Dissolve, gaussianBlur.BlendMode);
    AssertAreEqual(90d, gaussianBlur.Opacity);
    AssertAreEqual(true, gaussianBlur.IsEnabled);

    // ενημέρωση τιμών φίλτρου
    gaussianBlur.Radius = 1;
    gaussianBlur.BlendMode = BlendMode.Divide;
    gaussianBlur.Opacity = 75;
    gaussianBlur.IsEnabled = false;
    AddNoiseSmartFilter addNoise = (AddNoiseSmartFilter)smartObj.SmartFilters.Filters[1];
    addNoise.Distribution = NoiseDistribution.Uniform;

    // προσθήκη νέων στοιχείων φίλτρου
    var filters = new List<SmartFilter>(smartObj.SmartFilters.Filters);
    filters.Add(new GaussianBlurSmartFilter());
    filters.Add(new AddNoiseSmartFilter());
    smartObj.SmartFilters.Filters = filters.ToArray();

    // εφαρμογή αλλαγών
    smartObj.SmartFilters.UpdateResourceValues();

    // Εφαρμογή φίλτρων
    smartObj.SmartFilters.Filters[0].Apply(image.Layers[2]);
    smartObj.SmartFilters.Filters[4].ApplyToMask(image.Layers[2]);

    image.Save(outputPsd);
}

using (var image = (PsdImage)Image.Load(outputPsd))
{
    SmartObjectLayer smartObj = (SmartObjectLayer)image.Layers[1];

    GaussianBlurSmartFilter gaussianBlur = (GaussianBlurSmartFilter)smartObj.SmartFilters.Filters[0];

    // έλεγχος τιμών φίλτρου
    AssertAreEqual(1d, gaussianBlur.Radius);
    AssertAreEqual(BlendMode.Divide, gaussianBlur.BlendMode);
    AssertAreEqual(75d, gaussianBlur.Opacity);
    AssertAreEqual(false, gaussianBlur.IsEnabled);

    AssertAreEqual(true, smartObj.SmartFilters.Filters[5] is GaussianBlurSmartFilter);
    AssertAreEqual(true, smartObj.SmartFilters.Filters[6] is AddNoiseSmartFilter);
}
```

### Δείτε επίσης

* class [SmartFilter](../smartfilter/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* assembly [Aspose.PSD](../../)


