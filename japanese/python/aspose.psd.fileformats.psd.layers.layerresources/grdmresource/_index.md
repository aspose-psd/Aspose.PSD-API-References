---
title: "GrdmResource クラス"
type: docs
weight: 340
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| color_model | short | r/w | カラー モデル。<br/>            'Gradient type' = 'Noise' の場合、'Color Model' を RGB/SHB/LAB (3/4/6) に割り当てることができます。 |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | カラー ポイントを取得または設定します。 |
| ディザ | bool | r/w | グラデーションがディザ処理されているかどうか。 |
| expansion_count | short | r/w | 拡張カウント (Photoshop 6.0 では = 2)。 |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | このグラデーションのモード<br/>            'Gradient Type' = 'Solid/Noise' (0/1) を決定します。 |
| gradient_name | string | r/w | グラデーションの名前: Unicode 文字列、パディング済み。 |
| 補間 | short | r/w | 補間。'Gradient Type' = 'Solid' のとき、スムーズさを決定します (GradientMode = 0)。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp フォーマットの最大色。<br/>            色は ARGB チャネルを持ち、各チャネルは 16 ビットです。 |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat.Rgba64Bpp フォーマットの最小色。<br/>            色は ARGB チャネルを持ち、各チャネルは 16 ビットです。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| 逆 | bool | r/w | グラデーションが逆方向かどうか。 |
| rnd_number_seed | int | r/w | ノイズグラデーションの色を生成するために使用される乱数シードです。 |
| roughness | int | r/w | 粗さ係数<br/>            'Gradient type' が 'Noise' の場合、'Roughness' (0 - 2048) を割り当てることができます。 |
| show_transparency | short | r/w | 透明度表示フラグ<br/>            'Gradient type' が 'Noise' の場合、'Add transparency' を true に設定できます。 |
| signature | int | r | 署名を取得します。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | 透明度ポイントを取得または設定します。 |
| use_vector_color | short | r/w | ベクトルカラーを使用するフラグ。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソース データを指定されたストリーム コンテナに保存します。 |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

[GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| psd_version | int | リソースの PSD バージョン。 |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

リソース データを指定されたストリーム コンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

