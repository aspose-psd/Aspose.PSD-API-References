---
title: "IText Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | Öğeleri alır. |
| text | string | r | Metni alır. |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | Metin yönelimini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | Metin bölümünü sona ekler |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | Belirtilen konuma [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) ekler |
| [produce_portion()](#produce_portion__3) | Varsayılan parametrelerle yeni bölümü üretir |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | Girdi veya varsayılan parametrelerle yeni bölümleri üretir. |
| [remove_portion(index)](#remove_portion_index_5) | Belirtilen indeksteki bölümü kaldırır |
| update_layer_data() | Katman verilerini günceller. |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

Metin bölümünü sona ekler

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Bölüm. |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

Belirtilen konuma [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) ekler

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Bölüm. |
| indeks | int | İndeks. |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

Varsayılan parametrelerle yeni bölümü üretir

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Yeni oluşturulan [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) referansı. |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

Girdi veya varsayılan parametrelerle yeni bölümleri üretir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| portions_of_text | string | Yeni [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) oluşturmak için metin bölümleri. |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | Boş değilse yeni [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) içinde uygulanacak bir stil, aksi takdirde varsayılan olur. |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | Null değilse yeni [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) içinde uygulanacak bir paragraf, aksi takdirde varsayılan olur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | Girdi parametrelerine göre yeni [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) bölümlerini döndürür. |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

Belirtilen indeksteki bölümü kaldırır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| indeks | int | İndeks. |

