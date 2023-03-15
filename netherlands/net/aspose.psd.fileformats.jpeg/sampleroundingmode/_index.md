---
title: Enum SampleRoundingMode
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode opsomming. Definieert een manier waarop een nbit waarde wordt geconverteerd naar een 8bit waarde.
type: docs
weight: 1530
url: /nl/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Definieert een manier waarop een n-bit waarde wordt geconverteerd naar een 8-bit waarde.

```csharp
public enum SampleRoundingMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Extrapolate | `0` | Extrapoleer een 8-bits waarde om deze in n bits te passen, waarbij 1 &lt; n &lt; 8. Het aantal van alle mogelijke 8-bits waarden is 1 &lt;&lt; 8 = 256, van 0 tot 255. Het aantal van alle mogelijke n-bit waarden is 1 &lt;&lt; n, van 0 tot (1 &lt;&lt; n) - 1. De meest redelijke n-bit waarde Vn die overeenkomt met een 8-bit waarde V8 is gelijk aan Vn = V8 &gt;&gt; (8 - N). |
| Truncate | `1` | Kap een 8-bits waarde af om deze in n bits te passen, waarbij 1 &lt; n &lt; 8. Het aantal van alle mogelijke n-bits waarden is 1 &lt;&lt; n, van 0 tot (1 &lt;&lt; n) - 1. De meest redelijke n-bit waarde Vn die overeenkomt met een 8-bit waarde V8 is gelijk aan Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* montage [Aspose.PSD](../../)


