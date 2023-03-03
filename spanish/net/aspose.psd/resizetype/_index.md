---
title: Enum ResizeType
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ResizeType enumeración. Especifica el tipo de cambio de tamaño.
type: docs
weight: 5370
url: /es/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Especifica el tipo de cambio de tamaño.

```csharp
public enum ResizeType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Los píxeles no se conservan durante la operación de cambio de tamaño. |
| LeftTopToLeftTop | `1` | El punto superior izquierdo de la nueva imagen coincidirá con el punto superior izquierdo de la imagen original. Se recortará si es necesario. |
| RightTopToRightTop | `2` | El punto superior derecho de la nueva imagen coincidirá con el punto superior derecho de la imagen original. Se recortará si es necesario. |
| RightBottomToRightBottom | `3` | El punto inferior derecho de la nueva imagen coincidirá con el punto inferior derecho de la imagen original. Se recortará si es necesario. |
| LeftBottomToLeftBottom | `4` | El punto inferior izquierdo de la nueva imagen coincidirá con el punto inferior izquierdo de la imagen original. Se recortará si es necesario. |
| CenterToCenter | `5` | El centro de la nueva imagen coincidirá con el centro de la imagen original. Se recortará si es necesario. |
| LanczosResample | `6` | Remuestrear usando el algoritmo lanczos con a=3. |
| NearestNeighbourResample | `7` | Remuestrear usando el algoritmo del vecino más cercano. |
| AdaptiveResample | `8` | Remuestreo usando algoritmo adaptativo basado en función racional ponderada y combinada y algoritmos de interpolación lanczos3. |
| BilinearResample | `9` | Volver a muestrear mediante interpolación bilineal. Se permite el prefiltrado de imágenes para eliminar el ruido antes de volver a muestrear, cuando sea necesario |
| HighQualityResample | `10` | La remuestra de alta calidad |
| CatmullRom | `11` | El método de interpolación cúbica Catmull-Rom. |
| CubicConvolution | `12` | El método de interpolación de convolución cúbica |
| CubicBSpline | `13` | El método de interpolación cúbica CubicBSpline |
| Mitchell | `14` | El método de interpolación cúbica de Mitchell |
| SinC | `15` | El método de interpolación cúbica Sinc (Lanczos3) |
| Bell | `16` | El método de interpolación de Bell |

### Ejemplos

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de cambio de tamaño SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de cambio de tamaño de Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

El código siguiente muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de cambio de tamaño de Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

El código siguiente muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de cambio de tamaño CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de cambio de tamaño CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

El siguiente código muestra cómo cambiar el tamaño de una imagen con un nuevo tipo de cambio de tamaño CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Carga una imagen existente en una instancia de la clase PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


