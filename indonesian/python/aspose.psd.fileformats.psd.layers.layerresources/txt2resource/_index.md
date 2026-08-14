---
title: "Txt2Resource Kelas"
type: docs
weight: 970
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Menginisialisasi sebuah instance baru dari kelas Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| data | byte | r/w | Mendapatkan atau mengatur data. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Menambahkan rekaman teks ke Resource dan mengembalikan id rekaman teks. |
| [get_text_data()](#get_text_data__2) | Mendapatkan rekaman teks dari data resource. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Menyimpan kontainer aliran yang ditentukan. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Menginisialisasi sebuah instance baru dari kelas Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Menambahkan rekaman teks ke Resource dan mengembalikan id rekaman teks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | string | Teks rekaman. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Batas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Mengembalikan Id rekaman teks untuk resource |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Mendapatkan rekaman teks dari data resource.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Array rekaman teks |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Menyimpan kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran. |
| psd_version | int | Versi PSD. |

