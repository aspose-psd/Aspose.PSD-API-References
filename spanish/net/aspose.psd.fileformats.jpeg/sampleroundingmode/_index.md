---
title: Enum SampleRoundingMode
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode enumeración. Define una forma en la que un valor de n bits se convierte en un valor de 8 bits.
type: docs
weight: 1530
url: /es/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Define una forma en la que un valor de n bits se convierte en un valor de 8 bits.

```csharp
public enum SampleRoundingMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Extrapolate | `0` | Extrapolar un valor de 8 bits para encajarlo en n bits, donde 1 &lt; n &lt; 8. El número de todos los valores de 8 bits posibles es 1 &lt;&lt; 8 = 256, de 0 a 255. El número de todos los posibles Los valores de n bits son 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1. El valor de n bits más razonable Vn correspondiente a algún valor de 8 bits V8 es igual a Vn = V8 &gt;&gt; (8 - norte). |
| Truncate | `1` | Trunca un valor de 8 bits para ajustarlo a n bits, donde 1 &lt; n &lt; 8. El número de todos los valores posibles de n bits es 1 &lt;&lt; n, de 0 a (1 &lt;&lt; n) - 1. El valor de n bits más razonable Vn correspondiente a algún valor de 8 bits V8 es igual a Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* asamblea [Aspose.PSD](../../)


