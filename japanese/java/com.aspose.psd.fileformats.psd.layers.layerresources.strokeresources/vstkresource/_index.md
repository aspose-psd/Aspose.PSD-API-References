---
title: "VstkResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "リソースクラス VstkResource です。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

リソースクラス VstkResource。ベクトルストロークデータに関する情報を含みます。リソースは resourcedata の AssignItems メソッドで初期化するか、クラスのプロパティに値を割り当てることで初期化する必要があります。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [VstkResource()](#VstkResource--) | 新しい [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) クラスのインスタンスを初期化します。 |
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
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Vstk リソースからアイテム構造体を割り当てます。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | リソースが PSB 固有かどうかをチェックし、設定します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | ClassID インスタンスを取得または設定します。 |
| [getClassName_internalized()](#getClassName-internalized--) | クラス名を取得または設定します。 |
| [getFillEnabled()](#getFillEnabled--) | ストローク塗りが有効かどうかを示す値を取得または設定します。 |
| [getFillSettings()](#getFillSettings--) | ストロークの塗り設定を取得または設定します。 |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getLength()](#getLength--) | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | レイヤーリソースに必要な最小の psd バージョンを取得します。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getStrokeEnabled()](#getStrokeEnabled--) | ストローク効果が有効かどうかを示す値を取得または設定します。 |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | ストロークのブレンドモードを取得または設定します。 |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | ストロークエンティティを取得または設定します。 |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | ストロークスタイルの線の配置を取得または設定します。 |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | ストロークスタイルのラインキャップのタイプを取得または設定します。 |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | ストロークラインキャップの幅を取得または設定します。 |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | ストロークスタイルのラインダッシュオフセットを取得または設定します。 |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | 線の破線配列を取得または設定します。 |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | ストロークスタイルのラインジョインタイプを取得または設定します。 |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | ストロークライン幅を取得または設定します。 |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | ストロークスタイルのマイターレミットを取得または設定します。 |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | ストロークスタイルの不透明度 (0-100%) を取得または設定します。 |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | ストロークスタイルの解像度を取得または設定します。 |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | Stroke style scale lock を取得または設定します。 |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | Stroke adjust を取得または設定します。 |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | stroke style version を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | リソースを指定されたストリームコンテナに保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | ClassID インスタンスを取得または設定します。 |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | クラス名を取得または設定します。 |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | ストローク塗りが有効かどうかを示す値を取得または設定します。 |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | ストロークの塗り設定を取得または設定します。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | ストローク効果が有効かどうかを示す値を取得または設定します。 |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | ストロークのブレンドモードを取得または設定します。 |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | ストロークエンティティを取得または設定します。 |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | ストロークスタイルの線の配置を取得または設定します。 |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | ストロークスタイルのラインキャップのタイプを取得または設定します。 |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | ストロークラインキャップの幅を取得または設定します。 |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | ストロークスタイルのラインダッシュオフセットを取得または設定します。 |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | 線の破線配列を取得または設定します。 |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | ストロークスタイルのラインジョインタイプを取得または設定します。 |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | ストロークライン幅を取得または設定します。 |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | ストロークスタイルのマイターレミットを取得または設定します。 |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | Stroke stryle opacity (0-100%) を取得または設定します。 |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | ストロークスタイルの解像度を取得または設定します。 |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | Stroke style scale lock を取得または設定します。 |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | Stroke adjust を取得または設定します。 |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | stroke style version を取得または設定します。 |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


新しい [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) クラスのインスタンスを初期化します。

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Vstk リソースからアイテム構造体を割り当てます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | OSTypeStructure インスタンスのリスト。 |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


ClassID インスタンスを取得または設定します。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


クラス名を取得または設定します。

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


ストローク塗りが有効かどうかを示す値を取得または設定します。

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


ストロークの塗り設定を取得または設定します。

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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
### getSignature() {#getSignature--}
```
public int getSignature()
```


レイヤーリソースのシグネチャを取得します。

**Returns:**
int
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


ストローク効果が有効かどうかを示す値を取得または設定します。

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


ストロークのブレンドモードを取得または設定します。

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


Stroke entity を取得または設定します。プロパティはストロークの塗り設定を決定します。

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


ストロークスタイルの線の配置を取得または設定します。

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


ストロークスタイルのラインキャップのタイプを取得または設定します。

値: ストロークスタイルのラインキャップのタイプ。

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


ストロークラインキャップの幅を取得または設定します。

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


ストロークスタイルのラインダッシュオフセットを取得または設定します。

値: ストロークスタイルのラインダッシュオフセット。

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


線の破線配列を取得または設定します。

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


ストロークスタイルのラインジョインタイプを取得または設定します。

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


ストロークライン幅を取得または設定します。

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


ストロークスタイルのマイターレミットを取得または設定します。

値: ストロークスタイルのミータリミット。

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


ストロークスタイルの不透明度 (0-100%) を取得または設定します。

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


ストロークスタイルの解像度を取得または設定します。

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


Stroke style scale lock を取得または設定します。

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


Stroke adjust を取得または設定します。

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


stroke style version を取得または設定します。

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


ClassID インスタンスを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


クラス名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


ストローク塗りが有効かどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


ストロークの塗り設定を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


ストローク効果が有効かどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


ストロークのブレンドモードを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


Stroke entity を取得または設定します。プロパティはストロークの塗り設定を決定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


ストロークスタイルの線の配置を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


ストロークスタイルのラインキャップのタイプを取得または設定します。

値: ストロークスタイルのラインキャップのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


ストロークラインキャップの幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


ストロークスタイルのラインダッシュオフセットを取得または設定します。

値: ストロークスタイルのラインダッシュオフセット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


線の破線配列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


ストロークスタイルのラインジョインタイプを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


ストロークライン幅を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


ストロークスタイルのマイターレミットを取得または設定します。

値: ストロークスタイルのミータリミット。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


Stroke stryle opacity (0-100%) を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


ストロークスタイルの解像度を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


Stroke style scale lock を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


Stroke adjust を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


stroke style version を取得または設定します。

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

