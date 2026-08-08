---
title: "PsdColorPalette"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD カラーパレットです。"
type: docs
weight: 13
url: /ja/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

PSD カラーパレットです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。 |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | 新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | パレットをコピーします。 |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | パレットをコピーします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | インデックスで 32 ビット ARGB パレットカラーを取得します。 |
| [getArgb32Entries()](#getArgb32Entries--) | 32 ビット ARGB カラーの配列を取得します。 |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | インデックスでパレットカラーを取得します。 |
| [getEntries()](#getEntries--) | [Color](../../com.aspose.psd/color) 構造体の配列を取得します。 |
| [getEntriesCount()](#getEntriesCount--) | エントリ数を取得します。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 最も近い色のインデックスを取得します。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 最も近い色のインデックスを取得します。 |
| [getRawEntries()](#getRawEntries--) | 生のカラーパレットエントリーデータを取得します。 |
| [getRawEntriesCount()](#getRawEntriesCount--) | 生のカラーパレットエントリ数を取得します。 |
| [getTransparentColor()](#getTransparentColor--) | 透過色を取得します。 |
| [getTransparentIndex()](#getTransparentIndex--) | 透過色のインデックスを取得します。 |
| [hasTransparentColor()](#hasTransparentColor--) | 透過色が存在するかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | コンパクトパレットかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |
| transparentIndex | short | 透過色インデックスです。 |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rawEntriesData | byte[] | 生のエントリーデータです。 |
| isCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rawEntriesData | byte[] | 生のエントリーデータです。 |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rawEntriesData | byte[] | 生のエントリーデータです。 |
| transparentIndex | short | 透過色インデックスです。注：インデックスは生のエントリインデックスではなく、変換されたカラー配列用です。 |
| useCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rawEntriesData | byte[] | 生のエントリーデータです。 |
| transparentIndex | short | 透過色インデックスです。注：インデックスは生のエントリインデックスではなく、変換されたカラー配列用です。 |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | カラーパレットの 32 ビット ARGB エントリです。 |
| isCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | カラーパレットのエントリです。 |
| isCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | カラーパレットのエントリです。 |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | カラーパレットのエントリです。 |
| transparentIndex | short | 透過色インデックスです。 |
| useCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


新しい [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) クラスのインスタンスを初期化し、IsCompactPalette は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | カラーパレットのエントリです。 |
| transparentIndex | short | 透過色インデックスです。 |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


パレットをコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


パレットをコピーします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | カラーパレット。 |
| useCompactPalette | boolean | コンパクトパレットかどうかを示します。 |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


32 ビット ARGB カラーの配列を取得します。

**Returns:**
int[] - この [ColorPalette](../../com.aspose.psd/colorpalette) を構成する 32 ビット ARGB 構造体の配列です。値: エントリ。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
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
public final Color[] getEntries()
```


[Color](../../com.aspose.psd/color) 構造体の配列を取得します。

**Returns:**
com.aspose.psd.Color[] - この [ColorPalette](../../com.aspose.psd/colorpalette) を構成する [Color](../../com.aspose.psd/color) 構造体の配列です。値: エントリ。
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


エントリ数を取得します。

値: エントリ数。

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


最も近い色のインデックスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb32Color | int | 32 ビット ARGB カラーです。 |

**Returns:**
int - 最も近い色のインデックスです。
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


生のカラーパレットエントリーデータを取得します。

値: 生のカラーパレットエントリデータです。

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


生のカラーパレットエントリ数を取得します。

値: 生のカラーパレットエントリ数です。

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


透過色を取得します。

値: 透明色です。

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


透過色のインデックスを取得します。

値: 透明色のインデックスです。

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


透過色が存在するかどうかを示す値を取得します。

値: 透明色が存在する場合は true、そうでない場合は false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


コンパクトパレットかどうかを示す値を取得します。

値: パレットがコンパクトな場合は true、そうでない場合は false。

--------------------

コンパクトパレットとは、可能な限り指定されたパレットエントリのみを画像が含むことを意味し、言い換えれば画像がよりコンパクトになり、占有スペースが少なくなります。そうでない場合、2^BitsPerPixel のエントリが存在し、画像はすべての可能なパレットエントリのためにより多くのスペースを確保します。この値を true に設定し、パレットエントリを変更すると、データの移動が発生する可能性があるためパフォーマンスにペナルティがかかることがありますので、注意して使用してください。

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

