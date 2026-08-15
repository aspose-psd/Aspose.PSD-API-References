---
title: "ColorMatrix 클래스"
type: docs
weight: 770
url: /ko/python-net/aspose.psd/colormatrix/
---

**Summary:** Defines a 5 x 5 matrix that contains the coordinates for the RGBA space. Several methods of the [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) class adjust image colors by using a color matrix. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ColorMatrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ColorMatrix()](#ColorMatrix__1) | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 클래스의 새 인스턴스를 초기화합니다. |
| [ColorMatrix(new_color_matrix)](#ColorMatrix_new_color_matrix_2) | 지정된 매트릭스 <paramref name=\"newColorMatrix\" />의 요소를 사용하여 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| MATRIX_DIMENSIONS_COUNT [static] | int | r | 매트릭스 차원의 수입니다. |
| MATRIX_DIMENSION_ELEMENTS_COUNT [static] | int | r | 매트릭스 차원에 있는 요소의 수입니다. |
| MATRIX_TOTAL_ELEMENTS_COUNT [static] | int | r | 매트릭스의 전체 요소 수입니다. |
| matrix00 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 0(영) 행 및 0 열에 있는 요소를 가져오거나 설정합니다. |
| matrix01 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 0(영) 행 및 첫 번째 열에 있는 요소를 가져오거나 설정합니다. |
| matrix02 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 0(영) 행 및 두 번째 열에 있는 요소를 가져오거나 설정합니다. |
| matrix03 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 0(영) 행 및 세 번째 열의 요소를 가져오거나 설정합니다. |
| matrix04 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 0(영) 행 및 네 번째 열의 요소를 가져오거나 설정합니다. |
| matrix10 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 첫 번째 행 및 0(영) 열의 요소를 가져오거나 설정합니다. |
| matrix11 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 첫 번째 행 및 첫 번째 열의 요소를 가져오거나 설정합니다. |
| matrix12 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 첫 번째 행 및 두 번째 열의 요소를 가져오거나 설정합니다. |
| matrix13 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 첫 번째 행 및 세 번째 열의 요소를 가져오거나 설정합니다. |
| matrix14 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 첫 번째 행 및 네 번째 열의 요소를 가져오거나 설정합니다. |
| matrix20 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 두 번째 행 및 0(영) 열의 요소를 가져오거나 설정합니다. |
| matrix21 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 두 번째 행 및 첫 번째 열의 요소를 가져오거나 설정합니다. |
| matrix22 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 두 번째 행 및 두 번째 열의 요소를 가져오거나 설정합니다. |
| matrix23 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 두 번째 행 및 세 번째 열의 요소를 가져오거나 설정합니다. |
| matrix24 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 두 번째 행 및 네 번째 열의 요소를 가져오거나 설정합니다. |
| matrix30 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 세 번째 행 및 0(영) 열의 요소를 가져오거나 설정합니다. |
| matrix31 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 세 번째 행 및 첫 번째 열의 요소를 가져오거나 설정합니다. |
| matrix32 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 세 번째 행 및 두 번째 열의 요소를 가져오거나 설정합니다. |
| matrix33 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 세 번째 행 및 세 번째 열의 요소를 가져오거나 설정합니다. |
| matrix34 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 세 번째 행 및 네 번째 열의 요소를 가져오거나 설정합니다. |
| matrix40 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 네 번째 행 및 0(영) 열의 요소를 가져오거나 설정합니다. |
| matrix41 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 네 번째 행 및 첫 번째 열의 요소를 가져오거나 설정합니다. |
| matrix42 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 네 번째 행 및 두 번째 열의 요소를 가져오거나 설정합니다. |
| matrix43 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 네 번째 행 및 세 번째 열의 요소를 가져오거나 설정합니다. |
| matrix44 | float | r/w | 이 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 네 번째 행 및 네 번째 열의 요소를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [get_matrix()](#get_matrix__1) | 행렬 값을 가져옵니다. |


### Constructor: ColorMatrix() {#ColorMatrix__1}


```
 ColorMatrix() 
```

[ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: ColorMatrix(new_color_matrix) {#ColorMatrix_new_color_matrix_2}


```
 ColorMatrix(new_color_matrix) 
```

지정된 매트릭스 <paramref name=\"newColorMatrix\" />의 요소를 사용하여 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | float[] | 새 [ColorMatrix](/psd/python-net/aspose.psd/colormatrix/)의 요소 값들. |

### Method: get_matrix() {#get_matrix__1}


```
 get_matrix() 
```

행렬 값을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| float[] | 행렬 값 배열. |


