---
title: "CompleteCallback"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Funzione di callback per ricevere l'evento di completamento del task."
type: docs
weight: 15
url: /it/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Funzione di callback per ricevere l'evento di completamento del task.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Funzione di callback per ricevere l'evento di completamento del task. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Funzione di callback per ricevere l'evento di completamento del task.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | Il task asincrono. |
| wasCancelled | boolean | se impostato su  true  [annullato]. |
| errore | java.lang.Throwable | L'errore. |

