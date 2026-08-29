---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RawColorHelper-Methode. Erstellt eine 16‑Bit‑pro‑Kanal‑CMYK‑Farbe"
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Erstellt eine CMYK-Farbe mit 16 Bit pro Kanal.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | UInt16 | Der Cyan‑Komponentenwert (0‑65535). |
| m | UInt16 | Der Magenta‑Komponentenwert (0‑65535). |
| y | UInt16 | Der Gelb‑Komponentenwert (0‑65535). |
| k | UInt16 | Der Key (schwarz) Komponentenwert (0‑65535). |

### Rückgabewert

Eine neue [`RawColor`](../../rawcolor/) Instanz, die die CMYK-Farbe darstellt.

## Hinweise

Die Farbkomponenten werden in einem 64‑Bit‑Integer in folgender Reihenfolge gepackt: Cyan (Bits 48‑63), Magenta (Bits 32‑47), Gelb (Bits 16‑31) und Key/Schwarz (Bits 0‑15).

### Siehe auch

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


