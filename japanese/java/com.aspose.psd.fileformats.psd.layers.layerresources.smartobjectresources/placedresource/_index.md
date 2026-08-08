---
title: "PlacedResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD ファイル内の配置レイヤーまたはスマートオブジェクトレイヤーに関する共通情報を含む PlacedResource クラスを定義します。"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public abstract class PlacedResource extends LayerResource implements IPlacedLayerResource
```

PlacedResource クラスは、PSD ファイル内の配置レイヤーまたはスマートオブジェクトレイヤーに関する共通情報を含むことを定義します。Adobe\ufffd Photoshop\ufffd 画像でスマートオブジェクトレイヤーをサポートするために使用されます。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CustomEnvelopeWarpKey_internalized](#CustomEnvelopeWarpKey-internalized) | カスタムエンベロープワープ名 |
| [DefaultWarpCladIdClassName_internalized](#DefaultWarpCladIdClassName-internalized) | デフォルトワープクラス名 |
| [EmptyClassName_internalized](#EmptyClassName-internalized) | デフォルトワープクラス名 |
| [ExpectedWarpDescriptorVersion_internalized](#ExpectedWarpDescriptorVersion-internalized) | 期待されるワープディスクリプタバージョン |
| [ExpectedWarpVersion_internalized](#ExpectedWarpVersion-internalized) | 期待されるワープバージョン |
| [HorizontalIdName_internalized](#HorizontalIdName-internalized) | 水平識別子名 |
| [MeshPointsKeyName_internalized](#MeshPointsKeyName-internalized) | メッシュポイントキー名 |
| [OrientationIdName_internalized](#OrientationIdName-internalized) | 方向識別子名 |
| [PlacedVersionValue_internalized](#PlacedVersionValue-internalized) | 期待されるバージョン値 |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB ヘッダー バージョン |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 固有のリソース署名。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD ヘッダー バージョン |
| [RationalPointClassIdName_internalized](#RationalPointClassIdName-internalized) | 有理点クラス識別子名 |
| [ResourceSignature](#ResourceSignature) | 共通リソース署名。 |
| [SizeOfDouble_internalized](#SizeOfDouble-internalized) | double のサイズ |
| [SizeOfInt_internalized](#SizeOfInt-internalized) | int のサイズ |
| [TransformValueCount_internalized](#TransformValueCount-internalized) | 変換値カウント |
| [UOrderKey_internalized](#UOrderKey-internalized) | u 次元キー |
| [VOrderKey_internalized](#VOrderKey-internalized) | v 次元キー |
| [VerticalIdName_internalized](#VerticalIdName-internalized) | 垂直識別子名 |
| [WarpCustomName_internalized](#WarpCustomName-internalized) | ワープカスタム名 |
| [WarpHeaderLength_internalized](#WarpHeaderLength-internalized) | ワープヘッダー長. |
| [WarpKey_internalized](#WarpKey-internalized) | ワープキー. |
| [WarpNoneName_internalized](#WarpNoneName-internalized) | ワープなし名 |
| [WarpPerspectiveKey_internalized](#WarpPerspectiveKey-internalized) | ワープパースペクティブキー |
| [WarpPerspectiveOtherKey_internalized](#WarpPerspectiveOtherKey-internalized) | ワープパースペクティブその他 |
| [WarpRotateKey_internalized](#WarpRotateKey-internalized) | ワープ回転キー |
| [WarpStyleKey_internalized](#WarpStyleKey-internalized) | ワープスタイルキー |
| [WarpValueKey_internalized](#WarpValueKey-internalized) | ワープ値キー |
| [ZeroChar_internalized](#ZeroChar-internalized) | ゼロ文字. |
| [ventureLicense_internalized](#ventureLicense-internalized) | ベンチャー ライセンス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [assert_internalized(Object actualValue, Object expectedValue, String message)](#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-) | 指定された実際の値が期待値と等しいことをアサートします。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | リソースが PSB 固有かどうかをチェックし、設定します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | 配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。 |
| [getBottom()](#getBottom--) | 配置されたレイヤーのPSD画像における下部位置を取得または設定します。 |
| [getBounds()](#getBounds--) | 配置されたレイヤーのPSDファイルにおける境界を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getDefaultUnitType_internalized()](#getDefaultUnitType-internalized--) | Left、Top、Right、Bottom、TransformMatrix などの割り当て値のデフォルト単位タイプを取得または設定します。 |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 水平メッシュポイントの測定単位を取得または設定します。 |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [getItems()](#getItems--) | ワープ項目を取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getLeft()](#getLeft--) | 配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。 |
| [getLength()](#getLength--) | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [getPageNumber()](#getPageNumber--) | 配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。 |
| [getPerspective()](#getPerspective--) | 配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。 |
| [getPerspectiveOther()](#getPerspectiveOther--) | 配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。 |
| [getPlacedLayerType()](#getPlacedLayerType--) | 配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | レイヤーリソースに必要な最小の psd バージョンを取得します。 |
| [getRight()](#getRight--) | 配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getTop()](#getTop--) | 配置されたレイヤーのPSD画像における上部位置を取得または設定します。 |
| [getTotalPages()](#getTotalPages--) | 配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。 |
| [getTransformMatrix()](#getTransformMatrix--) | 配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。 |
| [getUOrder()](#getUOrder--) | 配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。 |
| [getUniqueId()](#getUniqueId--) | 配置されたレイヤーのPSD画像におけるグローバル一意識別子を取得または設定します。 |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | 配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。 |
| [getValue()](#getValue--) | 配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。 |
| [getVersion()](#getVersion--) | 配置されたレイヤーのPSDファイルのバージョンを取得します（通常は3）。 |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 垂直メッシュポイントの測定単位を取得または設定します。 |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [getWarpClassID_internalized()](#getWarpClassID-internalized--) | クラスIDを取得または設定します。 |
| [getWarpClassName_internalized()](#getWarpClassName-internalized--) | ワープクラス名を取得または設定します。 |
| [getWarpDescriptorVersion_internalized()](#getWarpDescriptorVersion-internalized--) | ワープ ディスクリプタ バージョンを取得または設定します。 |
| [getWarpItems_internalized()](#getWarpItems-internalized--) | ワープ項目を取得または設定します。 |
| [getWarpVersion_internalized()](#getWarpVersion-internalized--) | ワープ バージョンを取得または設定します。 |
| [get_Item(String index)](#get-Item-java.lang.String-) | 指定されたインデックスの [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) を取得します。 |
| [hasBoundsUnits_internalized()](#hasBoundsUnits-internalized--) | このインスタンスが境界単位を持つかどうかを示す値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [initProreties_internalized(PlaceResourceParams plLdResourceParams)](#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-) |  |
| [isCustom()](#isCustom--) | このインスタンスのワープ スタイルがカスタムかどうかを示す値を取得または設定します。 |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [isRotateOrientationHorizontal_internalized()](#isRotateOrientationHorizontal-internalized--) | このインスタンスの回転方向が水平かどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | リソースを指定されたストリームコンテナに保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | 配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。 |
| [setBottom(double value)](#setBottom-double-) | 配置されたレイヤーのPSD画像における下部位置を取得または設定します。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 配置されたレイヤーのPSDファイルにおける境界を取得または設定します。 |
| [setCustom(boolean value)](#setCustom-boolean-) | このインスタンスのワープ スタイルがカスタムかどうかを示す値を取得または設定します。 |
| [setDefaultUnitType_internalized(int value)](#setDefaultUnitType-internalized-int-) | Left、Top、Right、Bottom、TransformMatrix などの割り当て値のデフォルト単位タイプを取得または設定します。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 水平メッシュポイントの測定単位を取得または設定します。 |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | ワープ項目を取得または設定します。 |
| [setLeft(double value)](#setLeft-double-) | 配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。 |
| [setPerspective(double value)](#setPerspective-double-) | 配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。 |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | 配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。 |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | 配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。 |
| [setRight(double value)](#setRight-double-) | 配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。 |
| [setRotateOrientationHorizontal_internalized(boolean value)](#setRotateOrientationHorizontal-internalized-boolean-) | このインスタンスの回転方向が水平かどうかを示す値を取得または設定します。 |
| [setTop(double value)](#setTop-double-) | 配置されたレイヤーのPSD画像における上部位置を取得または設定します。 |
| [setTotalPages(int value)](#setTotalPages-int-) | 配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。 |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | 配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。 |
| [setUOrder(int value)](#setUOrder-int-) | 配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。 |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | 配置されたレイヤーのPSD画像におけるグローバル一意識別子を取得または設定します。 |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | 配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。 |
| [setValue(double value)](#setValue-double-) | 配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。 |
| [setVersion(int value)](#setVersion-int-) | 配置されたレイヤーのPSDファイルのバージョンを取得します（通常は3）。 |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | 垂直メッシュポイントの測定単位を取得または設定します。 |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [setWarpClassID_internalized(ClassID value)](#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | クラスIDを取得または設定します。 |
| [setWarpClassName_internalized(String value)](#setWarpClassName-internalized-java.lang.String-) | ワープクラス名を取得または設定します。 |
| [setWarpDescriptorVersion_internalized(int value)](#setWarpDescriptorVersion-internalized-int-) | ワープ ディスクリプタ バージョンを取得または設定します。 |
| [setWarpVersion_internalized(int value)](#setWarpVersion-internalized-int-) | ワープ バージョンを取得または設定します。 |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomEnvelopeWarpKey_internalized {#CustomEnvelopeWarpKey-internalized}
```
public static final String CustomEnvelopeWarpKey_internalized
```


カスタムエンベロープワープ名

### DefaultWarpCladIdClassName_internalized {#DefaultWarpCladIdClassName-internalized}
```
public static final String DefaultWarpCladIdClassName_internalized
```


デフォルトワープクラス名

### EmptyClassName_internalized {#EmptyClassName-internalized}
```
public static final String EmptyClassName_internalized
```


デフォルトワープクラス名

### ExpectedWarpDescriptorVersion_internalized {#ExpectedWarpDescriptorVersion-internalized}
```
public static final int ExpectedWarpDescriptorVersion_internalized
```


期待されるワープディスクリプタバージョン

### ExpectedWarpVersion_internalized {#ExpectedWarpVersion-internalized}
```
public static final int ExpectedWarpVersion_internalized
```


期待されるワープバージョン

### HorizontalIdName_internalized {#HorizontalIdName-internalized}
```
public static final String HorizontalIdName_internalized
```


水平識別子名

### MeshPointsKeyName_internalized {#MeshPointsKeyName-internalized}
```
public static final String MeshPointsKeyName_internalized
```


メッシュポイントキー名

### OrientationIdName_internalized {#OrientationIdName-internalized}
```
public static final String OrientationIdName_internalized
```


方向識別子名

### PlacedVersionValue_internalized {#PlacedVersionValue-internalized}
```
public static final int PlacedVersionValue_internalized
```


期待されるバージョン値

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

### RationalPointClassIdName_internalized {#RationalPointClassIdName-internalized}
```
public static final String RationalPointClassIdName_internalized
```


有理点クラス識別子名

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


共通リソース署名。

### SizeOfDouble_internalized {#SizeOfDouble-internalized}
```
public static final int SizeOfDouble_internalized
```


double のサイズ

### SizeOfInt_internalized {#SizeOfInt-internalized}
```
public static final int SizeOfInt_internalized
```


int のサイズ

### TransformValueCount_internalized {#TransformValueCount-internalized}
```
public static final int TransformValueCount_internalized
```


変換値カウント

### UOrderKey_internalized {#UOrderKey-internalized}
```
public static final String UOrderKey_internalized
```


u 次元キー

### VOrderKey_internalized {#VOrderKey-internalized}
```
public static final String VOrderKey_internalized
```


v 次元キー

### VerticalIdName_internalized {#VerticalIdName-internalized}
```
public static final String VerticalIdName_internalized
```


垂直識別子名

### WarpCustomName_internalized {#WarpCustomName-internalized}
```
public static final String WarpCustomName_internalized
```


ワープカスタム名

### WarpHeaderLength_internalized {#WarpHeaderLength-internalized}
```
public static final int WarpHeaderLength_internalized
```


ワープヘッダー長.

### WarpKey_internalized {#WarpKey-internalized}
```
public static final String WarpKey_internalized
```


ワープ キーです。また、デフォルトのワープ クラス名でもあります。

### WarpNoneName_internalized {#WarpNoneName-internalized}
```
public static final String WarpNoneName_internalized
```


ワープなし名

### WarpPerspectiveKey_internalized {#WarpPerspectiveKey-internalized}
```
public static final String WarpPerspectiveKey_internalized
```


ワープパースペクティブキー

### WarpPerspectiveOtherKey_internalized {#WarpPerspectiveOtherKey-internalized}
```
public static final String WarpPerspectiveOtherKey_internalized
```


ワープパースペクティブその他

### WarpRotateKey_internalized {#WarpRotateKey-internalized}
```
public static final String WarpRotateKey_internalized
```


ワープ回転キー

### WarpStyleKey_internalized {#WarpStyleKey-internalized}
```
public static final String WarpStyleKey_internalized
```


ワープスタイルキー

### WarpValueKey_internalized {#WarpValueKey-internalized}
```
public static final String WarpValueKey_internalized
```


ワープ値キー

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


ゼロ文字.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


ベンチャー ライセンス。

### assert_internalized(Object actualValue, Object expectedValue, String message) {#assert-internalized-java.lang.Object-java.lang.Object-java.lang.String-}
```
public static void assert_internalized(Object actualValue, Object expectedValue, String message)
```


指定された実際の値が期待値と等しいことをアサートします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| actualValue | java.lang.Object | 実際の値です。 |
| expectedValue | java.lang.Object | 期待される値です。 |
| メッセージ | java.lang.String | メッセージです。 |

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
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public int getAntiAliasPolicy()
```


