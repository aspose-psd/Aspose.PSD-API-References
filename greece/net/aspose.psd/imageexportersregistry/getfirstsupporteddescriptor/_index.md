---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "ImageExportersRegistry μέθοδος. Λαμβάνει τον πρώτο ευρεθέντα υποστηριζόμενο περιγραφέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και εικόνα"
type: docs
weight: 40
url: /el/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Εικόνα | Η εικόνα για εξαγωγή. |
| επιλογές | ImageOptionsBase | Οι επιλογές. |

### Τιμή Επιστροφής

Ο περιγραφέας εξαγωγέα που υποστηρίζει την καθορισμένη εικόνα και τις επιλογές αποθήκευσης ή null εάν δεν βρεθεί τέτοιος περιγραφέας.

## Σχόλια

Ο πρώτος περιγραφέας εξαγωγέα θα είναι στην πραγματικότητα ο τελευταίος που έχει καταχωρηθεί.

### Δείτε επίσης

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


