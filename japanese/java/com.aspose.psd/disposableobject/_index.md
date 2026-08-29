---
title: "DisposableObject"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "破棄可能なオブジェクトを表します。"
type: docs
weight: 39
url: /ja/java/com.aspose.psd/disposableobject/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

破棄可能なオブジェクトを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
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

