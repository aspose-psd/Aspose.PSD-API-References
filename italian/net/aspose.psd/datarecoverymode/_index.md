---
title: Enum DataRecoveryMode
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.DataRecoveryMode enum. La modalità di recupero dati.
type: docs
weight: 730
url: /it/net/aspose.psd/datarecoverymode/
---
## DataRecoveryMode enumeration

La modalità di recupero dati.

```csharp
public enum DataRecoveryMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | Non è implicito alcun recupero dei dati. Ogni volta che il formato del file contiene dati danneggiati, viene generata l'eccezione appropriata. |
| ConsistentRecover | `1` | La modalità di recupero consistente tenta di recuperare tutti i dati purché il danneggiamento non rompa il formato del file e consenta un'ulteriore elaborazione corretta. |
| MaximalRecover | `2` | La modalità di recupero massimo recupera tutti i dati anche se il formato del file ha una struttura danneggiata e un'ulteriore elaborazione può produrre effetti non presidiati. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


