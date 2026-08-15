---
title: "TiffSRational Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Yeni bir [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) sınıfı örneği başlatır. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Yeni bir [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) sınıfı örneği başlatır. |
| [TiffSRational(value)](#TiffSRational_value_3) | Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | Kesir hesaplaması için epsilon |
| payda | int | r | Paydayı alır. |
| pay | int | r | Payı alır. |
| değer | float | r | Float değerini alır. |
| value_d | double | r | Double değerini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Verilen değeri bir kesire yaklaştırır. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Verilen değeri bir kesire yaklaştırır. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Verilen değeri bir kesire yaklaştırır. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Verilen değeri bir kesire yaklaştırır. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Yeni bir [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) sınıfı örneği başlatır.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Yeni bir [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pay | int | Pay. |
| payda | int | Payda. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Yeni bir [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | int | Pay değeri. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Hatası [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) değerinden daha az olan bir rasyonel sayı. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Hatası [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) değerinden daha az olan bir rasyonel sayı. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Hata değeri <paramref name="epsilon" /> değerinden daha az olan bir rasyonel sayı. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Hata değeri <paramref name="epsilon" /> değerinden daha az olan bir rasyonel sayı. |


