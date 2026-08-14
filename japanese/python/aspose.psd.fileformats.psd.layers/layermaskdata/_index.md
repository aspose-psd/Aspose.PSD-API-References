---
title: "LayerMaskData クラス"
type: docs
weight: 970
url: /ja/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bottom | int | r/w | 下部のレイヤーマスク位置を取得または設定します。 |
| data_size | int | r | レイヤーマスクデータのサイズを取得します。 |
| default_color | byte | r/w | デフォルトの色を取得または設定します。 |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | レイヤーマスクフラグを取得または設定します。 |
| image_data | byte | r/w | PSDファイル内のレイヤーマスクデータ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| 左 | int | r/w | 左側のレイヤーマスク位置を取得または設定します。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSDファイル内のレイヤーマスクのマスク [Rectangle](/psd/python-net/aspose.psd/rectangle/) を取得または設定します。<br/>            左、右、上、下のプロパティを受け取り、[Rectangle](/psd/python-net/aspose.psd/rectangle/) を作成します。 |
| 右 | int | r/w | 右側のレイヤーマスク位置を取得または設定します。 |
| top | int | r/w | 上部のレイヤーマスク位置を取得または設定します。 |


