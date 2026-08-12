---
title: "GifOptions.ColorResolution"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad GifOptions. Obtiene o establece la resolución de color del GIF"
type: docs
weight: 30
url: /es/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

Obtiene o establece la resolución de color del GIF.

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

La resolución de color.

## Observaciones

Color Resolution - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la cual se seleccionaron los colores del gráfico, no el número de colores realmente usados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina fuente.

### Ver también

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


