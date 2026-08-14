---
title: "IColorConverter Klasse"
type: docs
weight: 1690
url: /de/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Konvertiert die übergebenen Daten in das Ausgabeformat. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Konvertiert die übergebenen Daten in das Ausgabeformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Das Quellformat. |
| data | byte | Die Quelldaten. |
| offset | int | Der Offset in Bytes, an dem das Kopieren der Daten beginnen soll. |
| bit_start | int | Der Bit-Start. Hinweis: Dieser Wert ist nicht byte‑ausgerichtet, sondern das tatsächliche Bit, an dem das Kopieren beginnen soll. |
| samples_count | int | Die Probenanzahl. |
| lines_count | int | Die Zeilenanzahl. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Das Zielformat. |
| output_data | byte | Die Ausgabedaten. |
| output_offset | int | Der Ausgabeverzögerungsversatz, an dem das Kopieren von Daten beginnen soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl konvertierter Bytes. |


