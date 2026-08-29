---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "CmykColorHelper μέθοδος. Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC"
type: docs
weight: 120
url: /el/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

Μετατρέπει RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixel | Int32[] | Τα χρώματα RGB παρουσιάζονται ως 32-bit ακέραιες τιμές. |
| startIndex | Int32 | Ο αρχικός δείκτης του χρώματος RGB. |
| μήκος | Int32 | Ο αριθμός των εικονοστοιχείων RGB προς μετατροπή. |
| rgbIccStream | Stream | Η ροή προφίλ RGB. |
| cmykIccStream | Stream | Η ροή προφίλ CMYK. |

### Τιμή Επιστροφής

Τα χρώματα CMYK παρουσιάζονται ως πίνακας byte.

### Δείτε επίσης

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


