---
title: "RawColorHelper.CreateCmyk8BitColor"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo RawColorHelper. Crea un colore CMYK a 8 bit per canale"
type: docs
weight: 50
url: /it/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk8bitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk8BitColor method

Crea un colore CMYK a 8 bit per canale.

```csharp
public static RawColor CreateCmyk8BitColor(byte c, byte m, byte y, byte k)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | Byte | Il valore del componente ciano (0-255). |
| m | Byte | Il valore del componente magenta (0-255). |
| y | Byte | Il valore del componente giallo (0-255). |
| k | Byte | Il valore del componente chiave (nero) (0-255). |

### Valore di ritorno

Una nuova istanza di [`RawColor`](../../rawcolor/) che rappresenta il colore CMYK.

## Osservazioni

I componenti di colore sono impacchettati in un intero a 32 bit nell'ordine: ciano (bit 24-31), magenta (bit 16-23), giallo (bit 8-15) e chiave/nero (bit 0-7).

### Vedi anche

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


