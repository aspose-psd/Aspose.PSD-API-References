---
title: "TypeToolInfoResource Kelas"
type: docs
weight: 1000
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Menginisialisasi instance baru dari kelas TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| a_component | short | r/w | Mendapatkan atau mengatur sebuah komponen. |
| b_component | short | r/w | Mendapatkan atau mengatur komponen b. |
| character_count | int | r/w | Mendapatkan atau mengatur jumlah karakter. |
| color_space_value | short | r/w | Mendapatkan atau mengatur nilai ruang warna. |
| font_version | short | r/w | Mendapatkan atau mengatur versi font. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Mendapatkan atau mengatur font. |
| fonts_count | short | r | Mendapatkan jumlah font. |
| g_component | short | r/w | Mendapatkan atau mengatur komponen g. |
| horizontal_placement | int | r/w | Mendapatkan atau mengatur penempatan horizontal. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| line_count | short | r | Mendapatkan jumlah baris. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Mendapatkan atau mengatur baris. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| r_component | short | r/w | Mendapatkan atau mengatur komponen r. |
| scale_factor | int | r/w | Mendapatkan atau mengatur faktor skala. |
| selection_end | int | r/w | Mendapatkan atau mengatur akhir seleksi. |
| selection_start | int | r/w | Mendapatkan atau mengatur awal seleksi. |
| signature | int | r | Mendapatkan signature. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Mendapatkan atau mengatur gaya font. |
| styles_count | short | r | Mendapatkan jumlah gaya. |
| transform_matrix | double | r/w | Mendapatkan atau mengatur matriks transformasi. |
| type_value | short | r/w | Mendapatkan atau mengatur nilai tipe. |
| version | short | r/w | Mendapatkan atau mengatur versi. |
| vertical_placement | int | r/w | Mendapatkan atau mengatur penempatan vertikal. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan kontainer aliran yang ditentukan. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Menginisialisasi instance baru dari kelas TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| psd_version | int | Versi PSD. |

