---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "IfxsResource πεδίο. Το κλειδί πληροφοριών εργαλείου τύπου"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

Το κλειδί πληροφοριών του εργαλείου τύπου.

```csharp
public const int TypeToolKey;
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Το παράδειγμα έχει 2 ομάδες στρωμάτων με εφέ
    // Ομάδα στρώματος με ένα εφέ
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Ομάδα στρώματος με πολλά εφέ
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Λάβετε τον αριθμό των εφέ και επαληθεύστε την ποσότητά τους
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Ένα εφέ στο ομαδικό στρώμα βρίσκεται στον πόρο 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Δύο ή περισσότερα εφέ σε ένα ομαδικό στρώμα βρίσκονται στον πόρο 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Προσθέστε μια τρίτη σκιά σε ένα ομαδικό στρώμα με πολλαπλά εφέ
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Δείτε επίσης

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


