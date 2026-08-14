---
title: "Kelas LayerHashCalculator"
type: docs
weight: 960
url: /id/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Summary:** Hash Calculator for PSD Layers. It can be used to found equals or different layers in different PSD files

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerHashCalculator

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LayerHashCalculator(layer)](#LayerHashCalculator_layer_1) | Menginisialisasi instance baru dari kelas [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_blending_hash()](#get_blending_hash__1) | Mendapatkan hash pencampuran. |
| [get_channels_hash()](#get_channels_hash__2) | Mendapatkan hash saluran. |
| [get_content_hash()](#get_content_hash__3) | Mendapatkan hash konten. |


### Constructor: LayerHashCalculator(layer) {#LayerHashCalculator_layer_1}


```
 LayerHashCalculator(layer) 
```

Menginisialisasi instance baru dari kelas [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lapisan. |

### Method: get_blending_hash() {#get_blending_hash__1}


```
 get_blending_hash() 
```

Mendapatkan hash pencampuran.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Hash unik untuk Opsi Pencampuran Lapisan |


### Method: get_channels_hash() {#get_channels_hash__2}


```
 get_channels_hash() 
```

Mendapatkan hash saluran.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Hash semua saluran lapisan |


### Method: get_content_hash() {#get_content_hash__3}


```
 get_content_hash() 
```

Mendapatkan hash konten.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Hash dari parameter penting lapisan. Hash ini berbeda untuk semua jenis lapisan. |


