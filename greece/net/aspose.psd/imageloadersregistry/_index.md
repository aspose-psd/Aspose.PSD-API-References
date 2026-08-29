---
title: "Κλάση ImageLoadersRegistry"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.ImageLoadersRegistry. Αντιπροσωπεύει το μητρώο φορτωτών εικόνας"
type: docs
weight: 5270
url: /el/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

Αναπαριστά το μητρώο φορτωτών εικόνας.

```csharp
public static class ImageLoadersRegistry
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Λαμβάνει τους καταχωρημένους περιγραφείς. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Λαμβάνει τις καταχωρημένες μορφές φόρτωσης εικόνας. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Δημιουργεί τον πρώτο βρεθέντα φορτωτή που είναι κατάλληλος για το καθορισμένο *stream* και προαιρετικά για τις *loadOptions*. |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα που είναι κατάλληλος για το καθορισμένο *stream* και προαιρετικά για τις *loadOptions*. |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Λαμβάνει την πρώτη υποστηριζόμενη μορφή αρχείου με βάση το όνομα τύπου της. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Καταχωρεί τον καθορισμένο περιγραφέα φορτωτή εικόνας. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Καταχωρεί τον φορτωτή. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Καταργεί την καταχώρηση του φορτωτή. |

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


