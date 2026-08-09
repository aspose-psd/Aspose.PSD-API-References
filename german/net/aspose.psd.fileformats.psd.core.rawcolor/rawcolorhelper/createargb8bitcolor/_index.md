---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RawColorHelper-Methode. Erstellt eine 8‑Bit‑pro‑Kanal‑ARGB‑Farbe"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Erstellt eine ARGB-Farbe mit 8 Bit pro Kanal.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | Byte | Der Alpha‑Komponentenwert (0‑255). |
| r | Byte | Der Rot‑Komponentenwert (0‑255). |
| g | Byte | Der Grün‑Komponentenwert (0‑255). |
| b | Byte | Der Blau‑Komponentenwert (0‑255). |

### Rückgabewert

Eine neue [`RawColor`](../../rawcolor/)-Instanz, die die ARGB‑Farbe darstellt.

## Hinweise

Die Farbkomponenten werden in einem 32‑Bit‑Integer in folgender Reihenfolge gepackt: Alpha (Bits 24‑31), Rot (Bits 16‑23), Grün (Bits 8‑15) und Blau (Bits 0‑7).

### Siehe auch

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Erstellt eine ARGB-Farbe mit 8 Bit pro Kanal aus Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| drawingColor | Farbe | Die System.Drawing‑Farbe |

### Rückgabewert

Eine neue [`RawColor`](../../rawcolor/)-Instanz, die die ARGB‑Farbe darstellt.

## Hinweise

Die Farbkomponenten werden in einem 32‑Bit‑Integer in folgender Reihenfolge gepackt: Alpha (Bits 24‑31), Rot (Bits 16‑23), Grün (Bits 8‑15) und Blau (Bits 0‑7).

### Siehe auch

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


