---
title: "IColorConverter クラス"
type: docs
weight: 1690
url: /ja/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | 渡されたデータを出力形式に変換します。 |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

渡されたデータを出力形式に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | ソース形式です。 |
| data | byte | ソースデータ。 |
| offset | int | データコピーを開始すべきバイト単位のオフセット。 |
| bit_start | int | ビット開始位置。注意: この値はバイトアラインされているわけではなく、コピーを開始すべき実際のビット位置です。 |
| samples_count | int | サンプル数。 |
| lines_count | int | 行数。 |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | 宛先形式です。 |
| output_data | byte | 出力データ。 |
| output_offset | int | データコピーを開始すべき出力オフセット。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 変換されたバイト数。 |


