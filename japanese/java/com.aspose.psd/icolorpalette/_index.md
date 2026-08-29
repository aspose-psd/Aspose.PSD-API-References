---
title: "IColorPalette"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カラーパレットインターフェイスです。"
type: docs
weight: 117
url: /ja/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

カラーパレットインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | インデックスで 32 ビット ARGB パレットカラーを取得します。 |
| [getArgb32Entries()](#getArgb32Entries--) | 32 ビット ARGB 構造体の配列を取得します。 |
| [getColor(int index)](#getColor-int-) | インデックスでパレットカラーを取得します。 |
| [getEntries()](#getEntries--) | com.aspose.psd.Color 構造体の配列を取得します。 |
| [getEntriesCount()](#getEntriesCount--) | エントリ数を取得します。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 最も近い色のインデックスを取得します。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 最も近い 32 ビット ARGB カラーのインデックスを取得します。 |
| [isCompactPalette()](#isCompactPalette--) | コンパクトパレットが使用されているかどうかを示す値を取得します。 |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


32 ビット ARGB 構造体の配列を取得します。

**Returns:**
int[] - 32 ビット ARGB エントリです。この  com.aspose.psd.ColorPalette を構成する 32 ビット ARGB 構造体の配列です。
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


com.aspose.psd.Color 構造体の配列を取得します。

**Returns:**
com.aspose.psd.Color[] - エントリです。この  com.aspose.psd.ColorPalette を構成する  com.aspose.psd.Color  構造体の配列です。
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


エントリ数を取得します。

**Returns:**
int - エントリ数です。
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


最も近い 32 ビット ARGB カラーのインデックスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb32Color | int | 32 ビット ARGB カラーです。 |

**Returns:**
int - 最も近い色のインデックスです。
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


コンパクトパレットが使用されているかどうかを示す値を取得します。

コンパクトパレットとは、可能な限り指定されたパレットエントリのみを画像が含むことを意味し、言い換えれば画像がよりコンパクトになり、占有スペースが少なくなります。そうでない場合、2^BitsPerPixel のエントリが存在し、画像はすべての可能なパレットエントリのためにより多くのスペースを確保します。この値を true に設定し、パレットエントリを変更すると、データの移動が発生する可能性があるためパフォーマンスにペナルティがかかることがありますので、注意して使用してください。

**Returns:**
boolean - コンパクト パレットが使用されている場合は true、そうでない場合は false です。
