---
title: "GifOptions.DoPaletteCorrection"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad GifOptions. Obtiene o establece un valor que indica si se aplica la corrección de paleta"
type: docs
weight: 40
url: /es/net/aspose.psd.imageoptions/gifoptions/dopalettecorrection/
---
{{< psd/tize >}}
## GifOptions.DoPaletteCorrection property

Obtiene o establece un valor que indica si se aplica la corrección de paleta.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Property Value

`true` si se aplica la corrección de paleta; de lo contrario, `false`.

## Observaciones

La corrección de paleta significa que cada vez que la imagen se exporta a GIF, los colores de la imagen original serán analizados para crear la paleta que mejor coincida (en caso de que la paleta de la imagen no exista o no se haya especificado en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen resultante tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.

### Ver también

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


