---
title: "IAsyncTask"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il task asincrono."
type: docs
weight: 16
url: /it/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Il task asincrono.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [abort()](#abort--) | Interrompe questa attività. |
| [cancel()](#cancel--) | Annulla questa attività. |
| [getError()](#getError--) | Ottiene l'errore dell'attività disponibile dopo il completamento dell'attività. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Ottiene il gestore dell'evento di avanzamento dell'attività asincrona. |
| [getResult()](#getResult--) | Ottiene il risultato di questa attività. |
| [isBusy()](#isBusy--) | Ottiene un valore che indica se questa attività è attualmente in esecuzione. |
| [isCanceled()](#isCanceled--) | Ottiene un valore che indica se questa attività è stata annullata. |
| [isFaulted()](#isFaulted--) | Ottiene un valore che indica se questa attività ha generato un errore. |
| [runAsync()](#runAsync--) | Esegue questa attività. |
| [runAsync(int priority)](#runAsync-int-) | Esegue questa attività. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Imposta il delegato di callback di completamento. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Imposta il gestore dell'evento di avanzamento dell'attività asincrona. |
### abort() {#abort--}
```
public abstract void abort()
```


Interrompe questa attività. L'attività viene completata immediatamente, con il rischio di non liberare le risorse interne non gestite.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Annulla questa attività. L'attività viene completata in modo sicuro mediante l'arresto controllato dell'algoritmo.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Ottiene l'errore dell'attività disponibile dopo il completamento dell'attività.

Valore: L'errore dell'attività.

**Returns:**
java.lang.Throwable - l'errore dell'attività disponibile dopo il completamento dell'attività.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Ottiene il gestore dell'evento di avanzamento dell'attività asincrona.

Valore: Il gestore dell'evento di avanzamento del task asincrono.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Ottiene il risultato di questa attività.

Valore: Il risultato di questo task.

**Returns:**
java.lang.Object - il risultato di questo task.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Ottiene un valore che indica se questa attività è attualmente in esecuzione.

Valore:  true  se questo task è attualmente in esecuzione; altrimenti,  false .

**Returns:**
boolean - un valore che indica se questo task è attualmente in esecuzione.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Ottiene un valore che indica se questa attività è stata annullata.

Valore:  true  se questo task è stato annullato; altrimenti,  false .

**Returns:**
boolean - un valore che indica se questo task è stato annullato.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Ottiene un valore che indica se questa attività ha generato un errore.

Valore:  true  se questo task ha generato un errore; altrimenti,  false .

**Returns:**
boolean - un valore che indica se questo task ha generato un errore.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Esegue questa attività.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Esegue questa attività.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| priorità | int | La priorità del thread. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Imposta il delegato di callback di completamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Il callback di completamento. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Imposta il gestore dell'evento di avanzamento dell'attività asincrona.

Valore: Il gestore dell'evento di avanzamento del task asincrono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | il gestore dell'evento di avanzamento del task asincrono. |

