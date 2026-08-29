---
title: "RawColorHelper.CreateArgb16BitColor"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo RawColorHelper. Crea un colore ARGB a 16 bit per canale"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb16bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateArgb16BitColor method

Crea un colore ARGB a 16 bit per canale.

```csharp
public static RawColor CreateArgb16BitColor(ushort a, ushort r, ushort g, ushort b)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | UInt16 | Il valore del componente alfa (0-65535). |
| r | UInt16 | Il valore del componente rosso (0-65535). |
| g | UInt16 | Il valore del componente verde (0-65535). |
| b | UInt16 | Il valore del componente blu (0-65535). |

### Valore di ritorno

Una nuova istanza di [`RawColor`](../../rawcolor/) che rappresenta il colore ARGB.

## Osservazioni

I componenti di colore sono impacchettati in un intero a 64 bit nell'ordine: alfa (bit 48-63), rosso (bit 32-47), verde (bit 16-31) e blu (bit 0-15).

### Vedi anche

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


