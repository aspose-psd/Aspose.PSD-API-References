---
title: "ISmartObjectLayerResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD ファイル内のスマートオブジェクトレイヤーリソースに関する情報を含む ISmartObjectLayerResource インターフェイスを定義します。"
type: docs
weight: 18
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/ismartobjectlayerresource/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.IPlacedLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource)
```
public interface ISmartObjectLayerResource extends IPlacedLayerResource
```

ISmartObjectLayerResource インターフェイスは、PSD ファイル内のスマートオブジェクトレイヤーリソースに関する情報を含みます。また、Adobe\ufffd Photoshop\ufffd 画像の Sold と Sole の両方のリソースを指定するために使用されるマークアップインターフェイスでもあります。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPlacedId()](#getPlacedId--) | PSD 画像内のこのスマートオブジェクトレイヤーデータの一意識別子を取得または設定します。 |
| [setPlacedId(UUID value)](#setPlacedId-java.util.UUID-) | PSD 画像内のこのスマートオブジェクトレイヤーデータの一意識別子を取得または設定します。 |
### getPlacedId() {#getPlacedId--}
```
public abstract UUID getPlacedId()
```


PSD 画像内のこのスマートオブジェクトレイヤーデータの一意識別子を取得または設定します。

Value: このスマートオブジェクトレイヤーリソースの一意の識別子です。

**Returns:**
java.util.UUID
### setPlacedId(UUID value) {#setPlacedId-java.util.UUID-}
```
public abstract void setPlacedId(UUID value)
```


PSD 画像内のこのスマートオブジェクトレイヤーデータの一意識別子を取得または設定します。

Value: このスマートオブジェクトレイヤーリソースの一意の識別子です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

