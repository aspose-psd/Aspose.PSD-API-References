---
title: "IAsyncTask"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Tugas asinkron."
type: docs
weight: 16
url: /id/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Tugas asinkron.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [abort()](#abort--) | Menghentikan tugas ini. |
| [cancel()](#cancel--) | Membatalkan tugas ini. |
| [getError()](#getError--) | Mendapatkan kesalahan tugas yang tersedia setelah tugas selesai. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Mendapatkan penangan peristiwa kemajuan tugas asinkron. |
| [getResult()](#getResult--) | Mendapatkan hasil tugas ini. |
| [isBusy()](#isBusy--) | Mendapatkan nilai yang menunjukkan apakah tugas ini sedang berjalan. |
| [isCanceled()](#isCanceled--) | Mendapatkan nilai yang menunjukkan apakah tugas ini dibatalkan. |
| [isFaulted()](#isFaulted--) | Mendapatkan nilai yang menunjukkan apakah tugas ini mengalami kegagalan. |
| [runAsync()](#runAsync--) | Menjalankan tugas ini. |
| [runAsync(int priority)](#runAsync-int-) | Menjalankan tugas ini. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Mengatur delegasi panggilan balik lengkap. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Mengatur penangan peristiwa kemajuan tugas asinkron. |
### abort() {#abort--}
```
public abstract void abort()
```


Menghentikan tugas ini. Tugas selesai segera, dengan risiko tidak membebaskan sumber daya tidak terkelola internal.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Membatalkan tugas ini. Tugas selesai dengan aman melalui penghentian terkontrol algoritma.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Mendapatkan kesalahan tugas yang tersedia setelah tugas selesai.

Nilai: Kesalahan tugas.

**Returns:**
java.lang.Throwable - kesalahan tugas yang tersedia setelah tugas selesai.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Mendapatkan penangan peristiwa kemajuan tugas asinkron.

Nilai: Penangan acara kemajuan dari tugas asinkron.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Mendapatkan hasil tugas ini.

Nilai: Hasil dari tugas ini.

**Returns:**
java.lang.Object - hasil dari tugas ini.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Mendapatkan nilai yang menunjukkan apakah tugas ini sedang berjalan.

Nilai:  true  jika tugas ini sedang berjalan; sebaliknya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah tugas ini sedang berjalan.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Mendapatkan nilai yang menunjukkan apakah tugas ini dibatalkan.

Nilai:  true  jika tugas ini dibatalkan; sebaliknya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah tugas ini dibatalkan.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Mendapatkan nilai yang menunjukkan apakah tugas ini mengalami kegagalan.

Nilai:  true  jika tugas ini mengalami kesalahan; sebaliknya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah tugas ini mengalami kesalahan.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Menjalankan tugas ini.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Menjalankan tugas ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prioritas | int | Prioritas thread. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Mengatur delegasi panggilan balik lengkap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Callback lengkap. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Mengatur penangan peristiwa kemajuan tugas asinkron.

Nilai: Penangan acara kemajuan dari tugas asinkron.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | penangan acara kemajuan dari tugas asinkron. |

