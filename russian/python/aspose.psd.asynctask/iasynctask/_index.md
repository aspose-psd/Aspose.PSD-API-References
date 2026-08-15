---
title: "Класс IAsyncTask"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| is_busy | bool | r | Возвращает значение, указывающее, выполняется ли эта задача в данный момент. |
| is_canceled | bool | r | Возвращает значение, указывающее, была ли эта задача отменена. |
| is_faulted | bool | r | Возвращает значение, указывающее, завершилась ли эта задача с ошибкой. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Возвращает прогресс асинхронной задачи. |
| result | object | r | Возвращает результат этой задачи. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| abort() | Прерывает эту задачу.<br/>            Задача завершается немедленно, с риском не освобождения внутренних неуправляемых ресурсов. |
| cancel() | Отменяет эту задачу.<br/>            Задача завершается безопасно за счёт контролируемой остановки алгоритма. |
| run_async() | Запускает эту задачу. |


