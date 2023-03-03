---
title: TiffOptions.ColorMap
second_title: Referencia de API de Aspose.PSD para .NET
description: TiffOptions propiedad. Obtiene o establece el mapa de colores.
type: docs
weight: 70
url: /es/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Obtiene o establece el mapa de colores.

```csharp
public ushort[] ColorMap { get; set; }
```

### El valor de la propiedad

El mapa de colores.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | valor |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | El mapa de color se puede definir para muestras por píxel igual a 1 únicamente. o Los bits por muestra no están definidos. |
| ArgumentOutOfRangeException | value;La longitud de la matriz debe corresponder a la siguiente fórmula: 3 * (2**BitsPerSample). |

### Ver también

* class [TiffOptions](../)
* espacio de nombres [Aspose.PSD.ImageOptions](../../tiffoptions/)
* asamblea [Aspose.PSD](../../../)


