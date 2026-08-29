---
title: "IText"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Antarmuka untuk Penyuntingan Teks pada Lapisan Teks"
type: docs
weight: 11
url: /id/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Antarmuka untuk Penyuntingan Teks pada Lapisan Teks
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Menambahkan bagian teks ke akhir |
| [getItems()](#getItems--) | Mendapatkan item-item. |
| [getText()](#getText--) | Mendapatkan teks. |
| [getTextOrientation()](#getTextOrientation--) | Mendapatkan atau mengatur orientasi teks. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Menyisipkan [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) ke posisi yang ditentukan |
| [producePortion()](#producePortion--) | Menghasilkan bagian baru dengan parameter default |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Menghasilkan bagian-bagian baru dengan parameter masukan atau default. |
| [removePortion(int index)](#removePortion-int-) | Menghapus bagian pada indeks yang ditentukan |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Mendapatkan atau mengatur orientasi teks. |
| [updateLayerData()](#updateLayerData--) | Memperbarui data lapisan. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Menambahkan bagian teks ke akhir

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Bagian tersebut. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Mendapatkan item-item.

Nilai: Item-item.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Mendapatkan teks.

Value: Teks.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Mendapatkan atau mengatur orientasi teks.

Nilai: Orientasi teks.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Menyisipkan [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) ke posisi yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Bagian tersebut. |
| indeks | int | Indeks tersebut. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Menghasilkan bagian baru dengan parameter default

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Menghasilkan bagian-bagian baru dengan parameter masukan atau default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Bagian-bagian teks untuk membuat ITextPortion baru. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Gaya yang, jika tidak null, akan diterapkan dalam yang baru   , jika tidak akan menjadi default. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Paragraf yang, jika tidak null, akan diterapkan dalam yang baru   , jika tidak akan menjadi default. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Mengembalikan bagian-bagian baru  ITextPortion  berdasarkan parameter masukan.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Menghapus bagian pada indeks yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks tersebut. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Mendapatkan atau mengatur orientasi teks.

Nilai: Orientasi teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Memperbarui data lapisan.

