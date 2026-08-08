---
title: "IPlacedLayerResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD ファイル内の配置レイヤーに関する情報を含む IPlacedLayerResource インターフェイスを定義します。"
type: docs
weight: 17
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

IPlacedLayerResource インターフェイスを定義します。このインターフェイスは PSD ファイル内の配置レイヤーに関する情報を含みます。Adobe\\ufffd Photoshop\\ufffd 画像で PlLd、Sold、Sole リソースを指定するために使用されるマークアップインターフェイスです。Adobe\\ufffd Photoshop\\ufffd 画像でスマートオブジェクトレイヤーをサポートするために使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | 配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。 |
| [getBottom()](#getBottom--) | 配置されたレイヤーのPSD画像における下部位置を取得または設定します。 |
| [getBounds()](#getBounds--) | 配置されたレイヤーのPSDファイルにおける境界を取得または設定します。 |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | 水平メッシュポイントの測定単位を取得または設定します。 |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [getItems()](#getItems--) | ワープ項目を取得または設定します。 |
| [getLeft()](#getLeft--) | 配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。 |
| [getPageNumber()](#getPageNumber--) | 配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。 |
| [getPerspective()](#getPerspective--) | 配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。 |
| [getPerspectiveOther()](#getPerspectiveOther--) | 配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。 |
| [getPlacedLayerType()](#getPlacedLayerType--) | 配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。 |
| [getRight()](#getRight--) | 配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。 |
| [getTop()](#getTop--) | 配置されたレイヤーのPSD画像における上部位置を取得または設定します。 |
| [getTotalPages()](#getTotalPages--) | 配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。 |
| [getTransformMatrix()](#getTransformMatrix--) | 配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。 |
| [getUOrder()](#getUOrder--) | 配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。 |
| [getUniqueId()](#getUniqueId--) | PSD 画像内のスマートオブジェクト配置レイヤーのグローバル一意識別子を取得または設定します。 |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | 配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。 |
| [getValue()](#getValue--) | 配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。 |
| [getVersion()](#getVersion--) | PSD ファイル内の配置レイヤーのバージョンを取得します。通常は 3〜5 です。 |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | 垂直メッシュポイントの測定単位を取得または設定します。 |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [isCustom()](#isCustom--) | このインスタンスのワープ スタイルがカスタムかどうかを示す値を取得または設定します。 |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | 配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。 |
| [setBottom(double value)](#setBottom-double-) | 配置されたレイヤーのPSD画像における下部位置を取得または設定します。 |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | 配置されたレイヤーのPSDファイルにおける境界を取得または設定します。 |
| [setCustom(boolean value)](#setCustom-boolean-) | このインスタンスのワープ スタイルがカスタムかどうかを示す値を取得または設定します。 |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | 水平メッシュポイントの測定単位を取得または設定します。 |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | ワープ項目を取得または設定します。 |
| [setLeft(double value)](#setLeft-double-) | 配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。 |
| [setPerspective(double value)](#setPerspective-double-) | 配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。 |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | 配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。 |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | 配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。 |
| [setRight(double value)](#setRight-double-) | 配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。 |
| [setTop(double value)](#setTop-double-) | 配置されたレイヤーのPSD画像における上部位置を取得または設定します。 |
| [setTotalPages(int value)](#setTotalPages-int-) | 配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。 |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | 配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。 |
| [setUOrder(int value)](#setUOrder-int-) | 配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。 |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | PSD 画像内のスマートオブジェクト配置レイヤーのグローバル一意識別子を取得または設定します。 |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | 配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。 |
| [setValue(double value)](#setValue-double-) | 配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。 |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | 垂直メッシュポイントの測定単位を取得または設定します。 |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | 配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。 |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。

値: 配置されたレイヤーのアンチエイリアス ポリシー。

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


配置されたレイヤーのPSD画像における下部位置を取得または設定します。

値: 配置されたレイヤーの下部位置。

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


配置されたレイヤーのPSDファイルにおける境界を取得または設定します。

値: 配置されたレイヤーの境界。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


水平メッシュポイントの測定単位を取得または設定します。

値: 水平メッシュポイントの測定単位。

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


ワープ項目を取得または設定します。

値: ワープ アイテム。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。

値: 配置されたレイヤーの左側位置。

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。

値: 配置されたレイヤーのページ番号。

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。

値: 配置されたレイヤーの遠近法値。

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。

値: 配置されたレイヤーの他の遠近法値。

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。

値: 配置されたレイヤーのタイプ。

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。

値: 配置されたレイヤーの右側位置。

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


配置されたレイヤーのPSD画像における上部位置を取得または設定します。

値: 配置されたレイヤーの上部位置。

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。

Value: 配置されたレイヤーの総ページ数。

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。

Value: 配置されたレイヤーの変換行列。

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。

Value: 配置されたレイヤーのU順序値。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


PSD 画像内のスマートオブジェクト配置レイヤーのグローバル一意識別子を取得または設定します。

Value: 配置されたレイヤーの一意識別子。

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。

Value: 配置されたレイヤーのV順序値。

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。

Value: 配置されたレイヤーのワープ値。

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


PSD ファイル内の配置レイヤーのバージョンを取得します。通常は 3〜5 です。

値: 配置レイヤーまたはスマートオブジェクトレイヤーのバージョン。

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


垂直メッシュポイントの測定単位を取得または設定します。

Value: 垂直メッシュポイントの測定単位。

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


このインスタンスのワープスタイルがカスタムかどうかを示す値を取得または設定します。true の場合、メッシュポイントが含まれます。false に設定すると、メッシュポイントが消去されます。

値: 配置レイヤーまたはスマートオブジェクトレイヤーリソースにカスタムスタイルがある場合は true、そうでない場合は false。

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


配置されたレイヤーのPSD画像におけるアンチエイリアスポリシーを取得または設定します。

値: 配置されたレイヤーのアンチエイリアス ポリシー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


配置されたレイヤーのPSD画像における下部位置を取得または設定します。

値: 配置されたレイヤーの下部位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


配置されたレイヤーのPSDファイルにおける境界を取得または設定します。

値: 配置されたレイヤーの境界。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


このインスタンスのワープスタイルがカスタムかどうかを示す値を取得または設定します。true の場合、メッシュポイントが含まれます。false に設定すると、メッシュポイントが消去されます。

値: 配置レイヤーまたはスマートオブジェクトレイヤーリソースにカスタムスタイルがある場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


水平メッシュポイントの測定単位を取得または設定します。

値: 水平メッシュポイントの測定単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


ワープ項目を取得または設定します。

値: ワープ アイテム。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


配置されたレイヤーのPSDファイルにおける左位置を取得または設定します。

値: 配置されたレイヤーの左側位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


配置されたレイヤーのPSDファイルにおけるページ番号を取得または設定します。

値: 配置されたレイヤーのページ番号。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


配置されたレイヤーのPSDファイルにおける遠近値を取得または設定します。

値: 配置されたレイヤーの遠近法値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


配置されたレイヤーのPSDファイルにおけるその他の遠近値を取得または設定します。

値: 配置されたレイヤーの他の遠近法値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


配置されたレイヤーのPSDファイルにおけるタイプを取得または設定します。

値: 配置されたレイヤーのタイプ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


配置されたレイヤーのPSDファイルにおける右位置を取得または設定します。

値: 配置されたレイヤーの右側位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


配置されたレイヤーのPSD画像における上部位置を取得または設定します。

値: 配置されたレイヤーの上部位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


配置されたレイヤーのPSDファイルにおける総ページ数を取得または設定します。

Value: 配置されたレイヤーの総ページ数。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


配置されたレイヤーのPSDファイルにおける変換行列を取得または設定します。

Value: 配置されたレイヤーの変換行列。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


配置されたレイヤーのPSDファイルにおけるU順序値を取得または設定します。

Value: 配置されたレイヤーのU順序値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


PSD 画像内のスマートオブジェクト配置レイヤーのグローバル一意識別子を取得または設定します。

Value: 配置されたレイヤーの一意識別子。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


配置されたレイヤーのPSDファイルにおけるV順序値を取得または設定します。

Value: 配置されたレイヤーのV順序値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


配置されたレイヤーのPSD画像におけるワープ値を取得または設定します。

Value: 配置されたレイヤーのワープ値。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


垂直メッシュポイントの測定単位を取得または設定します。

Value: 垂直メッシュポイントの測定単位。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


配置されたレイヤーのPSDファイルにおける水平メッシュポイントを取得または設定します。

値: 配置されたレイヤーの水平メッシュポイント。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double[] |  |

