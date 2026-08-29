---
title: "Font"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "フォントの顔サイズやスタイル属性を含む、テキストの特定の書式を定義します。"
type: docs
weight: 46
url: /ja/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

フォントの顔、サイズ、スタイル属性を含むテキストの特定の書式を定義します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | 指定された既存の  com.aspose.psd.Font  と  com.aspose.psd.FontStyle  列挙体を使用する新しい  com.aspose.psd.Font  を初期化します。 |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | 指定されたサイズを使用して新しい  com.aspose.psd.Font  を初期化します。 |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | 指定されたサイズとスタイルを使用して新しい  com.aspose.psd.Font  を初期化します。 |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | 指定されたサイズ、スタイル、単位、文字セットを使用して新しい  com.aspose.psd.Font  を初期化します。 |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 指定されたサイズ、スタイル、単位を使用して新しい  com.aspose.psd.Font  を初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone()](#deepClone--) | この  Font  の正確なディープコピーを作成します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが  com.aspose.psd.Font  であり、この  com.aspose.psd.Font  と同じプロパティ値を持つかどうかを示します。 |
| [getBold()](#getBold--) | この  Font  が太字かどうかを示す値を取得します。 |
| [getCharacterSet()](#getCharacterSet--) | この  Font  が使用する文字セットを指定するバイト値を取得します。 |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | この  Font  が斜体かどうかを示す値を取得します。 |
| [getName()](#getName--) | この  Font  のフェイス名を取得します。 |
| [getSize()](#getSize--) | この  Font  の em サイズを、  P:Aspose.Imaging.Font.Unit  プロパティで指定された単位で測定して取得します。 |
| [getStrikeout()](#getStrikeout--) | この  Font  がフォントに横線を指定しているかどうかを示す値を取得します。 |
| [getStyle()](#getStyle--) | この  Font  のスタイル情報を取得します。 |
| [getUnderline()](#getUnderline--) | この  Font  が下線付きかどうかを示す値を取得します。 |
| [getUnit()](#getUnit--) | この  Font  の測定単位を取得します。 |
| [hashCode()](#hashCode--) | この  com.aspose.psd.Font  のハッシュコードを取得します。 |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | 指定されたサイズと単位を使用して新しい  com.aspose.psd.Font  を初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この  com.aspose.psd.Font  の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


指定された既存の  com.aspose.psd.Font  と  com.aspose.psd.FontStyle  列挙体を使用する新しい  com.aspose.psd.Font  を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | 新しい  com.aspose.psd.Font  を作成する元となる既存の  com.aspose.psd.Font  。 |
| newStyle | int | 新しい  com.aspose.psd.FontStyle  を新しい  com.aspose.psd.Font に適用します。複数の  com.aspose.psd.FontStyle  列挙体の値は OR 演算子で組み合わせることができます。 |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


指定されたサイズを使用して新しい  com.aspose.psd.Font  を初期化します。文字セットは  F:Aspose.Imaging.CharacterSet.Default に、グラフィック単位は  F:Aspose.Imaging.GraphicsUnit.Point に、フォントスタイルは  F:Aspose.Imaging.FontStyle.Regular に設定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font の名前の文字列表現です。 |
| emSize | float | 新しいフォントのポイント単位の em サイズです。 |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


指定されたサイズとスタイルを使用して新しい  com.aspose.psd.Font  を初期化します。文字セットは  F:Aspose.Imaging.CharacterSet.Default に、グラフィック単位は  F:Aspose.Imaging.GraphicsUnit.Point に設定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font の名前の文字列表現です。 |
| emSize | float | 新しいフォントのポイント単位の em サイズです。 |
| style | int | 新しいフォントの  com.aspose.psd.FontStyle  です。 |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


指定されたサイズ、スタイル、単位、文字セットを使用して新しい  com.aspose.psd.Font  を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font の名前の文字列表現です。 |
| emSize | float | unit パラメータで指定された単位での新しいフォントの em サイズです。 |
| style | int | 新しいフォントの  com.aspose.psd.FontStyle  です。 |
| unit | int | 新しいフォントの  com.aspose.psd.GraphicsUnit  です。 |
| characterSet | int | このフォントで使用する文字セットです。 |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


指定されたサイズ、スタイル、単位を使用して新しい  com.aspose.psd.Font  を初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font の名前の文字列表現です。 |
| emSize | float | unit パラメータで指定された単位での新しいフォントの em サイズです。 |
| style | int | 新しいフォントの  com.aspose.psd.FontStyle  です。 |
| unit | int | 新しいフォントの  com.aspose.psd.GraphicsUnit  です。 |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


この  Font  の正確なディープコピーを作成します。

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが  com.aspose.psd.Font  であり、この  com.aspose.psd.Font  と同じプロパティ値を持つかどうかを示します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | テスト対象のオブジェクトです。 |

**Returns:**
boolean - obj パラメータが  com.aspose.psd.Font  であり、この  com.aspose.psd.Font  と同じプロパティ値を持つ場合は true、そうでない場合は false。
### getBold() {#getBold--}
```
public boolean getBold()
```


この  Font  が太字かどうかを示す値を取得します。

**Returns:**
boolean - この  Font  が太字の場合は true、そうでない場合は false。
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


この  Font  が使用する文字セットを指定するバイト値を取得します。

**Returns:**
int - この  Font  が使用する文字セットです。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


この  Font  が斜体かどうかを示す値を取得します。

**Returns:**
boolean - この  Font  が斜体の場合は true、そうでない場合は false。
### getName() {#getName--}
```
public String getName()
```


この  Font  のフェイス名を取得します。

**Returns:**
java.lang.String - この  Font  のフェイス名の文字列表現です。
### getSize() {#getSize--}
```
public float getSize()
```


この  Font  の em サイズを、  P:Aspose.Imaging.Font.Unit  プロパティで指定された単位で測定して取得します。

**Returns:**
float - この  Font  の em サイズです。
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


この  Font  がフォントに横線を指定しているかどうかを示す値を取得します。

**Returns:**
boolean - この  Font  に横線が引かれている場合は true、そうでない場合は false。
### getStyle() {#getStyle--}
```
public int getStyle()
```


この  Font  のスタイル情報を取得します。

**Returns:**
int - この  Font  のスタイル情報を含む  FontStyle  列挙体です。
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


この  Font  が下線付きかどうかを示す値を取得します。

**Returns:**
boolean - この  Font  が下線付きの場合は true、そうでない場合は false。
### getUnit() {#getUnit--}
```
public int getUnit()
```


この  Font  の測定単位を取得します。

**Returns:**
int - この  Font  の測定単位を表す  GraphicsUnit  です。
### hashCode() {#hashCode--}
```
public int hashCode()
```


この  com.aspose.psd.Font  のハッシュコードを取得します。

**Returns:**
int - この  com.aspose.psd.Font  のハッシュコードです。
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


指定されたサイズと単位を使用して新しい  com.aspose.psd.Font  を初期化します。文字セットは  F:Aspose.Imaging.CharacterSet.Default に設定され、スタイルは  F:Aspose.Imaging.FontStyle.Regular に設定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | java.lang.String | com.aspose.psd.Font の名前の文字列表現です。 |
| emSize | float | unit パラメータで指定された単位での新しいフォントの em サイズです。 |
| unit | int | 新しいフォントの  com.aspose.psd.GraphicsUnit  です。 |

**Returns:**
[Font](../../com.aspose.psd/font)
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


この  com.aspose.psd.Font  の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この  com.aspose.psd.Font を表す文字列です。
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

