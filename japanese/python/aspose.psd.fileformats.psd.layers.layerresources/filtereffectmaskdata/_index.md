---
title: "FilterEffectMaskData クラス"
type: docs
weight: 310
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | 新しい [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | チャンネルを取得します。 |
| guid | string | r | GUID を取得します。 |
| 長さを取得または設定します。 | int | r | フィルタマスクデータの長さ（バイト単位）を取得します。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | シートマスクの矩形を取得します。 |
| max_channels | int | r | チャンネル数の最大値を取得します。 |
| pixels_depth | int | r | ピクセルの深度を取得します。 |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | チャンネルの矩形を取得します。 |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | シートマスクを取得します。 |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | ユーザーマスクを取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

新しい [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| guid | string | リソース GUID です。 |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | チャンネルの矩形です。 |
| pixels_depth | int | ピクセルの深度です。 |
| max_channels | int | 最大チャンネル数の値です。 |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | チャンネルです。 |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | ユーザーマスク。 |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | シートマスク矩形。 |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | シートマスク。 |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |

