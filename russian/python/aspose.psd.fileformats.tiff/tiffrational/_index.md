---
title: "Класс TiffRational"
type: docs
weight: 30
url: /ru/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | Эпсилон для вычисления дроби |
| знаменатель | uint | r | Возвращает знаменатель. |
| числитель | uint | r | Возвращает числитель. |
| значение | float | r | Возвращает значение типа float. |
| value_d | double | r | Возвращает значение типа double. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Аппроксимирует предоставленное значение в дробь. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Аппроксимирует предоставленное значение в дробь. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Аппроксимирует предоставленное значение в дробь. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Аппроксимирует предоставленное значение в дробь. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| числитель | uint | Числитель. |
| знаменатель | uint | Знаменатель. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | uint | Значение числителя. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Аппроксимирует предоставленное значение в дробь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | double | Значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Рациональное число с ошибкой меньше, чем [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Аппроксимирует предоставленное значение в дробь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Рациональное число с ошибкой меньше, чем [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Аппроксимирует предоставленное значение в дробь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | double | Значение. |
| эпсилон | double | Разрешённая ошибка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Рациональное число с ошибкой меньше, чем <paramref name=\"epsilon\" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Аппроксимирует предоставленное значение в дробь.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | float | Значение. |
| эпсилон | double | Разрешённая ошибка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Рациональное число с ошибкой меньше, чем <paramref name=\"epsilon\" />. |


