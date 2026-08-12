---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RawColorHelper metod. Skapar en 16‑bit per kanal ARGB‑färg"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Skapar en 16-bitars per kanal ARGB-färg.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | UInt16 | Alfakomponentens värde (0‑65535). |
| r | UInt16 | Rödkomponentens värde (0‑65535). |
| g | UInt16 | Grönkomponentens värde (0‑65535). |
| b | UInt16 | Blåkomponentens värde (0‑65535). |

### Returvärde

En ny [`RawColor`](../../rawcolor/) instans som representerar ARGB‑färgen.

## Anmärkningar

Färgkomponenterna packas in i ett 64‑bitars heltal i följande ordning: alfa (bitar 48‑63), röd (bitar 32‑47), grön (bitar 16‑31) och blå (bitar 0‑15).

### Se även

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


