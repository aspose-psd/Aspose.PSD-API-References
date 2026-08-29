---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "RawColorHelper methode. Maakt een 16-bit per kanaal ARGB-kleur."
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Creëert een ARGB-kleur met 16 bits per kanaal.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | UInt16 | De alfa componentwaarde (0-65535). |
| r | UInt16 | De rode componentwaarde (0-65535). |
| g | UInt16 | De groene componentwaarde (0-65535). |
| b | UInt16 | De blauwe componentwaarde (0-65535). |

### Retourwaarde

Een nieuw [`RawColor`](../../rawcolor/) exemplaar dat de ARGB-kleur vertegenwoordigt.

## Opmerkingen

De kleurcomponenten worden verpakt in een 64-bit geheel getal in de volgorde: alfa (bits 48-63), rood (bits 32-47), groen (bits 16-31) en blauw (bits 0-15).

### Zie ook

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


