---
title: "SmartObjectResource クラス"
type: docs
weight: 900
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| anti_alias_policy | int | r/w | PSD 画像内のスマートオブジェクトレイヤーデータのアンチエイリアスポリシーを取得または設定します。 |
| bottom | double | r/w | PSD 画像内の配置レイヤーの下部位置を取得または設定します。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | PSD ファイル内の配置レイヤーの境界を取得または設定します。 |
| comp | int | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの comp 値を取得または設定します。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">スマートオブジェクトのレイヤーコンプ</see> |
| comp_id | int | r/w | 現在選択されている子ドキュメントの comp の ID を取得または設定します。選択されていない場合は -1 になります。<br/>            コンポはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe Photoshop ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、このプロパティは PSD ファイル内のスマートオブジェクトレイヤーのレイヤーコンプ選択識別子を取得します。<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">スマートオブジェクトのレイヤーコンプ</see> |
| crop | int | r/w | PSD 画像内のスマートオブジェクトレイヤーデータの crop を取得または設定します。 |
| duration_denominator | int | r/w | duration denominator を取得または設定します。 |
| duration_numerator | int | r/w | duration numerator を取得または設定します。 |
| frame_count | int | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータのフレーム数を取得または設定します。 |
| frame_step_denominator | int | r/w | frame step denominator を取得または設定します。 |
| frame_step_numerator | int | r/w | frame step numerator を取得または設定します。 |
| 高さ | double | r/w | 高さを取得または設定します。 |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 水平メッシュポイントの測定単位を取得または設定します。 |
| horizontal_mesh_points | double | r/w | PSD ファイル内の配置レイヤーの水平メッシュポイントを取得または設定します。 |
| is_custom | bool | r/w | このインスタンスのワープスタイルがカスタムかどうかを示す値を取得または設定します。<br/>            true の場合、メッシュポイントが含まれます。false に設定すると、メッシュポイントが消去されます。 |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの記述子項目を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 左 | double | r/w | PSD ファイル内の配置レイヤーの左位置を取得または設定します。 |
| 長さを取得または設定します。 | int | r | スマートオブジェクトリソースの長さ（バイト単位）を取得します。 |
| non_affine_transform_matrix | double | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの非アフィン変換行列を取得または設定します。 |
| original_comp_id | int | r | 子ドキュメント用に現在選択されている Comp の元の ID を取得します。選択されていない場合は -1 になります。<br/>            このプロパティは PSD ファイル内のスマートオブジェクトレイヤーの元のレイヤー Comp 選択識別子を取得します。<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">スマートオブジェクトのレイヤーコンプ</see> |
| page_number | int | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータのページ番号を取得または設定します。 |
| perspective | double | r/w | PSD ファイル内の配置レイヤーの遠近値を取得または設定します。 |
| perspective_other | double | r/w | PSD ファイル内の配置レイヤーのその他の遠近値を取得または設定します。 |
| placed_id | Guid | r/w | PSD 画像内のこのスマートオブジェクトレイヤーデータの一意の識別子を取得または設定します。 |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータのタイプを取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| resolution | double | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの解像度を取得または設定します。 |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの解像度測定単位を取得または設定します。 |
| 右 | double | r/w | PSD ファイル内の配置レイヤーの右位置を取得または設定します。 |
| signature | int | r | 署名を取得します。 |
| top | double | r/w | PSD 画像内の配置レイヤーの上位置を取得または設定します。 |
| total_pages | int | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの総ページ数を取得または設定します。 |
| transform_matrix | double | r/w | PSD ファイル内のスマートオブジェクトレイヤーデータの変換行列を取得または設定します。 |
| u_order | int | r/w | PSD ファイル内の配置レイヤーの U 順序値を取得または設定します。 |
| unique_id | Guid | r/w | PSD 画像内のスマートオブジェクトレイヤーデータのグローバル一意識別子を取得または設定します [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/)。 |
| v_order | int | r/w | PSD ファイル内の配置レイヤーの V 順序値を取得または設定します。 |
| 値 | double | r/w | PSD 画像内の配置レイヤーのワープ値を取得または設定します。 |
| version | int | r | PSD ファイル内の配置レイヤーのバージョンを取得します（通常は 3）。 |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | 垂直メッシュポイントの測定単位を取得または設定します。 |
| vertical_mesh_points | double | r/w | PSD ファイル内の配置レイヤーの水平メッシュポイントを取得または設定します。 |
| width | double | r/w | 幅を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | スマートオブジェクトリソースを指定されたストリームコンテナに保存します。 |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

スマートオブジェクトリソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

