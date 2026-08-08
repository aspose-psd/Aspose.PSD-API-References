---
title: "LengthRecord"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "サブパス長レコードクラス"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

サブパス長レコードクラス
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | 新しい [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) クラスのインスタンスを初期化します。 |
| [LengthRecord()](#LengthRecord--) | 新しい [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | ベジエノットレコードの数を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getLength_internalized()](#getLength-internalized--) | 長さを取得します。 |
| [getPathOperations()](#getPathOperations--) | パス操作を取得または設定します。 |
| [getRecordCount()](#getRecordCount--) | レコード数を取得または設定します。 |
| [getShapeIndex()](#getShapeIndex--) | レイヤー内の現在のパスシェイプのインデックスを取得または設定します。 |
| [getSourceData_internalized()](#getSourceData-internalized--) | 元のソースデータバイトを取得します。 |
| [getType()](#getType--) | タイプを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | このインスタンスが閉じているかどうかを示す値を取得または設定します。 |
| [isOpen()](#isOpen--) | このインスタンスが開いているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | ベジエノットレコードの数を取得または設定します。 |
| [setClosed(boolean value)](#setClosed-boolean-) | このインスタンスが閉じているかどうかを示す値を取得または設定します。 |
| [setOpen(boolean value)](#setOpen-boolean-) | このインスタンスが開いているかどうかを示す値を取得または設定します。 |
| [setPathOperations(int value)](#setPathOperations-int-) | パス操作を取得または設定します。 |
| [setRecordCount(int value)](#setRecordCount-int-) | レコード数を取得または設定します。 |
| [setShapeIndex(int value)](#setShapeIndex-int-) | レイヤー内の現在のパスシェイプのインデックスを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


新しい [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | レコードデータです。 |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


新しい [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) クラスのインスタンスを初期化します。

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
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


ベジエノットレコードの数を取得または設定します。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength_internalized() {#getLength-internalized--}
```
public final int getLength_internalized()
```


長さを取得します。

値: 長さ。

**Returns:**
int
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


パス操作を取得または設定します。

**Returns:**
int
### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


レコード数を取得または設定します。

値: レコード数。

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


レイヤー内の現在のパスシェイプのインデックスを取得または設定します。

**Returns:**
int
### getSourceData_internalized() {#getSourceData-internalized--}
```
public final byte[] getSourceData_internalized()
```


元のソースデータバイトを取得します。

**Returns:**
byte[] - バイト配列。
### getType() {#getType--}
```
public short getType()
```


タイプを取得します。

値: タイプです。

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


このインスタンスが閉じているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが閉じている場合; それ以外の場合は  false .

**Returns:**
boolean
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


このインスタンスが開いているかどうかを示す値を取得または設定します。

値: このインスタンスが開いている場合は true、そうでない場合は false。

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




### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


ベジエノットレコードの数を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


このインスタンスが閉じているかどうかを示す値を取得または設定します。

Value:  true  このインスタンスが閉じている場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


このインスタンスが開いているかどうかを示す値を取得または設定します。

値: このインスタンスが開いている場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


パス操作を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


レコード数を取得または設定します。

値: レコード数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


レイヤー内の現在のパスシェイプのインデックスを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

