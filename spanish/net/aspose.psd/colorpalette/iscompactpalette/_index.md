---
title: ColorPalette.IsCompactPalette
second_title: Referencia de API de Aspose.PSD para .NET
description: ColorPalette propiedad. Obtiene o establece un valor que indica si se utiliza la paleta compacta.
type: docs
weight: 60
url: /es/net/aspose.psd/colorpalette/iscompactpalette/
---
## ColorPalette.IsCompactPalette property

Obtiene o establece un valor que indica si se utiliza la paleta compacta.

```csharp
public bool IsCompactPalette { get; }
```

### El valor de la propiedad

`verdadero` si se utiliza paleta compacta; de lo contrario,`FALSO`.

### Observaciones

Paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible o, en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario, habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las entradas de paleta posibles. Establecer este valor en verdadero y cambiar las entradas de la paleta puede causar una reducción del rendimiento, ya que puede ocurrir un movimiento de datos, así que utilícelo con cuidado.

### Ver también

* class [ColorPalette](../)
* espacio de nombres [Aspose.PSD](../../colorpalette/)
* asamblea [Aspose.PSD](../../../)


