---
title: "XmpTrailerPi"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "XMP トレーラーの処理指示を表します。"
type: docs
weight: 22
url: /ja/java/com.aspose.psd.xmp/xmptrailerpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

XMP トレーラーの処理指示を表します。

end="w" または end="r" の部分は、パケットスキャンプロセッサによって XMP をインプレースで変更できるかどうかを判断するために使用されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | XmpTrailerPi クラスの新しいインスタンスを初期化します。 |
| [XmpTrailerPi()](#XmpTrailerPi--) | XmpTrailerPi クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。 |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | xmp 値を XML 表現に変換します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.psd.xmp.XmpTrailerPi-) | 現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。 |
| [isWritable()](#isWritable--) | このインスタンスが書き込み可能かどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWritable(boolean value)](#setWritable-boolean-) | このインスタンスが書き込み可能かどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


XmpTrailerPi クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isWritable | boolean | トレーラが書き込み可能かどうかを示します。 |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


XmpTrailerPi クラスの新しいインスタンスを初期化します。

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpTrailerPi deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する System.Object。 |

**Returns:**
boolean - この指定された System.Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp 値を XML 表現に変換します。

**Returns:**
java.lang.String - XMP の XML 表現を返します。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.psd.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


現在のオブジェクトが同じ型の別のオブジェクトと等しいかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | このオブジェクトと比較するオブジェクト。 |

**Returns:**
boolean - 現在のオブジェクトが other パラメータと等しい場合は true、そうでない場合は false。
### isWritable() {#isWritable--}
```
public boolean isWritable()
```


このインスタンスが書き込み可能かどうかを示す値を取得または設定します。

値: このインスタンスが書き込み可能な場合は true、そうでない場合は false。

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




### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


このインスタンスが書き込み可能かどうかを示す値を取得または設定します。

値: このインスタンスが書き込み可能な場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

