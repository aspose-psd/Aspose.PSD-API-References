---
title: "Clase TiffRational"
type: docs
weight: 30
url: /es/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| EPSILON [estático] | double | r | El epsilon para el cálculo de fracciones |
| denominador | uint | r | Obtiene el denominador. |
| numerador | uint | r | Obtiene el numerador. |
| value | float | r | Obtiene el valor flotante. |
| value_d | double | r | Obtiene el valor doble. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Aproxima el valor proporcionado a una fracción. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Aproxima el valor proporcionado a una fracción. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| numerador | uint | El numerador. |
| denominador | uint | El denominador. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Inicializa una nueva instancia de la clase [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| value | uint | El valor del numerador. |

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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un número racional con un error menor que [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un número racional con un error menor que [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un número racional con un error menor que <paramref name="epsilon" />. |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un número racional con un error menor que <paramref name="epsilon" />. |


