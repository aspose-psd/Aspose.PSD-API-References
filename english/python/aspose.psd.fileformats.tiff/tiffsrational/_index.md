---
title: TiffSRational Class
type: docs
weight: 40
url: /python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.1.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initializes a new instance of the [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) class. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initializes a new instance of the [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) class. |
| [TiffSRational(value)](#TiffSRational_value_3) | Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [static] | double | r | The epsilon for fraction calculation |
| denominator | int | r | Gets the denominator. |
| nominator | int | r | Gets the nominator. |
| value | float | r | Gets the float value. |
| value_d | double | r | Gets the double value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approximates the provided value to a fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approximates the provided value to a fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approximates the provided value to a fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approximates the provided value to a fraction. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initializes a new instance of the [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) class.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initializes a new instance of the [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| nominator | int | The nominator. |
| denominator | int | The denominator. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initializes a new instance of the [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | int | The nominator value. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | A rational number having error less than [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | A rational number having error less than [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | A rational number having error less than <paramref name="epsilon" />. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | A rational number having error less than <paramref name="epsilon" />. |


