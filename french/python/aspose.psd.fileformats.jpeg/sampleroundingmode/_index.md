---
title: "SampleRoundingMode Énumération"
type: docs
weight: 70
url: /fr/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---

Définit une méthode selon laquelle une valeur n bits est convertie en une valeur 8 bits.

**Module:** [aspose.psd.fileformats.jpeg](/psd/python-net/aspose.psd.fileformats.jpeg/)

**Full Name:** aspose.psd.fileformats.jpeg.SampleRoundingMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| EXTRAPOLATE | Extrapole une valeur de 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8.<br/>            Le nombre de toutes les valeurs possibles de 8 bits est 1 &lt;&lt; 8 = 256, de 0 à 255.<br/>            Le nombre de toutes les valeurs possibles de n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1.<br/>            La valeur de n bits la plus raisonnable Vn correspondant à une valeur de 8 bits V8 est égale à Vn = V8 &gt;&gt; (8 - n). |
| TRUNCATE | Tronque une valeur de 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8.<br/>            Le nombre de toutes les valeurs possibles de n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1.<br/>            La valeur de n bits la plus raisonnable Vn correspondant à une valeur de 8 bits V8 est égale à Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
