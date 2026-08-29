---
title: "Κλάση BritResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource κλάση. Κλάση BritResource. Πόρος του επιπέδου προσαρμογής Φωτεινότητας/Αντίθεσης"
type: docs
weight: 2600
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Κλάση BritResource. Πόρος της στρώσης προσαρμογής Φωτεινότητας/Αντίθεσης.

```csharp
public class BritResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BritResource](britresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `BritResource`. |
| [BritResource](britresource/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `BritResource`. Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή: 2 Φωτεινότητα 2 Αντίθεση 2 Μέση τιμή για φωτεινότητα και αντίθεση 1 μόνο χρώμα Lab Δεν χρησιμοποιείται σε σύγχρονα PSD (CS5 και μετά) όπου υπάρχει το CgEd. Το CgEd αποθηκεύει ιδιότητες πληροφοριών. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `BritResource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Λαμβάνει ή ορίζει τη φωτεινότητα. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Λαμβάνει ή ορίζει την αντίθεση. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Λαμβάνει ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


