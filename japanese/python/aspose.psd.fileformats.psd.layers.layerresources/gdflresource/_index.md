---
title: "GdFlResource クラス"
type: docs
weight: 330
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | GdFlResource クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| align_with_layer | bool | r/w | [レイヤーに合わせる]かどうかを示す値を取得または設定します。 |
| 角度 | double | r/w | 角度を取得または設定します。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | RGB の色を取得します。 |
| color_model | string | r/w | カラーモデル - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl")。 |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | カラーポイントを取得します。 |
| dither | bool | r/w | この [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) がディザリングかどうかを示す値を取得または設定します。 |
| gradient_interval | double | r/w | グラデーション間隔を取得または設定します。 |
| gradient_mode | string | r/w | このグラデーションのモードです。<br/>            'Gradient Type' を 'Solid/Noise' (= "CstS"/"ClNs") に決定します。 |
| gradient_name | string | r/w | グラデーションの名前を取得または設定します。 |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | グラデーションのタイプを取得または設定します。 |
| horizontal_offset | double | r/w | 水平オフセットを取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat の最大色。 |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | PixelDataFormat の最小色。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| reverse | bool | r/w | この [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) が逆方向かどうかを示す値を取得または設定します。 |
| rnd_number_seed | int | r/w | ノイズグラデーションの色を生成するために使用される乱数シードです。 |
| roughness | int | r/w | 粗さ係数。 |
| scale | int | r/w | スケールを取得または設定します。 |
| show_transparency | bool | r/w | 透明度を表示するフラグ。 |
| signature | int | r | 署名を取得します。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | 透明度ポイントを取得します。 |
| use_vector_color | bool | r/w | ベクトルカラーを使用するフラグ。 |
| vertical_offset | double | r/w | 垂直オフセットを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | リソースを指定されたストリームコンテナに保存します。 |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

GdFlResource クラスの新しいインスタンスを初期化します

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

