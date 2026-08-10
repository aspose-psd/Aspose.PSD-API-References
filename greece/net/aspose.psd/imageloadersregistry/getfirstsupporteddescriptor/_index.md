---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος ImageLoadersRegistry. Παίρνει τον πρώτο ευρεθέν υποστηριζόμενο περιγραφέα που είναι κατάλληλος για το καθορισμένο *stream* και προαιρετικά τα *loadOptions*"
type: docs
weight: 40
url: /el/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα που είναι κατάλληλος για το καθορισμένο *stream* και προαιρετικά για τις *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή. |
| loadOptions | LoadOptions | Οι επιλογές φόρτωσης. |

### Τιμή Επιστροφής

Ο περιγραφέας φορτωτή που υποστηρίζει το καθορισμένο *stream* και *loadOptions* ή null εάν δεν βρεθεί τέτοιος περιγραφέας.

## Σχόλια

Ο πρώτος περιγραφέας φορτωτή θα είναι στην πραγματικότητα ο τελευταίος που έχει καταχωρηθεί.

### Δείτε επίσης

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


