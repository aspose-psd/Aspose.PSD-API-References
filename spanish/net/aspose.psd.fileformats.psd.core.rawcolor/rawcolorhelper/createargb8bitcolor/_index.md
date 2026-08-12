---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método RawColorHelper. Crea un color ARGB de 8 bits por canal"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Crea un color ARGB de 8 bits por canal.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | Byte | El valor del componente alfa (0-255). |
| r | Byte | El valor del componente rojo (0-255). |
| g | Byte | El valor del componente verde (0-255). |
| b | Byte | El valor del componente azul (0-255). |

### Valor devuelto

Una nueva instancia de [`RawColor`](../../rawcolor/) que representa el color ARGB.

## Observaciones

Los componentes de color se empaquetan en un entero de 32 bits en el orden: alfa (bits 24-31), rojo (bits 16-23), verde (bits 8-15) y azul (bits 0-7).

### Ver también

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Crea un color ARGB de 8 bits por canal a partir de Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| drawingColor | Color | El color System.Drawing |

### Valor devuelto

Una nueva instancia de [`RawColor`](../../rawcolor/) que representa el color ARGB.

## Observaciones

Los componentes de color se empaquetan en un entero de 32 bits en el orden: alfa (bits 24-31), rojo (bits 16-23), verde (bits 8-15) y azul (bits 0-7).

### Ver también

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


