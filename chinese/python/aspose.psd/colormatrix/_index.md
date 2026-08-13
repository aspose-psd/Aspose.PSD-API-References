---
title: "ColorMatrix 类"
type: docs
weight: 770
url: /zh/python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | 初始化 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 类的新实例。 |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | 使用指定矩阵 <paramref name="newColorMatrix" /> 中的元素初始化 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | 矩阵维度的数量。 |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | 矩阵维度中元素的数量。 |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | 矩阵中元素的总数。 |
| matrix00 | float | r/w | 获取或设置此 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 第 0（零）行第 0 列的元素。 |
| matrix01 | float | r/w | 获取或设置此 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 第 0（零）行第一列的元素。 |
| matrix02 | float | r/w | 获取或设置此 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 第 0（零）行第二列的元素。 |
| matrix03 | float | r/w | 获取或设置此 [ColorMatrix] 的第 0（零）行和第三列的元素. |
| matrix04 | float | r/w | 获取或设置此 [ColorMatrix] 的第 0（零）行和第四列的元素. |
| matrix10 | float | r/w | 获取或设置此 [ColorMatrix] 的第一行和第 0（零）列的元素. |
| matrix11 | float | r/w | 获取或设置此 [ColorMatrix] 的第一行和第一列的元素. |
| matrix12 | float | r/w | 获取或设置此 [ColorMatrix] 的第一行和第二列的元素. |
| matrix13 | float | r/w | 获取或设置此 [ColorMatrix] 的第一行和第三列的元素. |
| matrix14 | float | r/w | 获取或设置此 [ColorMatrix] 的第一行和第四列的元素. |
| matrix20 | float | r/w | 获取或设置此 [ColorMatrix] 的第二行和第 0（零）列的元素. |
| matrix21 | float | r/w | 获取或设置此 [ColorMatrix] 的第二行和第一列的元素. |
| matrix22 | float | r/w | 获取或设置此 [ColorMatrix] 的第二行和第二列的元素. |
| matrix23 | float | r/w | 获取或设置此 [ColorMatrix] 的第二行和第三列的元素. |
| matrix24 | float | r/w | 获取或设置此 [ColorMatrix] 的第二行和第四列的元素. |
| matrix30 | float | r/w | 获取或设置此 [ColorMatrix] 的第三行和第 0（零）列的元素. |
| matrix31 | float | r/w | 获取或设置此 [ColorMatrix] 的第三行和第一列的元素. |
| matrix32 | float | r/w | 获取或设置此 [ColorMatrix] 的第三行和第二列的元素. |
| matrix33 | float | r/w | 获取或设置此 [ColorMatrix] 的第三行和第三列的元素. |
| matrix34 | float | r/w | 获取或设置此 [ColorMatrix] 的第三行和第四列的元素. |
| matrix40 | float | r/w | 获取或设置此 [ColorMatrix] 的第四行和第 0（零）列的元素. |
| matrix41 | float | r/w | 获取或设置此 [ColorMatrix] 的第四行和第一列的元素. |
| matrix42 | float | r/w | 获取或设置此 [ColorMatrix] 的第四行和第二列的元素. |
| matrix43 | float | r/w | 获取或设置此 [ColorMatrix] 的第四行和第三列的元素. |
| matrix44 | float | r/w | 获取或设置此 [ColorMatrix] 的第四行和第四列的元素. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | 获取矩阵的值. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

初始化 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 类的新实例。

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

使用指定矩阵 <paramref name="newColorMatrix" /> 中的元素初始化 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_color_matrix | float[] | 新的 [ColorMatrix] 的元素值. |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

获取矩阵的值.

**Returns**

| 类型 | 描述 |
| :- | :- |
| float[] | 矩阵值数组。 |


