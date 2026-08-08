---
title: "VectorPathData"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ベクトルパスを操作するクラスです。"
type: docs
weight: 18
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

ベクトルパスを操作するクラスです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) クラスの新しいインスタンスを初期化します。 |
| [VectorPathData()](#VectorPathData--) | [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | バージョンやフラグなどの一般情報のサイズ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | バイト配列として取得します。 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | リソース内のベクターパス データの長さをバイト単位で取得します。 |
| [getPaths()](#getPaths--) | パスレコードを取得または設定します。 |
| [getVersion()](#getVersion--) | バージョンを取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| [isInverted()](#isInverted--) | このインスタンスが反転しているかどうかを示す値を取得または設定します。 |
| [isNotLinked()](#isNotLinked--) | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | このインスタンスが無効かどうかを示す値を取得または設定します。 |
| [setInverted(boolean value)](#setInverted-boolean-) | このインスタンスが反転しているかどうかを示す値を取得または設定します。 |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | このインスタンスがリンクされていないかどうかを示す値を取得または設定します。 |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | パスレコードを取得または設定します。 |
| [setVersion(int value)](#setVersion-int-) | バージョンを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


[VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | リソース データ。 |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


[VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) クラスの新しいインスタンスを初期化します。

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


バージョンやフラグなどの一般情報のサイズ。

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


バイト配列として取得します。

**Returns:**
byte[] - リソースをバイト配列として表します。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


リソース内のベクターパス データの長さをバイト単位で取得します。

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


パスレコードを取得または設定します。

値: パス。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


バージョンを取得または設定します。

値: バージョン。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


このインスタンスが無効かどうかを示す値を取得または設定します。

値: このインスタンスが無効な場合は true、そうでない場合は false。

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


このインスタンスが反転しているかどうかを示す値を取得または設定します。

値: このインスタンスが反転している場合は true、そうでない場合は false。

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


このインスタンスがリンクされていないかどうかを示す値を取得または設定します。

値: このインスタンスがリンクされていない場合は true、そうでない場合は false。

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


このインスタンスが無効かどうかを示す値を取得または設定します。

値: このインスタンスが無効な場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


このインスタンスが反転しているかどうかを示す値を取得または設定します。

値: このインスタンスが反転している場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


このインスタンスがリンクされていないかどうかを示す値を取得または設定します。

値: このインスタンスがリンクされていない場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


パスレコードを取得または設定します。

値: パス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


バージョンを取得または設定します。

値: バージョン。

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

