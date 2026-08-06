---
title: "IText"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "واجهة لتحرير النص لطبقات النص."
type: docs
weight: 11
url: /ar/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

واجهة لتحرير النص لطبقات النص.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | يضيف جزء النص إلى النهاية |
| [getItems()](#getItems--) | يحصل على العناصر. |
| [getText()](#getText--) | يحصل على النص. |
| [getTextOrientation()](#getTextOrientation--) | يحصل أو يضبط اتجاه النص. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | يدرج [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) في الموضع المحدد |
| [producePortion()](#producePortion--) | ينتج الجزء الجديد باستخدام المعلمات الافتراضية |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | ينتج الأجزاء الجديدة باستخدام الإدخال أو المعلمات الافتراضية. |
| [removePortion(int index)](#removePortion-int-) | يزيل الجزء في الفهرس المحدد |
| [setTextOrientation(int value)](#setTextOrientation-int-) | يحصل أو يضبط اتجاه النص. |
| [updateLayerData()](#updateLayerData--) | يحدّث بيانات الطبقة. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


يضيف جزء النص إلى النهاية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | الجزء. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


يحصل على العناصر.

القيمة: العناصر.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


يحصل على النص.

القيمة: النص.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


يحصل أو يضبط اتجاه النص.

القيمة: اتجاه النص.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


يدرج [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) في الموضع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | الجزء. |
| الفهرس | int | الفهرس. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


ينتج الجزء الجديد باستخدام المعلمات الافتراضية

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


ينتج الأجزاء الجديدة باستخدام الإدخال أو المعلمات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | الأجزاء النصية لإنشاء ITextPortion جديد. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | نمط إذا لم يكن فارغًا سيُطبق في الجديد   ، وإلا سيكون الافتراضي. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | فقرة إذا لم تكن فارغة ستُطبق في الجديد   ، وإلا ستكون الافتراضية. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - يُرجع الأجزاء الجديدة ITextPortion بناءً على معلمات الإدخال.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


يزيل الجزء في الفهرس المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | الفهرس. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


يحصل أو يضبط اتجاه النص.

القيمة: اتجاه النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


يحدّث بيانات الطبقة.

