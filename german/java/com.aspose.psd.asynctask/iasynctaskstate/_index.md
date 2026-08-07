---
title: "IAsyncTaskState"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Bietet Zugriff auf den Zustand der asynchronen Aufgabe."
type: docs
weight: 17
url: /de/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Bietet Zugriff auf den Zustand der asynchronen Aufgabe.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getProgress()](#getProgress--) | Gibt den Fortschritt der asynchronen Aufgabe zurück. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Erhöht den maximalen Fortschrittswert. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Setzt den Fortschritt der asynchronen Aufgabe. |
| [isCanceled()](#isCanceled--) | Gibt einen Wert zurück, der angibt, ob die asynchrone Aufgabe abgebrochen wurde. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Gibt den Fortschritt der asynchronen Aufgabe zurück.

Wert: Der Fortschritt der asynchronen Aufgabe.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Erhöht den maximalen Fortschrittswert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Erhöhungswert. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Setzt den Fortschritt der asynchronen Aufgabe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Der Fortschrittszustand. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Gibt einen Wert zurück, der angibt, ob die asynchrone Aufgabe abgebrochen wurde.

Wert:  true  wenn die asynchrone Aufgabe abgebrochen wird; andernfalls  false .

**Returns:**
boolean - ein Wert, der angibt, ob die asynchrone Aufgabe abgebrochen wird.
