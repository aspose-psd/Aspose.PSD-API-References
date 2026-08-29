---
title: "構成"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "メモリ管理のグローバル構成"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.memorymanagement/configuration/
---

**Inheritance:**
java.lang.Object
```
public final class Configuration
```

メモリ管理のグローバル構成
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | 内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。 |
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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


内部バッファ全体に対して定義された最大許容サイズであるバッファサイズのヒントを取得します。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Returns:**
int - バッファサイズのヒントで、すべての内部バッファに対して定義された最大許容サイズです。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


すべての内部バッファに対して許容される最大サイズとして定義されたバッファサイズヒントを設定します。

値: バッファサイズのヒント（メガバイト単位）。0以下の値は内部バッファに対するメモリ制限がありません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズのヒント。 |

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

