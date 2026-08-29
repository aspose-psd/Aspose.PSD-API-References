---
title: "Cache"
second_title: "Aspose.PSD 的 Java API 参考"
description: "包含缓存设置。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

包含缓存设置。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | 获取已分配的磁盘字节数。 |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | 获取已分配的内存字节数。 |
| [getCacheFolder()](#getCacheFolder--) | 获取缓存文件夹。 |
| [getCacheType()](#getCacheType--) | 获取或设置使用的缓存方案。 |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | 获取一个值，指示重新分配是否应精确。 |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | 获取缓存的最大可用磁盘空间。 |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | 获取缓存在内存中的最大可用内存。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | 设置缓存文件夹。 |
| [setCacheType(int value)](#setCacheType-int-) | 设置使用的缓存方案。 |
| [setDefaults()](#setDefaults--) | 将  Cache  设置为默认值。 |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | 设置一个值，指示重新分配是否应精确。 |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | 设置缓存的最大可用磁盘空间。 |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | 设置缓存在内存中的最大可用内存。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


获取已分配的磁盘字节数。

**Returns:**
long - 已分配的磁盘字节计数。
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


获取已分配的内存字节数。

**Returns:**
long - 已分配的内存字节计数。
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


获取缓存文件夹。

**Returns:**
java.lang.String - 缓存文件夹。
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


获取或设置使用的缓存方案。

**Returns:**
int - 使用的缓存方案。
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


获取一个值，指示重新分配是否应精确。如果重新分配不是精确的，性能应更高。

**Returns:**
boolean -  true  如果重新分配是精确的；否则，  false 。

精确的重新分配将仅在指定的上限范围内执行额外内存的重新分配。若在重新分配期间为内存传递上限，则缓存数据将在可能的情况下复制到磁盘。若在重新分配期间为磁盘内存传递上限，则会抛出相应的异常。如果关闭此选项，由于不会进行额外的复制，性能应更高，但这也可能导致超出为内存或磁盘指定的上限。
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


获取缓存的最大可用磁盘空间。指定的值为兆字节计数。

**Returns:**
int - 缓存的最大可用磁盘空间。

值为 0 将消耗所有可用内存，并视为没有上限。
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


获取缓存在内存中的最大可用内存。指定的值为兆字节计数。

**Returns:**
int - 缓存的最大内存。

值为 0 将消耗所有可用内存，并视为没有上限。
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


设置缓存文件夹。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 缓存文件夹。 |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


设置使用的缓存方案。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 使用的缓存方案。 |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


将  Cache  设置为默认值。

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


设置一个值，指示重新分配是否应精确。如果重新分配不是精确的，性能应更高。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  如果重新分配是精确的；否则，  false 。 |

精确重新分配将仅在指定的上限范围内执行额外内存的重新分配。 在重新分配期间传入内存上限时，缓存数据将在可能的情况下复制到磁盘。 在重新分配期间传入磁盘内存上限时，将抛出相应的异常。 如果关闭此选项，性能应更高，因为在可能的情况下不会执行额外的复制，但这也可能导致传入的内存或磁盘上限被使用。 |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


设置缓存的最大可用磁盘空间。指定的值为兆字节数量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | int | 缓存的最大可用磁盘空间。 |

值为 0 将占用所有可用内存，并视为没有上限。 |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


设置缓存在内存中的最大可用内存。指定的值为兆字节数量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | int | 缓存的最大内存。 |

值为 0 将占用所有可用内存，并视为没有上限。 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

