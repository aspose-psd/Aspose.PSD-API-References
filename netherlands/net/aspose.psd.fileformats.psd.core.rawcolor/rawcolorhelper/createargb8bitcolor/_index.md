---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "RawColorHelper-methode. Maakt een 8‑bit per kanaal ARGB-kleur"
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Creëert een ARGB-kleur met 8 bits per kanaal.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | Byte | De alfacomponentwaarde (0-255). |
| r | Byte | De rode componentwaarde (0-255). |
| g | Byte | De groene componentwaarde (0-255). |
| b | Byte | De blauwe componentwaarde (0-255). |

### Retourwaarde

Een nieuw [`RawColor`](../../rawcolor/) exemplaar dat de ARGB-kleur vertegenwoordigt.

## Opmerkingen

De kleurcomponenten worden verpakt in een 32‑bit integer in de volgorde: alfa (bits 24-31), rood (bits 16-23), groen (bits 8-15) en blauw (bits 0-7).

### Zie ook

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Creëert een ARGB-kleur met 8 bits per kanaal vanuit Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| drawingColor | Color | De System.Drawing Color |

### Retourwaarde

Een nieuw [`RawColor`](../../rawcolor/) exemplaar dat de ARGB-kleur vertegenwoordigt.

## Opmerkingen

De kleurcomponenten worden verpakt in een 32‑bit integer in de volgorde: alfa (bits 24-31), rood (bits 16-23), groen (bits 8-15) en blauw (bits 0-7).

### Zie ook

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


