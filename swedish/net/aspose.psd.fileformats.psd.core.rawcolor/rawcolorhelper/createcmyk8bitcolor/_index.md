---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RawColorHelper metod. Skapar en 8‑bit per kanal CMYK‑färg"
type: docs
weight: 50
url: /sv/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Skapar en 8-bitars per kanal CMYK-färg.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | Byte | Cyan‑komponentens värde (0‑255). |
| m | Byte | Magenta‑komponentens värde (0‑255). |
| y | Byte | Gul‑komponentens värde (0‑255). |
| k | Byte | Nyckel (svart) komponentens värde (0‑255). |

### Returvärde

En ny [`RawColor`](../../rawcolor/) instans som representerar CMYK-färgen.

## Anmärkningar

Färgkomponenterna packas in i ett 32-bitars heltal i följande ordning: cyan (bitar 24-31), magenta (bitar 16-23), gul (bitar 8-15) och nyckel/svart (bitar 0-7).

### Se även

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


