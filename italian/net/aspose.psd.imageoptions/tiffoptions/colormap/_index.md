---
title: TiffOptions.ColorMap
second_title: Aspose.PSD per riferimento API .NET
description: TiffOptions proprietà. Ottiene o imposta la mappa dei colori.
type: docs
weight: 70
url: /it/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Ottiene o imposta la mappa dei colori.

```csharp
public ushort[] ColorMap { get; set; }
```

### Valore della proprietà

La mappa dei colori.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | valore |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | La mappa colori può essere definita solo per campioni per pixel pari a 1. o I bit per campione non sono definiti. |
| ArgumentOutOfRangeException | value;La lunghezza dell'array deve corrispondere alla seguente formula: 3 * (2**BitsPerSample). |

### Guarda anche

* class [TiffOptions](../)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../tiffoptions/)
* assemblea [Aspose.PSD](../../../)


