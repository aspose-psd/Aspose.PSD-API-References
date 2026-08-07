---
title: "CompleteCallback"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Fungsi callback untuk menerima peristiwa penyelesaian tugas."
type: docs
weight: 15
url: /id/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Fungsi callback untuk menerima peristiwa penyelesaian tugas.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Fungsi callback untuk menerima peristiwa penyelesaian tugas. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Fungsi callback untuk menerima peristiwa penyelesaian tugas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | Tugas asinkron. |
| wasCancelled | boolean | jika diatur ke  true  [dibatalkan]. |
| kesalahan | java.lang.Throwable | Kesalahan tersebut. |

