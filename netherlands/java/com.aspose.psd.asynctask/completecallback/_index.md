---
title: "CompleteCallback"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Callback-functie om het taakvoltooiings-evenement te ontvangen."
type: docs
weight: 15
url: /nl/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Callback-functie om het taakvoltooiings-evenement te ontvangen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Callback-functie om het taakvoltooiings-evenement te ontvangen. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Callback-functie om het taakvoltooiings-evenement te ontvangen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | De asynchrone taak. |
| wasCancelled | boolean | indien ingesteld op  true  [was geannuleerd]. |
| fout | java.lang.Throwable | De fout. |

