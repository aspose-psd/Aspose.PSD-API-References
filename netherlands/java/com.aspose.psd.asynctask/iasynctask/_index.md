---
title: "IAsyncTask"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De asynchrone taak."
type: docs
weight: 16
url: /nl/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

De asynchrone taak.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [abort()](#abort--) | Breekt deze taak af. |
| [cancel()](#cancel--) | Annuleert deze taak. |
| [getError()](#getError--) | Haalt de taakfout op die beschikbaar is nadat de taak is voltooid. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Haalt de voortgangs‑eventhandler van de asynchrone taak op. |
| [getResult()](#getResult--) | Haalt het resultaat van deze taak op. |
| [isBusy()](#isBusy--) | Haalt een waarde op die aangeeft of deze taak momenteel wordt uitgevoerd. |
| [isCanceled()](#isCanceled--) | Haalt een waarde op die aangeeft of deze taak is geannuleerd. |
| [isFaulted()](#isFaulted--) | Haalt een waarde op die aangeeft of deze taak een fout heeft opgeleverd. |
| [runAsync()](#runAsync--) | Voert deze taak uit. |
| [runAsync(int priority)](#runAsync-int-) | Voert deze taak uit. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Stelt de volledige callback‑delegate in. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Stelt de voortgangs‑eventhandler van de asynchrone taak in. |
### abort() {#abort--}
```
public abstract void abort()
```


Breekt deze taak af. De taak wordt onmiddellijk voltooid, met het risico dat interne niet‑beheerde bronnen niet worden vrijgegeven.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Annuleert deze taak. De taak wordt veilig voltooid door gecontroleerd stoppen van het algoritme.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Haalt de taakfout op die beschikbaar is nadat de taak is voltooid.

Waarde: De taakfout.

**Returns:**
java.lang.Throwable - de taakfout die beschikbaar is nadat de taak is voltooid.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Haalt de voortgangs‑eventhandler van de asynchrone taak op.

Waarde: de voortgangs‑eventhandler van de asynchrone taak.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Haalt het resultaat van deze taak op.

Waarde: het resultaat van deze taak.

**Returns:**
java.lang.Object - het resultaat van deze taak.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Haalt een waarde op die aangeeft of deze taak momenteel wordt uitgevoerd.

Waarde:  true  als deze taak momenteel wordt uitgevoerd; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of deze taak momenteel wordt uitgevoerd.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Haalt een waarde op die aangeeft of deze taak is geannuleerd.

Waarde:  true  als deze taak werd geannuleerd; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of deze taak werd geannuleerd.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Haalt een waarde op die aangeeft of deze taak een fout heeft opgeleverd.

Waarde:  true  als deze taak een fout had; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of deze taak een fout had.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Voert deze taak uit.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Voert deze taak uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prioriteit | int | De prioriteit van de thread. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Stelt de volledige callback‑delegate in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | De volledige callback. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Stelt de voortgangs‑eventhandler van de asynchrone taak in.

Waarde: de voortgangs‑eventhandler van de asynchrone taak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | de voortgangs‑eventhandler van de asynchrone taak. |

