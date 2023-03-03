---
title: PsdColorPalette.IsCompactPalette
second_title: Referencia de API de Aspose.PSD para .NET
description: PsdColorPalette propiedad. Obtiene un valor que indica si se compacta la paleta.
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Obtiene un valor que indica si se compacta la paleta.

```csharp
public bool IsCompactPalette { get; }
```

### El valor de la propiedad

`verdadero` si compacta la paleta; de lo contrario,`FALSO`.

### Observaciones

Paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible o, en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario, habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de paleta . Establecer este valor en verdadero y cambiar las entradas de la paleta puede causar una reducción del rendimiento, ya que puede ocurrir un movimiento de datos, así que utilícelo con cuidado.

### Ver también

* class [PsdColorPalette](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* asamblea [Aspose.PSD](../../../)


