---
title: "RasterCachedImage.Resize"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RasterCachedImage. Redimensiona la imagen"
type: docs
weight: 120
url: /es/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Redimensiona la imagen.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | El nuevo alto. |
| resizeType | ResizeType | El tipo de redimensionado. |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensiona la imagen.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | El nuevo alto. |
| configuraciones | ImageResizeSettings | Los ajustes de redimensionado. |

### Ver también

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


