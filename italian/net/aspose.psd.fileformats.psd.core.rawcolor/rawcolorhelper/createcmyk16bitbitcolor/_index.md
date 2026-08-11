---
title: "RawColorHelper.CreateCmyk16BitBitColor"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo RawColorHelper. Crea un colore CMYK a 16 bit per canale"
type: docs
weight: 40
url: /it/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createcmyk16bitbitcolor/
---
{{< psd/tize >}}
## RawColorHelper.CreateCmyk16BitBitColor method

Crea un colore CMYK a 16 bit per canale.

```csharp
public static RawColor CreateCmyk16BitBitColor(ushort c, ushort m, ushort y, ushort k)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | UInt16 | Il valore del componente ciano (0-65535). |
| m | UInt16 | Il valore del componente magenta (0-65535). |
| y | UInt16 | Il valore del componente giallo (0-65535). |
| k | UInt16 | Il valore del componente chiave (nero) (0-65535). |

### Valore di ritorno

Una nuova istanza di [`RawColor`](../../rawcolor/) che rappresenta il colore CMYK.

## Osservazioni

I componenti di colore sono impacchettati in un intero a 64 bit nell'ordine: ciano (bit 48-63), magenta (bit 32-47), giallo (bit 16-31) e chiave/nero (bit 0-15).

### Vedi anche

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


