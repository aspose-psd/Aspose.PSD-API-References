---
title: "IAsyncTaskState"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Proporciona acceso al estado de la tarea asíncrona."
type: docs
weight: 17
url: /es/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Proporciona acceso al estado de la tarea asíncrona.
## Métodos

| Método | Descripción |
| --- | --- |
| [getProgress()](#getProgress--) | Obtiene el progreso de la tarea asíncrona. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Incrementa el valor máximo del progreso. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Establece el progreso de la tarea asíncrona. |
| [isCanceled()](#isCanceled--) | Obtiene un valor que indica si la tarea asíncrona está cancelada. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Obtiene el progreso de la tarea asíncrona.

Valor: El progreso de la tarea asíncrona.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Incrementa el valor máximo del progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El valor de incremento. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Establece el progreso de la tarea asíncrona.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | El estado del progreso. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Obtiene un valor que indica si la tarea asíncrona está cancelada.

Valor:  true  si la tarea asíncrona está cancelada; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si la tarea asíncrona está cancelada.
