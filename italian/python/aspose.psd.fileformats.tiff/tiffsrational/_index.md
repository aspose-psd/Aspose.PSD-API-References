---
title: "Classe TiffSRational"
type: docs
weight: 40
url: /it/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Inizializza una nuova istanza della classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Inizializza una nuova istanza della classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [statico] | double | r | L'epsilon per il calcolo della frazione |
| denominatore | int | r | Restituisce il denominatore. |
| numeratore | int | r | Restituisce il numeratore. |
| value | float | r | Restituisce il valore float. |
| value_d | double | r | Restituisce il valore double. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approssima il valore fornito a una frazione. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Inizializza una nuova istanza della classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Inizializza una nuova istanza della classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| numeratore | int | Il numeratore. |
| denominatore | int | Il denominatore. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | int | Il valore del numeratore. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | double | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un numero razionale con errore inferiore a [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | float | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un numero razionale con errore inferiore a [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | double | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un numero razionale con errore inferiore a <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | float | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un numero razionale con errore inferiore a <paramref name="epsilon" />. |


