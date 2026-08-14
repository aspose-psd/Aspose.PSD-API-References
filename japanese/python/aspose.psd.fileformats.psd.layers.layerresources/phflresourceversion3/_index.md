---
title: "PhflResourceVersion3 クラス"
type: docs
weight: 810
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion3

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PhflResourceVersion3()](#PhflResourceVersion3__1) | [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) クラスの新しいインスタンスを初期化します。 |
| [PhflResourceVersion3(data)](#PhflResourceVersion3_data_2) | [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | PSB 固有のリソース署名です。 |
| RESOURCE_SIGNATURE [static] | int | r | 共通のリソース署名です。 |
| TYPE_TOOL_KEY [static] | int | r | タイプツール情報キーです。 |
| color_space | short | r | カラースペースを取得します。 |
| color_x | float | r/w | X の色を取得または設定します。 |
| color_y | float | r/w | Y の色を取得または設定します。 |
| color_z | float | r/w | Z の色を取得または設定します。 |
| density | int | r/w | 密度を取得または設定します。 |
| key | int | r | レイヤーリソースキーを取得します。 |
| 長さを取得または設定します。 | int | r | レイヤーリソースの長さ（バイト単位）を取得します。 |
| preserve_luminosity | bool | r/w | [preserve luminosity] を示す値を取得または設定します。 |
| psd_version | int | r | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限がないことを示します。 |
| signature | int | r | 署名を取得します。 |
| version | short | r | バージョンを取得します。デフォルトは 2 または 3 です |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | 色を取得します。 |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | リソースを指定されたストリームコンテナに保存します。 |
| [set_rgb_color(color)](#set_rgb_color_color_3) | RGB カラーを設定します。 |


### Constructor: PhflResourceVersion3() {#PhflResourceVersion3__1}


```
 PhflResourceVersion3() 
```

[PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) クラスの新しいインスタンスを初期化します。

### Constructor: PhflResourceVersion3(data) {#PhflResourceVersion3_data_2}


```
 PhflResourceVersion3(data) 
```

[PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | リソースのデータです。 |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

色を取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | RGB カラー |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

リソースを指定されたストリームコンテナに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |
| psd_version | int | PSD バージョンです。 |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

RGB カラーを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 色。 |

