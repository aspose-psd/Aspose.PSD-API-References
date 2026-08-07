---
title: "CompleteCallback"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Rückruffunktion zum Empfangen des Aufgabenabschlussereignisses."
type: docs
weight: 15
url: /de/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Rückruffunktion zum Empfangen des Aufgabenabschlussereignisses.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Rückruffunktion zum Empfangen des Aufgabenabschlussereignisses. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Rückruffunktion zum Empfangen des Aufgabenabschlussereignisses.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | Die asynchrone Aufgabe. |
| wasCancelled | boolean | wenn auf true gesetzt [abgebrochen]. |
| Fehler | java.lang.Throwable | Der Fehler. |

