---
title: "Kelas IText"
type: docs
weight: 10
url: /id/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Mendapatkan item-item. |
| text | string | r | Mendapatkan teks. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Mendapatkan atau mengatur orientasi teks. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Menambahkan bagian teks ke akhir |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Menyisipkan [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) ke posisi yang ditentukan |
| [produce_portion()](#produce_portion__3) | Menghasilkan bagian baru dengan parameter default |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Menghasilkan bagian-bagian baru dengan parameter masukan atau default. |
| [remove_portion(index)](#remove_portion_index_5) | Menghapus bagian pada indeks yang ditentukan |
| update_layer_data() | Memperbarui data lapisan. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Menambahkan bagian teks ke akhir

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Bagian tersebut. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Menyisipkan [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) ke posisi yang ditentukan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Bagian tersebut. |
| index | int | Indeks. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Menghasilkan bagian baru dengan parameter default

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Referensi ke [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) yang baru dibuat. |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Menghasilkan bagian-bagian baru dengan parameter masukan atau default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| portions_of_text | string | Bagian-bagian teks untuk membuat [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) baru. |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Gaya yang, jika tidak null, akan diterapkan pada [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) baru, jika tidak maka akan menjadi default. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Sebuah paragraf yang, jika tidak null, akan diterapkan pada [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/), jika tidak akan menjadi default. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Mengembalikan bagian baru [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) berdasarkan parameter input. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Menghapus bagian pada indeks yang ditentukan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks. |

