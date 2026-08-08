---
title: "FileSource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ファイルの操作が可能なファイル ソースを表します。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

ファイルの操作が可能なファイル ソースを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | ストリーム コンテナを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | ファイルが一時的かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSource() {#FileSource--}
```
public FileSource()
```


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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
```


ストリーム コンテナを取得します。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

注意して使用してください。取得後にストリーム コンテナを破棄する必要があります。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public abstract boolean isTemporal()
```


ファイルが一時的かどうかを示す値を取得します。

**Returns:**
boolean - ファイルが一時的である場合は true、そうでない場合は false。
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

