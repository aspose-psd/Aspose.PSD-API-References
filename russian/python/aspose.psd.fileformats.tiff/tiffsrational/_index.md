---
title: "Класс TiffSRational"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Инициализирует новый экземпляр класса [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Инициализирует новый экземпляр класса [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | Эпсилон для вычисления дроби |
| знаменатель | int | r | Возвращает знаменатель. |
| числитель | int | r | Возвращает числитель. |
| значение | float | r | Возвращает значение типа float. |
| value_d | double | r | Возвращает значение типа double. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Аппроксимирует предоставленное значение в дробь. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Аппроксимирует предоставленное значение в дробь. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Аппроксимирует предоставленное значение в дробь. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Аппроксимирует предоставленное значение в дробь. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Инициализирует новый экземпляр класса [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Инициализирует новый экземпляр класса [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| числитель | int | Числитель. |
| знаменатель | int | Знаменатель. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Инициализирует новый экземпляр класса [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | int | Значение числителя. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Рациональное число с ошибкой меньше, чем [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Рациональное число с ошибкой меньше, чем [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Рациональное число с ошибкой меньше, чем <paramref name=\"epsilon\" />. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Рациональное число с ошибкой меньше, чем <paramref name=\"epsilon\" />. |


