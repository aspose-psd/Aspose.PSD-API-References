---
title: "IAsyncTask"
second_title: "Aspose.PSD för Java API-referens"
description: "Den asynkrona uppgiften."
type: docs
weight: 16
url: /sv/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Den asynkrona uppgiften.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [abort()](#abort--) | Avbryter den här uppgiften. |
| [cancel()](#cancel--) | Avbryter den här uppgiften. |
| [getError()](#getError--) | Hämtar uppgiftsfelet som är tillgängligt efter att uppgiften har slutförts. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Hämtar händelsehanteraren för framsteg för den asynkrona uppgiften. |
| [getResult()](#getResult--) | Hämtar resultatet av den här uppgiften. |
| [isBusy()](#isBusy--) | Hämtar ett värde som indikerar om den här uppgiften för närvarande körs. |
| [isCanceled()](#isCanceled--) | Hämtar ett värde som indikerar om den här uppgiften avbröts. |
| [isFaulted()](#isFaulted--) | Hämtar ett värde som indikerar om den här uppgiften misslyckades. |
| [runAsync()](#runAsync--) | Kör den här uppgiften. |
| [runAsync(int priority)](#runAsync-int-) | Kör den här uppgiften. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Ställer in den kompletta återanropsdelegaten. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Ställer in händelsehanteraren för framsteg för den asynkrona uppgiften. |
### abort() {#abort--}
```
public abstract void abort()
```


Avbryter den här uppgiften. Uppgiften avslutas omedelbart, med risken att interna ohanterade resurser inte frigörs.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Avbryter den här uppgiften. Uppgiften avslutas säkert genom kontrollerad stoppning av algoritmen.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Hämtar uppgiftsfelet som är tillgängligt efter att uppgiften har slutförts.

Värde: Uppgiftsfelet.

**Returns:**
java.lang.Throwable - uppgiftsfelet som är tillgängligt efter att uppgiften har slutförts.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Hämtar händelsehanteraren för framsteg för den asynkrona uppgiften.

Värde: Händelsehanteraren för framsteg för den asynkrona uppgiften.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Hämtar resultatet av den här uppgiften.

Värde: Resultatet av den här uppgiften.

**Returns:**
java.lang.Object - resultatet av den här uppgiften.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Hämtar ett värde som indikerar om den här uppgiften för närvarande körs.

Värde:  true  om den här uppgiften för närvarande körs; annars  false .

**Returns:**
boolean - ett värde som indikerar om den här uppgiften för närvarande körs.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Hämtar ett värde som indikerar om den här uppgiften avbröts.

Värde:  true  om den här uppgiften avbröts; annars  false .

**Returns:**
boolean - ett värde som indikerar om den här uppgiften avbröts.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Hämtar ett värde som indikerar om den här uppgiften misslyckades.

Värde:  true  om denna uppgift misslyckades; annars,  false .

**Returns:**
boolean - ett värde som indikerar om denna uppgift misslyckades.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Kör den här uppgiften.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Kör den här uppgiften.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prioritet | int | Trådens prioritet. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Ställer in den kompletta återanropsdelegaten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Den kompletta återanropet. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Ställer in händelsehanteraren för framsteg för den asynkrona uppgiften.

Värde: Händelsehanteraren för framsteg för den asynkrona uppgiften.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | händelsehanteraren för framsteg för den asynkrona uppgiften. |

