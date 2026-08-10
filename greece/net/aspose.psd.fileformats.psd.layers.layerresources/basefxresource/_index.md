---
title: "Κλάση BaseFxResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseFxResource κλάση. Πόρος βασικών εφέ"
type: docs
weight: 2550
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/basefxresource/
---
{{< psd/tize >}}
## BaseFxResource class

Βασικός πόρος εφέ

```csharp
public abstract class BaseFxResource : LayerResource
```

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

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη του πόρου multi-effects.

```csharp
[C#]

// Η εικόνα PSD περιέχει 2 εφέ Drop Shadow
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // Αναπαράγει την εικόνα PSD με 2 εφέ Drop Shadow
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Προσθέτει ένα τρίτο εφέ Drop Shadow.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // Απεικονίζει εικόνα PSD με 3 εφέ Drop Shadow
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Ο πόρος imfx χρησιμοποιείται εάν η στρώση περιέχει πολλαπλά εφέ του ίδιου τύπου.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Καθαρίζει όλα τα εφέ
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // Απεικονίζει εικόνα PSD με 1 εφέ Drop Shadow (τα άλλα διαγράφηκαν)
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // Ο πόρος lfx2 χρησιμοποιείται εάν η στρώση δεν περιέχει πολλαπλά εφέ του ίδιου τύπου.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Δείτε επίσης

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


