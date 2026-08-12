---
title: "Enumeración SampleRoundingMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode. Define una forma en que un valor n‑bit se convierte a un valor de 8 bits."
type: docs
weight: 1540
url: /es/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Define una forma en que un valor de n bits se convierte en un valor de 8 bits.

```csharp
public enum SampleRoundingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Extrapolate | `0` | Extrapola un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8. El número de todos los valores posibles de 8 bits es 1 &lt;&lt; 8 = 256, de 0 a 255. El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1. El valor de n bits más razonable Vn que corresponde a un valor de 8 bits V8 es igual a Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Trunca un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8. El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1. El valor de n bits más razonable Vn que corresponde a un valor de 8 bits V8 es igual a Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Ver también

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


