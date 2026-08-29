---
title: "GrdmResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "クラス GrdmResource."
type: docs
weight: 35
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

GrdmResource クラス。Gradient-Map レイヤーに関する情報を含みます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | 新しい [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | デフォルトのスケール。 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB ヘッダー バージョン |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 固有のリソース署名。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD ヘッダー バージョン |
| [ResourceSignature](#ResourceSignature) | 共通リソース署名。 |
| [TypeToolKey](#TypeToolKey) | タイプツール情報キー。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | ベンチャー ライセンス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | リソースが PSB 固有かどうかをチェックし、設定します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | カラーモデル。 |
| [getColorPoints()](#getColorPoints--) | カラー点を取得または設定します。 |
| [getData()](#getData--) | データを取得または設定します。 |
| [getDither()](#getDither--) | グラデーションがディザリングされているか。 |
| [getExpansionCount()](#getExpansionCount--) | 拡張カウント (Photoshop 6.0 では = 2)。 |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | 長さ (= 32 for Photoshop 6.0)。何に使用されるかの情報はありません。 |
| [getGradientMode()](#getGradientMode--) | このグラデーションのモードは 'Gradient Type' = 'Solid/Noise' (0/1) を決定します。 |
| [getGradientName()](#getGradientName--) | グラデーションの名前: パディングされた Unicode 文字列。 |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getInterpolation()](#getInterpolation--) | 補間。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | グラデーションの補間方法を取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getLength()](#getLength--) | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat.Rgba64Bpp フォーマットの最大色。 |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat.Rgba64Bpp フォーマットの最小色。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | このリソースに必要な最小 PSD バージョンを取得します。 |
| [getReverse()](#getReverse--) | 勾配が反転しています。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | ノイズグラデーションの色を生成するために使用される乱数シード。 |
| [getRoughness()](#getRoughness--) | 粗さ係数。'Gradient type' = 'Noise' の場合、'Roughness' (0 - 2048) を割り当てることができます。 |
| [getShowTransparency()](#getShowTransparency--) | 透明度表示フラグ。'Gradient type' = 'Noise' の場合、'Add transparency' を true に設定できます。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getTransparencyPoints()](#getTransparencyPoints--) | 透過点を取得または設定します。 |
| [getUseVectorColor()](#getUseVectorColor--) | ベクトルカラーを使用するフラグ。 |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | 勾配の長さを初期化します。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | リソースデータを指定されたストリームコンテナに保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setColorModel(short value)](#setColorModel-short-) | カラーモデル。 |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | カラー点を取得または設定します。 |
| [setDither(boolean value)](#setDither-boolean-) | グラデーションがディザリングされているか。 |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 拡張カウント (Photoshop 6.0 では = 2)。 |
| [setGradientMode(int value)](#setGradientMode-int-) | このグラデーションのモードは 'Gradient Type' = 'Solid/Noise' (0/1) を決定します。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | グラデーションの名前: パディングされた Unicode 文字列。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [setInterpolation(short value)](#setInterpolation-short-) | 補間。 |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | グラデーションの補間方法を取得または設定します。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp フォーマットの最大色。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp フォーマットの最小色。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 勾配が反転しています。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | ノイズグラデーションの色を生成するために使用される乱数シード。 |
| [setRoughness(int value)](#setRoughness-int-) | 粗さ係数。'Gradient type' = 'Noise' の場合、'Roughness' (0 - 2048) を割り当てることができます。 |
| [setShowTransparency(short value)](#setShowTransparency-short-) | 透明度表示フラグ。'Gradient type' = 'Noise' の場合、'Add transparency' を true に設定できます。 |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | 透過点を取得または設定します。 |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | ベクトルカラーを使用するフラグ。 |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


新しい [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| psdVersion | int | リソースの PSD バージョンです。 |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


デフォルトのスケール。

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB ヘッダー バージョン

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB 固有のリソース署名。

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD ヘッダー バージョン

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


共通リソース署名。

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


タイプツール情報キー。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


ベンチャー ライセンス。

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


リソースが PSB 固有かどうかをチェックし、設定します。現在、一部のリソースは認識されていませんが、保存時の動作を変更する PSB 固有リソースの完全なリストがあります。そのため、少なくとも UnknownResource でこれをチェックする必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | int | キーです。 |

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


カラーモデル。'Gradient type' = 'Noise' の場合、'Color Model' を RGB/SHB/LAB (3/4/6) に割り当てることができます。

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


カラー点を取得または設定します。

値: カラー点です。

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


データを取得または設定します。

値: データ。

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


グラデーションがディザリングされているか。

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


拡張カウント (Photoshop 6.0 では = 2)。

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


長さ (= 32 for Photoshop 6.0)。何に使用されるかの情報はありません。

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


このグラデーションのモードは 'Gradient Type' = 'Solid/Noise' (0/1) を決定します。

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


グラデーションの名前: パディングされた Unicode 文字列。

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


補間。'Gradient Type' = 'Solid' (GradientMode = 0) の場合、滑らかさを決定します。

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


グラデーションの補間方法を取得または設定します。

**Returns:**
long
### getKey() {#getKey--}
```
public final int getKey()
```


レイヤーリソースキーを取得します。

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


レイヤーリソースの長さ（バイト単位）を取得します。

**Returns:**
int
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat.Rgba64Bpp フォーマットの最大色。色は ARGB チャネルを持ち、各チャネルは 16 ビットです。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat.Rgba64Bpp フォーマットの最小色。色は ARGB チャネルを持ち、各チャネルは 16 ビットです。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


プレフィックスの長さを取得します。8BIM リソースの場合はデフォルト値が 12、8B64 の場合は 16 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| psdVersion | int | PSD バージョン。 |

**Returns:**
int - プレフィックスの長さ。
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


このリソースに必要な最小 PSD バージョンを取得します。補間方法が明示的に保存されている場合、バージョン 3 が必要です。

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


勾配が反転しています。

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


ノイズグラデーションの色を生成するために使用される乱数シード。

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


粗さ係数。'Gradient type' = 'Noise' の場合、'Roughness' (0 - 2048) を割り当てることができます。

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


透明度表示フラグ。'Gradient type' = 'Noise' の場合、'Add transparency' を true に設定できます。

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


レイヤーリソースのシグネチャを取得します。

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


透過点を取得または設定します。

値: 透過点です。

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


ベクトルカラーを使用するフラグ。

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


勾配の長さを初期化します。GradientLength は読み取り専用のため、一度だけ割り当て可能です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short | 値です。 |

### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


リソースが PSB 固有かどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | int | リソースキーです。 |

**Returns:**
boolean - リソースが PSB 固有の場合は true、そうでない場合は false。
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


このインスタンスがリソース PSB 固有かどうかを示す値を取得します。

値: このインスタンスがリソース PSB 固有の場合は true、そうでない場合は false。

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


リソースデータを指定されたストリームコンテナに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psdVersion | int | PSD バージョン。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


カスタムリソースヘッダーを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| 署名 | int | シグネチャです。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


ヘッダーのシグネチャ、識別子、長さを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| 署名 | int | シグネチャです。 |
| isLengthLong | boolean | true に設定すると、長さは長くなります。 |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


カラーモデル。'Gradient type' = 'Noise' の場合、'Color Model' を RGB/SHB/LAB (3/4/6) に割り当てることができます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


カラー点を取得または設定します。

値: カラー点です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


グラデーションがディザリングされているか。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


拡張カウント (Photoshop 6.0 では = 2)。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


このグラデーションのモードは 'Gradient Type' = 'Solid/Noise' (0/1) を決定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


グラデーションの名前: パディングされた Unicode 文字列。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


補間。'Gradient Type' = 'Solid' (GradientMode = 0) の場合、滑らかさを決定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


グラデーションの補間方法を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp フォーマットの最大色。色は ARGB チャネルを持ち、各チャネルは 16 ビットです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp フォーマットの最小色。色は ARGB チャネルを持ち、各チャネルは 16 ビットです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


勾配が反転しています。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


ノイズグラデーションの色を生成するために使用される乱数シード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


粗さ係数。'Gradient type' = 'Noise' の場合、'Roughness' (0 - 2048) を割り当てることができます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


透明度表示フラグ。'Gradient type' = 'Noise' の場合、'Add transparency' を true に設定できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


透過点を取得または設定します。

値: 透過点です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


ベクトルカラーを使用するフラグ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す String を返します。

**Returns:**
java.lang.String - このインスタンスを表す文字列です。
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

