---
title: "Κλάση LevlResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource κλάση. Κλάση LevlResource. Πόρος του επιπέδου προσαρμογής Έκθεσης"
type: docs
weight: 2950
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Κλάση LevlResource. Πόρος του στρώματος ρύθμισης έκθεσης

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `LevlResource`. Υποστηρίζεται σε λειτουργίες χρωμάτων GrayScale, Duotone, RGB, CMYK, Lab 2 bytes - Έκδοση (=2) 29 * 10 bytes - Σύνολα εγγραφών επιπέδου με 5 σύντομους ακέραιους 4 bytes - Κεφαλίδα Lvls (Ξεκινά στο δείκτη 292) 2 bytes - Έκδοση (=3) 2 bytes - Αριθμός συνολικών εγγραφών επιπέδου 10 * (Συνολικός Αριθμός - 29) Η μηδενική λήξη του πόρου Lvls πρέπει επίσης να διπλασιαστεί για τέσσερα. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Ανακτά την έκδοση. Η προεπιλογή είναι 2 |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Λαμβάνει το κανάλι. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


