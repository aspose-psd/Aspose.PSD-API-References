---
title: "TiffSRational-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initierar en ny instans av klassen [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initierar en ny instans av klassen [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| EPSILON [statisk] | double | r | Epsilon för bråkräkning |
| denominator | int | r | Hämtar nämnaren. |
| nominator | int | r | Hämtar täljaren. |
| värde | float | r | Hämtar flyttalsvärdet. |
| value_d | double | r | Hämtar dubbelvärdet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approximerar det angivna värdet till en bråkdel. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approximerar det angivna värdet till en bråkdel. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approximerar det angivna värdet till en bråkdel. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approximerar det angivna värdet till en bråkdel. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initierar en ny instans av klassen [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initierar en ny instans av klassen [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| nominator | int | Täljaren. |
| denominator | int | Nämnaren. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initierar en ny instans av klassen [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värde | int | Täljarens värde. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ett rationellt tal med fel mindre än [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ett rationellt tal med fel mindre än [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ett rationellt tal med fel mindre än <paramref name=\"epsilon\" />. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ett rationellt tal med fel mindre än <paramref name=\"epsilon\" />. |


