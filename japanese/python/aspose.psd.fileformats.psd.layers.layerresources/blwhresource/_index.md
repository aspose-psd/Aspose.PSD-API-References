---
title: "BlwhResource クラス"
type: docs
weight: 90
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | BlwhResource クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| black_and_white_preset_file_name | string | r/w | 白黒プリセットファイル名を取得または設定します。 |
| ブルー | int | r/w | ブルーの値を取得または設定します。 |
| bw_preset_kind | int | r/w | 白黒プリセット種別の値を取得または設定します。 |
| シアン | int | r/w | シアンの値を取得または設定します。 |
| グリーン | int | r/w | グリーンの値を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| マゼンタ | int | r/w | マゼンタの値を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| レッド | int | r/w | reds の値を取得または設定します。 |
| signature | int | r | 署名を取得します。 |
| tint_color | int | r/w | Tint Color の ARGB 値を取得または設定します。 |
| use_tint | bool | r/w | [tint color] が使用されているかどうかを示す値を取得または設定します。 |
| yellows | int | r/w | yellows の値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

BlwhResource クラスの新しいインスタンスを初期化します。

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

