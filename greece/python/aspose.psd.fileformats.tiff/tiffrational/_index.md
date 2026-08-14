---
title: "Τάξη TiffRational"
type: docs
weight: 30
url: /el/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| EPSILON [στατικό] | double | r | Το epsilon για τον υπολογισμό κλασματικών τιμών. |
| παρονομαστής | uint | r | Επιστρέφει τον παρονομαστή. |
| αριθμητής | uint | r | Επιστρέφει τον αριθμητή. |
| value | float | r | Επιστρέφει την τιμή float. |
| value_d | double | r | Επιστρέφει την τιμή double. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| αριθμητής | uint | Ο αριθμητής. |
| παρονομαστής | uint | Ο παρονομαστής. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | uint | Η τιμή του αριθμητή. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Προσεγγίζει την δοθείσα τιμή σε κλάσμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | double | Η value. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Προσεγγίζει την δοθείσα τιμή σε κλάσμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | float | Η value. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Προσεγγίζει την δοθείσα τιμή σε κλάσμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | double | Η value. |
| epsilon | double | Το επιτρεπόμενο σφάλμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Προσεγγίζει την δοθείσα τιμή σε κλάσμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | float | Η value. |
| epsilon | double | Το επιτρεπόμενο σφάλμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από <paramref name="epsilon" />. |


