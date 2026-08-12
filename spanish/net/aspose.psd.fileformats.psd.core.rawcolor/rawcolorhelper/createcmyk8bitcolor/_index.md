---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RawColorHelper. Crea un color CMYK de 8 bits por canal"
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Crea un color CMYK de 8 bits por canal.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | Byte | El valor del componente cian (0-255). |
| m | Byte | El valor del componente magenta (0-255). |
| y | Byte | El valor del componente amarillo (0-255). |
| k | Byte | El valor del componente clave (negro) (0-255). |

### Valor devuelto

Una nueva instancia de [`RawColor`](../../rawcolor/) que representa el color CMYK.

## Observaciones

Los componentes de color se empaquetan en un entero de 32 bits en el orden: cian (bits 24-31), magenta (bits 16-23), amarillo (bits 8-15) y clave/negro (bits 0-7).

### Ver también

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


