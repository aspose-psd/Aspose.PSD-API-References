---
title: "CompleteCallback"
second_title: "Java için Aspose.PSD API Referansı"
description: "Görev tamamlama olayını almak için geri çağırma işlevi."
type: docs
weight: 15
url: /tr/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Görev tamamlama olayını almak için geri çağırma işlevi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Görev tamamlama olayını almak için geri çağırma işlevi. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Görev tamamlama olayını almak için geri çağırma işlevi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | Asenkron görev. |
| wasCancelled | boolean | eğer  true  olarak ayarlanırsa  [was cancelled]. |
| error | java.lang.Throwable | Hata. |

