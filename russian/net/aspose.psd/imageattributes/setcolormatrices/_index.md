---
title: "ImageAttributes.SetColorMatrices"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageAttributes. Устанавливает матрицу коррекции цвета и матрицу коррекции оттенков серого для категории по умолчанию."
type: docs
weight: 130
url: /ru/net/aspose.psd/imageattributes/setcolormatrices/
---
{{< psd/tize >}}
## SetColorMatrices(ColorMatrix, ColorMatrix) {#setcolormatrices}

Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | Матрица коррекции цвета. |
| grayMatrix | ColorMatrix | Матрица корректировки градаций серого. |

### См. также

* class [ColorMatrix](../../colormatrix/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag) {#setcolormatrices_1}

Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для категории по умолчанию.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | Матрица коррекции цвета. |
| grayMatrix | ColorMatrix | Матрица корректировки градаций серого. |
| flags | ColorMatrixFlag | Элемент [`ColorMatrixFlag`](../../colormatrixflag/), который определяет тип изображения и цвета, которые будут затронуты матрицами корректировки цвета и градаций серого. |

### См. также

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) {#setcolormatrices_2}

Устанавливает матрицу коррекции цвета и матрицу коррекции градаций серого для указанной категории.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag mode, ColorAdjustType type)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | Матрица коррекции цвета. |
| grayMatrix | ColorMatrix | Матрица корректировки градаций серого. |
| mode | ColorMatrixFlag | Элемент [`ColorMatrixFlag`](../../colormatrixflag/), который определяет тип изображения и цвета, которые будут затронуты матрицами корректировки цвета и градаций серого. |
| type | ColorAdjustType | Элемент [`ColorAdjustType`](../../coloradjusttype/), который указывает категорию, для которой задаются матрицы корректировки цвета и градаций серого. |

### См. также

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


