---
title: "ImageAttributes クラス"
type: docs
weight: 2180
url: /ja/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | ImageAttributes クラスの新しいインスタンスを初期化します |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| clear_brush_remap_table() | この [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) オブジェクトのブラシカラーリマップテーブルをクリアします。 |
| clear_color_key() | デフォルトカテゴリのカラーキー（透明度範囲）をクリアします。 |
| [clear_color_key(type)](#clear_color_key_type_1) | 指定されたカテゴリのカラーキー（透明度範囲）をクリアします。 |
| clear_color_matrix() | デフォルトカテゴリのカラー調整マトリックスをクリアします。 |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | 指定されたカテゴリのカラー調整マトリックスをクリアします。 |
| clear_gamma() | デフォルトカテゴリのガンマ補正を無効にします。 |
| [clear_gamma(type)](#clear_gamma_type_3) | 指定されたカテゴリのガンマ補正を無効にします。 |
| clear_no_op() | デフォルトカテゴリの NoOp 設定をクリアします。 |
| [clear_no_op(type)](#clear_no_op_type_4) | 指定されたカテゴリの NoOp 設定をクリアします。 |
| clear_output_channel() | デフォルトカテゴリの CMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。 |
| [clear_output_channel(type)](#clear_output_channel_type_5) | 指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。 |
| clear_output_channel_color_profile() | デフォルトカテゴリの出力チャンネルカラープロファイル設定をクリアします。 |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | 指定されたカテゴリの出力チャンネルカラープロファイル設定をクリアします。 |
| clear_remap_table() | デフォルトカテゴリのカラーリマップテーブルをクリアします。 |
| [clear_remap_table(type)](#clear_remap_table_type_7) | 指定されたカテゴリのカラーリマップテーブルをクリアします。 |
| clear_threshold() | デフォルトカテゴリのしきい値をクリアします。 |
| [clear_threshold(type)](#clear_threshold_type_8) | 指定されたカテゴリのしきい値をクリアします。 |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | ブラシカテゴリのカラーリマップテーブルを設定します。 |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | デフォルトカテゴリのカラーキーを設定します。 |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | 指定されたカテゴリのカラーキー（透明度範囲）を設定します。 |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | 指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。 |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | デフォルトカテゴリのカラー調整マトリックスを設定します。 |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | デフォルトカテゴリのカラー調整マトリックスを設定します。 |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | 指定されたカテゴリのカラー調整マトリックスを設定します。 |
| [set_gamma(gamma)](#set_gamma_gamma_18) | デフォルトカテゴリのガンマ値を設定します。 |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | 指定されたカテゴリのガンマ値を設定します。 |
| set_no_op() | デフォルトカテゴリのカラー調整をオフにします。 |
| [set_no_op(type)](#set_no_op_type_20) | 指定されたカテゴリのカラー調整をオフにします。 |
| [set_output_channel(flags)](#set_output_channel_flags_21) | デフォルトカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | 指定されたカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。 |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | デフォルトカテゴリの出力チャンネルのカラープロファイルファイルを設定します。 |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | 指定されたカテゴリの出力チャンネルのカラープロファイルファイルを設定します。 |
| [set_remap_table(map)](#set_remap_table_map_25) | デフォルトカテゴリのカラーリマップテーブルを設定します。 |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | 指定されたカテゴリのカラーリマップテーブルを設定します。 |
| [set_threshold(threshold)](#set_threshold_threshold_27) | デフォルトカテゴリのしきい値（透明度範囲）を設定します。 |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | 指定されたカテゴリのしきい値（透明度範囲）を設定します。 |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | テクスチャをシェイプ全体やシェイプ境界でどのようにタイル配置するかを決定するために使用されるラップモードを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体にタイル配置されて埋められます。 |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | テクスチャをシェイプ全体やシェイプ境界でどのようにタイル配置するかを決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体にタイル配置されて埋められます。 |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | テクスチャをシェイプ全体やシェイプ境界でどのようにタイル配置するかを決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体にタイル配置されて埋められます。 |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

ImageAttributes クラスの新しいインスタンスを初期化します

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

指定されたカテゴリのカラーキー（透明度範囲）をクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素で、カラーキーがクリアされるカテゴリを指定します。 |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

指定されたカテゴリのカラー調整マトリックスをクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素で、カラー調整マトリックスがクリアされるカテゴリを指定します。 |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

指定されたカテゴリのガンマ補正を無効にします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素で、ガンマ補正が無効になるカテゴリを指定します。 |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

指定されたカテゴリの NoOp 設定をクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素で、NoOp 設定がクリアされるカテゴリを指定します。 |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

指定されたカテゴリの（シアン・マゼンタ・イエロー・ブラック）出力チャンネル設定をクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 出力チャネル設定がクリアされるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

指定されたカテゴリの出力チャンネルカラープロファイル設定をクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 出力チャネルプロファイル設定がクリアされるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

指定されたカテゴリのカラーリマップテーブルをクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | リマップテーブルがクリアされるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

指定されたカテゴリのしきい値をクリアします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | しきい値がクリアされるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

ブラシカテゴリのカラーリマップテーブルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) オブジェクトの配列です。 |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

デフォルトカテゴリのカラーキーを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | 低いカラーキーの値です。 |
| color_high | [Color](/psd/python-net/aspose.psd/color) | 高いカラーキーの値です。 |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

指定されたカテゴリのカラーキー（透明度範囲）を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | 低いカラーキーの値です。 |
| color_high | [Color](/psd/python-net/aspose.psd/color) | 高いカラーキーの値です。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | カラーキーが設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | カラー調整行列です。 |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | グレースケール調整行列です。 |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

デフォルトカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | カラー調整行列です。 |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | グレースケール調整行列です。 |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | カラー調整およびグレースケール調整行列の影響を受ける画像とカラーのタイプを指定する [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) の要素です。 |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

指定されたカテゴリのカラー調整マトリックスとグレースケール調整マトリックスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | カラー調整行列です。 |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | グレースケール調整行列です。 |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | カラー調整およびグレースケール調整行列の影響を受ける画像とカラーのタイプを指定する [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) の要素です。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | カラー調整およびグレースケール調整行列が設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

デフォルトカテゴリのカラー調整マトリックスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | カラー調整行列です。 |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

デフォルトカテゴリのカラー調整マトリックスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | カラー調整行列です。 |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | カラー調整行列の影響を受ける画像とカラーのタイプを指定する [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) の要素です。 |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

指定されたカテゴリのカラー調整マトリックスを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | カラー調整行列です。 |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | カラー調整行列の影響を受ける画像とカラーのタイプを指定する [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) の要素です。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | カラー調整行列が設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

デフォルトカテゴリのガンマ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ガンマ | float | ガンマ補正値です。 |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

指定されたカテゴリのガンマ値を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ガンマ | float | ガンマ補正値です。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | ガンマ値が設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

指定されたカテゴリのカラー調整をオフにします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | カラー補正がオフになるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

デフォルトカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | 出力チャネルを指定する [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) の要素です。 |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

指定されたカテゴリのCMYK（シアン・マゼンタ・イエロー・ブラック）出力チャンネルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | 出力チャネルを指定する [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) の要素です。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 出力チャネルが設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

デフォルトカテゴリの出力チャンネルのカラープロファイルファイルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_profile_filename | string | カラー プロファイル ファイルのパス名です。カラー プロファイル ファイルが %SystemRoot%\System32\Spool\Drivers\Color ディレクトリにある場合、このパラメーターはファイル名を指定できます。それ以外の場合、このパラメーターは完全修飾パス名でなければなりません。 |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

指定されたカテゴリの出力チャンネルのカラープロファイルファイルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color_profile_filename | string | カラー プロファイル ファイルのパス名です。カラー プロファイル ファイルが %SystemRoot%\System32\Spool\Drivers\Color ディレクトリにある場合、このパラメーターはファイル名を指定できます。それ以外の場合、このパラメーターは完全修飾パス名でなければなりません。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 出力チャネルのカラー プロファイル ファイルが設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

デフォルトカテゴリのカラーリマップテーブルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) 型のカラーペアの配列です。各カラーペアは既存のカラー（最初の値）と、マッピング先のカラー（2 番目の値）を含みます。 |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

指定されたカテゴリのカラーリマップテーブルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) 型のカラーペアの配列です。各カラーペアは既存のカラー（最初の値）と、マッピング先のカラー（2 番目の値）を含みます。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | カラーリマップテーブルが設定されるカテゴリを指定する [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素です。 |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

デフォルトカテゴリのしきい値（透明度範囲）を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| しきい値 | float | しきい値を指定する実数です。 |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

指定されたカテゴリのしきい値（透明度範囲）を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| しきい値 | float | 0.0 から 1.0 のしきい値で、色を最大値または最小値にマッピングするためにソートする際のブレークポイントとして使用されます。 |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) の要素で、色のしきい値が設定されるカテゴリを指定します。 |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

テクスチャをシェイプ全体やシェイプ境界でどのようにタイル配置するかを決定するために使用されるラップモードを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体にタイル配置されて埋められます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) の要素で、画像の繰り返しコピーが領域をタイル状に配置する方法を指定します。 |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

テクスチャをシェイプ全体やシェイプ境界でどのようにタイル配置するかを決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体にタイル配置されて埋められます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) の要素で、画像の繰り返しコピーが領域をタイル状に配置する方法を指定します。 |
| color | [Color](/psd/python-net/aspose.psd/color) | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) オブジェクトで、レンダリングされた画像の外側のピクセルの色を指定します。モードパラメータが [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) に設定され、DrawImage に渡されるソース矩形が画像自体より大きい場合、この色が表示されます。 |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

テクスチャをシェイプ全体やシェイプ境界でどのようにタイル配置するかを決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体にタイル配置されて埋められます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) の要素で、画像の繰り返しコピーが領域をタイル状に配置する方法を指定します。 |
| color | [Color](/psd/python-net/aspose.psd/color) | レンダリングされた画像の外側のピクセルの色を指定するカラーオブジェクトです。モードパラメータが [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) に設定され、DrawImage に渡されるソース矩形が画像自体より大きい場合、この色が表示されます。 |
| クランプ | bool | このパラメータは効果がありません。false に設定してください。 |

