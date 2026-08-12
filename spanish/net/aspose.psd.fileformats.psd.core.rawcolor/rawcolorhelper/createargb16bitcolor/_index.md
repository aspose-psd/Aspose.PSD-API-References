---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RawColorHelper. Crea un color ARGB de 16 bits por canal"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Crea un color ARGB de 16 bits por canal.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | UInt16 | El valor del componente alfa (0-65535). |
| r | UInt16 | El valor del componente rojo (0-65535). |
| g | UInt16 | El valor del componente verde (0-65535). |
| b | UInt16 | El valor del componente azul (0-65535). |

### Valor devuelto

Una nueva instancia de [`RawColor`](../../rawcolor/) que representa el color ARGB.

## Observaciones

Los componentes de color se empaquetan en un entero de 64 bits en el orden: alfa (bits 48-63), rojo (bits 32-47), verde (bits 16-31) y azul (bits 0-15).

### Ver también

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


