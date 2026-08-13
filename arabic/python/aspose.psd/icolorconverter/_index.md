---
title: "فئة IColorConverter"
type: docs
weight: 1690
url: /ar/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | يحوّل البيانات المُمرَّرة إلى صيغة الإخراج. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

يحوّل البيانات المُمرَّرة إلى صيغة الإخراج.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | تنسيق المصدر. |
| البيانات | byte | بيانات المصدر. |
| offset | int | الإزاحة بالبايت حيث يجب أن يبدأ نسخ البيانات. |
| bit_start | int | بداية البت. لاحظ أن هذه القيمة ليست محاذاة للبايت بل هي البت الفعلي حيث يجب أن يبدأ النسخ. |
| samples_count | int | عدد العينات. |
| lines_count | int | عدد الأسطر. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | تنسيق الوجهة. |
| output_data | byte | بيانات الإخراج. |
| output_offset | int | إزاحة الإخراج حيث يجب أن يبدأ نسخ البيانات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | عدد البايتات المحوّلة. |


