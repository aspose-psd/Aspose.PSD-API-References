---
title: "TiffOptions クラス"
type: docs
weight: 130
url: /ja/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。デフォルトではリトルエンディアン方式が使用されます。 |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。 |
| [TiffOptions(options)](#TiffOptions_options_3) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。 |
| [TiffOptions(tags)](#TiffOptions_tags_4) | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | アルファストレージオプションを取得または設定します。<br/>[TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) 以外のオプションは、3 つ以上の [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) が定義されている場合に使用されます。 |
| アーティスト | string | r/w | アーティストを取得または設定します。 |
| bits_per_pixel | int | r | 1ピクセルあたりのビット数を取得します。 |
| bits_per_sample | ushort | r/w | サンプルあたりのビット数を取得または設定します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | TIFF バイトオーダーを示す値を取得または設定します。 |
| color_map | ushort | r/w | カラー マップを取得または設定します。 |
| compressed_quality | int | r/w | 圧縮画像品質を取得または設定します。<br/>            Jpeg 圧縮で使用されます。 |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | 圧縮を取得または設定します。 |
| copyright | string | r/w | 著作権情報を取得または設定します。 |
| date_time | string | r/w | 日付と時刻を取得または設定します。 |
| default_memory_allocation_limit | int | r/w | デフォルトのメモリ割り当て上限を取得または設定します。 |
| default_replacement_font | string | r/w | デフォルトの置換フォントを取得または設定します（PSD ファイルの既存レイヤーフォントがシステムに存在しない場合に、ラスタにエクスポートする際にテキスト描画に使用されるフォント）。<br/>            正しいデフォルトフォント名を取得するには、次のコードスニペットを使用できます：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| document_name | string | r/w | ドキュメントの名前を取得または設定します。 |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | EXIF IFD へのポインタを取得または設定します。 |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | FAX T4 オプションを取得または設定します。 |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | TIFF ファイル標準を取得または設定します。 |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | バイト ビットのフィル順序を取得または設定します。 |
| full_frame | bool | r/w | [full frame] かどうかを示す値を取得または設定します。 |
| half_tone_hints | ushort | r/w | ハーフトーン ヒントを取得または設定します。 |
| image_description | string | r/w | 画像の説明を取得または設定します。 |
| image_length | uint | r/w | 画像の長さを取得または設定します。 |
| image_width | uint | r/w | 画像の幅を取得または設定します。 |
| ink_names | string | r/w | インク名を取得または設定します。 |
| is_extra_samples_present | bool | r | 追加サンプルが存在するかどうかを示す値を取得します。 |
| is_tiled | bool | r | 画像がタイル状かどうかを示す値を取得します。 |
| is_valid | bool | r | [TiffOptions]が正しく構成されているかどうかを示す値を取得します。失敗理由を見つけるには Validate メソッドを使用してください。 |
| max_sample_value | ushort | r/w | max sample value を取得または設定します。 |
| min_sample_value | ushort | r/w | min sample value を取得または設定します。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | マルチページオプション |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | 向きを取得または設定します。 |
| page_name | string | r/w | ページ名を取得または設定します。 |
| page_number | ushort | r/w | ページ番号タグを取得または設定します。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。 |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | フォトメトリックを取得または設定します。 |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | 平面構成を取得または設定します。 |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | LZW 圧縮用の predictor を取得または設定します。 |
| premultiply_components | bool | r/w | コンポーネントが事前乗算される必要があるかどうかを示す値を取得または設定します。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 解像度設定を取得または設定します。 |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | 解像度単位を取得または設定します。 |
| rows_per_strip | uint | r/w | ストリップあたりの行数を取得または設定します。 |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | サンプル形式を取得または設定します。 |
| samples_per_pixel | ushort | r | ピクセルあたりのサンプル数を取得します。このプロパティの値を変更するには、[TiffOptions.bits_per_sample] プロパティ セッターを使用してください。 |
| scanner_manufacturer | string | r/w | スキャナの製造元を取得または設定します。 |
| scanner_model | string | r/w | スキャナモデルを取得または設定します。 |
| smax_sample_value | uint | r/w | max sample value を取得または設定します。この値はサンプルデータに最も適したフィールド型（Byte、Short、Long のいずれか）を持ちます。 |
| smin_sample_value | uint | r/w | 最小サンプル値を取得または設定します。値はサンプルデータに最も適したフィールド型（Byte、Short、Long 型）を持ちます。 |
| software_type | string | r/w | ソフトウェアタイプを取得または設定します。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 画像を作成するためのソースを取得または設定します。 |
| strip_byte_counts | uint | r/w | ストリップバイトカウントを取得または設定します。 |
| strip_offsets | uint | r/w | ストリップオフセットを取得または設定します。 |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | このサブファイルに含まれるデータの種類に関する一般的な指標を取得または設定します。 |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | タグを取得または設定します。 |
| target_printer | string | r/w | 対象プリンターを取得または設定します。 |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | しきい値設定を取得または設定します。 |
| tile_byte_counts | uint | r/w | タイルバイトカウントを取得または設定します。 |
| tile_length | uint | r/w | タイルの長さを取得または設定します。 |
| tile_offsets | uint | r/w | タイルオフセットを取得または設定します。 |
| tile_width | uint | r/w | タイルの幅を取得または設定します。 |
| total_pages | ushort | r | 総ページ数を取得します。 |
| valid_tag_count | int | r | 有効なタグ数を取得します。これは総タグ数ではなく、保持可能なタグの数です。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | ベクトルラスター化オプションを取得または設定します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータ コンテナを取得または設定します。 |
| xp_author | string | r/w | Windows Explorerで使用される画像の作者を取得または設定します。 |
| xp_comment | string | r/w | Windows Explorerで使用される画像のコメントを取得または設定します。 |
| xp_keywords | string | r/w | Windows Explorerで使用される画像の件名を取得または設定します。 |
| xp_subject | string | r/w | Windows Explorerで使用される画像に関する情報を取得または設定します。 |
| xp_title | string | r/w | Windows Explorerで使用される画像に関する情報を取得または設定します。 |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x 位置を取得または設定します。 |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x 解像度を取得または設定します。 |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | YCbCrCoefficients を取得または設定します。 |
| y_cb_cr_subsampling | ushort | r/w | YCbCr フォトメトリックのサブサンプリング係数を取得または設定します。 |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y 位置を取得または設定します。 |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y 解像度を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | 新しいタグを追加します。 |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | タグを追加します。 |
| [clone()](#clone__3) | このインスタンスをクローンします。 |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | タイプでタグのインスタンスを取得します。 |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | 有効なタグの数を取得します。 |
| [is_tag_present(tag)](#is_tag_present_tag_6) | オプションにタグが存在するかどうかを判定します。 |
| [remove_tag(tag)](#remove_tag_tag_7) | タグを削除します。 |
| validate() | オプションが有効なタグの組み合わせを持つか検証します。 |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。デフォルトではリトルエンディアン方式が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | 期待される TIFF ファイル形式。 |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | 期待される TIFF ファイル形式。 |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | 使用する TIFF ファイル形式のバイトオーダーです。 |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | コピー元のオプションです。 |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

[TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | オプションを初期化するためのタグ。 |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

新しいタグを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 追加するタグ。 |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

タグを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 追加するタグ。 |

### Method: clone() {#clone__3}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | このインスタンスの浅いコピーを返します。 |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

タイプでタグのインスタンスを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | タグキー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | タグが存在すればそのインスタンス、存在しなければ null。 |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

有効なタグの数を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 検証するタグです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 有効なタグの数です。 |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

オプションにタグが存在するかどうかを判定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 確認するタグ ID。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | <c>true</c> はタグが存在する場合、そうでなければ <c>false</c>。 |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

タグを削除します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 削除するタグ。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | 正常に削除された場合は true |


