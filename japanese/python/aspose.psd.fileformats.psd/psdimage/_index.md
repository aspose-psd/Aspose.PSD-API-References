---
title: "PsdImage クラス"
type: docs
weight: 1760
url: /ja/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | 指定されたパスのラスタ画像（パス内の psd 画像ではありません）から [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用します - カラーモード - rgb、4 チャンネル、1 チャンネルあたり 8 ビット、圧縮 - Raw。 |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | 指定されたパスのラスタ画像（パス内の psd 画像ではありません）からコンストラクタ パラメータを使用して [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。 |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | 既存のラスタ画像（psd 画像ではありません）から RGB カラーモード、4 チャンネル、1 チャンネルあたり 8 ビット、圧縮なしで [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。 |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | 既存のラスタ画像（psd 画像ではありません）からコンストラクタ パラメータを使用して [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。 |
| [PsdImage(stream)](#PsdImage_stream_5) | 指定されたストリームのラスタ画像（ストリーム内の psd 画像ではありません）から [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用します - カラーモード - rgb、4 チャンネル、1 チャンネルあたり 8 ビット、圧縮 - Raw。 |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | 指定されたストリームのラスタ画像（ストリーム内の psd 画像ではありません）からコンストラクタ パラメータを使用して [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。 |
| [PsdImage(width, height)](#PsdImage_width_height_7) | 指定された幅と高さで [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用します。 |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | 指定された幅、高さ、paletter、カラーモード、チャンネル数、チャンネルビット長、および指定された圧縮モード パラメータで [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | デフォルトの PSD バージョンです。 |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | アクティブなレイヤーを取得または設定します。 |
| auto_adjust_palette | bool | r/w | 自動調整パレットかどうかを示す値を取得または設定します。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 背景色の値を取得または設定します。 |
| bits_per_channel | int | r | チャンネルあたりのビット数を取得します。 |
| bits_per_pixel | int | r | 画像のピクセルあたりビット数を取得します。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | オブジェクトの境界を取得します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| channels_count | int | r | PSD のチャンネル数を取得します。 |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD 画像の CMYK カラープロファイルを取得または設定します。正しい色変換のために RgbColorProfile とペアで使用する必要があります。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | カラーモードを取得または設定します。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | 圧縮方式を取得します。 |
| container | [Image](/psd/python-net/aspose.psd/image) | r | [Image](/psd/python-net/aspose.psd/image/) コンテナを取得します。 |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | オブジェクトのデータストリームを取得します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | ファイル形式の値を取得します |
| global_angle | int | r/w | 全体の角度を取得または設定します。 |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | グローバルレイヤーマスク情報を取得します。 |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | グローバルレイヤーリソースを取得または設定します。 |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | グレースケール PSD 画像用の GRAY（モノクロ）カラープロファイルを取得または設定します。 |
| has_alpha | bool | r | この [RasterImage](/psd/python-net/aspose.psd/rasterimage/) の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| has_background_color | bool | r/w | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| has_transparency_data | bool | r/w | 最初のアルファチャンネルがレイヤーデータを指定したときの合成結果の透明データを含むかどうかを示す値を取得または設定します。 |
| has_transparent_color | bool | r/w | 画像に透明色があるかどうかを示す値を取得します。 |
| 高さ | int | r | 画像の高さを取得します。 |
| horizontal_resolution | double | r/w | この [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) の水平解像度（インチあたりピクセル数）を取得または設定します。 |
| image_opacity | float | r | この画像の不透明度を取得します。 |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | PSD 画像リソースを取得または設定します。 |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 割り込みモニターを取得または設定します。 |
| is_cached | bool | r | 画像データが現在キャッシュされているかどうかを示す値を取得します。 |
| is_flatten | bool | r | PSD 画像がフラット化されているかどうかを示す値を取得します。 |
| is_raw_data_available | bool | r | 生データのロードがサポートされているかどうかを示す値を取得します。 |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | PSD レイヤーを取得または設定します。 |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | リンクされたレイヤーマネージャーを取得します。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| premultiply_components | bool | r/w | 画像コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | カスタムカラーコンバータを取得または設定します |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 生データ形式を取得します。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 現在の生データ設定を取得します。これらの設定を使用する場合、データは変換なしでロードされることに注意してください。 |
| raw_fallback_index | int | r/w | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | インデックスカラーコンバータを取得または設定します |
| raw_line_size | int | r | 生ラインサイズ（バイト単位）を取得します。 |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD 画像用の RGB カラープロファイルを取得または設定します。正しい色変換のためには CmykColorProfile とペアである必要があります。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r | オブジェクトのサイズを取得します。 |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | スマートオブジェクトプロバイダーを取得します。 |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | この [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) の [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) を取得します。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 画像の透明色を取得します。 |
| update_xmp_data | bool | r/w | XMP メタデータを更新するかどうかを示す値を取得または設定します。 |
| use_palette | bool | r | 画像パレットが使用されているかどうかを示す値を取得します。 |
| use_raw_data | bool | r/w | 生データロードが利用可能な場合に生データロードを使用するかどうかを示す値を取得または設定します。 |
| version | int | r/w | バージョンを取得または設定します。 |
| vertical_resolution | double | r/w | この [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| width | int | r | 画像の幅を取得します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | 白黒調整レイヤーを追加します。 |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | 明るさ/コントラスト調整レイヤーを追加します。 |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | デフォルトパラメータでチャンネルミキサー調整レイヤーを追加します。 |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | カラーバランス調整レイヤーを追加します。 |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | カーブ調整レイヤーを追加します。 |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | 露出調整レイヤーを追加します。 |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | グラデーションマップ調整レイヤーを追加します。 |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | 色相/彩度調整レイヤーを追加します。 |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | 反転調整レイヤーを追加します。 |
| [add_layer(layer)](#add_layer_layer_10) | レイヤーを追加します。 |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | レイヤー グループを追加します。 |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | レベル調整レイヤーを追加します。 |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | フォトフィルター レイヤーを追加します。 |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | ポスタライズ調整レイヤーを追加します。 |
| [add_regular_layer()](#add_regular_layer__15) | 新しい通常レイヤーを追加します。 |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | 選択カラー調整レイヤーを追加します。 |
| [add_shape_layer()](#add_shape_layer__17) | 空のシェイプレイヤーを追加します。<br/>            パスがありません。保存前にシェイプレイヤーに追加する必要があります。 |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | 新しいテキストレイヤーを追加します。 |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | しきい値調整レイヤーを追加します。 |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | ビブランス調整レイヤーを追加します。 |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | 画像の明るさを調整します。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | 画像のコントラスト調整 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | 画像のガンマ補正。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | 画像のガンマ補正。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | 事前定義された閾値による画像の二値化 |
| binarize_otsu() | 大津の閾値法による画像の二値化 |
| cache_data() | データをキャッシュし、基になる [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) から追加のデータ読み込みが行われないことを保証します。 |
| [can_load(file_path)](#can_load_file_path_28) | 指定されたファイルパスから画像をロードできるかどうかを判定します。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | 指定されたファイルパスから画像をロードできるかどうか、オプションで指定されたオープンオプションを使用して判定します。 |
| [can_load(stream)](#can_load_stream_30) | 指定されたストリームから画像をロードできるかどうかを判定します。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | 指定されたストリームから画像をロードできるかどうか、オプションで指定された <paramref name="loadOptions" /> を使用して判定します。 |
| [can_save(options)](#can_save_options_32) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [convert(new_options)](#convert_new_options_33) | この画像形式をオプションで指定された形式に変換します。 |
| [create(image_options, width, height)](#create_image_options_width_height_34) | 指定された作成オプションを使用して新しい画像を作成します。 |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | 画像のトリミング。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | 現在の画像にディザリングを実行します。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | 現在の画像にディザリングを実行します。 |
| [filter(rectangle, options)](#filter_rectangle_options_38) | 指定された矩形をフィルタリングします。 |
| flatten_image() | すべてのレイヤーを統合します。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| [get_default_options(args)](#get_default_options_args_41) | デフォルトのオプションを取得します。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | 部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | 部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | デフォルトの生データ配列を取得します。 |
| [get_file_format(file_path)](#get_file_format_file_path_45) | ファイル形式を取得します。 |
| [get_file_format(stream)](#get_file_format_stream_46) | ファイル形式を取得します。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | 現在の画像に適合する矩形を取得します。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | 現在の画像に適合する矩形を取得します。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | リソース画像が最後に変更された日時を取得します。 |
| [get_original_options()](#get_original_options__50) | 元のファイル設定に基づくオプションを取得します。<br/>これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。<br/>例えば、1ビット/ピクセルの白黒PNG画像を読み込み、[DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) メソッドで保存すると、8ビット/ピクセルのPNG画像が出力されます。<br/>これを回避し、1ビット/ピクセルのPNG画像として保存するには、このメソッドで対応する保存オプションを取得し、[Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) メソッドの第2パラメータとして渡します。 |
| [get_pixel(x, y)](#get_pixel_x_y_51) | 画像のピクセルを取得します。<br/>パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドの使用は避けてください。パフォーマンスに重大な影響を与える可能性があります。<br/>より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | 比例した高さを取得します。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | 比例した幅を取得します。 |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | 画像をグレースケール表現に変換します |
| [load(file_path)](#load_file_path_55) | 指定されたファイルから新しい画像をロードします。 |
| [load(file_path, load_options)](#load_file_path_load_options_56) | 指定されたファイルから新しい画像をロードします。 |
| [load(stream)](#load_stream_57) | 指定されたストリームから新しい画像をロードします。 |
| [load(stream, load_options)](#load_stream_load_options_58) | 指定されたストリームから新しい画像をロードします。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | 32ビット ARGB ピクセルをロードします。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | 64ビット ARGB ピクセルをロードします。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | CMYK 形式のピクセルをロードします。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | CMYK 形式のピクセルをロードします。<br/>このメソッドは非推奨です。より効果的な [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) メソッドを使用してください。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | 32ビット ARGB ピクセルを部分的に（ブロック単位で）ロードします。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | パック単位で部分的にピクセルをロードします。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | ピクセルをロードします。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | 生データをロードします。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | 生データをロードします。 |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | レイヤーを結合します。 |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | 指定されたスキャンラインインデックスで全スキャンラインを読み取ります。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | 指定されたスキャンラインインデックスで全スキャンラインを読み取ります。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | 許容差で一つの色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | 許容差で一つの色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | すべての非透過色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。<br/>            注: 透過性のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | すべての非透過色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。<br/>            注: 透過性のない画像に使用すると、すべての色が単一の色に置き換えられます。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | 画像のサイズを変更します。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | 画像のサイズを変更します。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | 画像のサイズを変更します。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | 高さを比例的にリサイズします。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | 高さを比例的にリサイズします。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | 高さを比例的にリサイズします。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | 幅を比例的にリサイズします。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | 幅を比例的にリサイズします。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | 幅を比例的にリサイズします。 |
| [rotate(angle)](#rotate_angle_84) | 画像を中心を基点に回転させます。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | 画像を中心を基点に回転させます。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | 画像を回転、反転、または回転と反転を行います。 |
| save() | 画像データを基になるストリームに保存します。 |
| [save(file_path)](#save_file_path_87) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, options)](#save_file_path_options_88) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, over_write)](#save_file_path_over_write_90) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(stream)](#save_stream_91) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(stream, options_base)](#save_stream_options_base_92) | 保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | 保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | 32ビット ARGB ピクセルを保存します。 |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | ピクセルを保存します（形式固有のメソッド）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | 生データを保存します。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | 画像のパレットを設定します。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | 指定された位置に画像ピクセルを設定します。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | この [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) の解像度を設定します。 |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

指定されたパスのラスタ画像（パス内の psd 画像ではありません）から [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用します - カラーモード - rgb、4 チャンネル、1 チャンネルあたり 8 ビット、圧縮 - Raw。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| パス | string | ピクセルとパレットデータを読み込むためのパスで、初期化にも使用します。 |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

指定されたパスのラスタ画像（パス内の psd 画像ではありません）からコンストラクタ パラメータを使用して [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| パス | string | ピクセルとパレットデータを読み込むためのパスで、初期化にも使用します。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | カラーモードです。 |
| channel_bit_depth | short | チャンネルごとの PSD ビット深度です。 |
| チャンネル | short | PSD のチャンネル数です。 |
| psd_version | int | PSD バージョンです。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 使用する圧縮方式です。 |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

既存のラスタ画像（psd 画像ではありません）から RGB カラーモード、4 チャンネル、1 チャンネルあたり 8 ビット、圧縮なしで [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | ピクセルとパレットデータを読み込む画像、及び初期化に使用する画像です。 |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

既存のラスタ画像（psd 画像ではありません）からコンストラクタ パラメータを使用して [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | ピクセルとパレットデータを読み込む画像、及び初期化に使用する画像です。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | カラーモードです。 |
| channel_bit_depth | short | チャンネルごとの PSD ビット深度です。 |
| チャンネル | short | PSD のチャンネル数です。 |
| psd_version | int | PSD バージョンです。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 使用する圧縮方式です。 |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

指定されたストリームのラスタ画像（ストリーム内の psd 画像ではありません）から [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。デフォルトパラメータで psd 画像を初期化するために使用します - カラーモード - rgb、4 チャンネル、1 チャンネルあたり 8 ビット、圧縮 - Raw。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ピクセルとパレットデータを読み込むストリーム、及び初期化に使用するストリームです。 |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

指定されたストリームのラスタ画像（ストリーム内の psd 画像ではありません）からコンストラクタ パラメータを使用して [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | ピクセルとパレットデータを読み込むストリーム、及び初期化に使用するストリームです。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | カラーモードです。 |
| channel_bit_depth | short | チャンネルごとの PSD ビット深度です。 |
| チャンネル | short | PSD のチャンネル数です。 |
| psd_version | int | PSD バージョンです。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 使用する圧縮方式です。 |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

指定された幅と高さで [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | int | 画像の幅です。 |
| 高さ | int | 画像の高さ。 |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

指定された幅、高さ、paletter、カラーモード、チャンネル数、チャンネルビット長、および指定された圧縮モード パラメータで [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) クラスの新しいインスタンスを初期化します。空の psd 画像を初期化するために使用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| width | int | 画像の幅です。 |
| 高さ | int | 画像の高さ。 |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | カラーパレット。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | カラーモードです。 |
| channel_bit_depth | short | チャンネルごとの PSD ビット深度です。 |
| チャンネル | short | PSD のチャンネル数です。 |
| psd_version | int | PSD バージョンです。 |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | 使用する圧縮方式です。 |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

白黒調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | 作成された白黒調整レイヤー。 |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

明るさ/コントラスト調整レイヤーを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | int | 明るさです。 |
| コントラスト | int | コントラストです。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | 作成された明るさ/コントラストレイヤー |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

デフォルトパラメータでチャンネルミキサー調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | 追加されたチャンネルミキサーレイヤー |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

カラーバランス調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | 新しく作成されたカラーバランスレイヤー。 |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

カーブ調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | 作成された [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) レイヤー |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

露出調整レイヤーを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| exposure | float | 露出です。 |
| offset | float | オフセット。 |
| gamma_correction | float | ガンマ補正。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | 作成された露出調整レイヤー |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

グラデーションマップ調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap インスタンス。 |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

色相/彩度調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | 新しく作成された色相/彩度レイヤー。 |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

反転調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | 作成された反転レイヤー |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

レイヤーを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | レイヤー。 |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

レイヤー グループを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| group_name | string | グループの名前。 |
| index | int | 挿入後のレイヤーのインデックスです。 |
| start_behaviour | bool | もし <c>true</c> に設定された場合、[start behaviour] は起動時にグループが開いた状態になります。そうでなければ最小化された状態になります。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | グループレイヤーを開く |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

レベル調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | 新しく作成されたレベルレイヤー |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

フォトフィルター レイヤーを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | 色。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | 作成されたフォトフィルターレイヤー |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

ポスタライズ調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer インスタンス。 |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

新しい通常レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 作成された通常レイヤー。 |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

選択カラー調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | 作成された選択的カラー調整レイヤー。 |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

空のシェイプレイヤーを追加します。<br/>            パスがありません。保存前にシェイプレイヤーに追加する必要があります。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer インスタンス。 |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

新しいテキストレイヤーを追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| text | string | レイヤーのテキスト。 |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | レイヤーの矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | 作成されたテキストレイヤー。 |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

しきい値調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | 作成されたしきい値調整レイヤー。 |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

ビブランス調整レイヤーを追加します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | 新しく作成されたビブランスレイヤー。 |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

画像の明るさを調整します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | int | 明るさの値です。 |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

画像のコントラスト調整

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| コントラスト | float | コントラスト値（範囲 [-100; 100]） |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

画像のガンマ補正。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ガンマ | float | 赤、緑、青チャンネルの係数用ガンマ |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

画像のガンマ補正。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| gamma_red | float | 赤チャンネル係数用ガンマ |
| gamma_green | float | 緑チャンネル係数用ガンマ |
| gamma_blue | float | 青チャンネル係数用ガンマ |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brightness_difference | double | ピクセルと、そのピクセルを中心とした s x s ウィンドウ内のピクセルの平均との明るさの差。 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brightness_difference | double | ピクセルと、そのピクセルを中心とした s x s ウィンドウ内のピクセルの平均との明るさの差。 |
| window_size | int | このピクセルを中心とした s x s ウィンドウのサイズ |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

事前定義された閾値による画像の二値化

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| しきい値 | byte | しきい値。ピクセルの対応するグレイ値がしきい値より大きい場合、255 の値が割り当てられ、そうでなければ 0 が割り当てられます。 |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

この画像形式をオプションで指定された形式に変換します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | 新しいオプション。 |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

画像のトリミング。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

現在の画像にディザリングを実行します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | ディザリング手法。 |
| bits_count | int | ディザリングの最終ビット数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

現在の画像にディザリングを実行します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | ディザリング手法。 |
| bits_count | int | ディザリングの最終ビット数。 |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | ディザリング用のカスタムパレット。 |

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

指定された矩形をフィルタリングします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形。 |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | オプション。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


```
 get_argb_32_pixel(x, y) 
```

画像の 32 ビット ARGB ピクセルを取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | ピクセルのX座標。 |
| y | int | ピクセルのY座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 指定された位置の32ビットARGBピクセル。 |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


```
 get_default_argb_32_pixels(rectangle) 
```

デフォルトの 32 ビット ARGB ピクセル配列を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを取得する矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | デフォルトのピクセル配列。 |


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを取得する矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分的なピクセルローダー。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを取得する矩形。 |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 部分的な生データローダー。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 生データ設定。 |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

デフォルトの生データ配列を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 生データを取得する矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 生データ設定。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| byte | デフォルトの生データ配列。 |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

リソース画像が最後に変更された日時を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| use_default | bool | <c>true</c> に設定された場合、FileInfo の情報をデフォルト値として使用します。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| datetime | リソース画像が最後に変更された日時。 |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

元のファイル設定に基づくオプションを取得します。<br/>これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。<br/>例えば、1ビット/ピクセルの白黒PNG画像を読み込み、[DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) メソッドで保存すると、8ビット/ピクセルのPNG画像が出力されます。<br/>これを回避し、1ビット/ピクセルのPNG画像として保存するには、このメソッドで対応する保存オプションを取得し、[Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) メソッドの第2パラメータとして渡します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 元のファイル設定に基づくオプション。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


```
 get_pixel(x, y) 
```

画像のピクセルを取得します。<br/>パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドの使用は避けてください。パフォーマンスに重大な影響を与える可能性があります。<br/>より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | ピクセルのX座標。 |
| y | int | ピクセルのY座標。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | 指定された位置のピクセル色。 |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| タイプ | 説明 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

32ビット ARGB ピクセルをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 読み込まれた 32 ビット ARGB ピクセル配列。 |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

64ビット ARGB ピクセルをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| long | 読み込まれた 64 ビット ARGB ピクセル配列。 |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

CMYK 形式のピクセルをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 読み込まれた CMYK ピクセルは 32 ビット整数値として表されます。 |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

CMYK 形式のピクセルをロードします。<br/>このメソッドは非推奨です。より効果的な [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) メソッドを使用してください。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | 読み込まれた CMYK ピクセル配列。 |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32ビット ARGB ピクセルを部分的に（ブロック単位で）ロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分的なピクセルローダー。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

パック単位で部分的にピクセルをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 希望する矩形。 |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | ピクセルローダー。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


```
 load_pixels(rectangle) 
```

ピクセルをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 読み込まれたピクセル配列。 |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

生データをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 生データを読み込む矩形。 |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 宛先画像の境界。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 読み込まれたデータに使用する生データ設定です。データが指定された形式でない場合、データ変換が実行されます。 |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 生データローダー。 |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

生データをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 生データを読み込む矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | 読み込まれたデータに使用する生データ設定です。データが指定された形式でない場合、データ変換が実行されます。 |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | 生データローダー。 |

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

レイヤーを結合します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 下層レイヤー。 |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | 上層レイヤー。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | マージ後の下層レイヤー |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


```
 read_argb_32_scan_line(scan_line_index) 
```

指定されたスキャンラインインデックスで全スキャンラインを読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scan_line_index | int | 走査ラインのゼロベースインデックス。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| int | 走査ラインの 32 ビット ARGB カラー値配列。 |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


```
 read_scan_line(scan_line_index) 
```

指定されたスキャンラインインデックスで全スキャンラインを読み取ります。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scan_line_index | int | 走査ラインのゼロベースインデックス。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | 走査ラインのピクセルカラー値配列。 |


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

許容差で一つの色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | 置換された色調を広げるために許容できる古い色の差分。 |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

許容差で一つの色を別の色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| old_color_argb | int | 置換される古い色の ARGB 値。 |
| old_color_diff | byte | 置換された色調を広げるために許容できる古い色の差分。 |
| new_color_argb | int | 古い色と置換するための新しい色の ARGB 値。 |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

すべての非透過色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。<br/>            注: 透過性のない画像に使用すると、すべての色が単一の色に置き換えられます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

すべての非透過色を新しい色に置き換え、元のアルファ値を保持して滑らかなエッジを保存します。<br/>            注: 透過性のない画像に使用すると、すべての色が単一の色に置き換えられます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_color_argb | int | 非透過色を置き換えるための新しいカラー ARGB 値です。 |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

画像のサイズを変更します。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| new_height | int | 新しい高さ。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズのタイプ。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

幅を比例的にリサイズします。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

幅を比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズのタイプ。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

幅を比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

画像を中心を基点に回転させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度（度）。正の値は時計回りに回転します。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


```
 rotate(angle, resize_proportionally, background_color) 
```

画像を中心を基点に回転させます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度（度）。正の値は時計回りに回転します。 |
| resize_proportionally | bool | もし <c>true</c> に設定すると、回転した矩形（角点）の投影に従って画像サイズが変更されます。そうでない場合は、寸法はそのままで内部画像内容のみが回転します。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | 背景色。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

画像を回転、反転、または回転と反転を行います。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 回転・フリップのタイプ。 |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |
| over_write | bool | もし <c>true</c> に設定するとファイル内容を上書きし、そうでなければ追記が行われます。 |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | オブジェクトのデータを保存するストリーム。 |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像のデータを保存するストリーム。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存オプション。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32ビット ARGB ピクセルを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを保存する矩形。 |
| pixels | int | 32ビット ARGB ピクセル配列。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

ピクセルを保存します（形式固有のメソッド）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを保存する矩形。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32ビット ARGB ピクセル配列。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

生データを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| data | byte | 生データ。 |
| data_offset | int | 開始生データオフセット。 |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 生データ矩形。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | データが存在する生データ設定。 |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

指定された位置に画像の 32 ビット ARGB ピクセルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | ピクセルのX座標。 |
| y | int | ピクセルのY座標。 |
| argb_32_color | int | 指定位置の 32 ビット ARGB ピクセル。 |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

画像のパレットを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 設定するパレット。 |
| update_colors | bool | <c>true</c> に設定された場合、色は新しいパレットに従って更新されます。そうでない場合、カラーインデックスは変更されません。変更されないインデックスは、対応するパレットエントリがない場合、画像の読み込み時にクラッシュする可能性があります。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


```
 set_pixel(x, y, color) 
```

指定された位置に画像ピクセルを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| x | int | ピクセルのX座標。 |
| y | int | ピクセルのY座標。 |
| color | [Color](/psd/python-net/aspose.psd/color) | 指定された位置のピクセルカラーです。 |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

この [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) の解像度を設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dpi_x | double | 水平解像度（dpi）を、[RasterImage](/psd/python-net/aspose.psd/rasterimage/) のドット数で表したもの。 |
| dpi_y | double | 垂直解像度（dpi）を、[RasterImage](/psd/python-net/aspose.psd/rasterimage/) のドット数で表したもの。 |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| タイプ | 説明 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

指定されたスキャンラインインデックスに全スキャンラインを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scan_line_index | int | 走査ラインのゼロベースインデックス。 |
| argb_32_pixels | int | 書き込む 32 ビット ARGB カラー配列です。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

指定されたスキャンラインインデックスに全スキャンラインを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scan_line_index | int | 走査ラインのゼロベースインデックス。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 書き込むピクセルカラー配列です。 |