配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。

値: 配置されたレイヤーのアンチエイリアス ポリシー。

**Returns:**
int
### getBottom() {#getBottom--}
```
public final double getBottom()
```


配置されたレイヤーのPSD画像における下部位置を取得または設定します。

値: 配置されたレイヤーの下部位置。

**Returns:**
double
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


配置されたレイヤーのPSDファイルにおける境界を取得または設定します。

値: 配置されたレイヤーの境界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultUnitType_internalized() {#getDefaultUnitType-internalized--}
```
public final int getDefaultUnitType_internalized()
```


Left、Top、Right、Bottom、TransformMatrix などの割り当て値のデフォルト単位タイプを取得または設定します。

値: デフォルトの測定単位タイプ。

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
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public final int getHorizontalMeshPointUnit()
```


水平メッシュポイントの測定単位を取得または設定します。

値: 水平メッシュポイントの測定単位。

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public final double[] getHorizontalMeshPoints()
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Returns:**
double[]
### getItems() {#getItems--}
```
public OSTypeStructure[] getItems()
```


ワープ項目を取得または設定します。

値: ワープ アイテム。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


レイヤーリソースキーを取得します。

**Returns:**
int
### getLeft() {#getLeft--}
```
public final double getLeft()
```


配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。

値: 配置されたレイヤーの左側位置。

**Returns:**
double
### getLength() {#getLength--}
```
public abstract int getLength()
```


レイヤーリソースの長さ（バイト単位）を取得します。

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。

値: 配置されたレイヤーのページ番号。

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public final double getPerspective()
```


配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。

値: 配置されたレイヤーの遠近法値。

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public final double getPerspectiveOther()
```


配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。

値: 配置されたレイヤーの他の遠近法値。

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public int getPlacedLayerType()
```


配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。

値: 配置されたレイヤーのタイプ。

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
### getRight() {#getRight--}
```
public final double getRight()
```


配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。

値: 配置されたレイヤーの右側位置。

**Returns:**
double
### getSignature() {#getSignature--}
```
public int getSignature()
```


レイヤーリソースのシグネチャを取得します。

**Returns:**
int
### getTop() {#getTop--}
```
public final double getTop()
```


配置されたレイヤーのPSD画像における上部位置を取得または設定します。

値: 配置されたレイヤーの上部位置。

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。

Value: 配置されたレイヤーの総ページ数。

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public double[] getTransformMatrix()
```


配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。

Value: 配置されたレイヤーの変換行列。

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public final int getUOrder()
```


配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。

Value: 配置されたレイヤーのU順序値。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public UUID getUniqueId()
```


配置されたレイヤーのPSD画像におけるグローバル一意識別子を取得または設定します。

Value: 配置されたレイヤーの一意識別子。

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public final int getVOrder()
```


配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。

Value: 配置されたレイヤーのV順序値。

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。

Value: 配置されたレイヤーのワープ値。

**Returns:**
double
### getVersion() {#getVersion--}
```
public final int getVersion()
```


配置されたレイヤーのPSDファイルのバージョンを取得します（通常は3）。

Value: 配置されたレイヤーのバージョン。

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public final int getVerticalMeshPointUnit()
```


垂直メッシュポイントの測定単位を取得または設定します。

Value: 垂直メッシュポイントの測定単位。

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public final double[] getVerticalMeshPoints()
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Returns:**
double[]
### getWarpClassID_internalized() {#getWarpClassID-internalized--}
```
public final ClassID getWarpClassID_internalized()
```


クラスIDを取得または設定します。

Value: クラスID。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName_internalized() {#getWarpClassName-internalized--}
```
public final String getWarpClassName_internalized()
```


ワープクラス名を取得または設定します。

Value: ワープクラス名。

**Returns:**
java.lang.String
### getWarpDescriptorVersion_internalized() {#getWarpDescriptorVersion-internalized--}
```
public final int getWarpDescriptorVersion_internalized()
```


ワープ ディスクリプタ バージョンを取得または設定します。

Value: ワープ記述子のバージョン。

**Returns:**
int
### getWarpItems_internalized() {#getWarpItems-internalized--}
```
public OSTypeStructure[] getWarpItems_internalized()
```


ワープ項目を取得または設定します。

値: ワープ アイテム。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion_internalized() {#getWarpVersion-internalized--}
```
public final int getWarpVersion_internalized()
```


ワープ バージョンを取得または設定します。

Value: ワープのバージョン。

**Returns:**
int
### get_Item(String index) {#get-Item-java.lang.String-}
```
public final OSTypeStructure get_Item(String index)
```


指定されたインデックスの [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | java.lang.String | キー名。 |

**Returns:**
[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) - The found [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) instance or null.
### hasBoundsUnits_internalized() {#hasBoundsUnits-internalized--}
```
public final boolean hasBoundsUnits_internalized()
```


このインスタンスが境界単位を持つかどうかを示す値を取得します。

Value: このインスタンスにバウンド単位がある場合は true、そうでない場合は false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initProreties_internalized(PlaceResourceParams plLdResourceParams) {#initProreties-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams-}
```
public final void initProreties_internalized(PlaceResourceParams plLdResourceParams)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| plLdResourceParams | com.aspose.internal.fileformats.psd.layers.layerresources.smartobjectresources.PlaceResourceParams |  |

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


このインスタンスのワープスタイルがカスタムかどうかを示す値を取得または設定します。true の場合、メッシュポイントが含まれます。false に設定すると、メッシュポイントが消去されます。

Value: 配置されたレイヤーがカスタムスタイルを持つ場合は true、そうでない場合は false。

**Returns:**
boolean
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
### isRotateOrientationHorizontal_internalized() {#isRotateOrientationHorizontal-internalized--}
```
public final boolean isRotateOrientationHorizontal_internalized()
```


このインスタンスの回転方向が水平かどうかを示す値を取得または設定します。

Value: 回転方向が水平の場合は true、そうでない場合は false。

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
public abstract void save(StreamContainer streamContainer, int psdVersion)
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

### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public void setAntiAliasPolicy(int value)
```


配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。

値: 配置されたレイヤーのアンチエイリアス ポリシー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


配置されたレイヤーのPSD画像における下部位置を取得または設定します。

値: 配置されたレイヤーの下部位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


配置されたレイヤーのPSDファイルにおける境界を取得または設定します。

値: 配置されたレイヤーの境界。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public final void setCustom(boolean value)
```


このインスタンスのワープスタイルがカスタムかどうかを示す値を取得または設定します。true の場合、メッシュポイントが含まれます。false に設定すると、メッシュポイントが消去されます。

Value: 配置されたレイヤーがカスタムスタイルを持つ場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setDefaultUnitType_internalized(int value) {#setDefaultUnitType-internalized-int-}
```
public final void setDefaultUnitType_internalized(int value)
```


Left、Top、Right、Bottom、TransformMatrix などの割り当て値のデフォルト単位タイプを取得または設定します。

値: デフォルトの測定単位タイプ。

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

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public final void setHorizontalMeshPointUnit(int value)
```


水平メッシュポイントの測定単位を取得または設定します。

値: 水平メッシュポイントの測定単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public final void setHorizontalMeshPoints(double[] value)
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public void setItems(OSTypeStructure[] value)
```


ワープ項目を取得または設定します。

値: ワープ アイテム。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。

値: 配置されたレイヤーの左側位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。

値: 配置されたレイヤーのページ番号。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public final void setPerspective(double value)
```


配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。

値: 配置されたレイヤーの遠近法値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public final void setPerspectiveOther(double value)
```


配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。

値: 配置されたレイヤーの他の遠近法値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public void setPlacedLayerType(int value)
```


配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。

値: 配置されたレイヤーのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。

値: 配置されたレイヤーの右側位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setRotateOrientationHorizontal_internalized(boolean value) {#setRotateOrientationHorizontal-internalized-boolean-}
```
public final void setRotateOrientationHorizontal_internalized(boolean value)
```


このインスタンスの回転方向が水平かどうかを示す値を取得または設定します。

Value: 回転方向が水平の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


配置されたレイヤーのPSD画像における上部位置を取得または設定します。

値: 配置されたレイヤーの上部位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public void setTotalPages(int value)
```


配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。

Value: 配置されたレイヤーの総ページ数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public void setTransformMatrix(double[] value)
```


配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。

Value: 配置されたレイヤーの変換行列。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public final void setUOrder(int value)
```


配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。

Value: 配置されたレイヤーのU順序値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public void setUniqueId(UUID value)
```


配置されたレイヤーのPSD画像におけるグローバル一意識別子を取得または設定します。

Value: 配置されたレイヤーの一意識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public final void setVOrder(int value)
```


配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。

Value: 配置されたレイヤーのV順序値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。

Value: 配置されたレイヤーのワープ値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


配置されたレイヤーのPSDファイルのバージョンを取得します（通常は3）。

Value: 配置されたレイヤーのバージョン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public final void setVerticalMeshPointUnit(int value)
```


垂直メッシュポイントの測定単位を取得または設定します。

Value: 垂直メッシュポイントの測定単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public final void setVerticalMeshPoints(double[] value)
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setWarpClassID_internalized(ClassID value) {#setWarpClassID-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID_internalized(ClassID value)
```


クラスIDを取得または設定します。

Value: クラスID。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName_internalized(String value) {#setWarpClassName-internalized-java.lang.String-}
```
public final void setWarpClassName_internalized(String value)
```


ワープクラス名を取得または設定します。

Value: ワープクラス名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setWarpDescriptorVersion_internalized(int value) {#setWarpDescriptorVersion-internalized-int-}
```
public final void setWarpDescriptorVersion_internalized(int value)
```


ワープ ディスクリプタ バージョンを取得または設定します。

Value: ワープ記述子のバージョン。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWarpVersion_internalized(int value) {#setWarpVersion-internalized-int-}
```
public final void setWarpVersion_internalized(int value)
```


ワープ バージョンを取得または設定します。

Value: ワープのバージョン。

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

