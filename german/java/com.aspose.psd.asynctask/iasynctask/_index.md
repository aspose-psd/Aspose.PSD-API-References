---
title: "IAsyncTask"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die asynchrone Aufgabe."
type: docs
weight: 16
url: /de/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Die asynchrone Aufgabe.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [abort()](#abort--) | Bricht diese Aufgabe ab. |
| [cancel()](#cancel--) | Storniert diese Aufgabe. |
| [getError()](#getError--) | Liefert den Aufgabenfehler, der nach Abschluss der Aufgabe verfügbar ist. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Liefert den Fortschritts-Event-Handler der asynchronen Aufgabe. |
| [getResult()](#getResult--) | Liefert das Ergebnis dieser Aufgabe. |
| [isBusy()](#isBusy--) | Liefert einen Wert, der angibt, ob diese Aufgabe gerade ausgeführt wird. |
| [isCanceled()](#isCanceled--) | Liefert einen Wert, der angibt, ob diese Aufgabe abgebrochen wurde. |
| [isFaulted()](#isFaulted--) | Liefert einen Wert, der angibt, ob diese Aufgabe fehlerhaft war. |
| [runAsync()](#runAsync--) | Führt diese Aufgabe aus. |
| [runAsync(int priority)](#runAsync-int-) | Führt diese Aufgabe aus. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Setzt den vollständigen Callback-Delegaten. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Setzt den Fortschritts-Event-Handler der asynchronen Aufgabe. |
### abort() {#abort--}
```
public abstract void abort()
```


Bricht diese Aufgabe ab. Die Aufgabe wird sofort abgeschlossen, mit dem Risiko, interne nicht verwaltete Ressourcen nicht freizugeben.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Storniert diese Aufgabe. Die Aufgabe wird sicher abgeschlossen, indem der Algorithmus kontrolliert gestoppt wird.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Liefert den Aufgabenfehler, der nach Abschluss der Aufgabe verfügbar ist.

Wert: Der Aufgabenfehler.

**Returns:**
java.lang.Throwable - der Aufgabenfehler, der nach Abschluss der Aufgabe verfügbar ist.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Liefert den Fortschritts-Event-Handler der asynchronen Aufgabe.

Wert: Der Fortschritts-Event-Handler der asynchronen Aufgabe.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Liefert das Ergebnis dieser Aufgabe.

Wert: Das Ergebnis dieser Aufgabe.

**Returns:**
java.lang.Object - das Ergebnis dieser Aufgabe.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Liefert einen Wert, der angibt, ob diese Aufgabe gerade ausgeführt wird.

Wert:  true  wenn diese Aufgabe gerade ausgeführt wird; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob diese Aufgabe derzeit ausgeführt wird.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Liefert einen Wert, der angibt, ob diese Aufgabe abgebrochen wurde.

Value:  true  wenn diese Aufgabe abgebrochen wurde; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob diese Aufgabe abgebrochen wurde.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Liefert einen Wert, der angibt, ob diese Aufgabe fehlerhaft war.

Value:  true  wenn diese Aufgabe fehlerhaft war; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob diese Aufgabe fehlerhaft war.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Führt diese Aufgabe aus.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Führt diese Aufgabe aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Priorität | int | Die Thread-Priorität. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Setzt den vollständigen Callback-Delegaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Der vollständige Rückruf. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Setzt den Fortschritts-Event-Handler der asynchronen Aufgabe.

Wert: Der Fortschritts-Event-Handler der asynchronen Aufgabe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Der Fortschritts-Event-Handler der asynchronen Aufgabe. |

