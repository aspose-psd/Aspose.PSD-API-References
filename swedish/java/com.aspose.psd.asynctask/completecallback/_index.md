---
title: "CompleteCallback"
second_title: "Aspose.PSD för Java API-referens"
description: "Återuppringningsfunktion för att ta emot uppgiftens slutförande‑händelse."
type: docs
weight: 15
url: /sv/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Återuppringningsfunktion för att ta emot uppgiftens slutförande‑händelse.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Återuppringningsfunktion för att ta emot uppgiftens slutförande‑händelse. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Återuppringningsfunktion för att ta emot uppgiftens slutförande‑händelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | Den asynkrona uppgiften. |
| wasCancelled | boolean | om satt till  true  [avbröts]. |
| fel | java.lang.Throwable | Felet. |

