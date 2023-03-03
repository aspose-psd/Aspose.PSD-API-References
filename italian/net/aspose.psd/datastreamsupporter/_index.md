---
title: Class DataStreamSupporter
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.DataStreamSupporter classe. Il contenitore del flusso di dati.
type: docs
weight: 740
url: /it/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

Il contenitore del flusso di dati.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta alcuna lettura dei dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Memorizza i dati nella cache e garantisce che non venga eseguito alcun caricamento di dati aggiuntivi dal sottostante[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Salva i dati dell'oggetto nella corrente`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Salva i dati dell'oggetto nella posizione file specificata. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Salva i dati dell'oggetto nella posizione file specificata. |

### Guarda anche

* class [DisposableObject](../disposableobject/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


