---
title: "ProgressEventHandlerInfo"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bu sınıf, dış uygulamalarda dönüşüm ilerlemesini son kullanıcıya göstermek için kullanılabilecek, görüntü yükleme/kaydetme/dışa aktarma işlemlerinin ilerleme bilgilerini temsil eder"
type: docs
weight: 10
url: /tr/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Bu sınıf, dış uygulamada dönüşüm ilerlemesini son kullanıcıya göstermek için kullanılabilecek, görüntü yükleme/kaydetme/dışa aktarma işlemlerinin ilerleme bilgilerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | İlerleme olay işleyicisini ekler. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Olayın açıklamasını alır |
| [getEventType()](#getEventType--) | Olayın türünü alır. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | En son ilerleme olay işleyicisini alır. |
| [getMaxValue()](#getMaxValue--) | Üst ilerleme değeri limitini alır. |
| [getValue()](#getValue--) | Mevcut ilerleme değerini alır. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | İlerlemeyi gösterir. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | İlerlemeyi gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Üst ilerleme değeri limiti. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Mevcut ilerleme değeri. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


İlerleme olay işleyicisini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | İlerleme olay işleyicisi. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| toplam | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Olayın açıklamasını alır

Değer: Açıklama.

**Returns:**
java.lang.String - olayın açıklaması
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Olayın türünü alır.

Değer: Olayın türü.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


En son ilerleme olay işleyicisini alır.

Değer: En son ilerleme olay işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Üst ilerleme değeri limitini alır.

Değer: Üst ilerleme değeri sınırı.

**Returns:**
int - üst ilerleme değeri sınırı.
### getValue() {#getValue--}
```
public final int getValue()
```


Mevcut ilerleme değerini alır.

Değer: İlerleme değeri.

**Returns:**
int - mevcut ilerleme değeri.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


İlerlemeyi gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Olayın türü. |

**Returns:**
boolean - başarılı ise true, aksi takdirde false
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


İlerlemeyi gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Olayın türü. |
| değer | int | Değer. |

**Returns:**
boolean - başarılı ise true, aksi takdirde false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


Üst ilerleme değeri limiti.

Değer: Üst ilerleme değeri sınırı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | üst ilerleme değeri sınırı. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Mevcut ilerleme değeri.

Değer: İlerleme değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | mevcut ilerleme değeri. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

