---
title: "FileCreateSource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "作成用のファイルソースを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.sources/filecreatesource/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.Source](../../com.aspose.psd/source)、[com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

作成用のファイルソースを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | FileCreateSource クラスの新しいインスタンスを初期化します。 |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | FileCreateSource クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | 作成するファイルパスを取得します。 |
| [getStreamContainer()](#getStreamContainer--) | ストリーム コンテナを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | ファイルが一時的かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


FileCreateSource クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 作成するファイルパス。 |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


FileCreateSource クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 作成するファイルパス。 |
| isTemporal | boolean | true に設定すると、作成されたファイルは一時的になります。 |

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
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


作成するファイルパスを取得します。

値: 作成するファイルパス。

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
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
public boolean isTemporal()
```


ファイルが一時的かどうかを示す値を取得します。

値: ファイルが一時的な場合は true、そうでない場合は false。

**Returns:**
boolean
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

