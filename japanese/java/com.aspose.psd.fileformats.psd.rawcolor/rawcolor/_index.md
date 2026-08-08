---
title: "RawColor"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Raw Color クラスは、任意のチャンネル数、任意のカラーモード、任意のビット深度で色を保存するのに役立ちます。内部クラスの中には RawColor をネイティブ形式に変換する際に問題があるものもあるため、API が CMYK カラーを提供する場合は、提供された形式を使用する方が信頼性が高いことに注意してください。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color クラスは、任意のチャンネル数、任意のカラーモード、任意のビット深度で色を保存するのに役立ちます。注意してください、内部クラスの中には RawColor をそのネイティブ形式に変換する際に問題があるものがあります。そのため、API が CMYK カラーを提供する場合は、提供された形式を使用する方が信頼性が高くなります。また、Raw Color が変換できる場合もあります。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | 新しい [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) クラスのインスタンスを初期化します。 |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | 事前定義されたカラーモードを使用して、ピクセルデータ形式から [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判定します。 |
| [getAsInt()](#getAsInt--) | 取得可能な場合、色を int として取得します。 |
| [getAsLong()](#getAsLong--) | 取得可能な場合、色を long として取得します。 |
| [getBitDepth()](#getBitDepth--) | Raw Color のビット深度を取得します。 |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 色が従うモードです。 |
| [getColorModeName()](#getColorModeName--) | カラーモードの名前を取得します。 |
| [getComponents()](#getComponents--) | 色のコンポーネントを取得します。 |
| [hashCode()](#hashCode--) | 現在のオブジェクトのハッシュコードを取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 演算子 == を実装します。 |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 演算子 != を実装します。 |
| [setAsInt(int value)](#setAsInt-int-) | 可能な場合、int 引数からすべてのチャンネルにデータを設定します。 |
| [setAsLong(long value)](#setAsLong-long-) | 可能な場合、int 引数からすべてのチャンネルにデータを設定します。 |
| [setColorMode(short value)](#setColorMode-short-) | 色が従うモードです。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


新しい [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | カスタムカラーコンポーネントです。 |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


事前定義されたカラーモードを使用して、ピクセルデータ形式から [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | ピクセルデータ形式です。 |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトがこのインスタンスと等しいかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するオブジェクトです。 |

**Returns:**
boolean -  指定された Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


取得可能な場合、色を int として取得します。

**Returns:**
int - チャンネルデータが Int に格納されます
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


取得可能な場合、色を long として取得します。

**Returns:**
long - チャンネルデータが Int に格納されます
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Raw Color のビット深度を取得します。例えば、各チャンネル/コンポーネントが 8 ビットの ARGB カラーの場合、ビット深度は 32 ビットです。各チャンネル/コンポーネントが 16 ビットのフル ARGB カラーの場合、ビット深度は 64 ビットになります。ビット深度はチャンネルのビット深度の合計から算出されます。チャンネルごとに異なるビット深度を持つことも可能です。

**Returns:**
int - すべてのチャンネルのビット深度の合計
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


色が従うモードです。

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


カラーモードの名前を取得します。カラーモード名はチャンネル/コンポーネントの名前から構成されます。

**Returns:**
java.lang.String - カラーモード名を含む文字列
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


色のコンポーネントを取得します。各コンポーネントは個別のチャンネルであり、一般的でないカラースキームを使用する場合は、各チャンネルを個別に扱う方が良いです。

値: 色のコンポーネント

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


現在のオブジェクトのハッシュコードを取得します。

**Returns:**
int - ハッシュコードです。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


演算子 == を実装します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 最初の RawColor です。 |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 2番目の RawColor。 |

**Returns:**
boolean - 演算子の結果。
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


演算子 != を実装します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 最初の RawColor です。 |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 2番目の RawColor。 |

**Returns:**
boolean - 演算子の結果。
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


可能な場合、int 引数からすべてのチャンネルにデータを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | コンポーネントデータを含む int 値 |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


可能な場合、int 引数からすべてのチャンネルにデータを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long | コンポーネントデータを含む int 値 |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


色が従うモードです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

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

