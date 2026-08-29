---
title: "IAsyncTaskState"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Fournit un accès à l'état de la tâche asynchrone."
type: docs
weight: 17
url: /fr/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Fournit un accès à l'état de la tâche asynchrone.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getProgress()](#getProgress--) | Obtient la progression de la tâche asynchrone. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Incrémente la valeur maximale de la progression. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Définit la progression de la tâche asynchrone. |
| [isCanceled()](#isCanceled--) | Obtient une valeur indiquant si la tâche asynchrone est annulée. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Obtient la progression de la tâche asynchrone.

Valeur : La progression de la tâche asynchrone.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Incrémente la valeur maximale de la progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La valeur d'augmentation. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Définit la progression de la tâche asynchrone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | L'état de progression. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Obtient une valeur indiquant si la tâche asynchrone est annulée.

Valeur :  true  si la tâche asynchrone est annulée ; sinon,  false .

**Returns:**
booléen - une valeur indiquant si la tâche asynchrone est annulée.
