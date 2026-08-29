---
title: "ColorComponent"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カラーコンポーネントはチャネル値とチャネル値の抽象化です。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

カラーコンポーネントは Channel Value と Channel Value の抽象化です。任意のカラーは ColorComponent の配列から構成されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | 新しいインスタンスを初期化します [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Color Component/Channel のビット深度を取得します |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Color Component の説明を取得します |
| [getFullName()](#getFullName--) | 名前とスペースで区切られた説明を含む color component のフルネームを取得します |
| [getName()](#getName--) | color component の名前を取得します。 |
| [getPermittedFullNames()](#getPermittedFullNames--) | 許可されたフルネームを取得します。 |
| [getValue()](#getValue--) | 値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | 値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


新しいインスタンスを初期化します [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) クラス。ご確認ください

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bitDepth | byte | ビット深度です。 |
| fullName | java.lang.String | フルネームです。 |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Color Component/Channel のビット深度を取得します

値: ビット深度です。

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Color Component の説明を取得します

値: 説明。

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


名前とスペースで区切られた説明を含む color component のフルネームを取得します

値: フルネームです。

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


color component の名前を取得します。

値: 名前です。

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


許可されたフルネームを取得します。

値: 許可されたフルネームです。

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


値を取得または設定します。注意してください、現在のビット深度で格納可能な範囲を超える値を設定しようとすると、例外がスローされます。

値: 値です。

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


値を取得または設定します。注意してください、現在のビット深度で格納可能な範囲を超える値を設定しようとすると、例外がスローされます。

値: 値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

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

