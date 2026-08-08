---
title: "Cache"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "キャッシュ設定を含みます。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

キャッシュ設定を含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | 割り当てられたディスクバイト数を取得します。 |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | 割り当てられたメモリ内バイト数を取得します。 |
| [getCacheFolder()](#getCacheFolder--) | キャッシュフォルダーを取得します。 |
| [getCacheType()](#getCacheType--) | 使用されるキャッシュスキームを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | 再割り当てが正確であるかどうかを示す値を取得します。 |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | キャッシュ用の最大利用可能ディスク容量を取得します。 |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | キャッシュ用の最大利用可能メモリを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | キャッシュフォルダーを設定します。 |
| [setCacheType(int value)](#setCacheType-int-) | 使用されるキャッシュスキームを設定します。 |
| [setDefaults()](#setDefaults--) | Cache の設定をデフォルトに設定します。 |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | 再割り当てが正確であるかどうかを示す値を設定します。 |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | キャッシュ用の最大利用可能ディスク容量を設定します。 |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | キャッシュ用の最大利用可能メモリを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


割り当てられたディスクバイト数を取得します。

**Returns:**
long - 割り当てられたディスクバイト数。
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


割り当てられたメモリ内バイト数を取得します。

**Returns:**
long - 割り当てられたメモリ内バイト数。
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


キャッシュフォルダーを取得します。

**Returns:**
java.lang.String - キャッシュフォルダー。
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


使用されるキャッシュスキームを取得または設定します。

**Returns:**
int - 使用されるキャッシュスキーム。
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


再割り当てが正確であるかどうかを示す値を取得します。再割り当てが正確でない場合、パフォーマンスは向上するはずです。

**Returns:**
boolean -  true  再割り当てが正確な場合; それ以外の場合は  false .

正確な再割り当ては、指定された上限まで追加メモリの再割り当てのみを実行します。再割り当て中にメモリ上限を指定すると、可能な場合はキャッシュされたデータがディスクにコピーされます。ディスクメモリ上限を指定すると、適切な例外がスローされます。このオプションをオフにすると、可能な限り追加のコピーが行われないためパフォーマンスが向上するはずですが、メモリまたはディスクの上限を指定したままになる可能性もあります。
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


キャッシュの最大利用可能ディスク容量を取得します。指定された値はメガバイト数です。

**Returns:**
int - キャッシュの最大利用可能ディスク容量。

0 の値は利用可能なすべてのメモリを消費し、上限なしとして扱われます。
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


キャッシュのメモリ上での最大利用可能メモリを取得します。指定された値はメガバイト数です。

**Returns:**
int - キャッシュの最大メモリ。

0 の値は利用可能なすべてのメモリを消費し、上限なしとして扱われます。
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


キャッシュフォルダーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | キャッシュフォルダー。 |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


使用されるキャッシュスキームを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 使用されているキャッシュスキーム。 |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


Cache の設定をデフォルトに設定します。

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


再割り当てが正確かどうかを示す値を設定します。再割り当てが正確でない場合、パフォーマンスは向上するはずです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | boolean | true  再割り当てが正確な場合; それ以外の場合は  false . |

正確な再割り当ては、指定された上限まで追加メモリの再割り当てのみを実行します。再割り当て中にメモリ上限を指定すると、可能な場合はキャッシュされたデータがディスクにコピーされます。ディスクメモリ上限を指定すると、適切な例外がスローされます。このオプションをオフにすると、可能な限り追加のコピーが行われないためパフォーマンスが向上するはずですが、メモリまたはディスクの上限を指定したままになる可能性もあります。 |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


キャッシュの最大利用可能ディスク容量を設定します。指定された値はメガバイト数です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | キャッシュの最大利用可能ディスク容量。 |

0 の値は利用可能なすべてのメモリを消費し、上限なしとして扱われます。 |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


キャッシュのメモリ上での最大利用可能メモリを設定します。指定された値はメガバイト数です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | キャッシュの最大メモリ。 |

0 の値は利用可能なすべてのメモリを消費し、上限なしとして扱われます。 |

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

