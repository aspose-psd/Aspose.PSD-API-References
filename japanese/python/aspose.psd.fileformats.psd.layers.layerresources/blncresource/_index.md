---
title: "BlncResource クラス"
type: docs
weight: 80
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | 新しい [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| highlights_cyan_red_balance | short | r/w | Highlights Cyan Red Balance を取得または設定します。 |
| highlights_magenta_green_balance | short | r/w | Highlights Magenta Green Balance を取得または設定します。 |
| highlights_yellow_blue_balance | short | r/w | Highlights Yellow Blue Balance を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| midtones_cyan_red_balance | short | r/w | Midtones Cyan Red Balance を取得または設定します。 |
| midtones_magenta_green_balance | short | r/w | Midtones Magenta Green Balance を取得または設定します。 |
| midtones_yellow_blue_balance | short | r/w | Midtones Yellow Blue Balance を取得または設定します。 |
| preserve_luminosity | bool | r/w | この [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) が輝度を保持するかどうかを示す値を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| shadows_cyan_red_balance | short | r/w | Shadows Cyan Red Balance を取得または設定します。 |
| shadows_magenta_green_balance | short | r/w | Shadows Magenta Green Balance を取得または設定します。 |
| shadows_yellow_blue_balance | short | r/w | Shadows Yellow Blue Balance を取得または設定します。 |
| signature | int | r | 署名を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

新しい [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) クラスのインスタンスを初期化します。

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

