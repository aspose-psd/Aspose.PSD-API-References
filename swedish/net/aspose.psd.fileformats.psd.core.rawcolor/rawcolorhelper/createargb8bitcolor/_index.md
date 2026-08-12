---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RawColorHelper-metod. Skapar en 8-bit per kanal ARGB-färg"
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Skapar en 8-bitars per kanal ARGB-färg.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | Byte | Alfa-komponentens värde (0-255). |
| r | Byte | Röd-komponentens värde (0-255). |
| g | Byte | Grön-komponentens värde (0-255). |
| b | Byte | Blå-komponentens värde (0-255). |

### Returvärde

En ny [`RawColor`](../../rawcolor/) instans som representerar ARGB‑färgen.

## Anmärkningar

Färgkomponenterna packas in i ett 32-bitars heltal i följande ordning: alfa (bitar 24-31), röd (bitar 16-23), grön (bitar 8-15) och blå (bitar 0-7).

### Se även

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Skapar en 8-bitars per kanal ARGB-färg från Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| drawingColor | Färg | System.Drawing-färgen |

### Returvärde

En ny [`RawColor`](../../rawcolor/) instans som representerar ARGB‑färgen.

## Anmärkningar

Färgkomponenterna packas in i ett 32-bitars heltal i följande ordning: alfa (bitar 24-31), röd (bitar 16-23), grön (bitar 8-15) och blå (bitar 0-7).

### Se även

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


