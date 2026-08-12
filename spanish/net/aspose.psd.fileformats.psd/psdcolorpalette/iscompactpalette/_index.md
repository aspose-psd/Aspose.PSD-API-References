---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "PsdColorPalette propiedad. Obtiene un valor que indica si la paleta está compacta"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Obtiene un valor que indica si la paleta es compacta.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` si la paleta está compacta; de lo contrario, `false`.

## Observaciones

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible, o en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de paleta. Establecer este valor en `true` y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, así que úselo con cuidado.

### Ver también

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


