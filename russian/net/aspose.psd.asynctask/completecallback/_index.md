---
title: "Делегат CompleteCallback"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Функция обратного вызова для получения события завершения задачи"
type: docs
weight: 70
url: /ru/net/aspose.psd.asynctask/completecallback/
---
{{< psd/tize >}}
## CompleteCallback delegate

Функция обратного вызова для получения события завершения задачи.

```csharp
public delegate void CompleteCallback(IAsyncTask task, bool wasCancelled, Exception error);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| task | IAsyncTask | Асинхронная задача. |
| wasCancelled | Boolean | если установлено в `true` [было отменено]. |
| ошибка | Exception | Ошибка. |

### См. также

* interface [IAsyncTask](../iasynctask/)
* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


