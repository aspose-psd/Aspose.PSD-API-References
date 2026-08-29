---
title: "Κλάση PhflResourceVersion3"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3 κλάση. Κλάση PhflResource. Πόρος του στρώματος ρύθμισης έκθεσης 2 Έκδοση 3 ή 2 12 4 bytes για κάθε χρώμα XYZ. Μόνο στην Έκδοση 3 10 2 bytes χρωματικού χώρου ακολουθούμενα από 4 2 bytes συνιστώσας χρώματος. Μόνο στην Έκδοση 2 4 Πυκνότητα 1 Διατήρηση φωτεινότητας"
type: docs
weight: 3260
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

Κλάση PhflResource. Πόρος της Exposure Adjustment Layer 2 Έκδοση ( = 3 ) ή ( = 2 ) 12 4 bytes για κάθε χρώμα XYZ (Μόνο στην Έκδοση 3) 10 2 bytes χρωματικός χώρος ακολουθούμενος από 4 * 2 bytes συνιστώσα χρώματος (Μόνο στην Έκδοση 2) 4 Πυκνότητα 1 Διατήρηση Φωτεινότητας

```csharp
public class PhflResourceVersion3 : PhflResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `PhflResourceVersion3`. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `PhflResourceVersion3`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | Λαμβάνει το χρωματικό χώρο. |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα X. |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα Y. |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα Z. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Λαμβάνει ή ορίζει την πυκνότητα. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Αποκτά ή ορίζει μια τιμή που υποδεικνύει εάν [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | Λαμβάνει την έκδοση. Η προεπιλογή είναι 2 ή 3. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | Λαμβάνει το χρώμα. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | Ορίζει το χρώμα RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


