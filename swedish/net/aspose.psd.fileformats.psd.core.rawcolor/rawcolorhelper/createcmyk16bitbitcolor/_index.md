---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RawColorHelper-metod. Skapar en 16-bit per kanal CMYK-färg"
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Skapar en 16-bitars per kanal CMYK-färg.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | UInt16 | Cyan-komponentens värde (0-65535). |
| m | UInt16 | Magenta-komponentens värde (0-65535). |
| y | UInt16 | Gul-komponentens värde (0-65535). |
| k | UInt16 | Nyckel-(svart)-komponentens värde (0-65535). |

### Returvärde

En ny [`RawColor`](../../rawcolor/) instans som representerar CMYK-färgen.

## Anmärkningar

Färgkomponenterna packas in i ett 64-bitars heltal i följande ordning: cyan (bitar 48-63), magenta (bitar 32-47), gul (bitar 16-31) och nyckel/svart (bitar 0-15).

### Se även

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


