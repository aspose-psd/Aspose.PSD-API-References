---
title: "فئة SizeF"
type: docs
weight: 4090
url: /ar/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [SizeF()](#SizeF__1) | يُنشئ مثيلاً جديداً لفئة SizeF |
| [SizeF(point)](#SizeF_point_2) | يُنشئ مثيلاً جديداً للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد. |
| [SizeF(size)](#SizeF_size_3) | يُنشئ مثيلاً جديداً للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من الـ [SizeF](/psd/python-net/aspose.psd/sizef/) المحدد. |
| [SizeF(width, height)](#SizeF_width_height_4) | يُنشئ مثيلاً جديداً للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من الأبعاد المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | يحصل على مثيل جديد للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) الذي تكون قيم [SizeF.width](/psd/python-net/aspose.psd/sizef/) و[SizeF.height](/psd/python-net/aspose.psd/sizef/) فيه صفر. |
| height | float | r/w | يحصل أو يعيّن المكوّن العمودي لهذا [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [SizeF](/psd/python-net/aspose.psd/sizef/) له عرض وارتفاع صفر. |
| width | float | r/w | يحصل أو يعيّن المكوّن الأفقي لهذا [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | يضيف عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) إلى عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) آخر. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | يطرح عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) آخر. |
| [to_point_f()](#to_point_f__3) | يحوِّل [SizeF](/psd/python-net/aspose.psd/sizef/) إلى [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | يحوِّل [SizeF](/psd/python-net/aspose.psd/sizef/) إلى هيكل [Size](/psd/python-net/aspose.psd/size/) بقيم حجم مقصوصة. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

يُنشئ مثيلاً جديداً لفئة SizeF

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

يُنشئ مثيلاً جديداً للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من الـ [PointF](/psd/python-net/aspose.psd/pointf/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | الـ [PointF](/psd/python-net/aspose.psd/pointf/) الذي سيُستخدم لتهيئة هذا [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

يُنشئ مثيلاً جديداً للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من الـ [SizeF](/psd/python-net/aspose.psd/sizef/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | الـ [SizeF](/psd/python-net/aspose.psd/sizef/) الذي سيُستخدم لإنشاء الـ [SizeF](/psd/python-net/aspose.psd/sizef/) الجديد. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

يُنشئ مثيلاً جديداً للهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من الأبعاد المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | float | مكوّن العرض للـ [SizeF](/psd/python-net/aspose.psd/sizef/) الجديد. |
| height | float | مكوّن الارتفاع للـ [SizeF](/psd/python-net/aspose.psd/sizef/) الجديد. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

يضيف عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) إلى عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) آخر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | الأول [SizeF](/psd/python-net/aspose.psd/sizef/) للإضافة. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | الثاني [SizeF](/psd/python-net/aspose.psd/sizef/) للإضافة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) هو نتيجة عملية الجمع. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

يطرح عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) من عرض وارتفاع هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) آخر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) على الجانب الأيسر من عامل الطرح. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | هيكل [SizeF](/psd/python-net/aspose.psd/sizef/) على الجانب الأيمن من عامل الطرح. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | الـ [SizeF](/psd/python-net/aspose.psd/sizef/) هو نتيجة عملية الطرح. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

يحوِّل [SizeF](/psd/python-net/aspose.psd/sizef/) إلى [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| النوع | الوصف |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | يرجع هيكل [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

يحوِّل [SizeF](/psd/python-net/aspose.psd/sizef/) إلى هيكل [Size](/psd/python-net/aspose.psd/size/) بقيم حجم مقصوصة.

**Returns**

| النوع | الوصف |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | يرجع هيكل [Size](/psd/python-net/aspose.psd/size/). |


