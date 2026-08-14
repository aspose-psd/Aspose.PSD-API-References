---
title: "VstkResource クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | VstkResource クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| fill_enabled | bool | r/w | ストロークの塗りが有効かどうかを示す値を取得または設定します。 |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | ストロークの塗り設定を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
| stroke_enabled | bool | r/w | ストローク効果が有効かどうかを示す値を取得または設定します。 |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | ストロークのブレンドモードを取得または設定します。 |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | ストロークエンティティを取得または設定します。このプロパティはストロークの塗り設定を決定します。 |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | ストロークスタイルのライン配置を取得または設定します。 |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | ストロークスタイルのラインキャップのタイプを取得または設定します。 |
| stroke_style_line_cap_width | double | r/w | ストロークのラインキャップ幅を取得または設定します。 |
| stroke_style_line_dash_offset | int | r/w | ストロークスタイルのラインダッシュオフセットを取得または設定します。 |
| stroke_style_line_dash_set | double | r/w | ラインダッシュの配列を取得または設定します。 |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | ストロークスタイルのラインジョインタイプを取得または設定します。 |
| stroke_style_line_width | double | r/w | ストロークのライン幅を取得または設定します。 |
| stroke_style_miter_limit | double | r/w | ストロークスタイルのミータリミットを取得または設定します。 |
| stroke_style_opacity | int | r/w | ストロークスタイルの不透明度 (0-100%) を取得または設定します。 |
| stroke_style_resolution | double | r/w | Strokeスタイルの解像度を取得または設定します。 |
| stroke_style_scale_lock | bool | r/w | Strokeスタイルのスケールロックを取得または設定します。 |
| stroke_style_stroke_adjust | bool | r/w | Stroke調整を取得または設定します。 |
| stroke_style_version | int | r/w | strokeスタイルのバージョンを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

VstkResource クラスの新しいインスタンスを初期化します

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

