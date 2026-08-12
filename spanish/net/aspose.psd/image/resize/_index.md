---
title: "Image.Resize"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Image. Redimensiona la imagen"
type: docs
weight: 200
url: /es/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Redimensiona la imagen.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | El nuevo alto. |
| resizeType | ResizeType | El tipo de redimensionado. |

### Ver también

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Redimensiona la imagen. Se utiliza el NearestNeighbourResample predeterminado.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | El nuevo alto. |

## Ejemplos

El siguiente ejemplo demuestra cómo redimensionar una imagen PSD y el resultado que obtenemos con Aspose.PSD.

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensiona la imagen.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | Int32 | El nuevo ancho. |
| newHeight | Int32 | El nuevo alto. |
| configuraciones | ImageResizeSettings | Los ajustes de redimensionado. |

### Ver también

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


