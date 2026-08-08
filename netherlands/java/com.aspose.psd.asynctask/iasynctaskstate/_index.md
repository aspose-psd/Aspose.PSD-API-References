---
title: "IAsyncTaskState"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Biedt toegang tot de status van de asynchrone taak."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Biedt toegang tot de status van de asynchrone taak.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getProgress()](#getProgress--) | Haalt de voortgang van de asynchrone taak op. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Verhoogt de maximale voortgangswaarde. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Stelt de voortgang van de asynchrone taak in. |
| [isCanceled()](#isCanceled--) | Haalt een waarde op die aangeeft of de asynchrone taak is geannuleerd. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Haalt de voortgang van de asynchrone taak op.

Waarde: De voortgang van de asynchrone taak.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Verhoogt de maximale voortgangswaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De toenamewaarde. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Stelt de voortgang van de asynchrone taak in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | De voortgangstoestand. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Haalt een waarde op die aangeeft of de asynchrone taak is geannuleerd.

Waarde:  true  als de asynchrone taak is geannuleerd; anders,  false .

**Returns:**
boolean - een waarde die aangeeft of de asynchrone taak is geannuleerd.
