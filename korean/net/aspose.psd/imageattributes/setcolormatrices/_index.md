---
title: "ImageAttributes.SetColorMatrices"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageAttributes 메서드. 기본 카테고리에 대한 coloradjustment 매트릭스와 grayscaleadjustment 매트릭스를 설정합니다"
type: docs
weight: 130
url: /ko/net/aspose.psd/imageattributes/setcolormatrices/
---
{{< psd/tize >}}
## SetColorMatrices(ColorMatrix, ColorMatrix) {#setcolormatrices}

기본 카테고리의 색 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | color-adjustment 매트릭스. |
| grayMatrix | ColorMatrix | grayscale-adjustment 매트릭스. |

### 또 보기

* class [ColorMatrix](../../colormatrix/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag) {#setcolormatrices_1}

기본 카테고리의 색 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag flags)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | color-adjustment 매트릭스. |
| grayMatrix | ColorMatrix | grayscale-adjustment 매트릭스. |
| flags | ColorMatrixFlag | color-adjustment 및 grayscale-adjustment 매트릭스에 영향을 받는 이미지 및 색상의 유형을 지정하는 [`ColorMatrixFlag`](../../colormatrixflag/) 요소. |

### 또 보기

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) {#setcolormatrices_2}

지정된 카테고리의 색 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag mode, ColorAdjustType type)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | color-adjustment 매트릭스. |
| grayMatrix | ColorMatrix | grayscale-adjustment 매트릭스. |
| mode | ColorMatrixFlag | color-adjustment 및 grayscale-adjustment 매트릭스에 영향을 받는 이미지 및 색상의 유형을 지정하는 [`ColorMatrixFlag`](../../colormatrixflag/) 요소. |
| type | ColorAdjustType | color-adjustment 및 grayscale-adjustment 매트릭스가 설정되는 카테고리를 지정하는 [`ColorAdjustType`](../../coloradjusttype/) 요소. |

### 또 보기

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


