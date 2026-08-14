---
title: "PatternFillSettings クラス"
type: docs
weight: 130
url: /ja/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | 新しい PatternFillSettings クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | レイヤーと [link with layer] かどうかを示す値を取得または設定します。 |
| 角度 | double | r/w | 角度を取得または設定します。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 色を取得または設定します。 |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 塗りつぶしタイプ |
| horizontal_offset | int | r/w | 水平オフセットを取得または設定します。 |
| linked | bool | r/w | この [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) がリンクされているかどうかを示す値を取得または設定します。 |
| pattern_data | int | r/w | パターンデータを取得または設定します。 |
| pattern_height | int | r/w | パターンの高さを取得または設定します。 |
| pattern_id | string | r/w | パターンの識別子を取得または設定します。 |
| pattern_name | string | r/w | パターンの名前を取得または設定します。 |
| pattern_width | int | r/w | パターンの幅を取得または設定します。 |
| point_type | string | r/w | ポイントの種類を取得または設定します。 |
| scale | double | r/w | スケールを取得または設定します。 |
| vertical_offset | int | r/w | 垂直オフセットを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | LFX2 リソースノードを生成します。 |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

新しい PatternFillSettings クラスのインスタンスを初期化します。

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

LFX2 リソースノードを生成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point_type | string | ポイントの種類。 |
| color | [Color](/psd/python-net/aspose.psd/color) | 色。 |
| pattern_name | string | パターンの名前。 |
| 識別子 | string | 識別子。 |
| scale | double | スケール。 |
| リンク | bool | 設定が <c>true</c> の場合、[linked]。 |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | オフセット。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) のリスト |


