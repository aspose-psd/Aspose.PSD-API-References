---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD για Αναφορά API .NET
description: ImageLoadersRegistry μέθοδος. Δημιουργεί τον πρώτο φορτωτή που βρέθηκε κατάλληλος για το καθορισμένοstream και προαιρετικά τοloadOptions .
type: docs
weight: 30
url: /el/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Δημιουργεί τον πρώτο φορτωτή που βρέθηκε κατάλληλος για το καθορισμένο*stream* και προαιρετικά το*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Το ρεύμα. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης. |

### Επιστρεφόμενη Αξία

Ο φορτωτής που υποστηρίζει το καθορισμένο*stream* και*loadOptions* ή null εάν δεν βρεθεί τέτοιος φορτωτής.

### Παρατηρήσεις

Ο πρώτος φορτωτής θα είναι στην πραγματικότητα ο τελευταίος εγγεγραμμένος.

### Δείτε επίσης

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* χώρος ονομάτων [Aspose.PSD](../../imageloadersregistry/)
* συνέλευση [Aspose.PSD](../../../)


