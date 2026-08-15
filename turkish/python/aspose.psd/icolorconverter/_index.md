---
title: "IColorConverter Sınıfı"
type: docs
weight: 1690
url: /tr/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Verilen verileri çıktı formatına dönüştürür. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Verilen verileri çıktı formatına dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Kaynak biçim. |
| veri | byte | Kaynak veri. |
| offset | int | Veri kopyalamanın başlaması gereken bayt cinsinden offset. |
| bit_start | int | Bit başlangıcı. Bu değerin bayt hizalı bir değer olmadığını, bunun yerine kopyalamanın başlaması gereken gerçek bit olduğunu unutmayın. |
| samples_count | int | Örnek sayısı. |
| lines_count | int | Satır sayısı. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Hedef biçim. |
| output_data | byte | Çıktı verisi. |
| output_offset | int | Veri kopyalamanın başlaması gereken çıktı offseti. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Dönüştürülen bayt sayısı. |


