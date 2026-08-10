---
title: "IColorConverter.Convert"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος IColorConverter. Μετατρέπει τα παρεχόμενα δεδομένα στη μορφή εξόδου"
type: docs
weight: 10
url: /el/net/aspose.psd/icolorconverter/convert/
---
{{< psd/tize >}}
## IColorConverter.Convert method

Μετατρέπει τα παρεχόμενα δεδομένα στη μορφή εξόδου.

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | Η μορφή προέλευσης. |
| δεδομένα | Byte[] | Τα δεδομένα προέλευσης. |
| offset | Int32 | Η μετατόπιση σε bytes όπου πρέπει να ξεκινήσει η αντιγραφή των δεδομένων. |
| bitStart | Int32 | Η αρχή του bit. Σημειώστε ότι αυτή η τιμή δεν είναι ευθυγραμμισμένη σε byte, αλλά είναι το πραγματικό bit όπου πρέπει να ξεκινήσει η αντιγραφή. |
| samplesCount | Int32 | Ο αριθμός των δειγμάτων. |
| linesCount | Int32 | Ο αριθμός των γραμμών. |
| destFormat | PixelDataFormat | Η μορφή προορισμού. |
| outputData | Byte[] | Τα δεδομένα εξόδου. |
| outputOffset | Int32 | Η μετατόπιση εξόδου όπου πρέπει να ξεκινήσει η αντιγραφή των δεδομένων. |

### Τιμή Επιστροφής

Ο αριθμός των μετατρεπόμενων bytes.

### Δείτε επίσης

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


