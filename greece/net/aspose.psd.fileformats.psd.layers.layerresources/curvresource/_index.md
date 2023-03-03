---
title: Class CurvResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource τάξη. Κλάση CurvResource. Προσαρμογή πόρων καμπυλών Επίπεδο 1 byte  0 εάν χρησιμοποιούνται καμπύλες 1 εάν χρησιμοποιούνται pixel στο map εάν 0 τότε 2 byte  σύντομο. Η προεπιλογή είναι 1 4 byte  int. Χρησιμοποιείται μόνο τελευταίο bytebit. Το πρώτο bit είναι για 1 κανάλι το τέταρτο bit για 4 κανάλια για παράδειγμα 2 byte  σύντομες θέσεις count 4 byte  πλήθος σημείων  σημεία καμπύλης 2 σύντομη πρώτη θέση δεύτερη ύψος 4 byte  λέξη Crv  2 bytes  σύντομη προεπιλογή είναι 4 για Curves 4 byte  εσ. Η προεπιλογή είναι 1 4 byte  point count 4 bytes  points count  points of curved 2 short πρώτη θέση δεύτερη ύψος 04 byte  Προηγείται να διπλωθεί για τέσσερα εάν 1 τότε 2 byte. Η προεπιλογή είναι 1 4 byte  int. Χρησιμοποιήθηκε μόνο το τελευταίο byte. Ένα κανάλι είναι σε ένα bit. Το πρώτο bit είναι για 1 κανάλι το τέταρτο bit για 4 κανάλια για παράδειγμα 256  πλήθος αλλαγμένων καναλιών  ταξινομημένες τιμές καναλιού στην περιοχή 0  255 4 byte  λέξη Crv  2 byte  σύντομη. Η προεπιλογή είναι 3 για pixel στο map 4 byte  int Channel count 2  256 byte  short 2 για ευρετήριο καναλιού 256 είναι ταξινομημένες τιμές καναλιού στην περιοχή 0  255
type: docs
weight: 2400
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Κλάση CurvResource. Προσαρμογή πόρων καμπυλών Επίπεδο 1 byte - 0 εάν χρησιμοποιούνται καμπύλες, 1 εάν χρησιμοποιούνται pixel στο map εάν 0 τότε: 2 byte - σύντομο. Η προεπιλογή είναι 1 4 byte - int. Χρησιμοποιείται μόνο τελευταίο byte-bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια για παράδειγμα 2 byte - σύντομες θέσεις count 4 byte * πλήθος σημείων - σημεία καμπύλης 2 σύντομη: πρώτη θέση, δεύτερη ύψος 4 byte - λέξη "Crv " 2 bytes - σύντομη προεπιλογή είναι 4 για Curves 4 byte - εσ. Η προεπιλογή είναι 1 4 byte - point count 4 bytes * points count - points of curved 2 short: πρώτη θέση, δεύτερη ύψος 0-4 byte - Προηγείται να διπλωθεί για τέσσερα εάν 1 τότε: 2 byte. Η προεπιλογή είναι 1 4 byte - int. Χρησιμοποιήθηκε μόνο το τελευταίο byte. Ένα κανάλι είναι σε ένα bit. Το πρώτο bit είναι για 1 κανάλι, το τέταρτο bit για 4 κανάλια για παράδειγμα 256 * πλήθος αλλαγμένων καναλιών - ταξινομημένες τιμές καναλιού στην περιοχή 0 - 255 4 byte - λέξη "Crv " 2 byte - σύντομη. Η προεπιλογή είναι 3 για pixel στο map 4 byte - int Channel count (2 + 256) byte - short 2 για ευρετήριο καναλιού, 256 είναι ταξινομημένες τιμές καναλιού στην περιοχή 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Αρχικοποιεί μια νέα παρουσία του`CurvResource` τάξη. |
| [CurvResource](curvresource/#constructor_1)(int) | Αρχικοποιεί μια νέα παρουσία του`CurvResource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι αποθηκευμένα δεδομένα διακριτά. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | Λαμβάνει την έκδοση psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Παίρνει την υπογραφή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Παίρνει τον ενεργό διαχειριστή. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Λαμβάνει τα δεδομένα καναλιού. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Παίρνει το curve manager. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


