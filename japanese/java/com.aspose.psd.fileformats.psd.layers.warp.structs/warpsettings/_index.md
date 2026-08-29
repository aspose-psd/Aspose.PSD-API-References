---
title: "WarpSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ワープ付きレイヤーのパラメータ"
type: docs
weight: 12
url: /ja/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

ワープ付きレイヤーのパラメータ
## Constructors

| Constructor | 説明 |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | 新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。 |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | 新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。 |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | 新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。 |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | ProcessingArea のデフォルト値 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | ワープ画像の境界を取得または設定します |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | ワープグリッドのサイズを取得または設定します。 |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | メッシュラインのサイズを取得または設定します。 |
| [getMeshPoints()](#getMeshPoints--) | Photoshop のメッシュポイント |
| [getRenderQuality()](#getRenderQuality--) | ワープレンダー品質の値を取得または設定します - 速度と品質の間で |
| [getRotate()](#getRotate--) | 回転値を取得または設定します |
| [getStyle()](#getStyle--) | ワープのスタイルを取得または設定します |
| [getValue()](#getValue--) | ワープの値を取得または設定します |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | MeshPoints のユーザー変更を取得または設定します |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | ワープ画像の境界を取得または設定します |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | ワープグリッドのサイズを取得または設定します。 |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | メッシュラインのサイズを取得または設定します。 |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Photoshop のメッシュポイント |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | リソースベクトルからメッシュポイントを返します |
| [setRenderQuality(int value)](#setRenderQuality-int-) | ワープレンダー品質の値を取得または設定します - 速度と品質の間で |
| [setRotate(int value)](#setRotate-int-) | 回転値を取得または設定します |
| [setStyle(int value)](#setStyle-int-) | ワープのスタイルを取得または設定します |
| [setValue(double value)](#setValue-double-) | ワープの値を取得または設定します |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | このワープパラメータを PlacedResource に保存します |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | このワープパラメータを PlacedResource に保存します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | ワープのメッシュポイント |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | ワープ画像の境界 |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | ワープのメッシュポイント |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | ワープ画像の境界 |
| style | int | ワープのスタイル |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | ワープ設定を持つ PS アイテム |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | ワープ画像の境界 |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


新しい [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | ワープ設定を持つリソース |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


ProcessingArea のデフォルト値

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


ワープ画像の境界を取得または設定します

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


ワープグリッドのサイズを取得または設定します。デフォルトは 1 です。

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


メッシュラインのサイズを取得または設定します。GridSize はクライアントが選択できる PS の定義です。各 GridSize には 4 本の Mesh Line があります。GridSize の数が 1 より大きい場合、最初の Grid の最後の Mesh Line と 2 番目の Grid の最初の Mesh Line は同じ Mesh Line になります。

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Photoshop のメッシュポイント

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


ワープレンダー品質の値を取得または設定します - 速度と品質の間で

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


回転値を取得または設定します

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


ワープのスタイルを取得または設定します

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


ワープの値を取得または設定します

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


MeshPoints のユーザー変更を取得または設定します

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


ワープ画像の境界を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


ワープグリッドのサイズを取得または設定します。デフォルトは 1 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


メッシュラインのサイズを取得または設定します。GridSize はクライアントが選択できる PS の定義です。各 GridSize には 4 本の Mesh Line があります。GridSize の数が 1 より大きい場合、最初の Grid の最後の Mesh Line と 2 番目の Grid の最初の Mesh Line は同じ Mesh Line になります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Photoshop のメッシュポイント

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


リソースベクトルからメッシュポイントを返します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | ワープ設定を持つリソース |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


ワープレンダー品質の値を取得または設定します - 速度と品質の間で

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


回転値を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


ワープのスタイルを取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


ワープの値を取得または設定します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


このワープパラメータを PlacedResource に保存します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | ワープ設定を持つリソース |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - この WarpParams からのワープパラメータを持つリソース
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


このワープパラメータを PlacedResource に保存します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | ワープ設定を持つリソース |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
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

