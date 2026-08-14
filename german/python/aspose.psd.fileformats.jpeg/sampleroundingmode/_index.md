---
title: "Aufzählung SampleRoundingMode"
type: docs
weight: 70
url: /de/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Definiert eine Methode, wie ein n‑Bit‑Wert in einen 8‑Bit‑Wert konvertiert wird.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Membername** | **Beschreibung** |
| :- | :- |
| EXTRAPOLATE | Extrapoliere einen 8‑Bit‑Wert, um ihn in n Bit zu passen, wobei 1 &lt; n &lt; 8.<br/>            Die Anzahl aller möglichen 8‑Bit‑Werte ist 1 &lt;&lt; 8 = 256, von 0 bis 255.<br/>            Die Anzahl aller möglichen n‑Bit‑Werte ist 1 &lt;&lt; n, von 0 bis (1 &lt;&lt; n) - 1.<br/>            Der am sinnvollsten n‑Bit‑Wert Vn, der einem 8‑Bit‑Wert V8 entspricht, ist Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Kürze einen 8‑Bit‑Wert, um ihn in n Bit zu passen, wobei 1 &lt; n &lt; 8.<br/>            Die Anzahl aller möglichen n‑Bit‑Werte ist 1 &lt;&lt; n, von 0 bis (1 &lt;&lt; n) - 1.<br/>            Der am sinnvollsten n‑Bit‑Wert Vn, der einem 8‑Bit‑Wert V8 entspricht, ist Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
