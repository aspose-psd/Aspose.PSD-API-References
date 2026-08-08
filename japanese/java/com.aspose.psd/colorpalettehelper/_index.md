---
title: "ColorPaletteHelper"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カラーパレット操作のためのヘルパークラス。"
type: docs
weight: 28
url: /ja/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

カラーパレット操作のためのヘルパークラス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create4Bit()](#create4Bit--) | 4 ビットのカラーパレットを作成します。 |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 4 ビットのグレースケールパレットを作成します。 |
| [create8Bit()](#create8Bit--) | 8 ビットのカラーパレットを作成します。 |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 8 ビットのグレースケールパレットを作成します。 |
| [createMonochrome()](#createMonochrome--) | 2色のみを含むモノクロ カラーパレットを作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | 画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。 |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | 画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。 |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | 画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。 |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | 初期画像の色値の上位ビットから構成された256色カラーパレットを取得します。 |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | 均一な256色カラーパレットを取得します。 |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | 指定されたパレットに透明色が含まれているかどうかを判定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


4 ビットのカラーパレットを作成します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


4 ビットのグレースケールパレットを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| minIsWhite | boolean | true に設定すると、パレットは白色で開始し、そうでなければ黒色で開始します。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


8 ビットのカラーパレットを作成します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


8 ビットのグレースケールパレットを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| minIsWhite | boolean | true に設定すると、パレットは白色で開始し、そうでなければ黒色で開始します。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


2色のみを含むモノクロ カラーパレットを作成します。

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | ラスタ画像です。 |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | 対象画像の境界です。 |
| entriesCount | int | 希望するエントリ数です。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | ラスタ画像です。 |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | 対象画像の境界です。 |
| entriesCount | int | 希望するエントリ数です。 |
| useImagePalette | boolean | 設定すると、利用可能な場合に独自の画像パレットを使用します。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


画像にカラーパレットがない場合、ラスタ画像からカラーパレットを取得します（画像をパレット化）。パレットが存在する場合は、計算を行う代わりにそれが使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | ラスタ画像です。 |
| entriesCount | int | 希望するエントリ数です。 |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


初期画像の色値の上位ビットから構成された256色カラーパレットを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 画像です。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


均一な256色カラーパレットを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | 画像です。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


指定されたパレットに透明色が含まれているかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | パレット。 |

**Returns:**
boolean - 指定されたパレットに透明色がある場合は true、そうでない場合は false。
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

