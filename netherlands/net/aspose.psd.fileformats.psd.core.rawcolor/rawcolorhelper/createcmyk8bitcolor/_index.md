---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "RawColorHelper methode. Maakt een 8-bit per kanaal CMYK-kleur."
type: docs
weight: 50
url: /nl/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Maakt een 8-bit per kanaal CMYK-kleur.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | Byte | De cyaancomponentwaarde (0-255). |
| m | Byte | De magentacomponentwaarde (0-255). |
| y | Byte | De geelcomponentwaarde (0-255). |
| k | Byte | De sleutel (zwart) componentwaarde (0-255). |

### Retourwaarde

Een nieuw [`RawColor`](../../rawcolor/) exemplaar dat de CMYK-kleur vertegenwoordigt.

## Opmerkingen

De kleurcomponenten worden verpakt in een 32‑bit integer in de volgorde: cyaan (bits 24-31), magenta (bits 16-23), geel (bits 8-15) en sleutel/zwart (bits 0-7).

### Zie ook

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


