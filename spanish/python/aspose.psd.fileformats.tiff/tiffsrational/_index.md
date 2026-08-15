---
title: "Clase TiffSRational"
type: docs
weight: 40
url: /es/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Inicializa una nueva instancia de la clase [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Inicializa una nueva instancia de la clase [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| EPSILON [estático] | double | r | El epsilon para el cálculo de fracciones |
| denominador | int | r | Obtiene el denominador. |
| numerador | int | r | Obtiene el numerador. |
| value | float | r | Obtiene el valor flotante. |
| value_d | double | r | Obtiene el valor doble. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Aproxima el valor proporcionado a una fracción. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Inicializa una nueva instancia de la clase [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Inicializa una nueva instancia de la clase [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| numerador | int | El numerador. |
| denominador | int | El denominador. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | int | El valor del numerador. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | double | El valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un número racional con un error menor que [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | float | El valor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un número racional con un error menor que [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | double | El valor. |
| epsilon | double | El error permitido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un número racional con un error menor que <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Aproxima el valor proporcionado a una fracción.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | float | El valor. |
| epsilon | double | El error permitido. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un número racional con un error menor que <paramref name="epsilon" />. |


