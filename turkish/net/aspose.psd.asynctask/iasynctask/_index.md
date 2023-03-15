---
title: Interface IAsyncTask
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.AsyncTask.IAsyncTask arayüz. Eşzamansız görev.
type: docs
weight: 80
url: /tr/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

Eşzamansız görev.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Görev tamamlandıktan sonra mevcut olan görev hatasını alır. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Bu görevin şu anda çalışıp çalışmadığını gösteren bir değer alır. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Bu görevin iptal edilip edilmediğini gösteren bir değer alır. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Bu görevin hatalı olup olmadığını gösteren bir değer alır. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Eşzamansız görevin ilerleme durumunu alır. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Bu görevin sonucunu alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Bu görevi iptal eder. Görev, dahili yönetilmeyen kaynakları serbest bırakmama riskiyle birlikte hemen tamamlanır. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Bu görevi iptal eder. Algoritmanın kontrollü durdurulması ile görev güvenli bir şekilde tamamlanır. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Bu görevi çalıştırır. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Bu görevi çalıştırır. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Tam geri arama temsilcisini ayarlar. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | İlerleme geri çağırma temsilcisini ayarlar. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* toplantı [Aspose.PSD](../../)


