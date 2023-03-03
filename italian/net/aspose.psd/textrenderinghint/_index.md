---
title: Enum TextRenderingHint
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.TextRenderingHint enum. Specifica la qualità del rendering del testo.
type: docs
weight: 5700
url: /it/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

Specifica la qualità del rendering del testo.

```csharp
public enum TextRenderingHint
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| SystemDefault | `0` | Ogni carattere viene disegnato utilizzando la sua bitmap glifo, con il suggerimento di rendering predefinito del sistema. Il testo verrà disegnato utilizzando qualsiasi impostazione di smussatura dei caratteri selezionata dall'utente per il sistema. |
| SingleBitPerPixelGridFit | `1` | Ogni carattere viene disegnato utilizzando la sua bitmap glifo. Il suggerimento viene utilizzato per migliorare l'aspetto del carattere su steli e curvatura. |
| SingleBitPerPixel | `2` | Ogni carattere viene disegnato utilizzando la sua bitmap glifo. Il suggerimento non viene utilizzato. |
| AntiAliasGridFit | `3` | Ogni carattere viene disegnato utilizzando la sua bitmap glifo con antialiasing con suggerimento. Qualità molto migliore grazie all'antialiasing, ma a un costo delle prestazioni più elevato. |
| AntiAlias | `4` | Ogni carattere viene disegnato utilizzando la sua bitmap glifo con antialiasing senza suggerimenti. Migliore qualità grazie all'antialiasing. Le differenze di larghezza del gambo possono essere evidenti perché il suggerimento è disattivato. |
| ClearTypeGridFit | `5` | Ogni carattere viene disegnato utilizzando la sua bitmap glifo ClearType con suggerimento. L'impostazione di massima qualità. Utilizzato per sfruttare le funzionalità dei caratteri ClearType. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


