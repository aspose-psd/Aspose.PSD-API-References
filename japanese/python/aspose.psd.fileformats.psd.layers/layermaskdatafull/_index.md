---
title: "LayerMaskDataFull クラス"
type: docs
weight: 980
url: /ja/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | LayerMaskDataFull クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| background_color | byte | r/w | 背景色を取得または設定します。 |
| bottom | int | r/w | 下部のレイヤーマスク位置を取得または設定します。 |
| data_size | int | r | レイヤーマスクデータのサイズを取得します。 |
| default_color | byte | r/w | デフォルトの色を取得または設定します。 |
| enclosing_bottom | int | r/w | PSD画像レイヤー内の囲む下部ラスターマスク位置を取得または設定します。 |
| enclosing_left | int | r/w | PSDファイルレイヤー内の囲む左側ラスターマスク位置を取得または設定します。 |
| enclosing_right | int | r/w | PSDファイルレイヤー内の囲む右側ラスターマスク位置を取得または設定します。 |
| enclosing_top | int | r/w | PSD画像レイヤー内のラスターマスクの囲む上部位置を取得または設定します。 |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | レイヤーマスクフラグを取得または設定します。 |
| image_data | byte | r/w | PSDファイル内のレイヤーマスクデータ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| 左 | int | r/w | 左側のレイヤーマスク位置を取得または設定します。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSDファイル内のレイヤーマスクのマスク [Rectangle](/psd/python-net/aspose.psd/rectangle/) を取得または設定します。<br/>            左、右、上、下のプロパティを受け取り、[Rectangle](/psd/python-net/aspose.psd/rectangle/) を作成します。 |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | ユーザー/ラスターマスクに使用されるレイヤーマスクフラグを取得または設定します。ベクターマスクの場合は Flags プロパティが使用されます。 |
| 右 | int | r/w | 右側のレイヤーマスク位置を取得または設定します。 |
| top | int | r/w | 上部のレイヤーマスク位置を取得または設定します。 |
| user_mask_data | byte | r/w | PSD ファイル内のレイヤーのユーザー（ラスタ）マスクデータを取得または設定します。（MaskData プロパティにはラスタライズされたベクターマスクがあります）。 |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD 画像レイヤー内のユーザーマスク（囲む）矩形を取得または設定します。 |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

LayerMaskDataFull クラスの新しいインスタンスを初期化します。

