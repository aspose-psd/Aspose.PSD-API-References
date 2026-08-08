---
title: "WarpSettings"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "ワープ付きレイヤーのパラメータ"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.psd.layers.warp/warpsettings/
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
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | 新しいインスタンスを初期化します [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) クラス。 |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | 新しいインスタンスを初期化します [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) クラス。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DefaultProcessingArea_internalized](#DefaultProcessingArea-internalized) | ProcessingArea のデフォルト値 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | ワープ画像の境界を取得または設定します |
| [getClass()](#getClass--) |  |
| [getMeshPoints()](#getMeshPoints--) | Photoshop のメッシュポイント |
| [getProcessingArea()](#getProcessingArea--) | 処理領域サイズの値を取得または設定します。 |
| [getRotate()](#getRotate--) | 回転値を取得または設定します |
| [getStyle()](#getStyle--) | ワープのスタイルを取得または設定します |
| [getValue()](#getValue--) | ワープの値を取得または設定します |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | MeshPoints のユーザー変更を取得または設定します |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | ワープ画像の境界を取得または設定します |
| [setMeshPoints(Point[] value)](#setMeshPoints-com.aspose.psd.Point---) | Photoshop のメッシュポイント |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | リソースベクトルからメッシュポイントを返します |
| [setProcessingArea(int value)](#setProcessingArea-int-) | 処理領域サイズの値を取得または設定します。 |
| [setRotate(int value)](#setRotate-int-) | 回転値を取得または設定します |
| [setStyle(int value)](#setStyle-int-) | ワープのスタイルを取得または設定します |
| [setValue(double value)](#setValue-double-) | ワープの値を取得または設定します |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | このワープパラメータを PlacedResource に保存します |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | このワープパラメータを PlacedResource に保存します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


新しいインスタンスを初期化します [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | ワープ設定を持つ PS アイテム |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | ワープ画像の境界 |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


新しいインスタンスを初期化します [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp/warpsettings) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | ワープ設定を持つリソース |

### DefaultProcessingArea_internalized {#DefaultProcessingArea-internalized}
```
public static final int DefaultProcessingArea_internalized
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
### getMeshPoints() {#getMeshPoints--}
```
public final Point[] getMeshPoints()
```


Photoshop のメッシュポイント

**Returns:**
com.aspose.psd.Point[]
### getProcessingArea() {#getProcessingArea--}
```
public final int getProcessingArea()
```


処理領域サイズの値を取得または設定します。デフォルト値は 10 です。範囲は [2;40] です

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

### setMeshPoints(Point[] value) {#setMeshPoints-com.aspose.psd.Point---}
```
public final void setMeshPoints(Point[] value)
```


Photoshop のメッシュポイント

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) |  |

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
### setProcessingArea(int value) {#setProcessingArea-int-}
```
public final void setProcessingArea(int value)
```


処理領域サイズの値を取得または設定します。デフォルト値は 10 です。範囲は [2;40] です

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

