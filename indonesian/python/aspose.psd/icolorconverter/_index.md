---
title: "Kelas IColorConverter"
type: docs
weight: 1690
url: /id/python-net/aspose.psd/icolorconverter/
---

**Summary:** The color converter.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IColorConverter

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset)](#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1) | Mengonversi data yang diberikan ke format keluaran. |


### Method: convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) {#convert_source_format_data_offset_bit_start_samples_count_lines_count_dest_format_output_data_output_offset_1}


```
 convert(source_format, data, offset, bit_start, samples_count, lines_count, dest_format, output_data, output_offset) 
```

Mengonversi data yang diberikan ke format keluaran.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Format sumber. |
| data | byte | Data sumber. |
| offset | int | Offset dalam byte dimana penyalinan data harus dimulai. |
| bit_start | int | Awal bit. Catatan nilai ini tidak selaras byte, melainkan bit aktual dimana penyalinan harus dimulai. |
| samples_count | int | Jumlah sampel. |
| lines_count | int | Jumlah baris. |
| dest_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | Format tujuan. |
| output_data | byte | Data keluaran. |
| output_offset | int | Offset keluaran dimana penyalinan data harus dimulai. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Jumlah byte yang dikonversi. |


