---
title: "TiffOptions.ColorMap"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad TiffOptions. Obtiene o establece el mapa de colores"
type: docs
weight: 70
url: /es/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Obtiene o establece el mapa de colores.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

El mapa de colores.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | valor |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | El mapa de colores solo puede definirse para muestras por píxel iguales a 1. o Los bits por muestra no están definidos. |
| ArgumentOutOfRangeException | valor;La longitud del arreglo debe corresponder a la siguiente fórmula: 3 * (2**BitsPerSample). |

### Ver también

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


