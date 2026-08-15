---
title: "ColorMatrix-klasse"
type: docs
weight: 770
url: /nl/python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initialiseert een nieuw exemplaar van de [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) klasse. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initialiseert een nieuw exemplaar van de [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) klasse met behulp van de elementen in de opgegeven matrix <paramref name="newColorMatrix" />. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | Het aantal matrixdimensies. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | Het aantal elementen in de matrixdimensie. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | Het totale aantal elementen in de matrix. |
| matrix00 | float | r/w | Haalt of stelt het element in op de 0 (nul) rij en 0 kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix01 | float | r/w | Haalt of stelt het element in op de 0 (nul) rij en eerste kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix02 | float | r/w | Haalt of stelt het element in op de 0 (nul) rij en tweede kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix03 | float | r/w | Haalt of stelt het element in op de 0 (nul) rij en derde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix04 | float | r/w | Haalt of stelt het element in op de 0 (nul) rij en vierde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix10 | float | r/w | Haalt of stelt het element in op de eerste rij en 0 (nul) kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix11 | float | r/w | Haalt of stelt het element in op de eerste rij en eerste kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix12 | float | r/w | Haalt of stelt het element in op de eerste rij en tweede kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix13 | float | r/w | Haalt of stelt het element in op de eerste rij en derde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix14 | float | r/w | Haalt of stelt het element in op de eerste rij en vierde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix20 | float | r/w | Haalt of stelt het element in op de tweede rij en 0 (nul) kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix21 | float | r/w | Haalt of stelt het element in op de tweede rij en eerste kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix22 | float | r/w | Haalt of stelt het element in op de tweede rij en tweede kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix23 | float | r/w | Haalt of stelt het element in op de tweede rij en derde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix24 | float | r/w | Haalt of stelt het element in op de tweede rij en vierde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix30 | float | r/w | Haalt of stelt het element in op de derde rij en 0 (nul) kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix31 | float | r/w | Haalt of stelt het element in op de derde rij en eerste kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix32 | float | r/w | Haalt of stelt het element in op de derde rij en tweede kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix33 | float | r/w | Haalt of stelt het element in op de derde rij en derde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix34 | float | r/w | Haalt of stelt het element in op de derde rij en vierde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix40 | float | r/w | Haalt of stelt het element in op de vierde rij en 0 (nul) kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix41 | float | r/w | Haalt het element op of stelt het in op de vierde rij en eerste kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix42 | float | r/w | Haalt het element op of stelt het in op de vierde rij en tweede kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix43 | float | r/w | Haalt het element op of stelt het in op de vierde rij en derde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix44 | float | r/w | Haalt het element op of stelt het in op de vierde rij en vierde kolom van deze [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | Haalt de matrixwaarden op. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initialiseert een nieuw exemplaar van de [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) klasse.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initialiseert een nieuw exemplaar van de [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) klasse met behulp van de elementen in de opgegeven matrix <paramref name="newColorMatrix" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | float[] | De waarden van de elementen voor de nieuwe [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

Haalt de matrixwaarden op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| float[] | De matrixwaarden-array. |


