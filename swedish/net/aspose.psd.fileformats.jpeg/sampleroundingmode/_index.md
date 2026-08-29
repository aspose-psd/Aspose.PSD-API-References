---
title: "Enum SampleRoundingMode"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode-enum. Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde."
type: docs
weight: 1540
url: /sv/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Definierar ett sätt på vilket ett n-bitars värde konverteras till ett 8-bitars värde.

```csharp
public enum SampleRoundingMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Extrapolate | `0` | Extrapolera ett 8-bitars värde för att passa in i n bitar, där 1 &lt; n &lt; 8. Antalet möjliga 8-bitars värden är 1 &lt;&lt; 8 = 256, från 0 till 255. Antalet möjliga n-bitars värden är 1 &lt;&lt; n, från 0 till (1 &lt;&lt; n) - 1. Det mest rimliga n-bitars värdet Vn som motsvarar ett 8-bitars värde V8 är lika med Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Trunkera ett 8-bitars värde för att passa in i n bitar, där 1 &lt; n &lt; 8. Antalet möjliga n-bitars värden är 1 &lt;&lt; n, från 0 till (1 &lt;&lt; n) - 1. Det mest rimliga n-bitars värdet Vn som motsvarar ett 8-bitars värde V8 är lika med Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Se även

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


