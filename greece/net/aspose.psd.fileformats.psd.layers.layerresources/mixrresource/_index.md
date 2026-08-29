---
title: "Κλάση MixrResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource. Κλάση MixrResource. Πόρος του στρώματος Προσαρμογής Μίκτη Καναλιών"
type: docs
weight: 3160
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Κλάση MixrResource. Πόρος της Channel Mixer Adjustment Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `MixrResource`. Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή: 2 Έκδοση (= 1) 2 Μονόχρωμο 20 χρώμα RGB ή CMYK συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 bytes χρώματος με 2 bytes σταθερά. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `MixrResource`. Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή: 2 Έκδοση (= 1) 2 Μονόχρωμο 20 χρώμα RGB ή CMYK συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 bytes χρώματος με 2 bytes σταθερά. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `MixrResource` είναι μονόχρωμο. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Λαμβάνει ή ορίζει την έκδοση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Λαμβάνει τα ακατέργαστα δεδομένα πληροφοριών καναλιού |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Ορίζει τις πληροφορίες καναλιού. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

### Δείτε επίσης

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


