---
title: "ColorPalette.IsCompactPalette"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad ColorPalette. Obtiene o establece un valor que indica si se usa una paleta compacta"
type: docs
weight: 60
url: /es/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

Obtiene o establece un valor que indica si se utiliza una paleta compacta.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` si se usa una paleta compacta; de lo contrario, `false`.

## Observaciones

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible, o en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de paleta. Establecer este valor en `true` y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, así que úselo con cuidado.

### Ver también

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


