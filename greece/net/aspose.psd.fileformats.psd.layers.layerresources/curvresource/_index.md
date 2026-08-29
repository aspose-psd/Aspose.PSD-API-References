---
title: "Κλάση CurvResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource κλάση. Κλάση CurvResource. Πόρος του επιπέδου προσαρμογής Καμπυλών 1 byte 0 εάν χρησιμοποιούνται καμπύλες 1 εάν χρησιμοποιούνται εικονοστοιχεία στον χάρτη εάν 0 τότε 2 bytes short. Η προεπιλογή είναι 1 4 bytes int. Χρησιμοποιείται μόνο το τελευταίο byte ανά bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια, για παράδειγμα 2 bytes short αριθμός σημείων 4 bytes αριθμός σημείου σημείων καμπύλης 2 short πρώτη θέση δεύτερο ύψος 4 bytes word Crv 2 bytes short η προεπιλογή είναι 4 για Καμπύλες 4 bytes int. Η προεπιλογή είναι 1 4 bytes αριθμός σημείων 4 bytes αριθμός σημείων σημείων καμπύλης 2 short πρώτη θέση δεύτερο ύψος 04 bytes Η ηγεσία πρέπει να διπλασιαστεί για τέσσερα εάν 1 τότε 2 bytes short. Η προεπιλογή είναι 1 4 bytes int. Χρησιμοποιείται μόνο το τελευταίο byte. Ένα κανάλι είναι σε ένα bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια, για παράδειγμα 256 αριθμός αλλαγμένων καναλιών διατεταγμένες τιμές καναλιού στο εύρος 0 255 4 bytes word Crv 2 bytes short. Η προεπιλογή είναι 3 για εικονοστοιχεία στον χάρτη 4 bytes int Αριθμός καναλιών 2 256 bytes short 2 για δείκτη καναλιού 256 είναι διατεταγμένες τιμές καναλιού στο εύρος 0 255."
type: docs
weight: 2660
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Κλάση CurvResource. Πόρος της στρώσης προσαρμογής Καμπύλες 1 byte - 0 αν χρησιμοποιούνται καμπύλες, 1 αν χρησιμοποιούνται pixel στον χάρτη, αν 0 τότε: 2 bytes - short. Η προεπιλογή είναι 1 4 bytes - int. Χρησιμοποιείται μόνο το τελευταίο byte ανά bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια, για παράδειγμα 2 bytes - short αριθμός σημείων 4 bytes * αριθμός σημείων - σημεία της καμπύλης 2 short: πρώτη θέση, δεύτερο ύψος 4 bytes - word "Crv " 2 bytes - short η προεπιλογή είναι 4 για Καμπύλες 4 bytes - int. Η προεπιλογή είναι 1 4 bytes - αριθμός σημείων 4 bytes * αριθμός σημείων - σημεία της καμπύλης 2 short: πρώτη θέση, δεύτερο ύψος 0-4 bytes - Προηγούμενο για τέσσερα αν 1 τότε: 2 bytes - short. Η προεπιλογή είναι 1 4 bytes - int. Χρησιμοποιείται μόνο το τελευταίο byte. Ένα κανάλι είναι σε ένα bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια, για παράδειγμα 256 * αριθμός αλλαγμένων καναλιών - διατεταγμένες τιμές καναλιού στο εύρος 0 - 255 4 bytes - word "Crv " 2 bytes - short. Η προεπιλογή είναι 3 για pixel στον χάρτη 4 bytes - int Αριθμός καναλιών (2 + 256) bytes - short 2 για δείκτη καναλιού, 256 είναι διατεταγμένες τιμές καναλιού στο εύρος 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | Αρχικοποιεί μια νέα παρουσία της κλάσης `CurvResource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι δεδομένα αποθηκευμένα διακριτά. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Λαμβάνει τον ενεργό διαχειριστή. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Λαμβάνει τα δεδομένα του καναλιού. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Λαμβάνει τον διαχειριστή καμπύλης. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


