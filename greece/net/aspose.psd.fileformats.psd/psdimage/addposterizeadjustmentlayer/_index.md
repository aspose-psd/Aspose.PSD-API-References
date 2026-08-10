---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "PsdImage μέθοδος. Προσθέτει Posterize Adjustment layer"
type: docs
weight: 430
url: /el/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

Προσθέτει το επίπεδο προσαρμογής Posterize.

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### Τιμή Επιστροφής

PosterizeLayer αντίγραφο.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα προσθήκης του PosterizeAdjustmentLayer μέσω του PsdImage.

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// Ελέγξτε τις αποθηκευμένες αλλαγές
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Δείτε επίσης

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


