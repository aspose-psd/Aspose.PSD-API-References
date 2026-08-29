---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "RawColorHelper-methode. Maakt een 16‑bit per kanaal CMYK-kleur"
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Creëert een CMYK-kleur met 16 bits per kanaal.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | UInt16 | De cyaancomponentwaarde (0-65535). |
| m | UInt16 | De magentacomponentwaarde (0-65535). |
| y | UInt16 | De geelcomponentwaarde (0-65535). |
| k | UInt16 | De sleutel (zwart) componentwaarde (0-65535). |

### Retourwaarde

Een nieuw [`RawColor`](../../rawcolor/) exemplaar dat de CMYK-kleur vertegenwoordigt.

## Opmerkingen

De kleurcomponenten worden verpakt in een 64‑bit integer in de volgorde: cyaan (bits 48-63), magenta (bits 32-47), geel (bits 16-31) en sleutel/zwart (bits 0-15).

### Zie ook

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


