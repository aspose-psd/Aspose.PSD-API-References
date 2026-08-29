---
title: "IAsyncTaskState"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Memberikan akses ke status tugas asinkron."
type: docs
weight: 17
url: /id/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Memberikan akses ke status tugas asinkron.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getProgress()](#getProgress--) | Mendapatkan kemajuan tugas asinkron. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Meningkatkan nilai maksimum kemajuan. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Mengatur kemajuan tugas asinkron. |
| [isCanceled()](#isCanceled--) | Mendapatkan nilai yang menunjukkan apakah tugas asinkron dibatalkan. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Mendapatkan kemajuan tugas asinkron.

Nilai: Kemajuan tugas asinkron.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Meningkatkan nilai maksimum kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai peningkatan. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Mengatur kemajuan tugas asinkron.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Status kemajuan. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Mendapatkan nilai yang menunjukkan apakah tugas asinkron dibatalkan.

Nilai:  true  jika tugas asinkron dibatalkan; sebaliknya,  false .

**Returns:**
boolean - nilai yang menunjukkan apakah tugas asinkron dibatalkan.
