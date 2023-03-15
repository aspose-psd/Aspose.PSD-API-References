---
title: GifOptions.DoPaletteCorrection
second_title: Referencia de API de Aspose.PSD para .NET
description: GifOptions propiedad. Obtiene o establece un valor que indica si se aplica la corrección de paleta.
type: docs
weight: 40
url: /es/net/aspose.psd.imageoptions/gifoptions/dopalettecorrection/
---
## GifOptions.DoPaletteCorrection property

Obtiene o establece un valor que indica si se aplica la corrección de paleta.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### El valor de la propiedad

`verdadero` si se aplica corrección de paleta; de lo contrario,`FALSO` .

### Observaciones

La corrección de paleta significa que cada vez que la imagen se exporta a GIF, los colores de la imagen de origen se analizarán para crear la paleta que mejor coincida (en caso de que la Paleta de imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algún tiempo, sin embargo, el la imagen de salida tendrá la mejor paleta de colores coincidentes y el resultado será visualmente mejor.

### Ver también

* class [GifOptions](../)
* espacio de nombres [Aspose.PSD.ImageOptions](../../gifoptions/)
* asamblea [Aspose.PSD](../../../)


