---
title: "캐시"
second_title: "Java용 Aspose.PSD API 참조"
description: "캐시 설정을 포함합니다."
type: docs
weight: 14
url: /ko/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

캐시 설정을 포함합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | 할당된 디스크 바이트 수를 가져옵니다. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | 할당된 메모리 내 바이트 수를 가져옵니다. |
| [getCacheFolder()](#getCacheFolder--) | 캐시 폴더를 가져옵니다. |
| [getCacheType()](#getCacheType--) | 사용되는 캐시 스킴을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | 재할당이 정확해야 하는지 여부를 나타내는 값을 가져옵니다. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | 캐시를 위한 최대 사용 가능한 디스크 공간을 가져옵니다. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | 캐시를 위한 메모리 내 최대 사용 가능한 메모리를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | 캐시 폴더를 설정합니다. |
| [setCacheType(int value)](#setCacheType-int-) | 사용되는 캐시 스킴을 설정합니다. |
| [setDefaults()](#setDefaults--) | 캐시 설정을 기본값으로 설정합니다. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | 재할당이 정확해야 하는지 여부를 나타내는 값을 설정합니다. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | 캐시를 위한 최대 사용 가능한 디스크 공간을 설정합니다. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | 캐시를 위한 메모리 내 최대 사용 가능한 메모리를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


할당된 디스크 바이트 수를 가져옵니다.

**Returns:**
long - 할당된 디스크 바이트 수.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


할당된 메모리 내 바이트 수를 가져옵니다.

**Returns:**
long - 할당된 메모리 내 바이트 수.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


캐시 폴더를 가져옵니다.

**Returns:**
java.lang.String - 캐시 폴더.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


사용되는 캐시 스킴을 가져오거나 설정합니다.

**Returns:**
int - 사용되는 캐시 스킴.
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


재할당이 정확해야 하는지 여부를 나타내는 값을 가져옵니다. 재할당이 정확하지 않으면 성능이 더 높아야 합니다.

**Returns:**
boolean -  true  재할당이 정확하면; 그렇지 않으면  false .

The 정확한 재할당은 지정된 상한까지 추가 메모리 재할당만 수행합니다. 재할당 중 메모리 상한을 지정하면 캐시된 데이터가 가능한 경우 디스크로 복사됩니다. 디스크 메모리 상한을 지정하면 적절한 예외가 발생합니다. 이 옵션을 끄면 가능한 경우 추가 복사가 수행되지 않아 성능이 향상될 수 있지만, 메모리 또는 디스크에 지정된 상한을 초과하게 될 수도 있습니다.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


캐시의 사용 가능한 최대 디스크 공간을 가져옵니다. 지정된 값은 메가바이트 수입니다.

**Returns:**
int - 캐시의 사용 가능한 최대 디스크 공간.

값이 0이면 모든 사용 가능한 메모리를 사용하고 상한이 없는 것으로 간주됩니다.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


메모리 내 캐시의 사용 가능한 최대 메모리를 가져옵니다. 지정된 값은 메가바이트 수입니다.

**Returns:**
int - 캐시의 최대 메모리.

값이 0이면 모든 사용 가능한 메모리를 사용하고 상한이 없는 것으로 간주됩니다.
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


캐시 폴더를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 캐시 폴더. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


사용되는 캐시 스킴을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 사용된 캐시 스키마. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


캐시 설정을 기본값으로 설정합니다.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


재할당이 정확해야 하는지 여부를 나타내는 값을 설정합니다. 재할당이 정확하지 않으면 성능이 향상될 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  if 재할당이 정확합니다; otherwise,  false . |

The 정확한 재할당은 지정된 상한까지 추가 메모리 재할당만 수행합니다. 재할당 중 메모리 상한을 지정하면 캐시된 데이터가 가능한 경우 디스크로 복사됩니다. 디스크 메모리 상한을 지정하면 적절한 예외가 발생합니다. 이 옵션을 끄면 가능한 경우 추가 복사가 수행되지 않아 성능이 향상될 수 있지만, 메모리 또는 디스크에 지정된 상한을 초과하게 될 수도 있습니다. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


캐시의 사용 가능한 최대 디스크 공간을 설정합니다. 지정된 값은 메가바이트 수입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 캐시의 사용 가능한 최대 디스크 공간. |

값이 0이면 모든 사용 가능한 메모리를 사용하고 상한이 없는 것으로 간주됩니다. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


메모리 내 캐시의 사용 가능한 최대 메모리를 설정합니다. 지정된 값은 메가바이트 수입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 캐시의 최대 메모리. |

값이 0이면 모든 사용 가능한 메모리를 사용하고 상한이 없는 것으로 간주됩니다. |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

