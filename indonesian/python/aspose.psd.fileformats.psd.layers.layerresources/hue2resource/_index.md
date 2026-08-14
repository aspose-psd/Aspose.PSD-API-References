---
title: "Kelas Hue2Resource"
type: docs
weight: 350
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Menginisialisasi sebuah instance baru dari kelas [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) . |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Menginisialisasi sebuah instance baru dari kelas [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| colorize | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) ini diwarnai. |
| hue | short | r/w | Mendapatkan atau mengatur hue utama. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| lightness | short | r/w | Mendapatkan atau mengatur kecerahan utama. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Mendapatkan rentang Lapisan Penyesuaian Hue/Saturation.<br/>            Rentang di PS dapat mengubah nama jika rentang diubah, jadi kita harus bekerja berdasarkan indeks |
| saturasi | short | r/w | Mendapatkan atau mengatur saturasi utama. |
| signature | int | r | Mendapatkan signature. |
| version | short | r | Mendapatkan versi. Defaultnya adalah 2 |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Menginisialisasi sebuah instance baru dari kelas [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) .

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Menginisialisasi sebuah instance baru dari kelas [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) .

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data sumber daya. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

