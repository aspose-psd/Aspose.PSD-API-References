---
title: "CgEdResource クラス"
type: docs
weight: 130
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | 新しい CgEdResource クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| auto | bool | r/w | この [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) が自動かどうかを示す値を取得または設定します。 |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | int | r/w | 明るさを取得または設定します。 |
| コントラスト | int | r/w | コントラストを取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| lab_color | bool | r/w | [lab color] が使用されているかどうかを示す値を取得または設定します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| mean_value_for_brightness_and_contrast | int | r/w | 明るさとコントラストの平均値を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
| use_legacy | bool | r/w | [use legacy] が使用されているかどうかを示す値を取得または設定します。 |
| version | int | r/w | バージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

新しい CgEdResource クラスのインスタンスを初期化します。

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

