---
title: Interface IAsyncTask
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.AsyncTask.IAsyncTask antarmuka. Tugas asinkron.
type: docs
weight: 80
url: /id/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

Tugas asinkron.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | Mendapat kesalahan tugas yang tersedia setelah tugas selesai. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | Mendapat nilai yang menunjukkan apakah tugas ini sedang berjalan. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | Mendapat nilai yang menunjukkan apakah tugas ini dibatalkan. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | Mendapat nilai yang menunjukkan apakah tugas ini salah. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | Mendapat progres tugas asinkron. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | Mendapat hasil dari tugas ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | Membatalkan tugas ini. Tugas segera diselesaikan, dengan risiko tidak membebaskan sumber daya internal yang tidak dikelola. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | Membatalkan tugas ini. Tugas diselesaikan dengan aman dengan penghentian algoritme yang terkontrol. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | Menjalankan tugas ini. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | Menjalankan tugas ini. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | Menyetel delegasi callback lengkap. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | Menetapkan delegasi panggilan balik progres. |

### Lihat juga

* ruang nama [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* perakitan [Aspose.PSD](../../)


