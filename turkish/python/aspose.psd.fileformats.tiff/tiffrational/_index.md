---
title: "TiffRational Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır. |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır. |
| [TiffRational(value)](#TiffRational_value_3) | Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | Kesir hesaplaması için epsilon |
| payda | uint | r | Paydayı alır. |
| pay | uint | r | Payı alır. |
| değer | float | r | Float değerini alır. |
| value_d | double | r | Double değerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Verilen değeri bir kesire yaklaştırır. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Verilen değeri bir kesire yaklaştırır. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Verilen değeri bir kesire yaklaştırır. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Verilen değeri bir kesire yaklaştırır. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır.

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pay | uint | Pay. |
| payda | uint | Payda. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | uint | Pay değeri. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Verilen değeri bir kesire yaklaştırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | double | Değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Hata değeri [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Verilen değeri bir kesire yaklaştırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Hata değeri [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Verilen değeri bir kesire yaklaştırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | double | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Hata değeri <paramref name="epsilon" /> değerinden daha az olan bir rasyonel sayı. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Verilen değeri bir kesire yaklaştırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | float | Değer. |
| epsilon | double | İzin verilen hata. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Hata değeri <paramref name="epsilon" /> değerinden daha az olan bir rasyonel sayı. |


