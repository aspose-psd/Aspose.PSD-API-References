---
title: "AiImage クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.psd.fileformats.ai/aiimage/
---

**Summary:** The Adobe Illustrator (AI)  Image.

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiImage

**Inheritance:** IObjectWithBounds, Image

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [AiImage()](#AiImage__1) | AiImage クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| active_page_index | int | r/w | アクティブページのインデックスを取得または設定します。 |
| auto_adjust_palette | bool | r/w | 自動調整パレットかどうかを示す値を取得または設定します。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 背景色の値を取得または設定します。 |
| bits_per_pixel | int | r | 画像のピクセルあたりビット数を取得します。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 画像の境界を取得します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| container | [Image](/psd/python-net/aspose.psd/image) | r | [Image](/psd/python-net/aspose.psd/image/) コンテナを取得します。 |
| data_section | [AiDataSection](/psd/python-net/aspose.psd.fileformats.ai/aidatasection) | r | データ セクションを取得します。 |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | オブジェクトのデータストリームを取得します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | ファイル形式の値を取得します。 |
| finalize_section | [AiFinalizeSection](/psd/python-net/aspose.psd.fileformats.ai/aifinalizesection) | r | ファイナライズ セクションを取得します。 |
| has_background_color | bool | r/w | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| header | [AiHeader](/psd/python-net/aspose.psd.fileformats.ai/aiheader) | r | ヘッダーを取得します。 |
| 高さ | int | r | 画像の高さを取得します。 |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 割り込みモニターを取得または設定します。 |
| is_cached | bool | r | オブジェクトのデータが現在キャッシュされており、データの読み取りが不要であるかどうかを示す値を取得します。 |
| layers | [AiLayerSection[]](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | r | レイヤー セクションを取得します。 |
| page_count | int | r | ページ数です。<br/>            古い AI 形式の画像では常に 0 です。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| setup_section | [AiSetupSection](/psd/python-net/aspose.psd.fileformats.ai/aisetupsection) | r | セットアップ セクションを取得します。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 画像サイズを取得します。 |
| use_palette | bool | r | 画像パレットが使用されているかどうかを示す値を取得します。 |
| version | [AiFormatVersion](/psd/python-net/aspose.psd.fileformats.ai/aiformatversion) | r | Adobe Illustrator 形式のバージョンを取得します。 |
| width | int | r | 画像の幅を取得します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r | XMP メタデータを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_layer(layer)](#add_layer_layer_1) | AI レイヤー セクションを追加します。 |
| cache_data() | データをキャッシュし、基になる [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) から追加のデータ読み込みが行われないことを保証します。 |
| [can_load(file_path)](#can_load_file_path_2) | 指定されたファイルパスから画像をロードできるかどうかを判定します。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_3) | 指定されたファイルパスから画像をロードできるかどうか、オプションで指定されたオープンオプションを使用して判定します。 |
| [can_load(stream)](#can_load_stream_4) | 指定されたストリームから画像をロードできるかどうかを判定します。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_5) | 指定されたストリームから画像をロードできるかどうか、オプションで指定された <paramref name="loadOptions" /> を使用して判定します。 |
| [can_save(options)](#can_save_options_6) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [create(image_options, width, height)](#create_image_options_width_height_7) | 指定された作成オプションを使用して新しい画像を作成します。 |
| [get_default_options(args)](#get_default_options_args_8) | デフォルトのオプションを取得します。 |
| [get_file_format(file_path)](#get_file_format_file_path_9) | ファイル形式を取得します。 |
| [get_file_format(stream)](#get_file_format_stream_10) | ファイル形式を取得します。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_11) | 現在の画像に適合する矩形を取得します。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_12) | 現在の画像に適合する矩形を取得します。 |
| [get_original_options()](#get_original_options__13) | 元のファイル設定に基づくオプションを取得します。<br/>これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。<br/>例えば、1ビット/ピクセルの白黒PNG画像を読み込み、[DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) メソッドで保存すると、8ビット/ピクセルのPNG画像が出力されます。<br/>これを回避し、1ビット/ピクセルのPNG画像として保存するには、このメソッドで対応する保存オプションを取得し、[Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) メソッドの第2パラメータとして渡します。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_14) | 比例した高さを取得します。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_15) | 比例した幅を取得します。 |
| [load(file_path)](#load_file_path_16) | 指定されたファイルから新しい画像をロードします。 |
| [load(file_path, load_options)](#load_file_path_load_options_17) | 指定されたファイルから新しい画像をロードします。 |
| [load(stream)](#load_stream_18) | 指定されたストリームから新しい画像をロードします。 |
| [load(stream, load_options)](#load_stream_load_options_19) | 指定されたストリームから新しい画像をロードします。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_20) | 画像のサイズを変更します。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_21) | 画像のサイズを変更します。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_22) | 画像のサイズを変更します。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_23) | 高さを比例的にリサイズします。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_24) | 高さを比例的にリサイズします。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_25) | 高さを比例的にリサイズします。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_26) | 幅を比例的にリサイズします。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_27) | 幅を比例的にリサイズします。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_28) | 幅を比例的にリサイズします。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_29) | 画像を回転、反転、または回転と反転を行います。 |
| save() | 画像データを基になるストリームに保存します。 |
| [save(file_path)](#save_file_path_30) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, options)](#save_file_path_options_31) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_32) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, over_write)](#save_file_path_over_write_33) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(stream)](#save_stream_34) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(stream, options_base)](#save_stream_options_base_35) | 保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_36) | 保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_37) | 画像のパレットを設定します。 |


### Constructor: AiImage() {#AiImage__1}


```
 AiImage() 
```

AiImage クラスの新しいインスタンスを初期化します

### Method: add_layer(layer) {#add_layer_layer_1}


```
 add_layer(layer) 
```

AI レイヤー セクションを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer | [AiLayerSection](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | AI レイヤー セクションです。 |

### Method: can_load(file_path)  [static] {#can_load_file_path_2}


```
 can_load(file_path) 
```

指定されたファイルパスから画像をロードできるかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたファイルから画像をロードできる場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_3}


```
 can_load(file_path, load_options) 
```

指定されたファイルパスから画像をロードできるかどうか、オプションで指定されたオープンオプションを使用して判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたファイルから画像をロードできる場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: can_load(stream)  [static] {#can_load_stream_4}


```
 can_load(stream) 
```

指定されたストリームから画像をロードできるかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ロード元ストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたストリームから画像をロードできる場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_5}


```
 can_load(stream, load_options) 
```

指定されたストリームから画像をロードできるかどうか、オプションで指定された <paramref name="loadOptions" /> を使用して判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ロード元ストリーム。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 指定されたストリームから画像をロードできる場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: can_save(options) {#can_save_options_6}


```
 can_save(options) 
```

渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 使用する保存オプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 渡された保存オプションで表される指定されたファイル形式に画像を保存できる場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

指定された作成オプションを使用して新しい画像を作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 画像オプション。 |
| width | int | 幅。 |
| 高さ | int | 高さ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 新しく作成された画像。 |


### Method: get_default_options(args) {#get_default_options_args_8}


```
 get_default_options(args) 
```

デフォルトのオプションを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| args | object | 引数。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | デフォルトオプション |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_9}


```
 get_file_format(file_path) 
```

ファイル形式を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 決定されたファイル形式。 |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_10}


```
 get_file_format(stream) 
```

ファイル形式を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 決定されたファイル形式。 |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_11}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

現在の画像に適合する矩形を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 適合矩形を取得する矩形。 |
| pixels | int | 32ビットARGBピクセル。 |
| width | int | オブジェクトの幅。 |
| 高さ | int | オブジェクトの高さ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 適合矩形、または適合矩形が見つからない場合の例外。 |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_12}


```
 get_fitting_rectangle(rectangle, width, height) 
```

現在の画像に適合する矩形を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 適合矩形を取得する矩形。 |
| width | int | オブジェクトの幅。 |
| 高さ | int | オブジェクトの高さ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 適合矩形、または適合矩形が見つからない場合の例外。 |


### Method: get_original_options() {#get_original_options__13}


```
 get_original_options() 
```

元のファイル設定に基づくオプションを取得します。<br/>これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。<br/>例えば、1ビット/ピクセルの白黒PNG画像を読み込み、[DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) メソッドで保存すると、8ビット/ピクセルのPNG画像が出力されます。<br/>これを回避し、1ビット/ピクセルのPNG画像として保存するには、このメソッドで対応する保存オプションを取得し、[Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) メソッドの第2パラメータとして渡します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 元のファイル設定に基づくオプション。 |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_14}


```
 get_proportional_height(width, height, new_width) 
```

比例した高さを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | int | 幅。 |
| 高さ | int | 高さ。 |
| new_width | int | 新しい幅。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 比例した高さ。 |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_15}


```
 get_proportional_width(width, height, new_height) 
```

比例した幅を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | int | 幅。 |
| 高さ | int | 高さ。 |
| new_height | int | 新しい高さ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 比例した幅。 |


### Method: load(file_path)  [static] {#load_file_path_16}


```
 load(file_path) 
```

指定されたファイルから新しい画像をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | 画像を読み込むファイルパス。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 読み込まれた画像。 |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_17}


```
 load(file_path, load_options) 
```

指定されたファイルから新しい画像をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | 画像を読み込むファイルパス。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 読み込まれた画像。 |


### Method: load(stream)  [static] {#load_stream_18}


```
 load(stream) 
```

指定されたストリームから新しい画像をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像を読み込むストリーム。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 読み込まれた画像。 |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_19}


```
 load(stream, load_options) 
```

指定されたストリームから新しい画像をロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像を読み込むストリーム。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | ロードオプション。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 読み込まれた画像。 |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_20}


```
 resize(new_width, new_height) 
```

画像のサイズを変更します。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| new_height | int | 新しい高さ。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_21}


```
 resize(new_width, new_height, resize_type) 
```

画像のサイズを変更します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| new_height | int | 新しい高さ。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズタイプ。 |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_22}


```
 resize(new_width, new_height, settings) 
```

画像のサイズを変更します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| new_height | int | 新しい高さ。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | リサイズ設定。 |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_23}


```
 resize_height_proportionally(new_height) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_24}


```
 resize_height_proportionally(new_height, resize_type) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズのタイプ。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_25}


```
 resize_height_proportionally(new_height, settings) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_26}


```
 resize_width_proportionally(new_width) 
```

幅を比例的にリサイズします。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_27}


```
 resize_width_proportionally(new_width, resize_type) 
```

幅を比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズのタイプ。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_28}


```
 resize_width_proportionally(new_width, settings) 
```

幅を比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_29}


```
 rotate_flip(rotate_flip_type) 
```

画像を回転、反転、または回転と反転を行います。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 回転フリップのタイプです。 |

### Method: save(file_path) {#save_file_path_30}


```
 save(file_path) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |

### Method: save(file_path, options) {#save_file_path_options_31}


```
 save(file_path, options) 
```

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_32}


```
 save(file_path, options, bounds_rectangle) 
```

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 対象画像の境界矩形です。空の矩形を設定すると、ソースの境界が使用されます。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_33}


```
 save(file_path, over_write) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |
| over_write | bool | もし <c>true</c> に設定するとファイル内容を上書きし、そうでなければ追記が行われます。 |

### Method: save(stream) {#save_stream_34}


```
 save(stream) 
```

オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | オブジェクトのデータを保存するストリーム。 |

### Method: save(stream, options_base) {#save_stream_options_base_35}


```
 save(stream, options_base) 
```

保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像のデータを保存するストリーム。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存オプション。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_36}


```
 save(stream, options_base, bounds_rectangle) 
```

保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像のデータを保存するストリーム。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存オプション。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 対象画像の境界矩形。空の矩形を設定するとソースの境界が使用されます。 |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_37}


```
 set_palette(palette, update_colors) 
```

画像のパレットを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 設定するパレット。 |
| update_colors | bool | <c>true</c> に設定された場合、色は新しいパレットに従って更新されます。そうでない場合、カラーインデックスは変更されません。変更されないインデックスは、対応するパレットエントリがない場合、画像の読み込み時にクラッシュする可能性があります。 |

