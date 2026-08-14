---
title: "PatternFillSettings Kelas"
type: docs
weight: 130
url: /id/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Menginisialisasi sebuah instance baru dari kelas PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [link with layer]. |
| sudut | double | r/w | Mendapatkan atau mengatur sudut. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur warna. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Tipe pengisian |
| horizontal_offset | int | r/w | Mendapatkan atau mengatur offset horizontal. |
| linked | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) ini terhubung. |
| pattern_data | int | r/w | Mendapatkan atau mengatur data pola. |
| pattern_height | int | r/w | Mendapatkan atau mengatur tinggi pola. |
| pattern_id | string | r/w | Mendapatkan atau mengatur pengidentifikasi pola. |
| pattern_name | string | r/w | Mendapatkan atau mengatur nama pola. |
| pattern_width | int | r/w | Mendapatkan atau mengatur lebar pola. |
| point_type | string | r/w | Mendapatkan atau mengatur tipe titik. |
| scale | double | r/w | Mendapatkan atau mengatur skala. |
| vertical_offset | int | r/w | Mendapatkan atau mengatur offset vertikal. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Menghasilkan node sumber daya LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Menginisialisasi sebuah instance baru dari kelas PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Menghasilkan node sumber daya LFX2.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point_type | string | Tipe titik. |
| color | [Color](/psd/python-net/aspose.psd/color) | Warna. |
| pattern_name | string | Nama pola. |
| pengidentifikasi | string | Pengidentifikasi. |
| scale | double | Skala. |
| ditautkan | bool | jika disetel ke <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Offset. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Daftar [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


