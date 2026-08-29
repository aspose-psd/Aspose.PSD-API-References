---
title: "CompleteCallback"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Fonction de rappel pour recevoir l'événement de fin de tâche."
type: docs
weight: 15
url: /fr/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Fonction de rappel pour recevoir l'événement de fin de tâche.
## Méthodes

| Méthode | Description |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Fonction de rappel pour recevoir l'événement de fin de tâche. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Fonction de rappel pour recevoir l'événement de fin de tâche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | La tâche asynchrone. |
| wasCancelled | booléen | si défini sur  true  [was cancelled]. |
| erreur | java.lang.Throwable | L'erreur. |

