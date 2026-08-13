---
title: "TiffRational 类"
type: docs
weight: 30
url: /zh/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | 初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。 |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | 初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。 |
| [TiffRational(value)](#TiffRational_value_3) | 初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [静态] | double | r | 用于分数计算的 epsilon |
| 分母 | uint | r | 获取分母。 |
| 分子 | uint | r | 获取分子。 |
| value | float | r | 获取浮点值。 |
| value_d | double | r | 获取双精度值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | 将提供的值近似为分数。 |
| [approximate_fraction(value)](#approximate_fraction_value_2) | 将提供的值近似为分数。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | 将提供的值近似为分数。 |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | 将提供的值近似为分数。 |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 分子 | uint | 分子。 |
| 分母 | uint | 分母。 |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

初始化 [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | uint | 分子值。 |

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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 误差小于 [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 的有理数。 |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 误差小于 [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) 的有理数。 |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 误差小于 <paramref name="epsilon" /> 的有理数。 |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | 误差小于 <paramref name="epsilon" /> 的有理数。 |


