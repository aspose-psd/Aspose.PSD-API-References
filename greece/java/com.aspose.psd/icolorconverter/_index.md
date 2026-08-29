---
title: "IColorConverter"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο μετατροπέας χρώματος."
type: docs
weight: 116
url: /el/java/com.aspose.psd/icolorconverter/
---
```
public interface IColorConverter
```

Ο μετατροπέας χρώματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)](#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-) | Μετατρέπει τα παρεχόμενα δεδομένα στη μορφή εξόδου. |
### convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset) {#convert-com.aspose.psd.PixelDataFormat-byte---int-int-int-int-com.aspose.psd.PixelDataFormat-byte---int-}
```
public abstract int convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, int outputOffset)
```


Μετατρέπει τα παρεχόμενα δεδομένα στη μορφή εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Η μορφή προέλευσης. |
| δεδομένα | byte[] | Τα δεδομένα πηγής. |
| μετατόπιση | int | Η μετατόπιση σε bytes όπου πρέπει να ξεκινήσει η αντιγραφή δεδομένων. |
| bitStart | int | Η αρχή του bit. Σημειώστε ότι αυτή η τιμή δεν είναι ευθυγραμμισμένη σε byte, αλλά είναι το πραγματικό bit όπου πρέπει να ξεκινήσει η αντιγραφή. |
| samplesCount | int | Ο αριθμός των δειγμάτων. |
| linesCount | int | Ο αριθμός των γραμμών. |
| destFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Η μορφή προορισμού. |
| outputData | byte[] | Τα δεδομένα εξόδου. |
| outputOffset | int | Η μετατόπιση εξόδου όπου πρέπει να ξεκινήσει η αντιγραφή δεδομένων. |

**Returns:**
int - Ο αριθμός των μετατρεπόμενων bytes.
