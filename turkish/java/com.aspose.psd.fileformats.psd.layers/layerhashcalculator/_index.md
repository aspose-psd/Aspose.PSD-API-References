---
title: "LayerHashCalculator"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD Katmanları için Hash Hesaplayıcı."
type: docs
weight: 20
url: /tr/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

PSD Katmanları için Karma Hesaplayıcı. Farklı PSD dosyalarında eşit veya farklı katmanları bulmak için kullanılabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Yeni bir [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Karıştırma karmasını alır. |
| [getChannelsHash()](#getChannelsHash--) | Kanallar karmasını alır. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | İçerik karmasını alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


Yeni bir [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Katman. |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Karıştırma karmasını alır.

**Returns:**
int - Katman Karıştırma Seçenekleri için benzersiz karma
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Kanallar karmasını alır.

**Returns:**
int - Tüm katman kanallarının karması
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


İçerik karmasını alır.

**Returns:**
int - Katmanların önemli parametrelerinin karması. Bu karma, tüm katman türleri için farklıdır
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

