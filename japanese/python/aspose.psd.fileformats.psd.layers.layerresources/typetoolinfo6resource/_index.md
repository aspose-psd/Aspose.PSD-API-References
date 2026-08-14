---
title: "TypeToolInfo6Resource クラス"
type: docs
weight: 990
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | 新しい [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| bottom | int | r/w | 下部の位置を取得または設定します。 |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | クラス ID を取得または設定します。 |
| class_name | string | r/w | クラス名を取得または設定します。 |
| descriptor_version | int | r/w | ディスクリプタ バージョンを取得または設定します。 |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | 項目を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 左 | int | r/w | 左側の位置を取得または設定します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| 右 | int | r/w | 右側の位置を取得または設定します。 |
| signature | int | r | 署名を取得します。 |
| text_version | short | r/w | テキストバージョンを取得または設定します。 |
| top | int | r/w | 上部の位置を取得または設定します。 |
| transform_matrix | double | r/w | 変換行列を取得または設定します。 |
| version | short | r/w | タイプツールのバージョンを取得または設定します。 |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | クラス ID を取得または設定します。 |
| warp_class_name | string | r/w | ワープクラス名を取得または設定します。 |
| warp_descriptor_version | int | r/w | ワープデスクリプタのバージョンを取得または設定します。 |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | ワープ項目を取得または設定します。 |
| warp_version | short | r/w | ワープバージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

新しい [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | クラス ID。 |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ワープクラス IDです。 |

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

