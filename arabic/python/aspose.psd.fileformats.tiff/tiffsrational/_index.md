---
title: "فئة TiffSRational"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | ينشئ مثيلاً جديدًا من الفئة [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | ينشئ مثيلاً جديدًا من الفئة [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| EPSILON [ثابت] | double | r | الإبسيلون لحساب الكسر. |
| المقام | int | r | يحصل على المقام. |
| البسط | int | r | يحصل على البسط. |
| قيمة | float | r | يحصل على قيمة الفاصلة العائمة. |
| value_d | double | r | يحصل على قيمة مزدوجة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | يقرب القيمة المقدمة إلى كسر. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

ينشئ مثيلاً جديدًا من الفئة [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

ينشئ مثيلاً جديدًا من الفئة [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البسط | int | البسط. |
| المقام | int | المقام. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | int | قيمة البسط. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | double | القيمة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | عدد نسبي يملك خطأً أقل من [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | float | القيمة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | عدد نسبي يملك خطأً أقل من [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | double | القيمة. |
| epsilon | double | الخطأ المسموح به. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | عدد نسبي له خطأ أقل من <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

يقرب القيمة المقدمة إلى كسر.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | float | القيمة. |
| epsilon | double | الخطأ المسموح به. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | عدد نسبي له خطأ أقل من <paramref name="epsilon" />. |


