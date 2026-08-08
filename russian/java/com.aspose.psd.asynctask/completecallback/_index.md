---
title: "CompleteCallback"
second_title: "Aspose.PSD for Java API Справочник"
description: "Функция обратного вызова для получения события завершения задачи."
type: docs
weight: 15
url: /ru/java/com.aspose.psd.asynctask/completecallback/
---
```
public interface CompleteCallback
```

Функция обратного вызова для получения события завершения задачи.
## Методы

| Метод | Описание |
| --- | --- |
| [run(IAsyncTask task, boolean wasCancelled, Throwable error)](#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-) | Функция обратного вызова для получения события завершения задачи. |
### run(IAsyncTask task, boolean wasCancelled, Throwable error) {#run-com.aspose.psd.asynctask.IAsyncTask-boolean-java.lang.Throwable-}
```
public abstract void run(IAsyncTask task, boolean wasCancelled, Throwable error)
```


Функция обратного вызова для получения события завершения задачи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| task | [IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) | Асинхронная задача. |
| wasCancelled | boolean | если установлено в  true  [was cancelled]. |
| ошибка | java.lang.Throwable | Ошибка. |

