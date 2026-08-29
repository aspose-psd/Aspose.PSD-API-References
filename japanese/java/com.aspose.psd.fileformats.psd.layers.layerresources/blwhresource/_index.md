---
title: "BlwhResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "BlwhResource クラスは白黒調整レイヤーのリソースです。"
type: docs
weight: 15
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

BlwhResource クラスは白黒調整レイヤーのリソースです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
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
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | 黒白プリセットのファイル名を取得または設定します。 |
| [getBlues()](#getBlues--) | 青の値を取得または設定します。 |
| [getBwPresetKind()](#getBwPresetKind--) | 黒白プリセットの種類の値を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | シアンの値を取得または設定します。 |
| [getData()](#getData--) | データを取得または設定します。 |
| [getGreens()](#getGreens--) | 緑の値を取得または設定します。 |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getLength()](#getLength--) | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [getMagentas()](#getMagentas--) | マゼンタの値を取得または設定します。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | レイヤーリソースに必要な最小の psd バージョンを取得します。 |
| [getReds()](#getReds--) | 赤の値を取得または設定します。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getTintColor()](#getTintColor--) | ARGB のティントカラーを取得します。 |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | 青のティントカラーの倍精度値を取得または設定します。 |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | 緑のティントカラーの倍精度値を取得または設定します。 |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | 赤のティントカラーの倍精度値を取得または設定します。 |
| [getUseTint()](#getUseTint--) | 使用されているかどうかを示す値を取得または設定します。[tint color] |
| [getYellows()](#getYellows--) | 黄の値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | リソースを指定されたストリームコンテナに保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | 黒白プリセットのファイル名を取得または設定します。 |
| [setBlues(int value)](#setBlues-int-) | 青の値を取得または設定します。 |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | 黒白プリセットの種類の値を取得または設定します。 |
| [setCyans(int value)](#setCyans-int-) | シアンの値を取得または設定します。 |
| [setGreens(int value)](#setGreens-int-) | 緑の値を取得または設定します。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [setMagentas(int value)](#setMagentas-int-) | マゼンタの値を取得または設定します。 |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 型構造でプロパティ値を設定します。 |
| [setReds(int value)](#setReds-int-) | 赤の値を取得または設定します。 |
| [setTintColor(int value)](#setTintColor-int-) | ティントカラーを設定します。 |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | 青のティントカラーの倍精度値を取得または設定します。 |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | 緑のティントカラーの倍精度値を取得または設定します。 |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | 赤のティントカラーの倍精度値を取得または設定します。 |
| [setUseTint(boolean value)](#setUseTint-boolean-) | 使用されているかどうかを示す値を取得または設定します。[tint color] |
| [setYellows(int value)](#setYellows-int-) | 黄の値を取得または設定します。 |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


[BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) クラスの新しいインスタンスを初期化します。

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


黒白プリセットのファイル名を取得または設定します。

値: 黒白プリセットのファイル名。

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


青の値を取得または設定します。

値: 青の値。

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


黒白プリセットの種類の値を取得または設定します。

値: 黒白プリセットの種類の値。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


シアンの値を取得または設定します。

値: シアンの値。

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


データを取得または設定します。

値: データ。

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


緑の値を取得または設定します。

値: 緑の値。

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


マゼンタの値を取得または設定します。

値: マゼンタの値。

**Returns:**
int
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


レイヤーリソースに必要な最小の psd バージョンを取得します。0 は制限がないことを示します。

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


赤の値を取得または設定します。

値: 赤の値。

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


レイヤーリソースのシグネチャを取得します。

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


ARGB のティントカラーを取得します。

**Returns:**
int - ARGB のティントカラー。
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


青のティントカラーの倍精度値を取得または設定します。

値: 青のティントカラーの double 値です。

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


緑のティントカラーの倍精度値を取得または設定します。

値: 緑のティントカラーの double 値です。

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


赤のティントカラーの倍精度値を取得または設定します。

値: 赤のティントカラーの double 値です。

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


使用されているかどうかを示す値を取得または設定します。[tint color]

値: 使用された場合は [tint color]、それ以外は false です。

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


黄の値を取得または設定します。

値: 黄色の値です。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


リソースを指定されたストリームコンテナに保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
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

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


黒白プリセットのファイル名を取得または設定します。

値: 黒白プリセットのファイル名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


青の値を取得または設定します。

値: 青の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


黒白プリセットの種類の値を取得または設定します。

値: 黒白プリセットの種類の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


シアンの値を取得または設定します。

値: シアンの値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


緑の値を取得または設定します。

値: 緑の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


マゼンタの値を取得または設定します。

値: マゼンタの値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


型構造でプロパティ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 構造体。 |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


赤の値を取得または設定します。

値: 赤の値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


ティントカラーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 値です。 |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


青のティントカラーの倍精度値を取得または設定します。

値: 青のティントカラーの double 値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


緑のティントカラーの倍精度値を取得または設定します。

値: 緑のティントカラーの double 値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


赤のティントカラーの倍精度値を取得または設定します。

値: 赤のティントカラーの double 値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


使用されているかどうかを示す値を取得または設定します。[tint color]

値: 使用された場合は [tint color]、それ以外は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


黄の値を取得または設定します。

値: 黄色の値です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

