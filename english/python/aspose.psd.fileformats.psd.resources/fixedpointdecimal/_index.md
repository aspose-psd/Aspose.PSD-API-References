---
title: FixedPointDecimal Class
type: docs
weight: 80
url: /python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/
---

**Summary:** Fixed-point decimal, with 16-bit integer and 16-bit fraction.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.FixedPointDecimal

**Aspose.PSD Version:** 23.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FixedPointDecimal(integer, fraction)](#FixedPointDecimal_integer_fraction_1) | Initializes a new instance of the [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) class. |
| [FixedPointDecimal(value)](#FixedPointDecimal_value_2) | Initializes a new instance of the [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) class. Split the high and low words of a 32-bit integer into a fixed-point number. |
| [FixedPointDecimal(value)](#FixedPointDecimal_value_3) | Initializes a new instance of the [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) class. Split the high and low words of a 32-bit integer into a fixed-point number. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fraction | int | r/w | Gets or sets the fraction. |
| integer | int | r/w | Gets or sets the integer. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [to_double()](#to_double__1) | Converts current fixed point decimal to double. |


### Constructor: FixedPointDecimal(integer, fraction) {#FixedPointDecimal_integer_fraction_1}


```
 FixedPointDecimal(integer, fraction) 
```

Initializes a new instance of the [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| integer | int | The integer. |
| fraction | int | The fraction. |

### Constructor: FixedPointDecimal(value) {#FixedPointDecimal_value_2}


```
 FixedPointDecimal(value) 
```

Initializes a new instance of the [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) class. Split the high and low words of a 32-bit integer into a fixed-point number.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | long | The value. |

### Constructor: FixedPointDecimal(value) {#FixedPointDecimal_value_3}


```
 FixedPointDecimal(value) 
```

Initializes a new instance of the [FixedPointDecimal](/psd/python-net/aspose.psd.fileformats.psd.resources/fixedpointdecimal/) class. Split the high and low words of a 32-bit integer into a fixed-point number.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double | The value. |

### Method: to_double() {#to_double__1}


```
 to_double() 
```

Converts current fixed point decimal to double.

**Returns**

| Type | Description |
| :- | :- |
| double | The converted value. |


