---
title: "IAsyncTaskState"
second_title: "Java için Aspose.PSD API Referansı"
description: "Asenkron görevin durumuna erişim sağlar."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Asenkron görevin durumuna erişim sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getProgress()](#getProgress--) | Asenkron görevin ilerlemesini alır. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | İlerleme maksimum değerini artırır. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Asenkron görevin ilerlemesini ayarlar. |
| [isCanceled()](#isCanceled--) | Asenkron görevin iptal edilip edilmediğini gösteren bir değer alır. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Asenkron görevin ilerlemesini alır.

Değer: Asenkron görevin ilerlemesi.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


İlerleme maksimum değerini artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Artış değeri. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Asenkron görevin ilerlemesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | İlerleme durumu. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Asenkron görevin iptal edilip edilmediğini gösteren bir değer alır.

Değer:  true  eğer asenkron görev iptal edilmişse; aksi takdirde,  false .

**Returns:**
boolean - asenkron görevin iptal edilip edilmediğini gösteren bir değer.
