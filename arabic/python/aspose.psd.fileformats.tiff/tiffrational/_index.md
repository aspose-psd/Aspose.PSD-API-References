---
title: "فئة TiffRational"
type: docs
weight: 30
url: /ar/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| EPSILON [ثابت] | double | r | الإبسيلون لحساب الكسر. |
| المقام | uint | r | يحصل على المقام. |
| البسط | uint | r | يحصل على البسط. |
| قيمة | float | r | يحصل على قيمة الفاصلة العائمة. |
| value_d | double | r | يحصل على قيمة مزدوجة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | يقرب القيمة المقدمة إلى كسر. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | يقرب القيمة المقدمة إلى كسر. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| البسط | uint | البسط. |
| المقام | uint | المقام. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

يُنشئ مثيلًا جديدًا للفئة [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| قيمة | uint | قيمة البسط. |

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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | عدد نسبي له خطأ أقل من [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | عدد نسبي له خطأ أقل من [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | عدد نسبي له خطأ أقل من <paramref name="epsilon" />. |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | عدد نسبي له خطأ أقل من <paramref name="epsilon" />. |


