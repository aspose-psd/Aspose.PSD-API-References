---
title: "Κλάση IfxsResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource κλάση. Πόρος ομάδας Ifxs για εφέ στρωμάτων."
type: docs
weight: 2840
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Πόρος Ifxs (πόρος εφέ ομάδας στρώματος)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [IfxsResource](ifxsresource/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Λαμβάνει την έκδοση του περιγραφέα. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

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

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


