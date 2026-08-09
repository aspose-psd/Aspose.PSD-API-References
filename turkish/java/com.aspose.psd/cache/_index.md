---
title: "Cache"
second_title: "Java için Aspose.PSD API Referansı"
description: "Önbellek ayarlarını içerir."
type: docs
weight: 14
url: /tr/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Önbellek ayarlarını içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Ayrılan disk bayt sayısını alır. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Ayrılan bellek içi bayt sayısını alır. |
| [getCacheFolder()](#getCacheFolder--) | Önbellek klasörünü alır. |
| [getCacheType()](#getCacheType--) | Kullanılan önbellek şemasını alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Yeniden tahsislemenin tam olup olmadığını gösteren bir değeri alır. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Önbellek için kullanılabilir en fazla disk alanını alır. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Önbellek için bellekte kullanılabilir en fazla belleği alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Önbellek klasörünü ayarlar. |
| [setCacheType(int value)](#setCacheType-int-) | Kullanılan önbellek şemasını ayarlar. |
| [setDefaults()](#setDefaults--) | Önbellek ayarlarını varsayılanlara ayarlar. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Yeniden tahsislemenin tam olup olmadığını gösteren bir değeri ayarlar. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Önbellek için kullanılabilir en fazla disk alanını ayarlar. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Önbellek için bellekte kullanılabilir en fazla belleği ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Ayrılan disk bayt sayısını alır.

**Returns:**
long - Ayrılan disk bayt sayısı.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Ayrılan bellek içi bayt sayısını alır.

**Returns:**
long - Ayrılan bellek içi bayt sayısı.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Önbellek klasörünü alır.

**Returns:**
java.lang.String - Önbellek klasörü.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Kullanılan önbellek şemasını alır veya ayarlar.

**Returns:**
int - Kullanılan önbellek şeması.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


Yeniden tahsislemenin tam olup olmadığını gösteren bir değeri alır. Yeniden tahsisleme tam değilse performans daha yüksek olmalıdır.

**Returns:**
boolean -  true  eğer yeniden tahsisleme tam ise; aksi takdirde,  false .

Tam yeniden tahsisleme, yalnızca belirtilen üst sınıra kadar ek bellek tahsis edecektir. Yeniden tahsisleme sırasında bellek içi için üst sınır verildiğinde, önbellek verileri mümkünse diske kopyalanacaktır. Yeniden tahsisleme sırasında disk belleği için üst sınır verildiğinde uygun istisna fırlatılır. Bu seçenek kapatıldığında, mümkün olduğunca ek kopyalama yapılmayacağı için performans daha yüksek olmalıdır; ancak bu, bellek veya disk için belirtilen üst sınırların aşılmasına da yol açabilir.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Önbellek için kullanılabilir en fazla disk alanını alır. Belirtilen değer megabayt sayısıdır.

**Returns:**
int - Önbellek için kullanılabilir en fazla disk alanı.

0 değeri tüm kullanılabilir belleği tüketir ve üst sınır olmadığını gösterir.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Bellekte önbellek için kullanılabilir en fazla belleği alır. Belirtilen değer megabayt sayısıdır.

**Returns:**
int - Önbellek için maksimum bellek.

0 değeri tüm kullanılabilir belleği tüketir ve üst sınır olmadığını gösterir.
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




### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


Önbellek klasörünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Önbellek klasörü. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Kullanılan önbellek şemasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Kullanılan önbellek şeması. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Önbellek ayarlarını varsayılanlara ayarlar.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Yeniden tahsislemenin tam olup olmadığını gösteren bir değer ayarlar. Yeniden tahsisleme tam değilse performans daha yüksek olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | true  eğer yeniden tahsisleme tam ise; aksi takdirde,  false . |

Tam yeniden tahsisleme, ek belleğin yeniden tahsislemesini yalnızca belirtilen üst sınıra kadar gerçekleştirir. Yeniden tahsisleme sırasında bellek içi için üst sınır verildiğinde, önbellek verileri mümkünse diske kopyalanır. Yeniden tahsisleme sırasında disk belleği için üst sınır verildiğinde uygun istisna fırlatılır. Bu seçenek kapatıldığında, mümkün olduğunda ek kopyalama yapılmayacağından performans daha yüksek olmalıdır, ancak bu aynı zamanda bellek veya disk için belirtilen üst sınırların aşılmasına da yol açabilir. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Önbellek için kullanılabilir en fazla disk alanını ayarlar. Belirtilen değer megabayt sayısıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Önbellek için kullanılabilir en fazla disk alanı. |

0 değeri tüm kullanılabilir belleği tüketir ve üst sınır olmadığını gösterir. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Bellekte önbellek için kullanılabilir en fazla belleği ayarlar. Belirtilen değer megabayt sayısıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Önbellek için en fazla bellek. |

0 değeri tüm kullanılabilir belleği tüketir ve üst sınır olmadığını gösterir. |

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

