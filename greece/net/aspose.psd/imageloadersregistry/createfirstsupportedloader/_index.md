---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ImageLoadersRegistry μέθοδος. Δημιουργεί τον πρώτο φορτωτή που βρέθηκε, κατάλληλο για το καθορισμένο *stream* και προαιρετικά για τις *loadOptions*"
type: docs
weight: 30
url: /el/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Δημιουργεί τον πρώτο βρεθέντα φορτωτή που είναι κατάλληλος για το καθορισμένο *stream* και προαιρετικά για τις *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης. |

### Τιμή Επιστροφής

Ο φορτωτής που υποστηρίζει το καθορισμένο *stream* και *loadOptions* ή null αν δεν βρεθεί τέτοιος φορτωτής.

## Σχόλια

Ο πρώτος φορτωτής θα είναι στην πραγματικότητα ο τελευταίος καταχωρημένος.

### Δείτε επίσης

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


