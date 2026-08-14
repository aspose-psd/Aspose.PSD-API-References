---
title: "MultiPageOptions クラス"
type: docs
weight: 70
url: /ja/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | 新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | エクスポート領域を取得または設定します。 |
| merge_layers | bool | r/w | 取得または設定します。値が [merege layers] かどうかを示します。 |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | 取得または設定します。モード。 |
| output_layers_names | string | r/w | 取得または設定します。出力レイヤー名（エクスポート形式がレイヤー名の指定をサポートしている場合に機能します。例: Psd） |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 取得または設定します。ページのラスタライズオプション。 |
| page_titles | string | r/w | 取得または設定します。ページタイトル。 |
| pages | int | r/w | 取得または設定します。ページ。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | 範囲配列からページを初期化します |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | エクスポート領域。 |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| page_titles | string | ページタイトル。 |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| page_titles | string | ページタイトル。 |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | エクスポート領域。 |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pages | int | ページ。 |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| pages | int | ページの配列。 |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | エクスポート領域。 |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | エクスポート領域。 |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | この [IntRange](/psd/python-net/aspose.psd/intrange/)。 |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

新しい [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | この [IntRange](/psd/python-net/aspose.psd/intrange/)。 |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | エクスポート領域。 |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

範囲配列からページを初期化します

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 範囲。 |

