---
title: "IAsyncTask Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| is_busy | bool | r | Bu görevin şu anda çalışıp çalışmadığını gösteren bir değer alır. |
| is_canceled | bool | r | Bu görevin iptal edilip edilmediğini gösteren bir değer alır. |
| is_faulted | bool | r | Bu görevin hatalı olup olmadığını gösteren bir değer alır. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | Asenkron görevin ilerlemesini alır. |
| result | object | r | Bu görevin sonucunu alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| abort() | Bu görevi iptal eder.<br/>            Görev hemen tamamlanır, dahili yönetilmeyen kaynakların serbest bırakılmama riski vardır. |
| cancel() | Bu görevi iptal eder.<br/>            Görev, algoritmanın kontrollü durdurulmasıyla güvenli bir şekilde tamamlanır. |
| run_async() | Bu görevi çalıştırır. |


