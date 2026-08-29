---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RawColorHelper-Methode. Erstellt eine 16‑Bit‑pro‑Kanal‑ARGB‑Farbe"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Erstellt eine ARGB-Farbe mit 16 Bit pro Kanal.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | UInt16 | Der Alpha‑Komponentenwert (0‑65535). |
| r | UInt16 | Der Rot‑Komponentenwert (0‑65535). |
| g | UInt16 | Der Grün‑Komponentenwert (0‑65535). |
| b | UInt16 | Der Blau‑Komponentenwert (0‑65535). |

### Rückgabewert

Eine neue [`RawColor`](../../rawcolor/)-Instanz, die die ARGB‑Farbe darstellt.

## Hinweise

Die Farbkomponenten werden in einem 64‑Bit‑Integer in folgender Reihenfolge gepackt: Alpha (Bits 48‑63), Rot (Bits 32‑47), Grün (Bits 16‑31) und Blau (Bits 0‑15).

### Siehe auch

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


