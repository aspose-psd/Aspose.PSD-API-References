---
title: "Antarmuka IAsyncTask"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Antarmuka Aspose.PSD.AsyncTask.IAsyncTask. Tugas asinkron"
type: docs
weight: 80
url: /id/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

Tugas asynchronous.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Mendapatkan kesalahan tugas yang tersedia setelah tugas selesai. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Mendapatkan nilai yang menunjukkan apakah tugas ini sedang berjalan. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Mendapatkan nilai yang menunjukkan apakah tugas ini dibatalkan. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Mendapatkan nilai yang menunjukkan apakah tugas ini mengalami kesalahan. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Mendapatkan kemajuan tugas asinkron. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Mendapatkan hasil dari tugas ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Membatalkan tugas ini. Tugas selesai segera, dengan risiko tidak membebaskan sumber daya tidak terkelola internal. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Membatalkan tugas ini. Tugas selesai dengan aman melalui penghentian terkontrol dari algoritma. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Menjalankan tugas ini. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Menjalankan tugas ini. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Mengatur delegasi callback lengkap. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Mengatur delegasi callback kemajuan. |

### Lihat Juga

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


