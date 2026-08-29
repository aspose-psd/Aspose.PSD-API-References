---
title: "ColorRangeHsl"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "HSV パラメータを変更できる 6 つのカラーレンジがあります。"
type: docs
weight: 22
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | 新しい [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) クラスのインスタンスを初期化します。 |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | 新しい [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | 色相を取得または設定します。 |
| [getLeftBorder()](#getLeftBorder--) | 左境界を取得または設定します。 |
| [getLightness()](#getLightness--) | 明度を取得または設定します。 |
| [getMostLeftBorder()](#getMostLeftBorder--) | 最左境界を取得または設定します。 |
| [getMostRightBorder()](#getMostRightBorder--) | 最右境界を取得または設定します。 |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | 範囲係数を取得します。 |
| [getRightBorder()](#getRightBorder--) | 右境界を取得または設定します。 |
| [getSaturation()](#getSaturation--) | 彩度を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | 色相が大きい範囲にあるかどうかを判定します。 |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | 色相が小さい範囲にあるかどうかを判定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | データを指定されたストリームコンテナに保存します。 |
| [setHue(short value)](#setHue-short-) | 色相を取得または設定します。 |
| [setLeftBorder(short value)](#setLeftBorder-short-) | 左境界を取得または設定します。 |
| [setLightness(short value)](#setLightness-short-) | 明度を取得または設定します。 |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | 最左境界を取得または設定します。 |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | 最右境界を取得または設定します。 |
| [setRightBorder(short value)](#setRightBorder-short-) | 右境界を取得または設定します。 |
| [setSaturation(short value)](#setSaturation-short-) | 彩度を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


新しい [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) クラスのインスタンスを初期化します。

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


新しい [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | カラー範囲データです。 |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getHue() {#getHue--}
```
public final short getHue()
```


色相を取得または設定します。

値: 色相。

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


左境界を取得または設定します。

値: 左境界。

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


明度を取得または設定します。

値: 明度。

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


最左境界を取得または設定します。

値: 最左境界。

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


最右境界を取得または設定します。

値: 最右境界。

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


範囲係数を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 色相 | double | 色相の値。 |

**Returns:**
double - 彩度範囲係数。
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


右境界を取得または設定します。

値: 右境界。

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


彩度を取得または設定します。

値: 飽和度。

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


色相が大きい範囲にあるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 色相 | double | 色相の値。 |

**Returns:**
boolean -  true  if hue in big range; otherwise,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


色相が小さい範囲にあるかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 色相 | double | 色相の値。 |

**Returns:**
boolean -  true  if hue in small range; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


データを指定されたストリームコンテナに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


色相を取得または設定します。

値: 色相。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


左境界を取得または設定します。

値: 左境界。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


明度を取得または設定します。

値: 明度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


最左境界を取得または設定します。

値: 最左境界。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


最右境界を取得または設定します。

値: 最右境界。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


右境界を取得または設定します。

値: 右境界。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


彩度を取得または設定します。

値: 飽和度。

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

