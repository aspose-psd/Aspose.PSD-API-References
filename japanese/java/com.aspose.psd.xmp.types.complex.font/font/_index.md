---
title: "Font"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "XMP フォントを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

XMP フォントを表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Font()](#Font--) | Font クラスの新しいインスタンスを初期化します。 |
| [Font(String fontFamily)](#Font-java.lang.String-) | Font クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 指定されたキーを追加します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | 複合フォントを構成するフォントのファイル名配列を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | フォントのフェイスを取得または設定します。 |
| [getFontFamily()](#getFontFamily--) | フォントファミリーを取得または設定します。 |
| [getFontFileName()](#getFontFileName--) | 完全パスなしのフォントファイル名を取得または設定します。 |
| [getFontName()](#getFontName--) | PostScript フォント名を取得または設定します。 |
| [getFontType()](#getFontType--) | フォントタイプを取得または設定します。 |
| [getNamespaceUri()](#getNamespaceUri--) | デフォルトの名前空間 URI を取得します。 |
| [getPrefix()](#getPrefix--) | プレフィックスを取得します。 |
| [getVersion()](#getVersion--) | フォントバージョンを取得または設定します。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP 形式で含まれる文字列値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | このフォントが複合かどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | 複合フォントを構成するフォントのファイル名配列を取得または設定します。 |
| [setComposite(boolean value)](#setComposite-boolean-) | このフォントが複合かどうかを示す値を取得または設定します。 |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | フォントのフェイスを取得または設定します。 |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | フォントファミリーを取得または設定します。 |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | 完全パスなしのフォントファイル名を取得または設定します。 |
| [setFontName(String value)](#setFontName-java.lang.String-) | PostScript フォント名を取得または設定します。 |
| [setFontType(String value)](#setFontType-java.lang.String-) | フォントタイプを取得または設定します。 |
| [setVersion(String value)](#setVersion-java.lang.String-) | フォントバージョンを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Font クラスの新しいインスタンスを初期化します。

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Font クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontFamily | java.lang.String | フォント ファミリ。 |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


指定されたキーを追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | java.lang.String | 追加された値で識別されるキーの文字列表現です。 |
| 値 | java.lang.Object | 追加する対象の値。 |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


複合フォントを構成するフォントのファイル名配列を取得または設定します。

値: 複合フォントを構成するフォントのファイル名の配列。

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


フォントのフェイスを取得または設定します。

値: フォントフェイス。

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


フォントファミリーを取得または設定します。

値: フォント ファミリ。

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


完全パスなしのフォントファイル名を取得または設定します。

値: 完全パスなしのフォントファイル名。

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


PostScript フォント名を取得または設定します。

値: PostScript フォント名。

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


フォントタイプを取得または設定します。

TrueType、Type 1、Open Type など。値: フォントタイプ。

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


デフォルトの名前空間 URI を取得します。

**Returns:**
java.lang.String - デフォルトの名前空間 URI。
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


プレフィックスを取得します。

**Returns:**
java.lang.String - プレフィックス。
### getVersion() {#getVersion--}
```
public String getVersion()
```


フォントバージョンを取得または設定します。

/version は Type1 フォント用、Apple True Type と OpenType 用の nameId 5、CID フォント用の /CIDFontVersion、ビットマップフォント用は空文字列です。値: フォントバージョン。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP 形式で含まれる文字列値を取得します。

**Returns:**
java.lang.String - XMP 形式で含まれる文字列値を返します。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


このフォントが複合かどうかを示す値を取得または設定します。

値: このフォントが複合フォントの場合は true、そうでない場合は false。

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




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


複合フォントを構成するフォントのファイル名配列を取得または設定します。

値: 複合フォントを構成するフォントのファイル名の配列。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


このフォントが複合かどうかを示す値を取得または設定します。

値: このフォントが複合フォントの場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


フォントのフェイスを取得または設定します。

値: フォントフェイス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


フォントファミリーを取得または設定します。

値: フォント ファミリ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


完全パスなしのフォントファイル名を取得または設定します。

値: 完全パスなしのフォントファイル名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


PostScript フォント名を取得または設定します。

値: PostScript フォント名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


フォントタイプを取得または設定します。

TrueType、Type 1、Open Type など。値: フォントタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


フォントバージョンを取得または設定します。

/version は Type1 フォント用、Apple True Type と OpenType 用の nameId 5、CID フォント用の /CIDFontVersion、ビットマップフォント用は空文字列です。値: フォントバージョン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

