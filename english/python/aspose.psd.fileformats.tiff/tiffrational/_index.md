---
title: TiffRational Class
type: docs
weight: 30
url: /python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class. |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class. |
| [TiffRational(value)](#TiffRational_value_3) | Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | The epsilon for fraction calculation |
| denominator | uint | r | Gets the denominator. |
| nominator | uint | r | Gets the nominator. |
| value | float | r | Gets the float value. |
| value_d | double | r | Gets the double value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approximates the provided value to a fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approximates the provided value to a fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approximates the provided value to a fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approximates the provided value to a fraction. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class.

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| nominator | uint | The nominator. |
| denominator | uint | The denominator. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | uint | The nominator value. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | A rational number having error less than [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | A rational number having error less than [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | double | The value. |
| epsilon | double | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | A rational number having error less than <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Approximates the provided value to a fraction.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | float | The value. |
| epsilon | double | The error allowed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | A rational number having error less than <paramref name="epsilon" />. |


