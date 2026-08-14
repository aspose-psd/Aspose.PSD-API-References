---
title: "ColorMatrix クラス"
type: docs
weight: 770
url: /ja/python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) クラスの新しいインスタンスを初期化します。 |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | 指定されたマトリックス <paramref name="newColorMatrix" /> の要素を使用して、[ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | マトリックスの次元数です。 |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | マトリックス次元の要素数です。 |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | マトリックス内の要素総数です。 |
| matrix00 | float | r/w | この [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) の 0 行目（ゼロ）および 0 列目の要素を取得または設定します。 |
| matrix01 | float | r/w | この [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) の 0 行目（ゼロ）および最初の列の要素を取得または設定します。 |
| matrix02 | float | r/w | この [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) の 0 行目（ゼロ）および2番目の列の要素を取得または設定します。 |
| matrix03 | float | r/w | この[ColorMatrix]の0（ゼロ）行目と3列目の要素を取得または設定します。 |
| matrix04 | float | r/w | この[ColorMatrix]の0（ゼロ）行目と4列目の要素を取得または設定します。 |
| matrix10 | float | r/w | この[ColorMatrix]の1行目と0（ゼロ）列目の要素を取得または設定します。 |
| matrix11 | float | r/w | この[ColorMatrix]の1行目と1列目の要素を取得または設定します。 |
| matrix12 | float | r/w | この[ColorMatrix]の1行目と2列目の要素を取得または設定します。 |
| matrix13 | float | r/w | この[ColorMatrix]の1行目と3列目の要素を取得または設定します。 |
| matrix14 | float | r/w | この[ColorMatrix]の1行目と4列目の要素を取得または設定します。 |
| matrix20 | float | r/w | この[ColorMatrix]の2行目と0（ゼロ）列目の要素を取得または設定します。 |
| matrix21 | float | r/w | この[ColorMatrix]の2行目と1列目の要素を取得または設定します。 |
| matrix22 | float | r/w | この[ColorMatrix]の2行目と2列目の要素を取得または設定します。 |
| matrix23 | float | r/w | この[ColorMatrix]の2行目と3列目の要素を取得または設定します。 |
| matrix24 | float | r/w | この[ColorMatrix]の2行目と4列目の要素を取得または設定します。 |
| matrix30 | float | r/w | この[ColorMatrix]の3行目と0（ゼロ）列目の要素を取得または設定します。 |
| matrix31 | float | r/w | この[ColorMatrix]の3行目と1列目の要素を取得または設定します。 |
| matrix32 | float | r/w | この[ColorMatrix]の3行目と2列目の要素を取得または設定します。 |
| matrix33 | float | r/w | この[ColorMatrix]の3行目と3列目の要素を取得または設定します。 |
| matrix34 | float | r/w | この[ColorMatrix]の3行目と4列目の要素を取得または設定します。 |
| matrix40 | float | r/w | この[ColorMatrix]の4行目と0（ゼロ）列目の要素を取得または設定します。 |
| matrix41 | float | r/w | この[ColorMatrix]の4行目と1列目の要素を取得または設定します。 |
| matrix42 | float | r/w | この[ColorMatrix]の4行目と2列目の要素を取得または設定します。 |
| matrix43 | float | r/w | この[ColorMatrix]の4行目と3列目の要素を取得または設定します。 |
| matrix44 | float | r/w | この[ColorMatrix]の4行目と4列目の要素を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | 行列の値を取得します。 |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

[ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) クラスの新しいインスタンスを初期化します。

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

指定されたマトリックス <paramref name="newColorMatrix" /> の要素を使用して、[ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | float[] | 新しい[ColorMatrix]の要素の値です。 |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

行列の値を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| float[] | 行列の値配列。 |


