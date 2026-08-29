---
title: "Enumeración ResizeType"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.ResizeType. Especifica el tipo de redimensionamiento"
type: docs
weight: 5870
url: /es/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Especifica el tipo de redimensionamiento.

```csharp
public enum ResizeType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Los píxeles no se conservan durante la operación de redimensionamiento. |
| LeftTopToLeftTop | `1` | El punto superior izquierdo de la nueva imagen coincidirá con el punto superior izquierdo de la imagen original. Se recortará si es necesario. |
| RightTopToRightTop | `2` | El punto superior derecho de la nueva imagen coincidirá con el punto superior derecho de la imagen original. Se recortará si es necesario. |
| RightBottomToRightBottom | `3` | El punto inferior derecho de la nueva imagen coincidirá con el punto inferior derecho de la imagen original. Se recortará si es necesario. |
| LeftBottomToLeftBottom | `4` | El punto inferior izquierdo de la nueva imagen coincidirá con el punto inferior izquierdo de la imagen original. Se recortará si es necesario. |
| CenterToCenter | `5` | El centro de la nueva imagen coincidirá con el centro de la imagen original. Se recortará si es necesario. |
| LanczosResample | `6` | Remuestrear usando el algoritmo Lanczos con a=3. |
| NearestNeighbourResample | `7` | Remuestrear usando el algoritmo de vecino más cercano. |
| AdaptiveResample | `8` | Remuestrear usando un algoritmo adaptativo basado en funciones racionales ponderadas y combinadas y algoritmos de interpolación Lanczos3. |
| BilinearResample | `9` | Remuestrear usando interpolación bilineal. Se permite el prefiltrado de la imagen para eliminar el ruido antes del remuestreo, cuando sea necesario. |
| HighQualityResample | `10` | El remuestreo de alta calidad |
| CatmullRom | `11` | El método de interpolación cúbica Catmull-Rom. |
| CubicConvolution | `12` | El método de interpolación Cubic Convolution |
| CubicBSpline | `13` | El método de interpolación cúbica CubicBSpline |
| Mitchell | `14` | El método de interpolación cúbica Mitchell |
| SinC | `15` | El método de interpolación cúbica Sinc (Lanczos3) |
| Bell | `16` | El método de interpolación Bell |

## Ejemplos

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de redimensionado SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de redimensionado Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de redimensionado Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de redimensionado CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de redimensionado CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de redimensionado CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


