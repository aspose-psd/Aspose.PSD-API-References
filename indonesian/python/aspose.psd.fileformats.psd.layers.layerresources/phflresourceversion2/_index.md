---
title: "Kelas PhflResourceVersion2"
type: docs
weight: 800
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Menginisialisasi sebuah instance baru dari kelas [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Menginisialisasi sebuah instance baru dari kelas [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| color_space | short | r | Mendapatkan ruang warna. |
| component_a | short | r/w | Mendapatkan atau mengatur komponen A dari warna |
| component_b | short | r/w | Mendapatkan atau mengatur komponen B |
| component_l | short | r/w | Mendapatkan atau mengatur komponen L dari warna |
| density | int | r/w | Mendapatkan atau mengatur kepadatan. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| preserve_luminosity | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [preserve luminosity]. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| version | short | r | Mendapatkan versi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Mendapatkan warna. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Mengatur warna RGB. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Menginisialisasi sebuah instance baru dari kelas [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Menginisialisasi sebuah instance baru dari kelas [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Mendapatkan warna.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Warna RGB |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Mengatur warna RGB.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Warna. |

