---
title: "ColorPalette"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カラーパレットを構成するカラーの配列を定義します。"
type: docs
weight: 27
url: /ja/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

カラーパレットを構成する色の配列を定義します。色は 32 ビット ARGB カラーです。継承できません。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | ColorPalette クラスの新しいインスタンスを初期化します。 |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | ColorPalette クラスの新しいインスタンスを初期化し、IsCompactPalette が false です。 |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | ColorPalette クラスの新しいインスタンスを初期化します。 |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | ColorPalette クラスの新しいインスタンスを初期化し、IsCompactPalette が false です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | パレットをコピーします。 |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | パレットをコピーします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | インデックスで 32 ビット ARGB パレットカラーを取得します。 |
| [getArgb32Entries()](#getArgb32Entries--) | 32 ビット ARGB 構造体の配列を取得します。 |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | インデックスでパレットカラーを取得します。 |
| [getEntries()](#getEntries--) | com.aspose.psd.Color 構造体の配列を取得します。 |
| [getEntriesCount()](#getEntriesCount--) | エントリ数を取得します。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 最も近い色のインデックスを取得します。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 最も近い色のインデックスを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | コンパクト パレットが使用されているかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


ColorPalette クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb32Entries | int[] | 32 ビット ARGB カラーパレット エントリです。 |
| isCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


ColorPalette クラスの新しいインスタンスを初期化し、IsCompactPalette が false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb32Entries | int[] | 32 ビット ARGB カラーパレット エントリです。 |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


ColorPalette クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | カラーパレットのエントリです。 |
| isCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


ColorPalette クラスの新しいインスタンスを初期化し、IsCompactPalette が false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | カラーパレットのエントリです。 |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


パレットをコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


パレットをコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |
| useCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


インデックスで 32 ビット ARGB パレットカラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | 32 ビット ARGB パレットカラーインデックスです。 |

**Returns:**
int - 指定されたインデックスによるカラーパレットエントリです。
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


32 ビット ARGB 構造体の配列を取得します。

**Returns:**
int[] - エントリ。 この Aspose.Imaging.ColorPalette を構成する 32 ビット ARGB 構造体の配列です。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


インデックスでパレットカラーを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | int | パレットカラーインデックスです。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


com.aspose.psd.Color 構造体の配列を取得します。

**Returns:**
com.aspose.psd.Color[] - エントリ。 この Aspose.Imaging.ColorPalette を構成する com.aspose.psd.Color 構造体の配列です。
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


エントリ数を取得します。

**Returns:**
int - エントリ数です。
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
```


最も近い色のインデックスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 色。 |

**Returns:**
int - 最も近い色のインデックスです。
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


最も近い色のインデックスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb32Color | int | 32 ビット ARGB カラーです。 |

**Returns:**
int - 最も近い色のインデックスです。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


コンパクト パレットが使用されているかどうかを示す値を取得または設定します。

**Returns:**
boolean - コンパクト パレットが使用されている場合は true、そうでない場合は false です。

コンパクトパレットとは、可能な限り指定されたパレットエントリのみを画像が含むことを意味し、言い換えれば画像がよりコンパクトになり、占有スペースが少なくなります。そうでない場合、2^BitsPerPixel のエントリが存在し、画像はすべての可能なパレットエントリのためにより多くのスペースを確保します。この値を true に設定し、パレットエントリを変更すると、データの移動が発生する可能性があるためパフォーマンスにペナルティがかかることがありますので、注意して使用してください。
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

