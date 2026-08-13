---
title: "IColorConverter 类"
type: docs
weight: 1690
url: /zh/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | 将传入的数据转换为输出格式。 |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

将传入的数据转换为输出格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 源格式。 |
| 数据 | byte | 源数据。 |
| offset | int | 数据复制应开始的字节偏移量。 |
| bit_start | int | 位起始位置。注意，此值不是字节对齐的，而是实际的位，复制应从该位开始。 |
| samples_count | int | 样本计数。 |
| lines_count | int | 行计数。 |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 目标格式。 |
| output_data | byte | 输出数据。 |
| output_offset | int | 数据复制应开始的输出偏移量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 已转换的字节计数。 |


