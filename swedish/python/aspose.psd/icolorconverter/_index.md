---
title: "IColorConverter-klass"
type: docs
weight: 1690
url: /sv/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Konverterar den överförda datan till utdataformatet. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Konverterar den överförda datan till utdataformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Källformatet. |
| data | byte | Källdata. |
| offset | int | Offseten i byte där datakopieringen ska börja. |
| bit_start | int | Bitstarten. Observera att detta värde inte är bytejusterat utan är den faktiska biten där kopieringen ska börja. |
| samples_count | int | Antalet prover. |
| lines_count | int | Antalet rader. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Målformatet. |
| output_data | byte | Utdata. |
| output_offset | int | Utdataförskjutningen där datakopiering ska börja. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet konverterade byte. |


