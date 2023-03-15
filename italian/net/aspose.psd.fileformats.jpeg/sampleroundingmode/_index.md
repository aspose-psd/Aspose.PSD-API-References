---
title: Enum SampleRoundingMode
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode enum. Definisce un modo in cui un valore a n bit viene convertito in un valore a 8 bit.
type: docs
weight: 1530
url: /it/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Definisce un modo in cui un valore a n bit viene convertito in un valore a 8 bit.

```csharp
public enum SampleRoundingMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Extrapolate | `0` | Estrapola un valore a 8 bit per adattarlo a n bit, dove 1 &lt; n &lt; 8. Il numero di tutti i possibili valori a 8 bit è 1 &lt;&lt; 8 = 256, da 0 a 255. Il numero di tutti i possibili I valori di n bit sono 1 &lt;&lt; n, da 0 a (1 &lt;&lt; n) - 1. Il valore di n bit più ragionevole Vn corrispondente a un valore di 8 bit V8 è uguale a Vn = V8 &gt;&gt; (8 - N). |
| Truncate | `1` | Tronca un valore a 8 bit per adattarlo a n bit, dove 1 &lt; n &lt; 8. Il numero di tutti i possibili valori a n bit è 1 &lt;&lt; n, da 0 a (1 &lt;&lt; n) - 1. Il valore di n bit più ragionevole Vn corrispondente a un valore di 8 bit V8 è uguale a Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assemblea [Aspose.PSD](../../)


