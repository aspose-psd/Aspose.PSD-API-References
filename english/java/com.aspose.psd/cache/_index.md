---
title: Cache
second_title: Aspose.PSD for Java API Reference
description: Contains cache settings.
type: docs
weight: 14
url: /java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Contains cache settings.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Gets the allocated disk bytes count. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Gets the allocated in-memory bytes count. |
| [getCacheFolder()](#getCacheFolder--) | Gets the cache folder. |
| [getCacheType()](#getCacheType--) | Gets or sets the cache scheme used. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Gets a value indicating whether reallocation should be exact or not. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Gets the maximum available disk space for cache. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Gets the maximum available memory for cache in memory. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Sets the cache folder. |
| [setCacheType(int value)](#setCacheType-int-) | Sets the cache scheme used. |
| [setDefaults()](#setDefaults--) | Sets the  Cache  settings to defaults. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Sets a value indicating whether reallocation should be exact or not. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Sets the maximum available disk space for cache. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Sets the maximum available memory for cache in memory. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Gets the allocated disk bytes count.

**Returns:**
long - The allocated disk bytes count.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Gets the allocated in-memory bytes count.

**Returns:**
long - The allocated in-memory bytes count.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Gets the cache folder.

**Returns:**
java.lang.String - The cache folder.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Gets or sets the cache scheme used.

**Returns:**
int - The cache scheme used.
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


Gets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher.

**Returns:**
boolean -  true  if reallocation is exact; otherwise,  false .

The exact reallocation will perform reallocation of additional memory only up to the upper limit specified. When passing upper limit for in-memory during reallocation the cached data will be copied to disk if possible. When passing upper limit for disk memory during reallocation the appropriate exception is thrown. The performance should be higher if this option is turned off as no additional copying will be performed if possible, however this may also lead to pass upper limits specified for memory or disk.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Gets the maximum available disk space for cache. The value specified is megabytes count.

**Returns:**
int - The maximum available disk space for cache.

Value of 0 will consume all available memory and serves as no upper limit.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Gets the maximum available memory for cache in memory. The value specified is megabytes count.

**Returns:**
int - The maximum memory for cache.

Value of 0 will consume all available memory and serves as no upper limit.
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


Sets the cache folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The cache folder. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Sets the cache scheme used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The cache scheme used. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Sets the  Cache  settings to defaults.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Sets a value indicating whether reallocation should be exact or not. If reallocation is non exact the performance should be higher.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if reallocation is exact; otherwise,  false .

The exact reallocation will perform reallocation of additional memory only up to the upper limit specified. When passing upper limit for in-memory during reallocation the cached data will be copied to disk if possible. When passing upper limit for disk memory during reallocation the appropriate exception is thrown. The performance should be higher if this option is turned off as no additional copying will be performed if possible, however this may also lead to pass upper limits specified for memory or disk. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Sets the maximum available disk space for cache. The value specified is megabytes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum available disk space for cache.

Value of 0 will consume all available memory and serves as no upper limit. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Sets the maximum available memory for cache in memory. The value specified is megabytes count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum memory for cache.

Value of 0 will consume all available memory and serves as no upper limit. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

