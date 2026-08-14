---
title: "PattResourceData クラス"
type: docs
weight: 780
url: /ja/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | PattResourceData クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 高さ | short | r | 高さを取得します。 |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | 画像モードを取得します。 |
| 長さを取得または設定します。 | int | r | パターンの長さを取得します。 |
| name | string | r/w | 名前を取得または設定します。 |
| pattern_data | int | r | パターンデータを取得します。 |
| pattern_id | string | r/w | パターンの識別子を取得または設定します。 |
| version | int | r | バージョンを取得します。 |
| width | short | r | 幅を取得します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | パターンデータを保存します。 |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | パターンを設定します。 |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

PattResourceData クラスの新しいインスタンスを初期化します

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

パターンデータを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

パターンを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pixels | int | ピクセルです。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 境界。 |

