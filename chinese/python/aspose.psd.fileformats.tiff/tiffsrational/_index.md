---
title: "TiffSRational 类"
type: docs
weight: 40
url: /zh/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | 初始化 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 类的新实例。 |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | 初始化 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 类的新实例。 |
| [TiffSRational(value)](#TiffSRational_value_3) | 初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [静态] | double | r | 用于分数计算的 epsilon |
| 分母 | int | r | 获取分母。 |
| 分子 | int | r | 获取分子。 |
| value | float | r | 获取浮点值。 |
| value_d | double | r | 获取双精度值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | 将提供的值近似为分数。 |
| [approximate_fraction(value)](#approximate_fraction_value_2) | 将提供的值近似为分数。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | 将提供的值近似为分数。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | 将提供的值近似为分数。 |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

初始化 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 类的新实例。

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

初始化 [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 分子 | int | 分子。 |
| 分母 | int | 分母。 |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | int | 分子值。 |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 一个误差小于 [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 的有理数。 |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | float | 值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 一个误差小于 [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) 的有理数。 |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 值。 |
| epsilon | double | 允许的误差。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 误差小于 <paramref name="epsilon" /> 的有理数。 |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

将提供的值近似为分数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | float | 值。 |
| epsilon | double | 允许的误差。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | 误差小于 <paramref name="epsilon" /> 的有理数。 |


