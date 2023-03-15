---
title: Class ImageLoadersRegistry
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ImageLoadersRegistry τάξη. Αντιπροσωπεύει το μητρώο φορτωτών εικόνων.
type: docs
weight: 4780
url: /el/net/aspose.psd/imageloadersregistry/
---
## ImageLoadersRegistry class

Αντιπροσωπεύει το μητρώο φορτωτών εικόνων.

```csharp
public static class ImageLoadersRegistry
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | Λαμβάνει τους καταχωρισμένους περιγραφείς. |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | Λαμβάνει τις καταχωρημένες μορφές φόρτωσης εικόνων. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | Δημιουργεί τον πρώτο φορτωτή που βρέθηκε κατάλληλος για το καθορισμένο*stream* και προαιρετικά το*loadOptions* . |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | Λαμβάνει τον υποστηριζόμενο περιγραφέα που βρέθηκε κατάλληλος για το καθορισμένο*stream* και προαιρετικά το*loadOptions* . |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | Λαμβάνει την πρώτη υποστηριζόμενη μορφή αρχείου με το όνομα τύπου. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με το όνομα τύπου του. |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | Καταχωρεί τον καθορισμένο περιγραφέα φόρτωσης εικόνων. |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | Καταχωρεί τον φορτωτή. |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | Καταργεί την εγγραφή του φορτωτή. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


