---
title: "IAsyncTaskState"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Fornisce l'accesso allo stato del task asincrono."
type: docs
weight: 17
url: /it/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Fornisce l'accesso allo stato del task asincrono.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProgress()](#getProgress--) | Restituisce l'avanzamento dell'attività asincrona. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Incrementa il valore massimo di avanzamento. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Imposta l'avanzamento dell'attività asincrona. |
| [isCanceled()](#isCanceled--) | Ottiene un valore che indica se l'attività asincrona è annullata. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Restituisce l'avanzamento dell'attività asincrona.

Valore: L'avanzamento dell'attività asincrona.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Incrementa il valore massimo di avanzamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore di incremento. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Imposta l'avanzamento dell'attività asincrona.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Lo stato di avanzamento. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Ottiene un valore che indica se l'attività asincrona è annullata.

Valore:  true  se l'attività asincrona è annullata; altrimenti,  false .

**Returns:**
boolean - un valore che indica se l'attività asincrona è annullata.
