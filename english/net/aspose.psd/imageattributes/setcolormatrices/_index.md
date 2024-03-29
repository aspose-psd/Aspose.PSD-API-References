---
title: ImageAttributes.SetColorMatrices
second_title: Aspose.PSD for .NET API Reference
description: ImageAttributes method. Sets the coloradjustment matrix and the grayscaleadjustment matrix for the default category
type: docs
weight: 130
url: /net/aspose.psd/imageattributes/setcolormatrices/
---
{{< psd/tize >}}
## SetColorMatrices(ColorMatrix, ColorMatrix) {#setcolormatrices}

Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | The color-adjustment matrix. |
| grayMatrix | ColorMatrix | The grayscale-adjustment matrix. |

### See Also

* class [ColorMatrix](../../colormatrix/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag) {#setcolormatrices_1}

Sets the color-adjustment matrix and the grayscale-adjustment matrix for the default category.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag flags)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | The color-adjustment matrix. |
| grayMatrix | ColorMatrix | The grayscale-adjustment matrix. |
| flags | ColorMatrixFlag | An element of [`ColorMatrixFlag`](../../colormatrixflag/) that specifies the type of image and color that will be affected by the color-adjustment and grayscale-adjustment matrices. |

### See Also

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) {#setcolormatrices_2}

Sets the color-adjustment matrix and the grayscale-adjustment matrix for a specified category.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag mode, ColorAdjustType type)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | The color-adjustment matrix. |
| grayMatrix | ColorMatrix | The grayscale-adjustment matrix. |
| mode | ColorMatrixFlag | An element of [`ColorMatrixFlag`](../../colormatrixflag/) that specifies the type of image and color that will be affected by the color-adjustment and grayscale-adjustment matrices. |
| type | ColorAdjustType | An element of [`ColorAdjustType`](../../coloradjusttype/) that specifies the category for which the color-adjustment and grayscale-adjustment matrices are set. |

### See Also

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


