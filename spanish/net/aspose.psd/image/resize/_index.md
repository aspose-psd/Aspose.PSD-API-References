---
title: Image.Resize
second_title: Referencia de API de Aspose.PSD para .NET
description: Image método. Cambia el tamaño de la imagen. El valor por defectoLeftTopToLeftTopse usa.
type: docs
weight: 190
url: /es/net/aspose.psd/image/resize/
---
## Resize(int, int) {#resize}

Cambia el tamaño de la imagen. El valor por defectoLeftTopToLeftTopse usa.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |

### Ejemplos

El siguiente ejemplo demuestra cómo cambiar el tamaño de la imagen PSD y el resultado que obtenemos con Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Cambia el tamaño de la imagen.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |
| resizeType | ResizeType | El tipo de cambio de tamaño. |

### Ver también

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Cambia el tamaño de la imagen.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | La nueva altura. |
| settings | ImageResizeSettings | La configuración de cambio de tamaño. |

### Ver también

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* espacio de nombres [Aspose.PSD](../../image/)
* asamblea [Aspose.PSD](../../../)


