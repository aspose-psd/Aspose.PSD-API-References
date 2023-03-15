---
title: Class GaussianBlurSmartFilter
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.SmartFilters.GaussianBlurSmartFilter τάξη. Το έξυπνο φίλτρο GaussianBlur.
type: docs
weight: 3430
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---
## GaussianBlurSmartFilter class

Το έξυπνο φίλτρο GaussianBlur.

```csharp
public sealed class GaussianBlurSmartFilter : SmartFilter
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [GaussianBlurSmartFilter](gaussianblursmartfilter/)() | Αρχικοποιεί μια νέα παρουσία του`GaussianBlurSmartFilter` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/blendmode/) { get; set; } | Λαμβάνει ή ρυθμίζει τη λειτουργία ανάμειξης. |
| override [FilterId](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filterid/) { get; } | Λαμβάνει το αναγνωριστικό τύπου έξυπνου φίλτρου. |
| [IsEnabled](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/isenabled/) { get; set; } | Λαμβάνει ή ορίζει την κατάσταση ενεργοποίησης του έξυπνου φίλτρου. |
| override [Name](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/name/) { get; } | Λαμβάνει το όνομα έξυπνου φίλτρου. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/opacity/) { get; set; } | Λαμβάνει ή ορίζει την τιμή αδιαφάνειας του έξυπνου φίλτρου. |
| [Radius](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/radius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα του έξυπνου φίλτρου Gauss. |
| [SourceDescriptor](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/sourcedescriptor/) { get; } | Η δομή της περιγραφής πηγής με δεδομένα έξυπνου φίλτρου. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/apply/)(RasterImage) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο[`RasterImage`](../../aspose.psd/rasterimage/) εικόνα. |
| [ApplyToMask](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/applytomask/)(Layer) | Εφαρμόζει το τρέχον φίλτρο στην είσοδο[`Layer`](../../aspose.psd.fileformats.psd.layers/layer/) δεδομένα μάσκας. |
| [Clone](../../aspose.psd.fileformats.psd.layers.smartfilters/smartfilter/clone/)() | Κάνει τον κλώνο κατά μέλος της τρέχουσας παρουσίας του τύπου. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [FilterType](../../aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/filtertype/) | Το αναγνωριστικό του τρέχοντος έξυπνου φίλτρου. |

### Παραδείγματα

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

    // Επεξεργασία έξυπνων φίλτρων
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../aspose.psd.fileformats.psd.layers.smartfilters/)
* συνέλευση [Aspose.PSD](../../)


