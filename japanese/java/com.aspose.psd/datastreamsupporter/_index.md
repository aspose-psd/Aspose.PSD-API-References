---
title: "DataStreamSupporter"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "データストリームコンテナです。"
type: docs
weight: 38
url: /ja/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

データストリームコンテナです。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | 画像が読み込まれたまたは保存されたときに発生します |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | クレジットが使用されたときに発生します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [cacheData()](#cacheData--) | データをキャッシュし、基礎となる DataStreamSupporter.DataStreamContainer から追加のデータ読み込みが行われないことを保証します。 |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | オブジェクトのデータストリームを取得します。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | ソース画像が存在する場合、そのファイルパスを取得します。 |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | オブジェクトがメモリ最適化戦略を使用するかどうかを示す値を取得します |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | オブジェクトのデータを現在の DataStreamSupporter に保存します。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(String filePath)](#save-java.lang.String-) | オブジェクトのデータを指定されたファイル場所に保存します。 |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | オブジェクトのデータを指定されたファイル場所に保存します。 |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | オブジェクトのデータストリームを設定します。 |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 保存後に [ignore after save] かどうかを示す値を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


画像が読み込まれたまたは保存されたときに発生します

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


クレジットが使用されたときに発生します

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


データをキャッシュし、基礎となる DataStreamSupporter.DataStreamContainer から追加のデータ読み込みが行われないことを保証します。

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

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


オブジェクトのデータストリームを取得します。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


ソース画像が存在する場合、そのファイルパスを取得します。ソースパスが見つからない場合は空文字列を返します。

**Returns:**
java.lang.String - ソース画像のファイルパスです。
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


オブジェクトがメモリ最適化戦略を使用するかどうかを示す値を取得します

Value:  true  オブジェクトがメモリ最適化戦略を使用する場合; それ以外の場合は  false 。

**Returns:**
boolean - オブジェクトがメモリ最適化戦略を使用するかどうかを示す値です
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値を取得します。

**Returns:**
boolean - オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


オブジェクトのデータを現在の DataStreamSupporter に保存します。

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | オブジェクトのデータを保存するストリーム。 |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ファイル | java.io.RandomAccessFile | オブジェクトのデータを保存するストリーム。 |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


オブジェクトのデータを指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | オブジェクトのデータを保存するためのファイルパス。 |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


オブジェクトのデータを指定されたファイル場所に保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | オブジェクトのデータを保存するためのファイルパス。 |
| overWrite | boolean | true に設定するとファイル内容を上書きし、そうでなければ追記されます。 |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


オブジェクトのデータストリームを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | オブジェクトのデータストリーム。 |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


保存後に [ignore after save] かどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | true  の場合は [ignore after save]; それ以外は false . |

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

