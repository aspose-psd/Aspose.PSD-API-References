---
title: "ColorMatrix Klasse"
type: docs
weight: 770
url: /de/python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initialisiert eine neue Instanz der [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) Klasse. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initialisiert eine neue Instanz der [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) Klasse unter Verwendung der Elemente in der angegebenen Matrix <paramref name="newColorMatrix" />. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Die Anzahl der Matrixdimensionen. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Die Anzahl der Elemente in einer Matrixdimension. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Die Gesamtzahl der Elemente in der Matrix. |
| matrix00 | float | r/w | Liest oder setzt das Element in der Zeile 0 (null) und Spalte 0 dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix01 | float | r/w | Liest oder setzt das Element in der Zeile 0 (null) und ersten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix02 | float | r/w | Liest oder setzt das Element in der Zeile 0 (null) und zweiten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix03 | float | r/w | Liest oder setzt das Element in der Zeile 0 (null) und dritten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix04 | float | r/w | Liest oder setzt das Element in der Zeile 0 (null) und vierten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix10 | float | r/w | Liest oder setzt das Element in der ersten Zeile und Spalte 0 (null) dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix11 | float | r/w | Liest oder setzt das Element in der ersten Zeile und ersten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix12 | float | r/w | Liest oder setzt das Element in der ersten Zeile und zweiten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix13 | float | r/w | Liest oder setzt das Element in der ersten Zeile und dritten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix14 | float | r/w | Liest oder setzt das Element in der ersten Zeile und vierten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix20 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und Spalte 0 (null) dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix21 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und ersten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix22 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und zweiten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix23 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und dritten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix24 | float | r/w | Liest oder setzt das Element in der zweiten Zeile und vierten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix30 | float | r/w | Liest oder setzt das Element in der dritten Zeile und Spalte 0 (null) dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix31 | float | r/w | Liest oder setzt das Element in der dritten Zeile und ersten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix32 | float | r/w | Liest oder setzt das Element in der dritten Zeile und zweiten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix33 | float | r/w | Liest oder setzt das Element in der dritten Zeile und dritten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix34 | float | r/w | Liest oder setzt das Element in der dritten Zeile und vierten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix40 | float | r/w | Liest oder setzt das Element in der vierten Zeile und 0 (null) Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix41 | float | r/w | Liest oder setzt das Element in der vierten Zeile und ersten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix42 | float | r/w | Liest oder setzt das Element in der vierten Zeile und zweiten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix43 | float | r/w | Liest oder setzt das Element in der vierten Zeile und dritten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix44 | float | r/w | Liest oder setzt das Element in der vierten Zeile und vierten Spalte dieser [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | Liest die Matrixwerte. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initialisiert eine neue Instanz der [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) Klasse.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initialisiert eine neue Instanz der [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) Klasse unter Verwendung der Elemente in der angegebenen Matrix <paramref name="newColorMatrix" />.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | float[] | Die Werte der Elemente für die neue [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

Liest die Matrixwerte.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float[] | Das Array der Matrixwerte. |


