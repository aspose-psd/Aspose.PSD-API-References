---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RawColorHelper. Crea un color CMYK de 16 bits por canal."
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Crea un color CMYK de 16 bits por canal.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| c | UInt16 | El valor del componente cian (0-65535). |
| m | UInt16 | El valor del componente magenta (0-65535). |
| y | UInt16 | El valor del componente amarillo (0-65535). |
| k | UInt16 | El valor del componente clave (negro) (0-65535). |

### Valor devuelto

Una nueva instancia de [`RawColor`](../../rawcolor/) que representa el color CMYK.

## Observaciones

Los componentes de color se empaquetan en un entero de 64 bits en el orden: cian (bits 48-63), magenta (bits 32-47), amarillo (bits 16-31) y clave/negro (bits 0-15).

### Ver también

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


