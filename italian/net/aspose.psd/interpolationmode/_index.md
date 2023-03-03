---
title: Enum InterpolationMode
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.InterpolationMode enum. IlInterpolationMode lenumerazione specifica lalgoritmo utilizzato quando le immagini vengono ridimensionate o ruotate.
type: docs
weight: 5030
url: /it/net/aspose.psd/interpolationmode/
---
## InterpolationMode enumeration

Il`InterpolationMode` l'enumerazione specifica l'algoritmo utilizzato quando le immagini vengono ridimensionate o ruotate.

```csharp
public enum InterpolationMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Invalid | `-1` | Modalità di interpolazione non valida. |
| Default | `0` | Specifica la modalità predefinita. |
| Low | `1` | Specifica l'interpolazione di bassa qualità. |
| High | `2` | Specifica l'interpolazione di alta qualità. |
| Bilinear | `3` | Specifica l'interpolazione bilineare. Non viene eseguito alcun prefiltro. Questa modalità non è adatta per ridurre un'immagine al di sotto del 50 percento della sua dimensione originale. |
| Bicubic | `4` | Specifica l'interpolazione bicubica. Non viene eseguito alcun prefiltro. Questa modalità non è adatta per ridurre un'immagine al di sotto del 25 percento rispetto alle dimensioni originali. |
| NearestNeighbor | `5` | Specifica l'interpolazione del vicino più prossimo. |
| HighQualityBilinear | `6` | Specifica l'interpolazione bilineare di alta qualità. Il prefiltraggio viene eseguito per garantire una termoretrazione di alta qualità. |
| HighQualityBicubic | `7` | Specifica l'interpolazione bicubica di alta qualità. Il prefiltraggio viene eseguito per garantire una termoretrazione di alta qualità. Questa modalità produce immagini trasformate della massima qualità. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


