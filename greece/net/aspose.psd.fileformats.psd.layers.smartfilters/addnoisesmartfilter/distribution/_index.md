---
title: AddNoiseSmartFilter.Distribution
second_title: Aspose.PSD για Αναφορά API .NET
description: AddNoiseSmartFilter ιδιοκτησία. Λαμβάνει ή ρυθμίζει την κατανομή του φίλτρου θορύβου.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.smartfilters/addnoisesmartfilter/distribution/
---
## AddNoiseSmartFilter.Distribution property

Λαμβάνει ή ρυθμίζει την κατανομή του φίλτρου θορύβου.

```csharp
public NoiseDistribution Distribution { get; set; }
```

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

* enum [NoiseDistribution](../../noisedistribution/)
* class [AddNoiseSmartFilter](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.SmartFilters](../../addnoisesmartfilter/)
* συνέλευση [Aspose.PSD](../../../)


