---
title: Class Blend
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Blend classe. Definisce un motivo di fusione. Questa classe non può essere ereditata.
type: docs
weight: 110
url: /it/net/aspose.psd/blend/
---
## Blend class

Definisce un motivo di fusione. Questa classe non può essere ereditata.

```csharp
public sealed class Blend
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Blend](blend/#constructor)() | Inizializza una nuova istanza di`Blend` classe. Il numero di elementi negli array factor e blend sarà pari a 1. |
| [Blend](blend/#constructor_1)(int) | Inizializza una nuova istanza di`Blend` classe con il numero specificato di fattori e posizioni. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Ottiene o imposta la matrice dei fattori di sfumatura per il gradiente. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Ottiene o imposta l'array di posizioni di sfumatura per il gradiente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Verifica se l'oggetto specificato è a`Blend` class ed è equivalente a this`Blend` classe. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Restituisce un codice hash per questa istanza. |

### Osservazioni

L'utilizzo tipico della classe di fusione è la definizione di un motivo di fusione per il pennello. E quindi le proprietà di fusione dovrebbero essere inizializzate con attenzione. Gli array nulli non sono consentiti. Il pennello genererà l'eccezione appropriata se i fattori di fusione o l'array di posizioni sono vuoti o la loro lunghezza non è la stessa. Se ci sono due o più elementi nell'array di posizioni, il primo elemento dovrebbe essere 0 e l'ultimo dovrebbe essere 1.

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


