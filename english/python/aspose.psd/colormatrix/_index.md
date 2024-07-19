---
title: ColorMatrix Class
type: docs
weight: 720
url: /python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | Initializes a new instance of the [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) class. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | Initializes a new instance of the [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) class using the elements in the specified matrix <paramref name="newColorMatrix" />. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | The number of matrix dimensions. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | The number of elements in matrix dimension. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | The total number of elements in the matrix. |
| matrix00 | float | r/w | Gets or sets the element at the 0 (zero) row and 0 column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix01 | float | r/w | Gets or sets the element at the 0 (zero) row and first column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix02 | float | r/w | Gets or sets the element at the 0 (zero) row and second column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix03 | float | r/w | Gets or sets the element at the 0 (zero) row and third column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix04 | float | r/w | Gets or sets the element at the 0 (zero) row and fourth column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix10 | float | r/w | Gets or sets the element at the first row and 0 (zero) column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix11 | float | r/w | Gets or sets the element at the first row and first column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix12 | float | r/w | Gets or sets the element at the first row and second column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix13 | float | r/w | Gets or sets the element at the first row and third column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix14 | float | r/w | Gets or sets the element at the first row and fourth column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix20 | float | r/w | Gets or sets the element at the second row and 0 (zero) column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix21 | float | r/w | Gets or sets the element at the second row and first column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix22 | float | r/w | Gets or sets the element at the second row and second column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix23 | float | r/w | Gets or sets the element at the second row and third column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix24 | float | r/w | Gets or sets the element at the second row and fourth column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix30 | float | r/w | Gets or sets the element at the third row and 0 (zero) column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix31 | float | r/w | Gets or sets the element at the third row and first column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix32 | float | r/w | Gets or sets the element at the third row and second column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix33 | float | r/w | Gets or sets the element at the third row and third column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix34 | float | r/w | Gets or sets the element at the third row and fourth column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix40 | float | r/w | Gets or sets the element at the fourth row and 0 (zero) column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix41 | float | r/w | Gets or sets the element at the fourth row and first column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix42 | float | r/w | Gets or sets the element at the fourth row and second column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix43 | float | r/w | Gets or sets the element at the fourth row and third column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
| matrix44 | float | r/w | Gets or sets the element at the fourth row and fourth column of this [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | Gets the matrix values. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

Initializes a new instance of the [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) class.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

Initializes a new instance of the [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) class using the elements in the specified matrix <paramref name="newColorMatrix" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_matrix | float[] | The values of the elements for the new [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/). |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

Gets the matrix values.

**Returns**

| Type | Description |
| :- | :- |
| float[] | The matrix values array. |


