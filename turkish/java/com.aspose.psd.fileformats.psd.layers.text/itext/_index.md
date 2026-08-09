---
title: "IText"
second_title: "Java için Aspose.PSD API Referansı"
description: "Metin Katmanları için Metin Düzenleme arayüzü"
type: docs
weight: 11
url: /tr/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Metin Katmanları için Metin Düzenleme arayüzü
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Metin bölümünü sona ekler |
| [getItems()](#getItems--) | Öğeleri alır. |
| [getText()](#getText--) | Metni alır. |
| [getTextOrientation()](#getTextOrientation--) | Metin yönelimini alır veya ayarlar. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Belirtilen konuma [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) ekler |
| [producePortion()](#producePortion--) | Varsayılan parametrelerle yeni bölümü üretir |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Girdi veya varsayılan parametrelerle yeni bölümleri üretir. |
| [removePortion(int index)](#removePortion-int-) | Belirtilen indeksteki bölümü kaldırır |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Metin yönelimini alır veya ayarlar. |
| [updateLayerData()](#updateLayerData--) | Katman verilerini günceller. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Metin bölümünü sona ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Bölüm. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Öğeleri alır.

Değer: Öğeler.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Metni alır.

Değer: Metin.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Metin yönelimini alır veya ayarlar.

Değer: Metin yönelimi.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Belirtilen konuma [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Bölüm. |
| indeks | int | İndeks. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Varsayılan parametrelerle yeni bölümü üretir

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Girdi veya varsayılan parametrelerle yeni bölümleri üretir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Yeni ITextPortion oluşturmak için metin bölümleri. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Null değilse yeni   içinde uygulanacak bir stil, aksi takdirde varsayılan olur. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Null değilse yeni   içinde uygulanacak bir paragraf, aksi takdirde varsayılan olur. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Girdi parametrelerine göre yeni ITextPortion bölümlerini döndürür.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Belirtilen indeksteki bölümü kaldırır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | İndeks. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Metin yönelimini alır veya ayarlar.

Değer: Metin yönelimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Katman verilerini günceller.

