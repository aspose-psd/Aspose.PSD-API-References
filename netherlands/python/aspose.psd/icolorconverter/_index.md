---
title: "IColorConverter Klasse"
type: docs
weight: 1690
url: /nl/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Converteert de doorgegeven gegevens naar het uitvoerformaat. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Converteert de doorgegeven gegevens naar het uitvoerformaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Het bronformaat. |
| data | byte | De brongegevens. |
| offset | int | De offset in bytes waar het kopiëren van gegevens moet beginnen. |
| bit_start | int | De bitstart. Merk op dat deze waarde niet byte‑gealigneerd is, maar de daadwerkelijke bit waar het kopiëren moet beginnen. |
| samples_count | int | Het aantal monsters. |
| lines_count | int | Het aantal regels. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Het bestemmingsformaat. |
| output_data | byte | De uitvoergegevens. |
| output_offset | int | De uitvoeroffset waar het kopiëren van gegevens moet starten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Het aantal geconverteerde bytes. |


