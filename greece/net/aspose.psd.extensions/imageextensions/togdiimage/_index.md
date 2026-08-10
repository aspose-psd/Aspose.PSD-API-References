---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος ImageExtensions. Μετατρέπει το Image σε Image"
type: docs
weight: 10
url: /el/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

Μετατρέπει το Image σε Image.

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εικόνα | Εικόνα | Η Εικόνα για μετατροπή. |

### Τιμή Επιστροφής

Η μετατρεπόμενη Εικόνα.

## Σχόλια

Προειδοποίηση, η εικόνα GDI μπορεί να έχει μικρότερα όρια από ό,τι έχει η *image*. Για να λάβετε όλα τα τμήματα της εικόνας, χρησιμοποιήστε πιο ασφαλή μέθοδο επέκτασης ToGdiImageFull.

### Δείτε επίσης

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


