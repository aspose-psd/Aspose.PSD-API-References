---
title: "PlLdResource クラス"
type: docs
weight: 820
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| anti_alias_policy | int | r/w | PSD 画像内の配置レイヤーのアンチエイリアスポリシーを取得または設定します。 |
| bottom | double | r/w | PSD 画像内の配置レイヤーの下部位置を取得または設定します。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD ファイル内の配置レイヤーの境界を取得または設定します。 |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 水平メッシュポイントの測定単位を取得または設定します。 |
| horizontal_mesh_points | double | r/w | PSD ファイル内の配置レイヤーの水平メッシュポイントを取得または設定します。 |
| is_custom | bool | r/w | このインスタンスのワープスタイルがカスタムかどうかを示す値を取得または設定します。<br/>            true の場合、メッシュポイントが含まれます。false に設定すると、メッシュポイントが消去されます。 |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | ワープ項目を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 左 | double | r/w | PSD ファイル内の配置レイヤーの左位置を取得または設定します。 |
| 長さを取得または設定します。 | int | r | PlLd リソースの長さ（バイト単位）を取得します。 |
| page_number | int | r/w | PSD ファイル内の配置レイヤーのページ番号を取得または設定します。 |
| perspective | double | r/w | PSD ファイル内の配置レイヤーの遠近値を取得または設定します。 |
| perspective_other | double | r/w | PSD ファイル内の配置レイヤーのその他の遠近値を取得または設定します。 |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD ファイル内の配置レイヤーのタイプを取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| 右 | double | r/w | PSD ファイル内の配置レイヤーの右位置を取得または設定します。 |
| signature | int | r | 署名を取得します。 |
| top | double | r/w | PSD 画像内の配置レイヤーの上位置を取得または設定します。 |
| total_pages | int | r/w | PSD ファイル内の配置レイヤーの総ページ数を取得または設定します。 |
| transform_matrix | double | r/w | PSD ファイル内の配置レイヤーの変換行列を取得または設定します。 |
| u_order | int | r/w | PSD ファイル内の配置レイヤーの U 順序値を取得または設定します。 |
| unique_id | Guid | r/w | PSD 画像内の配置レイヤーのグローバル一意識別子を取得または設定します。 |
| v_order | int | r/w | PSD ファイル内の配置レイヤーの V 順序値を取得または設定します。 |
| 値 | double | r/w | PSD 画像内の配置レイヤーのワープ値を取得または設定します。 |
| version | int | r | PSD ファイル内の配置レイヤーのバージョンを取得します（通常は 3）。 |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 垂直メッシュポイントの測定単位を取得または設定します。 |
| vertical_mesh_points | double | r/w | PSD ファイル内の配置レイヤーの水平メッシュポイントを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 指定されたストリーム コンテナに PlLD リソースを保存します。 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

指定されたストリーム コンテナに PlLD リソースを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

