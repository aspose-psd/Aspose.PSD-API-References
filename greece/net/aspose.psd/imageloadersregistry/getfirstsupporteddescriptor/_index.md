---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD για Αναφορά API .NET
description: ImageLoadersRegistry μέθοδος. Λαμβάνει τον υποστηριζόμενο περιγραφέα που βρέθηκε κατάλληλος για το καθορισμένοstream και προαιρετικά τοloadOptions .
type: docs
weight: 40
url: /el/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Λαμβάνει τον υποστηριζόμενο περιγραφέα που βρέθηκε κατάλληλος για το καθορισμένο*stream* και προαιρετικά το*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης. |

### Επιστρεφόμενη Αξία

Ο περιγραφέας φόρτωσης που υποστηρίζει το καθορισμένο*stream* και*loadOptions* ή μηδενική αν δεν βρεθεί τέτοιος περιγραφέας.

### Παρατηρήσεις

Ο πρώτος περιγραφέας φόρτωσης θα είναι στην πραγματικότητα ο τελευταίος καταχωρημένος.

### Δείτε επίσης

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* χώρος ονομάτων [Aspose.PSD](../../imageloadersregistry/)
* συνέλευση [Aspose.PSD](../../../)


