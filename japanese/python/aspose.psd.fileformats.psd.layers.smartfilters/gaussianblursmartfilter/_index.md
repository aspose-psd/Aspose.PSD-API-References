---
title: "GaussianBlurSmartFilter クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---

**Summary:** The GaussianBlur smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.GaussianBlurSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter__1) |  [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | 現在のスマートフィルタの識別子です。 |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | ブレンドモードを取得または設定します。 |
| filter_id | int | r | スマートフィルタタイプの識別子を取得します。 |
| is_enabled | bool | r/w | スマートフィルタの有効状態を取得または設定します。 |
| name | string | r | スマートフィルタの名前を取得します。 |
| opacity | double | r/w | スマートフィルタの不透明度の値を取得または設定します。 |
| 半径 | double | r/w | ガウススマートフィルタの半径を取得または設定します。 |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | スマートフィルタデータを含むソース記述子構造体です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | 入力の [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 画像に現在のフィルタを適用します。 |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | 入力の [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) マスクデータに現在のフィルタを適用します。 |
| [clone()](#clone__3) | 現在のインスタンスのメンバ単位のクローンを作成します。 |


### Constructor: GaussianBlurSmartFilter() {#GaussianBlurSmartFilter__1}


```
 GaussianBlurSmartFilter() 
```

 [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/) クラスの新しいインスタンスを初期化します。

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

入力の [RasterImage](/psd/python-net/aspose.psd/rasterimage/) 画像に現在のフィルタを適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | AiFinalizeSection Class |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

入力の [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) マスクデータに現在のフィルタを適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | マスクデータを含むレイヤーです。 |

### Method: clone() {#clone__3}


```
 clone() 
```

現在のインスタンスのメンバ単位のクローンを作成します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | 現在のインスタンスのメンバ単位のクローンを返します。 |


