---
title: "IColorConverter Κλάση"
type: docs
weight: 1690
url: /el/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Μετατρέπει τα παρεχόμενα δεδομένα στη μορφή εξόδου. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Μετατρέπει τα παρεχόμενα δεδομένα στη μορφή εξόδου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Η μορφή προέλευσης. |
| δεδομένα | byte | Τα δεδομένα προέλευσης. |
| offset | int | Η μετατόπιση σε bytes όπου πρέπει να αρχίσει η αντιγραφή δεδομένων. |
| bit_start | int | Η αρχή του bit. Σημειώστε ότι αυτή η τιμή δεν είναι ευθυγραμμισμένη σε byte, αλλά είναι το πραγματικό bit όπου πρέπει να αρχίσει η αντιγραφή. |
| samples_count | int | Ο αριθμός των δειγμάτων. |
| lines_count | int | Ο αριθμός των γραμμών. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Η μορφή προορισμού. |
| output_data | byte | Τα δεδομένα εξόδου. |
| output_offset | int | Η μετατόπιση εξόδου όπου πρέπει να αρχίσει η αντιγραφή δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο αριθμός των μετατρεπόμενων bytes. |


