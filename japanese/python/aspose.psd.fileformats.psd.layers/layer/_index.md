---
title: "Layer クラス"
type: docs
weight: 930
url: /ja/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Layer()](#Layer__1) | 新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。遅延初期化のためのコンストラクタです。 |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | バイト配列から新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。 |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | 新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。 |
| [Layer(stream)](#Layer_stream_4) | 新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | ブレンドモードシグネチャを表します。 |
| LAYER_HEADER_SIZE [static] | int | r | レイヤーヘッダーのサイズです。 |
| auto_adjust_palette | bool | r/w | 自動調整パレットかどうかを示す値を取得または設定します。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 背景色の値を取得または設定します。 |
| bits_per_pixel | int | r | 画像のピクセルあたりビット数を取得します。 |
| blend_clipped_elements | bool | r/w | クリップされた要素のブレンドを取得または設定します。 |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | ブレンドモードキーを取得または設定します。 |
| blend_mode_signature | int | r | ブレンドモードのシグネチャを取得します。 |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | ブレンドオプションを取得します。 |
| bottom | int | r/w | 下層レイヤーの位置を取得または設定します。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | オブジェクトの境界を取得します。 |
| buffer_size_hint | int | r/w | 内部バッファ全体で許容される最大サイズとして定義されたバッファサイズヒントを取得または設定します。 |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | チャンネル情報を取得または設定します。 |
| channels_count | ushort | r | レイヤーのチャンネル数を取得します。 |
| clipping | byte | r/w | レイヤーのクリッピングを取得または設定します。0 = ベース、1 = 非ベース。 |
| container | [Image](/psd/python-net/aspose.psd/image) | r | [Image](/psd/python-net/aspose.psd/image/) コンテナを取得します。 |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | オブジェクトのデータストリームを取得します。 |
| display_name | string | r/w | レイヤーの表示名を取得または設定します。 |
| 破棄済み | bool | r | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| extra_length | int | r | レイヤーの追加情報の長さ（バイト）を取得します。 |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | ファイル形式の値を取得します |
| fill_opacity | int | r/w | 塗りの不透明度を取得または設定します。 |
| filler | byte | r/w | レイヤーのフィラーを取得または設定します。 |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | レイヤーフラグを取得または設定します。<br/>            ビット 0 = 透過保護;<br/>            ビット 1 = 可視;<br/>            ビット 2 = 旧式;<br/>            ビット 3 = Photoshop 5.0 以降では 1、ビット 4 に有用な情報があるかを示す;<br/>            ビット 4 = ドキュメントの外観に関係しないピクセルデータ。 |
| has_alpha | bool | r | このインスタンスがアルファを持つかどうかを示す値を取得します。 |
| has_background_color | bool | r/w | 画像に背景色があるかどうかを示す値を取得または設定します。 |
| has_transparent_color | bool | r/w | 画像に透明色があるかどうかを示す値を取得します。 |
| 高さ | int | r | 画像の高さを取得します。 |
| horizontal_resolution | double | r/w | [RasterImage](/psd/python-net/aspose.psd/rasterimage/) の水平解像度（インチあたりピクセル数）を取得または設定します。 |
| image_opacity | float | r | この画像の不透明度を取得します。 |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 割り込みモニターを取得または設定します。 |
| is_cached | bool | r | 画像データが現在キャッシュされているかどうかを示す値を取得します。 |
| is_raw_data_available | bool | r | 生データのロードがサポートされているかどうかを示す値を取得します。 |
| is_visible | bool | r/w | レイヤーが表示されているかどうかを示す値を取得または設定します |
| is_visible_in_group | bool | r | このインスタンスがグループ内で表示されているかどうかを示す値を取得します（レイヤーがグループに属していない場合はルートグループを意味します）。 |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | レイヤーのブレンド範囲データを取得または設定します。 |
| layer_creation_date_time | datetime | r/w | レイヤーの作成日時を取得または設定します。 |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | レイヤーマスクデータを取得または設定します。 |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | レイヤーオプションを取得します。 |
| 左 | int | r/w | 左側のレイヤー位置を取得または設定します。 |
| 長さを取得または設定します。 | int | r | レイヤー全体の長さ（バイト単位）を取得します。 |
| name | string | r/w | レイヤー名を取得または設定します。 |
| opacity | byte | r/w | レイヤーの不透明度を取得または設定します。0 = 透明、255 = 不透明。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | カラーパレットを取得または設定します。ピクセルが直接表現されている場合、カラーパレットは使用されません。 |
| premultiply_components | bool | r/w | 画像コンポーネントを事前乗算する必要があるかどうかを示す値を取得または設定します。 |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | カスタムカラーコンバータを取得または設定します |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | 生データ形式を取得します。 |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | 現在の生データ設定を取得します。これらの設定を使用する場合、データは変換なしでロードされることに注意してください。 |
| raw_fallback_index | int | r/w | パレットインデックスが範囲外の場合に使用するフォールバックインデックスを取得または設定します |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | インデックスカラーコンバータを取得または設定します |
| raw_line_size | int | r | 生ラインサイズ（バイト単位）を取得します。 |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | レイヤーリソースを取得または設定します。 |
| 右 | int | r/w | 右側のレイヤー位置を取得または設定します。 |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | レイヤーリストの装飾シートカラーのハイライトを取得または設定します |
| size | [Size](/psd/python-net/aspose.psd/size) | r | オブジェクトのサイズを取得します。 |
| top | int | r/w | 上部のレイヤー位置を取得または設定します。 |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 画像の透明色を取得します。 |
| update_xmp_data | bool | r/w | XMP メタデータを更新するかどうかを示す値を取得または設定します。 |
| use_palette | bool | r | 画像パレットが使用されているかどうかを示す値を取得します。 |
| use_raw_data | bool | r/w | 生データロードが利用可能な場合に生データロードを使用するかどうかを示す値を取得または設定します。 |
| vertical_resolution | double | r/w | この [RasterImage](/psd/python-net/aspose.psd/rasterimage/) の垂直解像度（インチあたりピクセル数）を取得または設定します。 |
| width | int | r | 画像の幅を取得します。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP メタデータを取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | マスクを現在のレイヤーに追加します。 |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | 画像の明るさを調整します。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | 画像のコントラスト調整 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | 画像のガンマ補正。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | 画像のガンマ補正。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | 事前定義された閾値による画像の二値化 |
| binarize_otsu() | 大津の閾値法による画像の二値化 |
| cache_data() | データをキャッシュし、基になる [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) から追加のデータ読み込みが行われないことを保証します。 |
| [can_load(file_path)](#can_load_file_path_9) | 指定されたファイルパスから画像をロードできるかどうかを判定します。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | 指定されたファイルパスから画像をロードできるかどうか、オプションで指定されたオープンオプションを使用して判定します。 |
| [can_load(stream)](#can_load_stream_11) | 指定されたストリームから画像をロードできるかどうかを判定します。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | 指定されたストリームから画像をロードできるかどうか、オプションで指定された <paramref name="loadOptions" /> を使用して判定します。 |
| [can_save(options)](#can_save_options_13) | 渡された保存オプションで表される指定されたファイル形式に画像を保存できるかどうかを判定します。 |
| [create(image_options, width, height)](#create_image_options_width_height_14) | 指定された作成オプションを使用して新しい画像を作成します。 |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | 画像のトリミング。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | 現在の画像にディザリングを実行します。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | 現在の画像にディザリングを実行します。 |
| [draw_image(location, image)](#draw_image_location_image_18) | レイヤー上に画像を描画します。 |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | 画像の 32 ビット ARGB ピクセルを取得します。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | デフォルトの 32 ビット ARGB ピクセル配列を取得します。 |
| [get_default_options(args)](#get_default_options_args_21) | デフォルトのオプションを取得します。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | 部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | 部分ピクセルローダーを使用してデフォルトの生データ配列を取得します。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | デフォルトの生データ配列を取得します。 |
| [get_file_format(file_path)](#get_file_format_file_path_25) | ファイル形式を取得します。 |
| [get_file_format(stream)](#get_file_format_stream_26) | ファイル形式を取得します。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | 現在の画像に適合する矩形を取得します。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | 現在の画像に適合する矩形を取得します。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | リソース画像が最後に変更された日時を取得します。 |
| [get_original_options()](#get_original_options__30) | 元のファイル設定に基づくオプションを取得します。<br/>これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。<br/>例えば、1ビット/ピクセルの白黒PNG画像を読み込み、[DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) メソッドで保存すると、8ビット/ピクセルのPNG画像が出力されます。<br/>これを回避し、1ビット/ピクセルのPNG画像として保存するには、このメソッドで対応する保存オプションを取得し、[Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) メソッドの第2パラメータとして渡します。 |
| [get_pixel(x, y)](#get_pixel_x_y_31) | 画像のピクセルを取得します。<br/>パフォーマンス警告: すべての画像ピクセルを反復処理するためにこのメソッドの使用は避けてください。パフォーマンスに重大な影響を与える可能性があります。<br/>より効率的なピクセル操作のためには、`LoadArgb32Pixels` メソッドを使用してピクセル配列全体を一度に取得してください。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | 比例した高さを取得します。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | 比例した幅を取得します。 |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | 画像をグレースケール表現に変換します |
| [load(file_path)](#load_file_path_35) | 指定されたファイルから新しい画像をロードします。 |
| [load(file_path, load_options)](#load_file_path_load_options_36) | 指定されたファイルから新しい画像をロードします。 |
| [load(stream)](#load_stream_37) | 指定されたストリームから新しい画像をロードします。 |
| [load(stream, load_options)](#load_stream_load_options_38) | 指定されたストリームから新しい画像をロードします。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | 32ビット ARGB ピクセルをロードします。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | 64ビット ARGB ピクセルをロードします。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | CMYK 形式のピクセルをロードします。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | CMYK 形式のピクセルをロードします。<br/>このメソッドは非推奨です。より効果的な [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) メソッドを使用してください。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | 32ビット ARGB ピクセルを部分的に（ブロック単位で）ロードします。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | パック単位で部分的にピクセルをロードします。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | ピクセルをロードします。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | 生データをロードします。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | 生データをロードします。 |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | 指定されたレイヤーにレイヤーをマージします |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | 指定されたスキャンラインインデックスで全スキャンラインを読み取ります。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | 指定されたスキャンラインインデックスで全スキャンラインを読み取ります。 |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | 画像のサイズを変更します。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | 画像のサイズを変更します。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | 画像のサイズを変更します。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | 高さを比例的にリサイズします。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | 高さを比例的にリサイズします。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | 高さを比例的にリサイズします。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | 幅を比例的にリサイズします。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | 幅を比例的にリサイズします。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | 幅を比例的にリサイズします。 |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | 画像を中心を基点に回転させます。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | 画像を回転、反転、または回転と反転を行います。 |
| save() | 画像データを基になるストリームに保存します。 |
| [save(file_path)](#save_file_path_62) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, options)](#save_file_path_options_63) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | 保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(file_path, over_write)](#save_file_path_over_write_65) | オブジェクトのデータを指定されたファイル位置に保存します。 |
| [save(stream)](#save_stream_66) | オブジェクトのデータを指定されたストリームに保存します。 |
| [save(stream, options_base)](#save_stream_options_base_67) | 保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | 保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | 32ビット ARGB ピクセルを保存します。 |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | ピクセルを保存します（形式固有のメソッド）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | 生データを保存します。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | 指定された位置に画像の 32 ビット ARGB ピクセルを設定します。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | 画像のパレットを設定します。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | 指定された位置に画像ピクセルを設定します。 |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | 現在のレイヤーの浅いコピーを作成します。<br/>            説明については <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> を参照してください。 |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | 指定されたスキャンラインインデックスに全スキャンラインを書き込みます。 |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。遅延初期化のためのコンストラクタです。

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

バイト配列から新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | レイヤーの境界です。 |
| red_bytes | byte | 赤バイトです。 |
| green_bytes | byte | 緑バイトです。 |
| blue_bytes | byte | 青バイトです。 |
| name | string | レイヤー名です。 |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 画像。 |
| dispose_image | bool | <c>true</c> に設定された場合、[画像を破棄]。 |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

新しい [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像ストリームです。 |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

マスクを現在のレイヤーに追加します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | レイヤーマスクです。 |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

画像の明るさを調整します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 明るさを取得または設定します。<br/>            推奨範囲 1 - 1.5<br/>            デフォルト値 = 1.15 | int | 明るさの値です。 |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

画像のコントラスト調整

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| コントラスト | float | コントラスト値（範囲 [-100; 100]） |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

画像のガンマ補正。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ガンマ | float | 赤、緑、青チャンネルの係数用ガンマ |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brightness_difference | double | ピクセルと、そのピクセルを中心とした s x s ウィンドウ内のピクセルの平均との明るさの差。 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley の適応的閾値アルゴリズム（積分画像閾値法）を使用した画像の二値化

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| brightness_difference | double | ピクセルと、そのピクセルを中心とした s x s ウィンドウ内のピクセルの平均との明るさの差。 |
| window_size | int | このピクセルを中心とした s x s ウィンドウのサイズ |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

事前定義された閾値による画像の二値化

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| しきい値 | byte | しきい値。ピクセルの対応するグレイ値がしきい値より大きい場合、255 の値が割り当てられ、そうでなければ 0 が割り当てられます。 |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


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


### Method: can_load(stream)  [static] {#can_load_stream_11}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


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


### Method: can_save(options) {#can_save_options_13}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


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


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

画像のトリミング。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

現在の画像にディザリングを実行します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | ディザリング手法。 |
| bits_count | int | ディザリングの最終ビット数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


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

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

レイヤー上に画像を描画します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | 位置。 |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | 画像。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


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


### Method: get_default_options(args) {#get_default_options_args_21}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

部分ピクセルローダーを使用してデフォルトのピクセル配列を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを取得する矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分的なピクセルローダー。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


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


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

元のファイル設定に基づくオプションを取得します。<br/>これにより、元の画像のビット深度やその他のパラメータを変更せずに保持できます。<br/>例えば、1ビット/ピクセルの白黒PNG画像を読み込み、[DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) メソッドで保存すると、8ビット/ピクセルのPNG画像が出力されます。<br/>これを回避し、1ビット/ピクセルのPNG画像として保存するには、このメソッドで対応する保存オプションを取得し、[Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) メソッドの第2パラメータとして渡します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 元のファイル設定に基づくオプション。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| タイプ | 説明 |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32ビット ARGB ピクセルを部分的に（ブロック単位で）ロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを読み込む矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 部分的なピクセルローダー。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

パック単位で部分的にピクセルをロードします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 希望する矩形。 |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | ピクセルローダー。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


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

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

指定されたレイヤーにレイヤーをマージします

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | マージ先のレイヤー。 |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

画像のサイズを変更します。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| new_height | int | 新しい高さ。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズのタイプ。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

高さを比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_height | int | 新しい高さ。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

幅を比例的にリサイズします。デフォルトの [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) が使用されます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

幅を比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | リサイズのタイプ。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

幅を比例的にリサイズします。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| new_width | int | 新しい幅。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 画像リサイズ設定。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

画像を回転、反転、または回転と反転を行います。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 回転・フリップのタイプ。 |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

保存オプションに従って、指定されたファイル形式でオブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | ファイルパス。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | オプション。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 対象画像の境界矩形。空の矩形を設定するとソースの境界が使用されます。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

オブジェクトのデータを指定されたファイル位置に保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | string | オブジェクトのデータを保存するファイルパス。 |
| over_write | bool | もし <c>true</c> に設定するとファイル内容を上書きし、そうでなければ追記が行われます。 |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

オブジェクトのデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | オブジェクトのデータを保存するストリーム。 |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

保存オプションに従って、指定されたファイル形式で画像のデータを指定されたストリームに保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像のデータを保存するストリーム。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存オプション。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32ビット ARGB ピクセルを保存します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを保存する矩形。 |
| pixels | int | 32ビット ARGB ピクセル配列。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

ピクセルを保存します（形式固有のメソッド）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | ピクセルを保存する矩形。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32ビット ARGB ピクセル配列。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

画像のパレットを設定します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 設定するパレット。 |
| update_colors | bool | <c>true</c> に設定された場合、色は新しいパレットに従って更新されます。そうでない場合、カラーインデックスは変更されません。変更されないインデックスは、対応するパレットエントリがない場合、画像の読み込み時にクラッシュする可能性があります。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


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

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

現在のレイヤーの浅いコピーを作成します。<br/>            説明については <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> を参照してください。

**Returns**

| タイプ | 説明 |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | 現在の Layer の浅いコピーです。 |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| タイプ | 説明 |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

指定されたスキャンラインインデックスに全スキャンラインを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scan_line_index | int | 走査ラインのゼロベースインデックス。 |
| argb_32_pixels | int | 書き込む 32 ビット ARGB カラー配列です。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

指定されたスキャンラインインデックスに全スキャンラインを書き込みます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scan_line_index | int | 走査ラインのゼロベースインデックス。 |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 書き込むピクセルカラー配列です。 |

