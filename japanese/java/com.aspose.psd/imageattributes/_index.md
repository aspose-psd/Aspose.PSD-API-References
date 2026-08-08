---
title: "ImageAttributes"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "com.aspose.psd.ImageAttributes オブジェクトは、レンダリング中にビットマップとメタファイルの色がどのように操作されるかに関する情報を含んでいます。"
type: docs
weight: 55
url: /ja/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

com.aspose.psd.ImageAttributes オブジェクトは、レンダリング中にビットマップとメタファイルの色がどのように操作されるかに関する情報を含んでいます。com.aspose.psd.ImageAttributes オブジェクトは、カラー調整行列、グレースケール調整行列、ガンマ補正値、カラーマップテーブル、カラーしきい値など、いくつかのカラー調整設定を保持します。レンダリング中、色は補正、暗く、明るく、除去することができます。これらの操作を適用するには、com.aspose.psd.ImageAttributes オブジェクトを初期化し、その com.aspose.psd.ImageAttributes オブジェクトのパス（[Image](../../com.aspose.psd/image) のパスも併せて）を drawImage メソッドに渡します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | com.aspose.psd.ImageAttributes クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | GDI 画像属性。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | この com.aspose.psd.ImageAttributes オブジェクトのブラシ カラーリマップ テーブルをクリアします。 |
| [clearColorKey()](#clearColorKey--) | デフォルトカテゴリのカラーキー（透過範囲）をクリアします。 |
| [clearColorKey(int type)](#clearColorKey-int-) | 指定されたカテゴリのカラーキー（透過範囲）をクリアします。 |
| [clearColorMatrix()](#clearColorMatrix--) | デフォルトカテゴリのカラー調整行列をクリアします。 |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | 指定されたカテゴリのカラー調整行列をクリアします。 |
| [clearGamma()](#clearGamma--) | デフォルトカテゴリのガンマ補正を無効にします。 |
| [clearGamma(int type)](#clearGamma-int-) | 指定されたカテゴリのガンマ補正を無効にします。 |
| [clearNoOp()](#clearNoOp--) | デフォルトカテゴリの NoOp 設定をクリアします。 |
| [clearNoOp(int type)](#clearNoOp-int-) | 指定されたカテゴリの NoOp 設定をクリアします。 |
| [clearOutputChannel()](#clearOutputChannel--) | デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。 |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | 指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。 |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | デフォルトカテゴリの出力チャンネル カラープロファイル設定をクリアします。 |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | 指定されたカテゴリの出力チャンネル カラープロファイル設定をクリアします。 |
| [clearRemapTable()](#clearRemapTable--) | デフォルトカテゴリのカラーリマップテーブルをクリアします。 |
| [clearRemapTable(int type)](#clearRemapTable-int-) | 指定されたカテゴリのカラーリマップテーブルをクリアします。 |
| [clearThreshold()](#clearThreshold--) | デフォルトカテゴリのしきい値をクリアします。 |
| [clearThreshold(int type)](#clearThreshold-int-) | 指定されたカテゴリのしきい値をクリアします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | ブラシカテゴリのカラーリマップテーブルを設定します。 |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | デフォルトカテゴリのカラキーを設定します。 |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | 指定されたカテゴリのカラキー（透明度範囲）を設定します。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | 指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | デフォルトカテゴリのカラー調整マトリックスを設定します。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | デフォルトカテゴリのカラー調整マトリックスを設定します。 |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | 指定されたカテゴリのカラー調整マトリックスを設定します。 |
| [setGamma(float gamma)](#setGamma-float-) | デフォルトカテゴリのガンマ値を設定します。 |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | 指定されたカテゴリのガンマ値を設定します。 |
| [setNoOp()](#setNoOp--) | デフォルトカテゴリのカラー調整をオフにします。 |
| [setNoOp(int type)](#setNoOp-int-) | 指定されたカテゴリのカラー調整をオフにします。 |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | デフォルトカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | 指定されたカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | デフォルトカテゴリの出力チャンネルカラープロファイルファイルを設定します。 |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | 指定されたカテゴリの出力チャンネルカラープロファイルファイルを設定します。 |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | デフォルトカテゴリのカラーリマップテーブルを設定します。 |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | 指定されたカテゴリのカラーリマップテーブルを設定します。 |
| [setThreshold(float threshold)](#setThreshold-float-) | デフォルトカテゴリのしきい値（透明度範囲）を設定します。 |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | 指定されたカテゴリのしきい値（透明度範囲）を設定します。 |
| [setWrapMode(int mode)](#setWrapMode-int-) | テクスチャを形状上または形状境界にタイル配置する方法を決定するために使用されるラップモードを設定します。 |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | テクスチャを形状上または形状境界にタイル配置する方法を決定するために使用されるラップモードとカラーを設定します。 |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | テクスチャを形状上または形状境界にタイル配置する方法を決定するために使用されるラップモードとカラーを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


com.aspose.psd.ImageAttributes クラスの新しいインスタンスを初期化します。

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


GDI 画像属性。

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


この com.aspose.psd.ImageAttributes オブジェクトのブラシ カラーリマップ テーブルをクリアします。

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


デフォルトカテゴリのカラーキー（透過範囲）をクリアします。

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


指定されたカテゴリのカラーキー（透過範囲）をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラーキーがクリアされるカテゴリを指定します。 |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


デフォルトカテゴリのカラー調整行列をクリアします。

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


指定されたカテゴリのカラー調整行列をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラー調整マトリックスがクリアされるカテゴリを指定します。 |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


デフォルトカテゴリのガンマ補正を無効にします。

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


指定されたカテゴリのガンマ補正を無効にします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、ガンマ補正が無効になるカテゴリを指定します。 |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


デフォルトカテゴリの NoOp 設定をクリアします。

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


指定されたカテゴリの NoOp 設定をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、NoOp 設定がクリアされるカテゴリを指定します。 |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、出力チャンネル設定がクリアされるカテゴリを指定します。 |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


デフォルトカテゴリの出力チャンネル カラープロファイル設定をクリアします。

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


指定されたカテゴリの出力チャンネル カラープロファイル設定をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、出力チャンネルプロファイル設定がクリアされるカテゴリを指定します。 |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


デフォルトカテゴリのカラーリマップテーブルをクリアします。

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


指定されたカテゴリのカラーリマップテーブルをクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、リマップテーブルがクリアされるカテゴリを指定します。 |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


デフォルトカテゴリのしきい値をクリアします。

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


指定されたカテゴリのしきい値をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、しきい値がクリアされるカテゴリを指定します。 |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


ブラシカテゴリのカラーリマップテーブルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap オブジェクトの配列です。 |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


デフォルトカテゴリのカラキーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | 低いカラーキー値です。 |
| colorHigh | [Color](../../com.aspose.psd/color) | 高いカラーキー値です。 |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


指定されたカテゴリのカラキー（透明度範囲）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | 低いカラーキー値です。 |
| colorHigh | [Color](../../com.aspose.psd/color) | 高いカラーキー値です。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラーキーが設定されるカテゴリを指定します。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | カラー調整マトリックスです。 |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | グレースケール調整マトリックスです。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | カラー調整マトリックスです。 |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | グレースケール調整マトリックスです。 |
| フラグ | int | Aspose.Imaging.ColorMatrixFlag の要素で、カラー調整およびグレースケール調整マトリックスの影響を受ける画像と色のタイプを指定します。 |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | カラー調整マトリックスです。 |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | グレースケール調整マトリックスです。 |
| モード | int | Aspose.Imaging.ColorMatrixFlag の要素で、カラー調整およびグレースケール調整マトリックスの影響を受ける画像と色のタイプを指定します。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラー調整およびグレースケール調整マトリックスが設定されるカテゴリを指定します。 |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


デフォルトカテゴリのカラー調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | カラー調整マトリックスです。 |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


デフォルトカテゴリのカラー調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | カラー調整マトリックスです。 |
| フラグ | int | Aspose.Imaging.ColorMatrixFlag の要素で、カラー調整マトリックスの影響を受ける画像と色のタイプを指定します。 |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


指定されたカテゴリのカラー調整マトリックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | カラー調整マトリックスです。 |
| モード | int | Aspose.Imaging.ColorMatrixFlag の要素で、カラー調整マトリックスの影響を受ける画像と色のタイプを指定します。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラー調整マトリックスが設定されるカテゴリを指定します。 |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


デフォルトカテゴリのガンマ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| gamma | float | ガンマ補正値です。 |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


指定されたカテゴリのガンマ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| gamma | float | ガンマ補正値です。 |
| 型 | int | Aspose.Imaging.ColorAdjustType 列挙型の要素で、ガンマ値が設定されるカテゴリを指定します。 |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


デフォルトカテゴリのカラー調整をオフにします。

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


指定されたカテゴリのカラー調整をオフにします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラー補正がオフになるカテゴリを指定します。 |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


デフォルトカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フラグ | int | Aspose.Imaging.ColorChannelFlag の要素で、出力チャンネルを指定します。 |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


指定されたカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| フラグ | int | Aspose.Imaging.ColorChannelFlag の要素で、出力チャンネルを指定します。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、出力チャンネルが設定されるカテゴリを指定します。 |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


デフォルトカテゴリの出力チャンネルカラープロファイルファイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | カラー プロファイル ファイルのパス名です。カラー プロファイル ファイルが %SystemRoot%\\System32\\Spool\\Drivers\\Color ディレクトリにある場合、このパラメーターはファイル名を指定できます。それ以外の場合、このパラメーターは完全修飾パス名である必要があります。 |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


指定されたカテゴリの出力チャンネルカラープロファイルファイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | カラー プロファイル ファイルのパス名です。カラー プロファイル ファイルが %SystemRoot%\\System32\\Spool\\Drivers\\Color ディレクトリにある場合、このパラメーターはファイル名を指定できます。それ以外の場合、このパラメーターは完全修飾パス名である必要があります。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、出力チャネルのカラープロファイル ファイルが設定されるカテゴリを指定します。 |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


デフォルトカテゴリのカラーリマップテーブルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap 型のカラーペアの配列です。各カラーペアは既存の色（最初の値）と、マッピング先の色（2 番目の値）を含みます。 |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


指定されたカテゴリのカラーリマップテーブルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap 型のカラーペアの配列です。各カラーペアは既存の色（最初の値）と、マッピング先の色（2 番目の値）を含みます。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラーリマップ テーブルが設定されるカテゴリを指定します。 |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


デフォルトカテゴリのしきい値（透明度範囲）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threshold | float | しきい値を指定する実数です。 |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


指定されたカテゴリのしきい値（透明度範囲）を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threshold | float | 0.0 から 1.0 のしきい値で、最大値または最小値にマッピングされる色をソートするブレークポイントとして使用されます。 |
| 型 | int | Aspose.Imaging.ColorAdjustType の要素で、カラーしきい値が設定されるカテゴリを指定します。 |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


テクスチャをシェイプ全体またはシェイプの境界でどのようにタイル状に配置するかを決定するラップモードを設定します。テクスチャが対象シェイプより小さい場合、シェイプを埋めるようにタイル状に配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| モード | int | Aspose.Imaging.WrapMode の要素で、画像の繰り返しコピーを使用して領域をタイル状に配置する方法を指定します。 |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


テクスチャをシェイプ全体またはシェイプの境界でどのようにタイル状に配置するかを決定するラップモードとカラーを設定します。テクスチャが対象シェイプより小さい場合、シェイプを埋めるようにタイル状に配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| モード | int | Aspose.Imaging.WrapMode の要素で、画像の繰り返しコピーを使用して領域をタイル状に配置する方法を指定します。 |
| color | [Color](../../com.aspose.psd/color) | com.aspose.psd.ImageAttributes オブジェクトで、レンダリングされた画像の外側のピクセルの色を指定します。mode パラメータが WrapMode.Clamp に設定され、DrawImage に渡されるソース矩形が画像自体より大きい場合にこの色が表示されます。 |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


テクスチャをシェイプ全体またはシェイプの境界でどのようにタイル状に配置するかを決定するラップモードとカラーを設定します。テクスチャが対象シェイプより小さい場合、シェイプを埋めるようにタイル状に配置されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| モード | int | Aspose.Imaging.WrapMode の要素で、画像の繰り返しコピーを使用して領域をタイル状に配置する方法を指定します。 |
| color | [Color](../../com.aspose.psd/color) | レンダリングされた画像の外側のピクセルの色を指定するカラーオブジェクトです。mode パラメータが WrapMode.Clamp に設定され、DrawImage に渡されるソース矩形が画像自体より大きい場合にこの色が表示されます。 |
| クランプ | boolean | このパラメータは効果がありません。false に設定してください。 |

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

