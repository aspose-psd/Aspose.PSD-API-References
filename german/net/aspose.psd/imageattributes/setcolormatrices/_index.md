---
title: "ImageAttributes.SetColorMatrices"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageAttributes-Methode. Setzt die coloradjustment-Matrix und die grayscaleadjustment-Matrix für die Standardkategorie"
type: docs
weight: 130
url: /de/net/aspose.psd/imageattributes/setcolormatrices/
---
{{< psd/tize >}}
## SetColorMatrices(ColorMatrix, ColorMatrix) {#setcolormatrices}

Setzt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | Die color-adjustment-Matrix. |
| grayMatrix | ColorMatrix | Die grayscale-adjustment-Matrix. |

### Siehe auch

* class [ColorMatrix](../../colormatrix/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag) {#setcolormatrices_1}

Setzt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag flags)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | Die color-adjustment-Matrix. |
| grayMatrix | ColorMatrix | Die grayscale-adjustment-Matrix. |
| flags | ColorMatrixFlag | Ein Element von [`ColorMatrixFlag`](../../colormatrixflag/), das den Bild- und Farbtyp angibt, der von den color-adjustment- und grayscale-adjustment-Matrizen betroffen ist. |

### Siehe auch

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetColorMatrices(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) {#setcolormatrices_2}

Setzt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für eine angegebene Kategorie.

```csharp
public void SetColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, 
    ColorMatrixFlag mode, ColorAdjustType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | ColorMatrix | Die color-adjustment-Matrix. |
| grayMatrix | ColorMatrix | Die grayscale-adjustment-Matrix. |
| mode | ColorMatrixFlag | Ein Element von [`ColorMatrixFlag`](../../colormatrixflag/), das den Bild- und Farbtyp angibt, der von den color-adjustment- und grayscale-adjustment-Matrizen betroffen ist. |
| type | ColorAdjustType | Ein Element von [`ColorAdjustType`](../../coloradjusttype/), das die Kategorie angibt, für die die color-adjustment- und grayscale-adjustment-Matrizen festgelegt werden. |

### Siehe auch

* class [ColorMatrix](../../colormatrix/)
* enum [ColorMatrixFlag](../../colormatrixflag/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


