---
title: RasterImage.Crop
second_title: Referencia de API de Aspose.PSD para .NET
description: RasterImage método. Recorta el rectángulo especificado.
type: docs
weight: 240
url: /es/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Recorta el rectángulo especificado.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rectangle | Rectangle | el rectángulo |

### Ejemplos

El siguiente ejemplo de código muestra cómo recortar una imagen y guardarla.

```csharp
[C#]

// Implementar el método de recorte correcto para archivos PSD.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ver también

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* espacio de nombres [Aspose.PSD](../../rasterimage/)
* asamblea [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Recortar imagen con turnos.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| leftShift | Int32 | El desplazamiento a la izquierda. |
| rightShift | Int32 | El cambio correcto. |
| topShift | Int32 | El turno superior. |
| bottomShift | Int32 | El cambio de fondo. |

### Ver también

* class [RasterImage](../)
* espacio de nombres [Aspose.PSD](../../rasterimage/)
* asamblea [Aspose.PSD](../../../)


