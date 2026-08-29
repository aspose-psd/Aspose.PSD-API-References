---
title: "StringFormat"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "配置、向き、タブ位置などのテキストレイアウト情報をカプセル化し、表示操作として省略記号の挿入や数字の国別置換、OpenType 機能を提供します。"
type: docs
weight: 106
url: /ja/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

テキストレイアウト情報（配置、向き、タブ位置など）をカプセル化し、表示操作（省略記号の挿入や数字の国別置換など）と OpenType 機能を提供します。このクラスは継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [StringFormat()](#StringFormat--) | 新しい  com.aspose.psd.StringFormat  オブジェクトを初期化します。 |
| [StringFormat(int options)](#StringFormat-int-) | 指定された  com.aspose.psd.StringFormatFlags  列挙体と語言を使用して、新しい  com.aspose.psd.StringFormat  オブジェクトを初期化します。 |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | 指定された既存の  com.aspose.psd.StringFormat  オブジェクトから、新しい  com.aspose.psd.StringFormat  オブジェクトを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [deepClone()](#deepClone--) | この  com.aspose.psd.StringFormat  オブジェクトのディープクローンを作成します。 |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 垂直方向のテキスト配置情報を取得します。 |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | ローカル数字が西洋数字に置換される際に使用される言語を取得します。 |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | 数字置換に使用される方法を取得します。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getFirstTabOffset()](#getFirstTabOffset--) | テキスト行の開始位置と最初のタブ位置との間のスペース数を取得します。 |
| [getFormatFlags()](#getFormatFlags--) | 書式情報を含む  com.aspose.psd.StringFormatFlags  列挙体を取得します。 |
| [getGenericDefault()](#getGenericDefault--) | 汎用のデフォルト  com.aspose.psd.StringFormat  オブジェクトを取得します。 |
| [getGenericTypographic()](#getGenericTypographic--) | 汎用の組版用  com.aspose.psd.StringFormat  オブジェクトを取得します。 |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | この  com.aspose.psd.StringFormat  オブジェクトに対する  com.aspose.psd.HotkeyPrefix  オブジェクトを取得します。 |
| [getLineAlignment()](#getLineAlignment--) | 水平方向の行揃えを取得します。 |
| [getTabStops()](#getTabStops--) | タブ位置間の距離の配列を、  P:Aspose.Imaging.getGraphics().PageUnit  プロパティで指定された単位で取得します。 |
| [getTrimming()](#getTrimming--) | この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.StringTrimming 列挙体を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | 垂直方向のテキスト配置情報を設定します。 |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | ローカル数字が西洋数字に置き換えられる際に使用される言語を設定します。 |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | 数字置換に使用する方法を設定します。 |
| [setFormatFlags(int value)](#setFormatFlags-int-) | 書式情報を含む com.aspose.psd.StringFormatFlags 列挙体を設定します。 |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.HotkeyPrefix オブジェクトを設定します。 |
| [setLineAlignment(int value)](#setLineAlignment-int-) | 水平方向の行揃えを設定します。 |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | この com.aspose.psd.StringFormat オブジェクトのタブ位置を設定します。 |
| [setTrimming(int value)](#setTrimming-int-) | この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.StringTrimming 列挙体を設定します。 |
| [toString()](#toString--) | この com.aspose.psd.StringFormat オブジェクトを人間が読みやすい文字列に変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


新しい  com.aspose.psd.StringFormat  オブジェクトを初期化します。

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


指定された  com.aspose.psd.StringFormatFlags  列挙体と語言を使用して、新しい  com.aspose.psd.StringFormat  オブジェクトを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| オプション | int | 新しい com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.StringFormatFlags 列挙体です。 |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


指定された既存の  com.aspose.psd.StringFormat  オブジェクトから、新しい  com.aspose.psd.StringFormat  オブジェクトを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | 新しい com.aspose.psd.StringFormat オブジェクトを初期化する元となる com.aspose.psd.StringFormat オブジェクトです。 |

### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


この  com.aspose.psd.StringFormat  オブジェクトのディープクローンを作成します。

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


垂直方向のテキスト配置情報を取得します。

**Returns:**
int - テキスト配置情報を指定する com.aspose.psd.StringAlignment 列挙体です。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


ローカル数字が西洋数字に置換される際に使用される言語を取得します。

**Returns:**
int - ローカル数字が西洋数字に置き換えられる際に使用される言語を識別する、National Language Support (NLS) 言語識別子です。NLS 言語識別子として、System.Globalization.CultureInfo オブジェクトの P:System.Globalization.CultureInfo.LCID プロパティを渡すことができます。例えば、文字列 \"ar-EG\" を System.Globalization.CultureInfo コンストラクタに渡して System.Globalization.CultureInfo オブジェクトを作成したとします。その System.Globalization.CultureInfo オブジェクトの P:System.Globalization.CultureInfo.LCID プロパティと com.aspose.psd.StringDigitSubstitute.Traditional を com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) メソッドに渡すと、表示時にアラビア数字が西洋数字に置き換えられます。

このセッターは、廃止されたメソッド setDigitSubstitution 用に導入されました。
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


数字置換に使用される方法を取得します。

**Returns:**
int - 現在のフォントでサポートされていないため表示できない文字列の文字を置換する方法を指定する com.aspose.psd.StringDigitSubstitute 列挙体の値です。

このセッターは、廃止されたメソッド SetDigitSubstitution 用に導入されました。
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


テキスト行の開始位置と最初のタブ位置との間のスペース数を取得します。

**Returns:**
float - 最初のタブオフセットです。

このプロパティは、削除されたメソッド GetTabStops 用に導入されました。
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


書式情報を含む  com.aspose.psd.StringFormatFlags  列挙体を取得します。

**Returns:**
int - 書式情報を含む com.aspose.psd.StringFormatFlags 列挙体です。
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


汎用のデフォルト  com.aspose.psd.StringFormat  オブジェクトを取得します。

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


汎用の組版用  com.aspose.psd.StringFormat  オブジェクトを取得します。

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


この  com.aspose.psd.StringFormat  オブジェクトに対する  com.aspose.psd.HotkeyPrefix  オブジェクトを取得します。

**Returns:**
int - この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.HotkeyPrefix オブジェクトで、デフォルトは F:Aspose.Imaging.HotkeyPrefix.None です。
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


水平方向の行揃えを取得します。

**Returns:**
int - 行揃えを表す com.aspose.psd.StringAlignment 列挙体です。
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


タブ位置間の距離の配列を、  P:Aspose.Imaging.getGraphics().PageUnit  プロパティで指定された単位で取得します。

**Returns:**
float[] - タブ位置です。

このプロパティは、削除されたメソッド GetTabStops 用に導入されました。
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.StringTrimming 列挙体を取得します。

**Returns:**
int - この com.aspose.psd.StringFormat オブジェクトで描画されたテキストがレイアウト矩形の端を超えたときのトリミング方法を示す com.aspose.psd.StringTrimming 列挙体です。
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


垂直方向のテキスト配置情報を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | テキストの配置情報を指定する com.aspose.psd.StringAlignment 列挙型です。 |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


ローカル数字が西洋数字に置き換えられる際に使用される言語を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | ローカル数字が西欧数字に置き換えられる際に使用される言語を識別する、National Language Support (NLS) 言語識別子です。NLS 言語識別子として、 P:System.Globalization.CultureInfo.LCID プロパティを持つ System.Globalization.CultureInfo オブジェクトを渡すことができます。例えば、文字列 "ar-EG" を引数にして System.Globalization.CultureInfo コンストラクタを呼び出し、 System.Globalization.CultureInfo オブジェクトを作成したとします。そのオブジェクトの P:System.Globalization.CultureInfo.LCID プロパティを、 com.aspose.psd.StringDigitSubstitute.Traditional と共に com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) メソッドに渡すと、表示時にアラビア・インディック数字が西欧数字に置き換えられます。 |

廃止されたメソッド SetDigitSubstitution 用にセッターが導入されました。 |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


数字置換に使用する方法を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | 現在のフォントでサポートされていないため表示できない文字列内の文字を置き換える方法を指定する com.aspose.psd.StringDigitSubstitute 列挙値です。 |

廃止されたメソッド SetDigitSubstitution 用にセッターが導入されました。 |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


書式情報を含む com.aspose.psd.StringFormatFlags 列挙体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 書式設定情報を含む com.aspose.psd.StringFormatFlags 列挙型です。 |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.HotkeyPrefix オブジェクトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この com.aspose.psd.StringFormat オブジェクトに対する com.aspose.psd.HotkeyPrefix オブジェクトで、デフォルトは F:Aspose.Imaging.HotkeyPrefix.None です。 |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


水平方向の行揃えを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 行の配置を表す com.aspose.psd.StringAlignment 列挙型です。 |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


この com.aspose.psd.StringFormat オブジェクトのタブ位置を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstTabOffset | float | テキスト行の開始位置と最初のタブ位置との間のスペース数です。 |
| tabStops | float[] | タブ位置間の距離を、 com.aspose.psd.Graphics.PageUnit プロパティで指定された単位で表した配列です。 |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


この com.aspose.psd.StringFormat オブジェクトの com.aspose.psd.StringTrimming 列挙体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この com.aspose.psd.StringFormat オブジェクトで描画されたテキストがレイアウト矩形の端を超えたときにどのようにトリミングされるかを示す com.aspose.psd.StringTrimming 列挙型です。 |

### toString() {#toString--}
```
public String toString()
```


この com.aspose.psd.StringFormat オブジェクトを人間が読みやすい文字列に変換します。

**Returns:**
java.lang.String - この com.aspose.psd.StringFormat オブジェクトの文字列表現です。
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

