---
title: "Interfaz IAsyncTask"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Interfaz Aspose.PSD.AsyncTask.IAsyncTask. La tarea asíncrona"
type: docs
weight: 80
url: /es/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

La tarea asíncrona.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Obtiene el error de la tarea que está disponible después de que la tarea se haya completado. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Obtiene un valor que indica si esta tarea se está ejecutando actualmente. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Obtiene un valor que indica si esta tarea fue cancelada. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Obtiene un valor que indica si esta tarea falló. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Obtiene el progreso de la tarea asíncrona. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Obtiene el resultado de esta tarea. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Abortar esta tarea. La tarea se completa inmediatamente, con el riesgo de no liberar recursos internos no administrados. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Cancela esta tarea. La tarea se completa de forma segura mediante la detención controlada del algoritmo. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Ejecuta esta tarea. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Ejecuta esta tarea. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Establece el delegado de devolución de llamada de finalización. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Establece el delegado de devolución de llamada de progreso. |

### Ver también

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


