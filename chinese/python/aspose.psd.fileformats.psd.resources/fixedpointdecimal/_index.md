---
title: "FixedPointDecimal 类"
type: docs
weight: 80
url: /zh/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Summary:** Fixed-point decimal, with 16-bit integer and 16-bit fraction.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.FixedPointDecimal

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FixedPointDecimal(integer, fraction)](#FixedPointDecimal_integer_fraction_1) | 初始化 [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) 类的新实例。 |
| [FixedPointDecimal(value)](#FixedPointDecimal_value_2) | 初始化 [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) 类的新实例。将 32 位整数的高位和低位拆分为定点数。 |
| [FixedPointDecimal(value)](#FixedPointDecimal_value_3) | 初始化 [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) 类的新实例。将 32 位整数的高位和低位拆分为定点数。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fraction | int | 读/写 | 获取或设置分数。 |
| integer | int | 读/写 | 获取或设置整数。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_double()](#to_double__1) | 将当前定点小数转换为 double。 |


### Constructor: FixedPointDecimal(integer, fraction) {#FixedPointDecimal_integer_fraction_1}


```
 FixedPointDecimal(integer, fraction) 
```

初始化 [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| integer | int | 整数。 |
| fraction | int | 分数。 |

### Constructor: FixedPointDecimal(value) {#FixedPointDecimal_value_2}


```
 FixedPointDecimal(value) 
```

初始化 [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) 类的新实例。将 32 位整数的高位和低位拆分为定点数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | long | 值。 |

### Constructor: FixedPointDecimal(value) {#FixedPointDecimal_value_3}


```
 FixedPointDecimal(value) 
```

初始化 [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) 类的新实例。将 32 位整数的高位和低位拆分为定点数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 值。 |

### Method: to_double() {#to_double__1}


```
 to_double() 
```

将当前定点小数转换为 double。

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 转换后的值。 |


