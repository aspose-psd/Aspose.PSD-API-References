---
title: "Délégué CompleteCallback"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Fonction de rappel pour recevoir l'événement de fin de tâche"
type: docs
weight: 70
url: /fr/net/aspose.psd.asynctask/completecallback/
---
{{< psd/tize >}}
## CompleteCallback delegate

Fonction de rappel pour recevoir l'événement de fin de tâche.

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| task | IAsyncTask | La tâche asynchrone. |
| wasCancelled | Booléen | si défini sur `true` [a été annulé]. |
| erreur | Exception | L'erreur. |

### Voir aussi

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


