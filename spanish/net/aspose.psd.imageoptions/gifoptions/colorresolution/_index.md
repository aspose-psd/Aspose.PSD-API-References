---
title: GifOptions.ColorResolution
second_title: Referencia de API de Aspose.PSD para .NET
description: GifOptions propiedad. Obtiene o establece la resolución de color del GIF.
type: docs
weight: 30
url: /es/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
## GifOptions.ColorResolution property

Obtiene o establece la resolución de color del GIF.

```csharp
public byte ColorResolution { get; set; }
```

### El valor de la propiedad

La resolución de color.

### Observaciones

Resolución de color : número de bits por color primario disponible para la imagen original, menos 1. Este valor representa el tamaño de la paleta completa de la que se seleccionaron los colores del gráfico , no el número de colores realmente utilizados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe configurarse para indicar la riqueza de la paleta original, incluso si no todos los colores de toda la paleta están disponibles en la máquina de origen.

### Ver también

* class [GifOptions](../)
* espacio de nombres [Aspose.PSD.ImageOptions](../../gifoptions/)
* asamblea [Aspose.PSD](../../../)


