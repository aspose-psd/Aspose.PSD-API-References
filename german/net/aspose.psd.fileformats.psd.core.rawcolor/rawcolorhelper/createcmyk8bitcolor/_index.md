---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RawColorHelper-Methode. Erstellt eine 8‑Bit‑pro‑Kanal‑CMYK‑Farbe"
type: docs
weight: 50
url: /de/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Erstellt eine 8‑Bit‑pro‑Kanal‑CMYK‑Farbe.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | Byte | Der Cyan‑Komponentenwert (0‑255). |
| m | Byte | Der Magenta‑Komponentenwert (0‑255). |
| y | Byte | Der Gelb‑Komponentenwert (0‑255). |
| k | Byte | Der Key (schwarz) Komponentenwert (0-255). |

### Rückgabewert

Eine neue [`RawColor`](../../rawcolor/) Instanz, die die CMYK-Farbe darstellt.

## Hinweise

Die Farbkomponenten werden in einem 32‑Bit‑Integer in folgender Reihenfolge gepackt: Cyan (Bits 24‑31), Magenta (Bits 16‑23), Gelb (Bits 8‑15) und Key/Schwarz (Bits 0‑7).

### Siehe auch

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


