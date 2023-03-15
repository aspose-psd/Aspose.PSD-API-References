---
title: IColorConverter.Convert
second_title: Aspose.PSD για Αναφορά API .NET
description: IColorConverter μέθοδος. Μετατρέπει τα δεδομένα που έχουν περάσει στη μορφή εξόδου.
type: docs
weight: 10
url: /el/net/aspose.psd/icolorconverter/convert/
---
## IColorConverter.Convert method

Μετατρέπει τα δεδομένα που έχουν περάσει στη μορφή εξόδου.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Η μορφή πηγής. |
| data | Byte[] | Τα δεδομένα πηγής. |
| offset | Int32 | Η μετατόπιση σε byte όπου πρέπει να ξεκινήσει η αντιγραφή δεδομένων. |
| bitStart | Int32 | Το κομμάτι ξεκινά. Σημειώστε ότι αυτή η τιμή δεν είναι τιμή στοίχισης byte, αλλά είναι το πραγματικό bit όπου πρέπει να ξεκινήσει η αντιγραφή. |
| samplesCount | Int32 | Τα δείγματα μετράνε. |
| linesCount | Int32 | Οι γραμμές μετράνε. |
| destFormat | PixelDataFormat | Η μορφή προορισμού. |
| outputData | Byte[] | Τα δεδομένα εξόδου. |
| outputOffset | Int32 | Η μετατόπιση εξόδου όπου πρέπει να ξεκινήσει η αντιγραφή δεδομένων. |

### Επιστρεφόμενη Αξία

Τα byte που έχουν μετατραπεί μετράνε.

### Δείτε επίσης

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* χώρος ονομάτων [Aspose.PSD](../../icolorconverter/)
* συνέλευση [Aspose.PSD](../../../)


