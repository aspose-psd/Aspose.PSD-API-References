---
title: "IAsyncTaskState"
second_title: "Aspose.PSD för Java API-referens"
description: "Tillhandahåller åtkomst till tillståndet för den asynkrona uppgiften."
type: docs
weight: 17
url: /sv/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Tillhandahåller åtkomst till tillståndet för den asynkrona uppgiften.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getProgress()](#getProgress--) | Hämtar framsteg för den asynkrona uppgiften. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Ökar det maximala värdet för framsteg. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Ställer in framsteg för den asynkrona uppgiften. |
| [isCanceled()](#isCanceled--) | Hämtar ett värde som indikerar om den asynkrona uppgiften är avbruten. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Hämtar framsteg för den asynkrona uppgiften.

Värde: Framsteg för den asynkrona uppgiften.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Ökar det maximala värdet för framsteg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Ökningsvärdet. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Ställer in framsteg för den asynkrona uppgiften.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Framstegstillståndet. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Hämtar ett värde som indikerar om den asynkrona uppgiften är avbruten.

Värde:  true  om den asynkrona uppgiften är avbruten; annars,  false .

**Returns:**
boolean - ett värde som indikerar om den asynkrona uppgiften är avbruten.
