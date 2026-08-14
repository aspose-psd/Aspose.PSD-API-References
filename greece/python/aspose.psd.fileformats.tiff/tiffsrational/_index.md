---
title: "Τάξη TiffSRational"
type: docs
weight: 40
url: /el/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| EPSILON [στατικό] | double | r | Το epsilon για τον υπολογισμό κλασματικών τιμών. |
| παρονομαστής | int | r | Επιστρέφει τον παρονομαστή. |
| αριθμητής | int | r | Επιστρέφει τον αριθμητή. |
| value | float | r | Επιστρέφει την τιμή float. |
| value_d | double | r | Επιστρέφει την τιμή double. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Προσεγγίζει την δοθείσα τιμή σε κλάσμα. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| αριθμητής | int | Ο αριθμητής. |
| παρονομαστής | int | Ο παρονομαστής. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | int | Η τιμή του αριθμητή. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από το [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από το [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από <paramref name="epsilon" />. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Ένας ρητός αριθμός με σφάλμα μικρότερο από <paramref name="epsilon" />. |


