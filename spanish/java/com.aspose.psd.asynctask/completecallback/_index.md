---
title: "CompleteCallback"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Función de devolución de llamada para recibir el evento de finalización de la tarea."
type: docs
weight: 15
url: /es/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Función de devolución de llamada para recibir el evento de finalización de la tarea.
## Métodos

| Método | Descripción |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Función de devolución de llamada para recibir el evento de finalización de la tarea. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Función de devolución de llamada para recibir el evento de finalización de la tarea.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | La tarea asíncrona. |
| wasCancelled | boolean | si se establece a  true  [se canceló]. |
| error | java.lang.Throwable | El error. |

