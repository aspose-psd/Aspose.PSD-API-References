---
title: "فئة Size"
type: docs
weight: 4080
url: /ar/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Size()](#Size__1) | ينشئ مثيلاً جديدًا للفئة Size |
| [Size(point)](#Size_point_2) | ينشئ مثيلاً جديدًا للهيكل [Size](/psd/python-net/aspose.psd/size/) من الـ [Point](/psd/python-net/aspose.psd/point/) المحدد. |
| [Size(width, height)](#Size_width_height_3) | ينشئ مثيلاً جديدًا للهيكل [Size](/psd/python-net/aspose.psd/size/) من الأبعاد المحددة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | يحصل على مثيل جديد للهيكل [Size](/psd/python-net/aspose.psd/size/) الذي يحتوي على قيم [Size.width](/psd/python-net/aspose.psd/size/) و[Size.height](/psd/python-net/aspose.psd/size/) مضبوطة على الصفر. |
| height | int | r/w | يحصل أو يعيّن المكوّن الرأسي لهذا [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا [Size](/psd/python-net/aspose.psd/size/) له عرض وارتفاع يساوي 0. |
| width | int | r/w | يحصل أو يعيّن المكوّن الأفقي لهذا [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | يضيف العرض والارتفاع لهيكل [Size](/psd/python-net/aspose.psd/size/) واحد إلى العرض والارتفاع لهيكل [Size](/psd/python-net/aspose.psd/size/) آخر. |
| [ceiling(size)](#ceiling_size_2) | يحوّل الهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) المحدد إلى هيكل [Size](/psd/python-net/aspose.psd/size/) عن طريق تقريب قيم الهيكل [Size](/psd/python-net/aspose.psd/size/) إلى أقرب عدد صحيح أعلى. |
| [round(size)](#round_size_3) | يقوم بتحويل بنية [SizeF](/psd/python-net/aspose.psd/sizef/) المحددة إلى بنية [Size](/psd/python-net/aspose.psd/size/) عن طريق تقريب قيم بنية [SizeF](/psd/python-net/aspose.psd/sizef/) إلى أقرب القيم الصحيحة. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | يطرح عرض وارتفاع بنية [Size](/psd/python-net/aspose.psd/size/) واحدة من عرض وارتفاع بنية [Size](/psd/python-net/aspose.psd/size/) أخرى. |
| [truncate(size)](#truncate_size_5) | يقوم بتحويل بنية [SizeF](/psd/python-net/aspose.psd/sizef/) المحددة إلى بنية [Size](/psd/python-net/aspose.psd/size/) عن طريق تقليل قيم بنية [SizeF](/psd/python-net/aspose.psd/sizef/) إلى القيم الصحيحة الأدنى التالية. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

ينشئ مثيلاً جديدًا للفئة Size

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

ينشئ مثيلاً جديدًا للهيكل [Size](/psd/python-net/aspose.psd/size/) من الـ [Point](/psd/python-net/aspose.psd/point/) المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | نقطة [Point](/psd/python-net/aspose.psd/point/) التي يتم منها تهيئة هذا [Size](/psd/python-net/aspose.psd/size/). |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

ينشئ مثيلاً جديدًا للهيكل [Size](/psd/python-net/aspose.psd/size/) من الأبعاد المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | مكوّن العرض في الـ [Size](/psd/python-net/aspose.psd/size/) الجديد. |
| height | int | مكوّن الارتفاع في الـ [Size](/psd/python-net/aspose.psd/size/) الجديد. |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

يضيف العرض والارتفاع لهيكل [Size](/psd/python-net/aspose.psd/size/) واحد إلى العرض والارتفاع لهيكل [Size](/psd/python-net/aspose.psd/size/) آخر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | أول [Size](/psd/python-net/aspose.psd/size/) للإضافة. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | ثاني [Size](/psd/python-net/aspose.psd/size/) للإضافة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | بنية [Size](/psd/python-net/aspose.psd/size/) هي نتيجة عملية الجمع. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

يحوّل الهيكل [SizeF](/psd/python-net/aspose.psd/sizef/) المحدد إلى هيكل [Size](/psd/python-net/aspose.psd/size/) عن طريق تقريب قيم الهيكل [Size](/psd/python-net/aspose.psd/size/) إلى أقرب عدد صحيح أعلى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | بنية [SizeF](/psd/python-net/aspose.psd/sizef/) للتحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | بنية [Size](/psd/python-net/aspose.psd/size/) التي يحولها هذه الطريقة. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

يقوم بتحويل بنية [SizeF](/psd/python-net/aspose.psd/sizef/) المحددة إلى بنية [Size](/psd/python-net/aspose.psd/size/) عن طريق تقريب قيم بنية [SizeF](/psd/python-net/aspose.psd/sizef/) إلى أقرب القيم الصحيحة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | بنية [SizeF](/psd/python-net/aspose.psd/sizef/) للتحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | بنية [Size](/psd/python-net/aspose.psd/size/) التي يحولها هذه الطريقة. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

يطرح عرض وارتفاع بنية [Size](/psd/python-net/aspose.psd/size/) واحدة من عرض وارتفاع بنية [Size](/psd/python-net/aspose.psd/size/) أخرى.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | بنية [Size](/psd/python-net/aspose.psd/size/) على الجانب الأيسر من عامل الطرح. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | بنية [Size](/psd/python-net/aspose.psd/size/) على الجانب الأيمن من عامل الطرح. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | الـ [Size](/psd/python-net/aspose.psd/size/) هو نتيجة عملية الطرح. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

يقوم بتحويل بنية [SizeF](/psd/python-net/aspose.psd/sizef/) المحددة إلى بنية [Size](/psd/python-net/aspose.psd/size/) عن طريق تقليل قيم بنية [SizeF](/psd/python-net/aspose.psd/sizef/) إلى القيم الصحيحة الأدنى التالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | بنية [SizeF](/psd/python-net/aspose.psd/sizef/) للتحويل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | بنية [Size](/psd/python-net/aspose.psd/size/) التي يحولها هذه الطريقة. |


