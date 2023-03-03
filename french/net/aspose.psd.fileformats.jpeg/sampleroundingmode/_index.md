---
title: Enum SampleRoundingMode
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode énumération. Définit une manière dont une valeur de n bits est convertie en une valeur de 8 bits.
type: docs
weight: 1530
url: /fr/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

Définit une manière dont une valeur de n bits est convertie en une valeur de 8 bits.

```csharp
public enum SampleRoundingMode
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Extrapolate | `0` | Extrapoler une valeur 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8. Le nombre de toutes les valeurs 8 bits possibles est 1 &lt;&lt; 8 = 256, de 0 à 255. Le nombre de toutes les valeurs possibles valeurs de n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1. La valeur de n bits la plus raisonnable Vn correspondant à une valeur de 8 bits V8 est égale à Vn = V8 &gt;&gt; (8 - n). |
| Truncate | `1` | Tronque une valeur de 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8. Le nombre de toutes les valeurs de n bits possibles est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1. La valeur de n bits la plus raisonnable Vn correspondant à une valeur de 8 bits V8 est égale à Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* Assemblée [Aspose.PSD](../../)


