---
title: "DataStreamSupporter"
second_title: "Java için Aspose.PSD API Referansı"
description: "Veri akışı konteyneri."
type: docs
weight: 38
url: /tr/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Veri akışı konteyneri.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Görüntü yüklendiğinde veya kaydedildiğinde meydana gelir |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Kredi kullanıldığında meydana gelir |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [cacheData()](#cacheData--) | Verileri önbelleğe alır ve temel DataStreamSupporter.DataStreamContainer'dan ek veri yüklemesinin yapılmayacağını garanti eder. |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Nesnenin veri akışını alır. |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Kaynak görüntünün dosya yolunu, mevcutsa alır. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır. |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekli olmadığını gösteren bir değer alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Nesnenin verisini mevcut  DataStreamSupporter  içine kaydeder. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Nesnenin verisini belirtilen akışa kaydeder. |
| [save(String filePath)](#save-java.lang.String-) | Nesnenin verisini belirtilen dosya konumuna kaydeder. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Nesnenin verisini belirtilen dosya konumuna kaydeder. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Nesnenin veri akışını ayarlar. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Kaydetme sonrası [ignore after save] olup olmadığını gösteren bir değer ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Görüntü yüklendiğinde veya kaydedildiğinde meydana gelir

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Kredi kullanıldığında meydana gelir

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Verileri önbelleğe alır ve temel DataStreamSupporter.DataStreamContainer'dan ek veri yüklemesinin yapılmayacağını garanti eder.

### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Nesnenin veri akışını alır.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Kaynak görüntünün dosya yolunu varsa alır. Kaynak yol bulunamazsa boş bir dize döndürür.

**Returns:**
java.lang.String - Kaynak görüntünün dosya yolu.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını belirten bir değeri alır.

Value:  true  eğer nesne bellek optimizasyon stratejisi kullanıyorsa; aksi takdirde,  false .

**Returns:**
boolean - nesnenin bellek optimizasyon stratejisi kullanıp kullanmadığını gösteren bir değer
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekli olmadığını gösteren bir değer alır.

**Returns:**
boolean - nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekli olmadığını gösteren bir değer.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Nesnenin verisini mevcut  DataStreamSupporter  içine kaydeder.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Nesnenin verilerini kaydetmek için akış. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Nesnenin verisini belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Nesnenin verilerini kaydetmek için akış. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Nesnenin verisini belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Nesnenin verisinin kaydedileceği dosya yolu. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Nesnenin verisini belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Nesnenin verisinin kaydedileceği dosya yolu. |
| overWrite | boolean | true olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Nesnenin veri akışını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Nesnenin veri akışı. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Kaydetme sonrası [ignore after save] olup olmadığını gösteren bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer [kaydetmeden sonra yoksay]; aksi takdirde,  false . |

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

