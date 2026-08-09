---
title: "Enum SampleRoundingMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode enum. Définit une façon dont une valeur n bits est convertie en une valeur 8 bits."
type: docs
weight: 1540
url: /fr/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

Définit une façon dont une valeur n bits est convertie en une valeur de 8 bits.

```csharp
public enum SampleRoundingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Extrapolate | `0` | Extrapole une valeur 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8. Le nombre de toutes les valeurs possibles 8 bits est 1 &lt;&lt; 8 = 256, de 0 à 255. Le nombre de toutes les valeurs possibles n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1. La valeur n bits la plus raisonnable Vn correspondant à une valeur 8 bits V8 est égale à Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Tronque une valeur 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8. Le nombre de toutes les valeurs possibles n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1. La valeur n bits la plus raisonnable Vn correspondant à une valeur 8 bits V8 est égale à Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


