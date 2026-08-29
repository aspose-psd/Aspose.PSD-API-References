---
title: "IAsyncTask"
second_title: "Java için Aspose.PSD API Referansı"
description: "Asenkron görev."
type: docs
weight: 16
url: /tr/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Asenkron görev.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [abort()](#abort--) | Bu görevi durdurur. |
| [cancel()](#cancel--) | Bu görevi iptal eder. |
| [getError()](#getError--) | Görev tamamlandıktan sonra mevcut olan görev hatasını alır. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Asenkron görevin ilerleme olayı işleyicisini alır. |
| [getResult()](#getResult--) | Bu görevin sonucunu alır. |
| [isBusy()](#isBusy--) | Bu görevin şu anda çalışıp çalışmadığını gösteren bir değeri alır. |
| [isCanceled()](#isCanceled--) | Bu görevin iptal edilip edilmediğini gösteren bir değeri alır. |
| [isFaulted()](#isFaulted--) | Bu görevin hatalı olup olmadığını gösteren bir değeri alır. |
| [runAsync()](#runAsync--) | Bu görevi çalıştırır. |
| [runAsync(int priority)](#runAsync-int-) | Bu görevi çalıştırır. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Tamamlayıcı geri çağırma temsilcisini ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Asenkron görevin ilerleme olayı işleyicisini ayarlar. |
### abort() {#abort--}
```
public abstract void abort()
```


Bu görevi durdurur. Görev hemen tamamlanır, iç dahili yönetilmeyen kaynakların serbest bırakılmama riskiyle.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Bu görevi iptal eder. Görev, algoritmanın kontrollü durdurulmasıyla güvenli bir şekilde tamamlanır.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Görev tamamlandıktan sonra mevcut olan görev hatasını alır.

Değer: Görev hatası.

**Returns:**
java.lang.Throwable - görev tamamlandıktan sonra mevcut olan görev hatası.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Asenkron görevin ilerleme olayı işleyicisini alır.

Değer: Asenkron görevin ilerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Bu görevin sonucunu alır.

Değer: Bu görevin sonucu.

**Returns:**
java.lang.Object - bu görevin sonucu.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Bu görevin şu anda çalışıp çalışmadığını gösteren bir değeri alır.

Değer:  true  eğer bu görev şu anda çalışıyorsa; aksi takdirde,  false .

**Returns:**
boolean - bu görevin şu anda çalışıp çalışmadığını belirten bir değer.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Bu görevin iptal edilip edilmediğini gösteren bir değeri alır.

Değer:  true  bu görev iptal edildiyse; aksi takdirde,  false .

**Returns:**
boolean - bu görevin iptal edilip edilmediğini belirten bir değer.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Bu görevin hatalı olup olmadığını gösteren bir değeri alır.

Değer:  true  bu görev hatalıysa; aksi takdirde,  false .

**Returns:**
boolean - bu görevin hatalı olup olmadığını belirten bir değer.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Bu görevi çalıştırır.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Bu görevi çalıştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| öncelik | int | İş parçacığı önceliği. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Tamamlayıcı geri çağırma temsilcisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Tamamlayıcı geri çağırma. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Asenkron görevin ilerleme olayı işleyicisini ayarlar.

Değer: Asenkron görevin ilerleme olayı işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | asenkron görevin ilerleme olayı işleyicisi. |

