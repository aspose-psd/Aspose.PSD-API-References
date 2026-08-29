---
title: "Кеш"
second_title: "Aspose.PSD for Java API Справочник"
description: "Содержит настройки кэша."
type: docs
weight: 14
url: /ru/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

Содержит настройки кэша.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | Получает количество выделенных байтов на диске. |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | Получает количество выделенных байтов в памяти. |
| [getCacheFolder()](#getCacheFolder--) | Получает папку кеша. |
| [getCacheType()](#getCacheType--) | Получает или задает используемую схему кеша. |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | Получает значение, указывающее, должна ли переалокация быть точной или нет. |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | Получает максимальное доступное дисковое пространство для кеша. |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | Получает максимальную доступную память для кеша в памяти. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | Задает папку кеша. |
| [setCacheType(int value)](#setCacheType-int-) | Задает используемую схему кеша. |
| [setDefaults()](#setDefaults--) | Устанавливает настройки кеша по умолчанию. |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | Задает значение, указывающее, должна ли переалокация быть точной или нет. |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | Задает максимальное доступное дисковое пространство для кеша. |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | Задает максимальную доступную память для кеша в памяти. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


Получает количество выделенных байтов на диске.

**Returns:**
long - количество выделенных байтов на диске.
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


Получает количество выделенных байтов в памяти.

**Returns:**
long - количество выделенных байтов в памяти.
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


Получает папку кеша.

**Returns:**
java.lang.String - папка кеша.
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


Получает или задает используемую схему кеша.

**Returns:**
int - используемая схема кеша.
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


Получает значение, указывающее, должна ли переалокация быть точной или нет. Если переалокация неточная, производительность должна быть выше.

**Returns:**
boolean -  true  если переалокация точна; иначе  false .

Точная переалокация будет выполнять переалокацию дополнительной памяти только до указанного верхнего предела. При передаче верхнего предела для памяти во время переалокации кешированные данные будут скопированы на диск, если это возможно. При передаче верхнего предела для дисковой памяти во время переалокации будет выброшено соответствующее исключение. Производительность должна быть выше, если эта опция отключена, так как дополнительное копирование не будет выполняться, если это возможно, однако это также может привести к превышению указанных верхних пределов для памяти или диска.
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


Получает максимальное доступное дисковое пространство для кеша. Указанное значение — количество мегабайт.

**Returns:**
int - максимальное доступное дисковое пространство для кеша.

Значение 0 будет использовать всю доступную память и служит как отсутствие верхнего предела.
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


Получает максимальный доступный объём памяти для кэша в памяти. Указанное значение — количество мегабайт.

**Returns:**
int — максимальная память для кэша.

Значение 0 будет использовать всю доступную память и служит как отсутствие верхнего предела.
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


Задает папку кеша.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Папка кэша. |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


Задает используемую схему кеша.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Используемая схема кэша. |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Устанавливает настройки кеша по умолчанию.

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


Устанавливает значение, указывающее, должна ли переалокация быть точной или нет. Если переалокация неточная, производительность должна быть выше.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | boolean | true, если переалокация точна; иначе false. |

Точная переалокация будет выполнять переалокацию дополнительной памяти только до указанного верхнего предела. При передаче верхнего предела для оперативной памяти во время переалокации кэшированные данные будут скопированы на диск, если это возможно. При передаче верхнего предела для дисковой памяти во время переалокации будет выброшено соответствующее исключение. Производительность должна быть выше, если эта опция отключена, так как дополнительное копирование не будет выполняться, если это возможно, однако это также может привести к превышению указанных верхних пределов для памяти или диска. |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


Устанавливает максимальное доступное дисковое пространство для кэша. Указанное значение — количество мегабайт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Максимальное доступное дисковое пространство для кэша. |

Значение 0 будет использовать всю доступную память и служит как отсутствие верхнего предела. |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


Устанавливает максимальную доступную память для кэша в памяти. Указанное значение — количество мегабайт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int | Максимальная память для кэша. |

Значение 0 будет использовать всю доступную память и служит как отсутствие верхнего предела. |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

