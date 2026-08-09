---
title: "Aufzählung SampleRoundingMode"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode Aufzählung. Definiert eine Methode, wie ein n‑Bit‑Wert in einen 8‑Bit‑Wert konvertiert wird."
type: docs
weight: 1540
url: /de/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Definiert eine Methode, mit der ein n‑Bit‑Wert in einen 8‑Bit‑Wert konvertiert wird.

```csharp
public enum SampleRoundingMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Extrapolate | `0` | Extrapoliert einen 8‑Bit‑Wert, um ihn in n Bits zu passen, wobei 1 &lt; n &lt; 8. Die Anzahl aller möglichen 8‑Bit‑Werte ist 1 &lt;&lt; 8 = 256, von 0 bis 255. Die Anzahl aller möglichen n‑Bit‑Werte ist 1 &lt;&lt; n, von 0 bis (1 &lt;&lt; n) - 1. Der am sinnvollsten n‑Bit‑Wert Vn, der einem 8‑Bit‑Wert V8 entspricht, ist gleich Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Schneidet einen 8‑Bit‑Wert ab, um ihn in n Bits zu passen, wobei 1 &lt; n &lt; 8. Die Anzahl aller möglichen n‑Bit‑Werte ist 1 &lt;&lt; n, von 0 bis (1 &lt;&lt; n) - 1. Der am sinnvollsten n‑Bit‑Wert Vn, der einem 8‑Bit‑Wert V8 entspricht, ist gleich Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


