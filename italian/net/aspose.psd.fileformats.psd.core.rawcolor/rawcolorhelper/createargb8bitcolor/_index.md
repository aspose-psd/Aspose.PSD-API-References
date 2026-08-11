---
title: "RawColorHelper.CreateArgb8BitColor"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo RawColorHelper. Crea un colore ARGB a 8 bit per canale"
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolorhelper/createargb8bitcolor/
---
{{< psd/tize >}}
## CreateArgb8BitColor(byte, byte, byte, byte) {#createargb8bitcolor_1}

Crea un colore ARGB a 8 bit per canale.

```csharp
public static RawColor CreateArgb8BitColor(byte a, byte r, byte g, byte b)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | Byte | Il valore del componente alfa (0-255). |
| r | Byte | Il valore del componente rosso (0-255). |
| g | Byte | Il valore del componente verde (0-255). |
| b | Byte | Il valore del componente blu (0-255). |

### Valore di ritorno

Una nuova istanza di [`RawColor`](../../rawcolor/) che rappresenta il colore ARGB.

## Osservazioni

I componenti di colore sono impacchettati in un intero a 32 bit nell'ordine: alfa (bit 24-31), rosso (bit 16-23), verde (bit 8-15) e blu (bit 0-7).

### Vedi anche

* class [RawColor](../../rawcolor/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## CreateArgb8BitColor(Color) {#createargb8bitcolor}

Crea un colore ARGB a 8 bit per canale da Drawing.Color

```csharp
public static RawColor CreateArgb8BitColor(Color drawingColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| drawingColor | Color | Il colore System.Drawing |

### Valore di ritorno

Una nuova istanza di [`RawColor`](../../rawcolor/) che rappresenta il colore ARGB.

## Osservazioni

I componenti di colore sono impacchettati in un intero a 32 bit nell'ordine: alfa (bit 24-31), rosso (bit 16-23), verde (bit 8-15) e blu (bit 0-7).

### Vedi anche

* class [RawColor](../../rawcolor/)
* struct [Color](../../../aspose.psd/color/)
* class [RawColorHelper](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


