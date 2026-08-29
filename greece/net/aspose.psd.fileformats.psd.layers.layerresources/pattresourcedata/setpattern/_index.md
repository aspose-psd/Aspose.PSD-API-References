---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος PattResourceData. Ορίζει το buffer εικονοστοιχείων του μοτίβου και το μέγεθος στόχου, ενημερώνει το Πλάτος / Ύψος και αποθηκεύει τα δεδομένα για αποθήκευση χρησιμοποιώντας την προεπιλεγμένη λειτουργία συμπίεσης 0"
type: docs
weight: 110
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

Ορίζει το buffer εικονοστοιχείων του μοτίβου και το μέγεθος στόχου, ενημερώνει το [`Width`](../width/) / [`Height`](../height/), και αποθηκεύει τα δεδομένα για αποθήκευση χρησιμοποιώντας την προεπιλεγμένη λειτουργία συμπίεσης (0).

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | Int32[] | 32-bit pixel σε μορφή `0xAARRGGBB`. |
| όρια | Rectangle | Όρια pixel του μοτίβου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | Το μήκος του πίνακα pixel πρέπει να είναι ίσο με την περιοχή των ορίων. |

### Δείτε επίσης

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


