---
title: "Kelas ColorRangeHsl"
type: docs
weight: 180
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | Menginisialisasi sebuah instance baru dari kelas [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | Menginisialisasi sebuah instance baru dari kelas [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| hue | short | r/w | Mendapatkan atau mengatur hue. |
| left_border | short | r/w | Mendapatkan atau mengatur batas kiri. |
| lightness | short | r/w | Mendapatkan atau mengatur lightness. |
| most_left_border | short | r/w | Mendapatkan atau mengatur batas paling kiri. |
| most_right_border | short | r/w | Mendapatkan atau mengatur batas paling kanan. |
| right_border | short | r/w | Mendapatkan atau mengatur batas kanan. |
| saturasi | short | r/w | Mendapatkan atau mengatur saturasi. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | Mendapatkan Koefisien rentang. |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | Menentukan apakah hue berada dalam rentang besar. |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | Menentukan apakah hue berada dalam rentang kecil. |
| [save(stream_container)](#save_stream_container_4) | Menyimpan data ke kontainer aliran yang ditentukan. |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

Menginisialisasi sebuah instance baru dari kelas [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

Menginisialisasi sebuah instance baru dari kelas [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data rentang warna. |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

Mendapatkan Koefisien rentang.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| hue | double | Nilai hue. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Koefisien rentang saturasi. |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

Menentukan apakah hue berada dalam rentang besar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| hue | double | Nilai hue. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika hue berada dalam rentang besar; jika tidak, <c>false</c>. |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

Menentukan apakah hue berada dalam rentang kecil.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| hue | double | Nilai hue. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika hue berada dalam rentang kecil; jika tidak, <c>false</c>. |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

Menyimpan data ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |

