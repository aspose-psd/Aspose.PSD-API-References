---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Kelas ini mewakili informasi tentang kemajuan operasi memuat/menyimpan/mengekspor gambar yang dapat digunakan dalam aplikasi eksternal untuk menampilkan kemajuan konversi kepada pengguna akhir"
type: docs
weight: 10
url: /id/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Kelas ini mewakili informasi tentang kemajuan operasi memuat/menyimpan/mengekspor gambar, yang dapat digunakan dalam aplikasi eksternal untuk menampilkan kemajuan konversi kepada pengguna akhir.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Menambahkan penangan acara kemajuan. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Mendapatkan deskripsi acara |
| [getEventType()](#getEventType--) | Mendapatkan tipe acara. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Mendapatkan penangan acara kemajuan terbaru. |
| [getMaxValue()](#getMaxValue--) | Mendapatkan batas nilai kemajuan atas. |
| [getValue()](#getValue--) | Mendapatkan nilai kemajuan saat ini. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Menunjukkan kemajuan. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Menunjukkan kemajuan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Batas nilai kemajuan atas. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Nilai kemajuan saat ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Menambahkan penangan acara kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Penangan acara kemajuan. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| total | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan deskripsi acara

Nilai: Deskripsi.

**Returns:**
java.lang.String - deskripsi acara
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Mendapatkan tipe acara.

Nilai: Tipe acara.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Mendapatkan penangan acara kemajuan terbaru.

Nilai: Penangan acara kemajuan terbaru.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Mendapatkan batas nilai kemajuan atas.

Nilai: Batas nilai kemajuan atas.

**Returns:**
int - batas nilai kemajuan atas.
### getValue() {#getValue--}
```
public final int getValue()
```


Mendapatkan nilai kemajuan saat ini.

Nilai: Nilai kemajuan.

**Returns:**
int - nilai kemajuan saat ini.
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


Menunjukkan kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Tipe acara. |

**Returns:**
boolean - true jika berhasil, false jika tidak
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Menunjukkan kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Tipe acara. |
| nilai | int | Nilai. |

**Returns:**
boolean - true jika berhasil, false jika tidak
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


Batas nilai kemajuan atas.

Nilai: Batas nilai kemajuan atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | batas nilai progres atas. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Nilai kemajuan saat ini.

Nilai: Nilai kemajuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | nilai progres saat ini. |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

