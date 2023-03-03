---
title: Class PhflResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource τάξη. Τάξη PhflResource. Πόρος προσαρμογής έκθεσης Layer 2 Έκδοση   3  ή   2  12 4 byte το καθένα για χρώμα XYZ Μόνο στην έκδοση 3 10 χρωματικός χώρος 2 byte ακολουθούμενος από χρωματικός χώρος 4  2 byte στο στοιχείο χρώματος έκδοσης 2 4 Πυκνότητα 1 Διατήρηση φωτεινότητας
type: docs
weight: 2890
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Τάξη PhflResource. Πόρος προσαρμογής έκθεσης Layer 2 Έκδοση ( = 3 ) ή ( = 2 ) 12 4 byte το καθένα για χρώμα XYZ (Μόνο στην έκδοση 3) 10 χρωματικός χώρος 2 byte ακολουθούμενος από χρωματικός χώρος 4 * 2 byte στο στοιχείο χρώματος έκδοσης (2) 4 Πυκνότητα 1 Διατήρηση φωτεινότητας

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Λαμβάνει ή ορίζει την πυκνότητα. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [διατήρηση φωτεινότητας]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Λαμβάνει την έκδοση psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Παίρνει την υπογραφή. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Λαμβάνει την έκδοση. Η προεπιλογή είναι 2 ή 3 |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Παίρνει το χρώμα του RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Ορίζει το χρώμα RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


