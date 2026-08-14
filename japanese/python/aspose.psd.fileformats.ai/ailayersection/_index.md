---
title: "AiLayerSection クラス"
type: docs
weight: 50
url: /ja/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 青 | int | r/w | 青色コンポーネントを取得または設定します。 |
| color_index | int | r/w | カラーのインデックスを取得または設定します。<br/>            この引数は –1 から 26 の間の値を取ります。各整数は<br/>            ユーザーがレイヤーを識別するために割り当てられる色を表します。 |
| color_number | int | r/w | カラー番号を取得または設定します。-1 は Red、Green、Blue プロパティからのカスタムカラー値です。<br/>            レイヤーのカラー設定を指定します。 |
| dim_value | int | r/w | ディム値をパーセンテージで取得または設定します。<br/>            レイヤーに含まれるリンク画像およびビットマップ画像の強度を指定されたパーセンテージに減少させます。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| 緑 | int | r/w | 緑色コンポーネントを取得または設定します。 |
| has_multi_layer_masks | bool | r/w | このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。 |
| is_images_dimmed | bool | r/w | このレイヤーが暗くなるかどうかを示す値を取得または設定します。<br/>            レイヤーに含まれるリンク画像およびビットマップ画像の強度を低減します。 |
| is_locked | bool | r/w | このレイヤーがロックされているかどうかを示す値を取得または設定します。<br/>            アイテムへの変更を防止します。 |
| is_preview | bool | r/w | このレイヤーがプレビューかどうかを示す値を取得または設定します。<br/>            レイヤーに含まれるアートワークをアウトラインではなくカラーで表示します。 |
| is_printed | bool | r/w | このレイヤーが印刷されるかどうかを示す値を取得または設定します。<br/>            true の場合、レイヤーに含まれるアートワークを印刷可能にします。 |
| is_shown | bool | r/w | このレイヤーが表示されるかどうかを示す値を取得または設定します。<br/>            true の場合、レイヤーに含まれるすべてのアートワークをアートボード上に表示します。 |
| is_template | bool | r/w | レイヤー名を取得または設定します。<br/>            レイヤーパネルに表示されるアイテムの名前を指定します。 |
| name | string | r/w | ラスタ画像を取得します。 |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | 赤色コンポーネントを取得または設定します。 |
| 赤 | int | r/w | ラスタ画像を追加します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | ラスタ画像。 |
| [get_data()](#get_data__2) | 文字列データを取得します。 |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

ラスタ画像。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | AiFinalizeSection Class |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

文字列データを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | セクションの文字列データ |


