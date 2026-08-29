---
title: "TiffRational Klass"
type: docs
weight: 30
url: /sv/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| EPSILON [statisk] | double | r | Epsilon för bråkräkning |
| denominator | uint | r | Hämtar nämnaren. |
| nominator | uint | r | Hämtar täljaren. |
| värde | float | r | Hämtar flyttalsvärdet. |
| value_d | double | r | Hämtar dubbelvärdet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approximerar det angivna värdet till en bråkdel. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approximerar det angivna värdet till en bråkdel. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approximerar det angivna värdet till en bråkdel. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approximerar det angivna värdet till en bråkdel. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nominator | uint | Täljaren. |
| denominator | uint | Nämnaren. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | uint | Täljarens värde. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Approximerar det angivna värdet till en bråkdel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | double | Värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ett rationellt tal med fel mindre än [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Approximerar det angivna värdet till en bråkdel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ett rationellt tal med fel mindre än [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Approximerar det angivna värdet till en bråkdel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | double | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ett rationellt tal med fel mindre än <paramref name=\"epsilon\" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Approximerar det angivna värdet till en bråkdel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | float | Värdet. |
| epsilon | double | Det tillåtna felet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ett rationellt tal med fel mindre än <paramref name=\"epsilon\" />. |


