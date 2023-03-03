---
title: CmykColorHelper.ToCmykIccBytes
second_title: Aspose.PSD για Αναφορά API .NET
description: CmykColorHelper μέθοδος. Μετατρέπει το RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC.
type: docs
weight: 120
url: /el/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
## CmykColorHelper.ToCmykIccBytes method

Μετατρέπει το RGB σε CMYK χρησιμοποιώντας προσαρμοσμένα προφίλ ICC.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixels | Int32[] | Τα χρώματα RGB παρουσιάζονται ως ακέραιες τιμές 32-bit. |
| startIndex | Int32 | Ο δείκτης έναρξης του χρώματος RGB. |
| length | Int32 | Ο αριθμός των εικονοστοιχείων RGB προς μετατροπή. |
| rgbIccStream | Stream | Η ροή προφίλ RGB. |
| cmykIccStream | Stream | Η ροή προφίλ CMYK. |

### Επιστρεφόμενη Αξία

Τα χρώματα CMYK που παρουσιάζονται ως πίνακας byte.

### Δείτε επίσης

* class [CmykColorHelper](../)
* χώρος ονομάτων [Aspose.PSD](../../cmykcolorhelper/)
* συνέλευση [Aspose.PSD](../../../)


