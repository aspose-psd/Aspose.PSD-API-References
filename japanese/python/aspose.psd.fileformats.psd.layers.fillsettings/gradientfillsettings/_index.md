---
title: "GradientFillSettings クラス"
type: docs
weight: 50
url: /ja/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | 新しいインスタンスを初期化します [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) クラス。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | [レイヤーに合わせる]かどうかを示す値を取得または設定します。 |
| 角度 | double | r/w | 角度を取得または設定します。 |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | 色を取得または設定します。 |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | カラー ポイントを取得または設定します。 |
| dither | bool | r/w | この [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) がディザリングかどうかを示す値を取得または設定します。 |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | 塗りの種類です。 |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | このグラデーションのモードを取得します。<br/>            'Gradient Type' = 'Solid/Noise' (0/1) を決定します。 |
| gradient_name | string | r/w | グラデーションの名前を取得または設定します。 |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | グラデーションのタイプを取得または設定します。 |
| horizontal_offset | double | r/w | 水平方向のオフセット（パーセンテージ）を取得または設定します。 |
| 補間 | short | r/w | 補間。'Gradient Type' が 'Solid' のとき、滑らかさを決定します。値の範囲: 0-4096。 |
| reverse | bool | r/w | この [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) が逆方向かどうかを示す値を取得または設定します。 |
| scale | int | r/w | スケールを取得または設定します。 |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | 透明度ポイントを取得または設定します。 |
| vertical_offset | double | r/w | 垂直方向のオフセット（パーセンテージ）を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | カラーポイントを追加します。 |
| [add_transparency_point()](#add_transparency_point__2) | カラーポイントを追加します。 |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | LFX2 リソースノードを生成します。 |
| [remove_color_point(point)](#remove_color_point_point_4) | カラーポイントを削除します。 |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | 透明度ポイントを削除します。 |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

新しいインスタンスを初期化します [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) クラス。

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

カラーポイントを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | 作成されたカラーポイント |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

カラーポイントを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | 作成された透明度ポイント |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

LFX2 リソースノードを生成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | 生成された [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) のリスト |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

カラーポイントを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | ポイントです。 |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

透明度ポイントを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | ポイントです。 |

