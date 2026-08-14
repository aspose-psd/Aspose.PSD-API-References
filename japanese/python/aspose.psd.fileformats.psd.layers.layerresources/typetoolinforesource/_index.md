---
title: "TypeToolInfoResource クラス"
type: docs
weight: 1000
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | TypeToolInfoResource クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| a_component | short | r/w | コンポーネントを取得または設定します。 |
| b_component | short | r/w | b コンポーネントを取得または設定します。 |
| character_count | int | r/w | 文字数を取得または設定します。 |
| color_space_value | short | r/w | カラースペースの値を取得または設定します。 |
| font_version | short | r/w | フォントバージョンを取得または設定します。 |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | フォントを取得または設定します。 |
| fonts_count | short | r | フォント数を取得します。 |
| g_component | short | r/w | g コンポーネントを取得または設定します。 |
| horizontal_placement | int | r/w | 水平配置を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| line_count | short | r | 行数を取得します。 |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | 行を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| r_component | short | r/w | r コンポーネントを取得または設定します。 |
| scale_factor | int | r/w | スケールファクターを取得または設定します。 |
| selection_end | int | r/w | 選択終了位置を取得または設定します。 |
| selection_start | int | r/w | 選択開始位置を取得または設定します。 |
| signature | int | r | 署名を取得します。 |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | フォントスタイルを取得または設定します。 |
| styles_count | short | r | スタイル数を取得します。 |
| transform_matrix | double | r/w | 変換行列を取得または設定します。 |
| type_value | short | r/w | タイプ値を取得または設定します。 |
| version | short | r/w | バージョンを取得または設定します。 |
| vertical_placement | int | r/w | 垂直配置を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | 指定されたストリームコンテナを保存します。 |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

TypeToolInfoResource クラスの新しいインスタンスを初期化します

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

指定されたストリームコンテナを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

