---
title: "Kelas PsdImage"
type: docs
weight: 1760
url: /id/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur) dengan parameter konstruktor. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari gambar raster yang ada (bukan gambar psd) dengan mode warna RGB dengan 4 saluran, 8 bit per saluran, dan tanpa kompresi. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari gambar raster yang ada (bukan gambar psd) dengan parameter konstruktor. |
| [PsdImage(stream)](#PsdImage_stream_5) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran) dengan parameter konstruktor. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dengan lebar dan tinggi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dengan lebar, tinggi, palet, mode warna, jumlah saluran dan panjang bit saluran serta parameter mode kompresi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | Versi PSD default. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Mendapatkan atau mengatur lapisan aktif. |
| auto_adjust_palette | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| bits_per_channel | int | r | Mendapatkan bit per saluran. |
| bits_per_pixel | int | r | Mendapatkan jumlah bit per piksel gambar. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Mendapatkan batas objek. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| channels_count | int | r | Mendapatkan jumlah saluran PSD. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Mendapatkan atau mengatur profil warna CMYK untuk gambar PSD CMYK. Harus dipasangkan dengan RgbColorProfile untuk konversi warna yang benar. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Mendapatkan atau mengatur mode warna. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Mendapatkan metode kompresi. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Mendapatkan kontainer [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Mendapatkan aliran data objek. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan nilai format file |
| global_angle | int | r/w | Mendapatkan atau mengatur sudut global. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Mendapatkan info masker lapisan global. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Mendapatkan atau mengatur sumber daya lapisan global. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Mendapatkan atau mengatur profil warna GRAY (monokrom) untuk gambar PSD Grayscale. |
| has_alpha | bool | r | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| memiliki_warna_latar | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| has_transparency_data | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah saluran alfa pertama berisi data transparansi untuk hasil gabungan saat menentukan data lapisan. |
| memiliki_warna_transparan | bool | r/w | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| tinggi | int | r | Mendapatkan tinggi gambar. |
| horizontal_resolution | double | r/w | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| opasitas_gambar | float | r | Mendapatkan opasitas gambar ini. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | Mendapatkan atau mengatur sumber daya gambar PSD. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Mendapatkan atau mengatur monitor interupsi. |
| tersimpan_di_cache | bool | r | Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache. |
| is_flatten | bool | r | Mendapatkan nilai yang menunjukkan apakah gambar PSD telah diratakan. |
| data_mentah_tersedia | bool | r | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah didukung. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Mendapatkan atau mengatur lapisan PSD. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Mendapatkan manajer lapisan tertaut. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| komponen_premultiplikasi | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Mendapatkan atau mengatur konverter warna khusus |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Mendapatkan format data mentah. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Mendapatkan pengaturan data mentah saat ini. Catatan: saat menggunakan pengaturan ini, data dimuat tanpa konversi. |
| indeks_fallback_mentah | int | r/w | Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Mendapatkan atau mengatur konverter warna terindeks |
| ukuran_garis_mentah | int | r | Mendapatkan ukuran baris mentah dalam byte. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Mendapatkan atau mengatur profil warna RGB untuk gambar PSD CMYK. Harus dipasangkan dengan CmykColorProfile untuk konversi warna yang benar. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Mendapatkan ukuran objek. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Mendapatkan penyedia objek pintar. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Mendapatkan [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan warna transparan gambar. |
| update_xmp_data | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui. |
| use_palette | bool | r | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| use_raw_data | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah harus menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| version | int | r/w | Mendapatkan atau mengatur versi. |
| vertical_resolution | double | r/w | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| width | int | r | Mendapatkan lebar gambar. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Menambahkan lapisan penyesuaian hitam putih. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Menambahkan lapisan penyesuaian kecerahan/kontras. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Menambahkan lapisan penyesuaian pencampur saluran dengan parameter default |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Menambahkan lapisan penyesuaian keseimbangan warna. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Menambahkan lapisan penyesuaian kurva. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Menambahkan lapisan penyesuaian eksposur. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | Menambahkan lapisan Penyesuaian GradientMap. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Menambahkan lapisan penyesuaian hue/saturasi. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Menambahkan lapisan penyesuaian invert. |
| [add_layer(layer)](#add_layer_layer_10) | Menambahkan lapisan. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Menambahkan grup lapisan. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Menambahkan lapisan penyesuaian Levels. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | Menambahkan lapisan PhotoFilter. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Menambahkan lapisan Penyesuaian Posterize. |
| [add_regular_layer()](#add_regular_layer__15) | Menambahkan lapisan reguler baru. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Menambahkan lapisan penyesuaian warna selektif. |
| [add_shape_layer()](#add_shape_layer__17) | Tambahkan lapisan Bentuk kosong.<br/>            Tanpa jalur. Mereka harus ditambahkan ke lapisan bentuk sebelum disimpan. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Menambahkan lapisan Teks baru. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Menambahkan lapisan penyesuaian Threshold. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Menambahkan lapisan penyesuaian Vibrance. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Penyesuaian kecerahan untuk gambar. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Kontras gambar |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Koreksi gamma pada gambar. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Koreksi gamma pada gambar. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Binarisasi gambar dengan ambang batas yang telah ditentukan |
| binarize_otsu() | Binarisasi gambar dengan thresholding Otsu |
| cache_data() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) yang mendasari. |
| [can_load(file_path)](#can_load_file_path_28) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan opsi buka yang ditentukan. |
| [can_load(stream)](#can_load_stream_30) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan <paramref name="loadOptions" /> yang ditentukan. |
| [can_save(options)](#can_save_options_32) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi simpan yang diberikan. |
| [convert(new_options)](#convert_new_options_33) | Mengonversi format gambar ini ke format yang ditentukan dalam opsi. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Membuat gambar baru menggunakan opsi pembuatan yang ditentukan. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Memotong gambar. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Melakukan dithering pada gambar saat ini. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Melakukan dithering pada gambar saat ini. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Menyaring persegi panjang yang ditentukan. |
| flatten_image() | Menyatukan semua lapisan. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | Mendapatkan piksel ARGB 32-bit gambar. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Mendapatkan array piksel ARGB 32-bit default. |
| [get_default_options(args)](#get_default_options_args_41) | Mendapatkan opsi default. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Mendapatkan array piksel default menggunakan pemuat piksel parsial. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Mendapatkan array data mentah default menggunakan pemuat piksel parsial. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Mendapatkan array data mentah default. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Mendapatkan format file. |
| [get_file_format(stream)](#get_file_format_stream_46) | Mendapatkan format file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Mendapatkan tanggal dan waktu gambar sumber terakhir dimodifikasi. |
| [get_original_options()](#get_original_options__50) | Mendapatkan opsi berdasarkan pengaturan file asli.<br/>            Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah.<br/>            Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metode, gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan.<br/>            Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metode sebagai parameter kedua. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Mendapatkan satu piksel gambar.<br/>            Peringatan Kinerja: Hindari menggunakan metode ini untuk mengiterasi semua piksel gambar karena dapat menyebabkan masalah kinerja yang signifikan.<br/>            Untuk manipulasi piksel yang lebih efisien, gunakan metode `LoadArgb32Pixels` untuk mengambil seluruh array piksel sekaligus. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Mendapatkan tinggi proporsional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Mendapatkan lebar proporsional. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Transformasi gambar menjadi representasi skala abu-abu |
| [load(file_path)](#load_file_path_55) | Memuat gambar baru dari file yang ditentukan. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Memuat gambar baru dari file yang ditentukan. |
| [load(stream)](#load_stream_57) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(stream, load_options)](#load_stream_load_options_58) | Memuat gambar baru dari aliran yang ditentukan. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Memuat piksel ARGB 32-bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Memuat piksel ARGB 64-bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Memuat piksel dalam format CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Memuat piksel dalam format CMYK.<br/>            Metode ini sudah usang. Silakan gunakan metode yang lebih efektif yaitu [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Memuat piksel ARGB 32-bit secara parsial (per blok). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Memuat piksel secara parsial per paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Memuat piksel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Memuat data mentah. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Memuat data mentah. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Menggabungkan lapisan. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.<br/>            Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.<br/>            Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Mengubah ukuran gambar. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Mengubah ukuran gambar. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Mengubah ukuran gambar. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Mengubah ukuran tinggi secara proporsional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Mengubah ukuran tinggi secara proporsional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Mengubah ukuran tinggi secara proporsional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Mengubah ukuran lebar secara proporsional. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Mengubah ukuran lebar secara proporsional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Mengubah ukuran lebar secara proporsional. |
| [rotate(angle)](#rotate_angle_84) | Memutar gambar di sekitar pusat. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Memutar gambar di sekitar pusat. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Memutar, membalik, atau memutar dan membalik gambar. |
| save() | Menyimpan data gambar ke aliran dasar. |
| [save(file_path)](#save_file_path_87) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(file_path, options)](#save_file_path_options_88) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(stream)](#save_stream_91) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(stream, options_base)](#save_stream_options_base_92) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | Menyimpan piksel ARGB 32-bit. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Menyimpan piksel (metode khusus format). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Menyimpan data mentah. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Menetapkan piksel ARGB 32-bit gambar untuk posisi yang ditentukan. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Menetapkan palet gambar. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Menetapkan piksel gambar untuk posisi yang ditentukan. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Mengatur resolusi untuk [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur untuk memuat data piksel dan palet serta menginisialisasinya. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam jalur) dengan parameter konstruktor.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur untuk memuat data piksel dan palet serta menginisialisasinya. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Mode warna. |
| channel_bit_depth | short | Kedalaman bit PSD per saluran. |
| saluran | short | Jumlah saluran PSD. |
| psd_version | int | Versi PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kompresi yang akan digunakan. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari gambar raster yang ada (bukan gambar psd) dengan mode warna RGB dengan 4 saluran, 8 bit per saluran, dan tanpa kompresi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar untuk memuat data piksel dan palet darinya serta menginisialisasi. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari gambar raster yang ada (bukan gambar psd) dengan parameter konstruktor.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar untuk memuat data piksel dan palet darinya serta menginisialisasi. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Mode warna. |
| channel_bit_depth | short | Kedalaman bit PSD per saluran. |
| saluran | short | Jumlah saluran PSD. |
| psd_version | int | Versi PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kompresi yang akan digunakan. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran). Digunakan untuk menginisialisasi gambar psd dengan parameter default - Mode warna - rgb, 4 saluran, 8 bit per saluran, Kompresi - Raw.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk memuat data piksel dan palet darinya serta menginisialisasi. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dari jalur yang ditentukan dari gambar raster (bukan gambar psd dalam aliran) dengan parameter konstruktor.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk memuat data piksel dan palet darinya serta menginisialisasi. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Mode warna. |
| channel_bit_depth | short | Kedalaman bit PSD per saluran. |
| saluran | short | Jumlah saluran PSD. |
| psd_version | int | Versi PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kompresi yang akan digunakan. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dengan lebar dan tinggi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Lebar gambar. |
| tinggi | int | Tinggi gambar. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Menginisialisasi instance baru dari kelas [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dengan lebar, tinggi, palet, mode warna, jumlah saluran dan panjang bit saluran serta parameter mode kompresi yang ditentukan. Digunakan untuk menginisialisasi gambar psd kosong.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Lebar gambar. |
| tinggi | int | Tinggi gambar. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet warna. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Mode warna. |
| channel_bit_depth | short | Kedalaman bit PSD per saluran. |
| saluran | short | Jumlah saluran PSD. |
| psd_version | int | Versi PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kompresi yang akan digunakan. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Menambahkan lapisan penyesuaian hitam putih.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | Lapisan penyesuaian hitam putih yang dibuat. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Menambahkan lapisan penyesuaian kecerahan/kontras.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kecerahan | int | Kecerahan. |
| kontras | int | Kontras. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Lapisan kecerahan/kontras yang dibuat |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Menambahkan lapisan penyesuaian pencampur saluran dengan parameter default

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Lapisan Pencampur Saluran yang ditambahkan |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Menambahkan lapisan penyesuaian keseimbangan warna.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Lapisan keseimbangan warna yang baru dibuat. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Menambahkan lapisan penyesuaian kurva.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Lapisan [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) yang dibuat |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Menambahkan lapisan penyesuaian eksposur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| eksposur | float | Eksposur. |
| offset | float | Offset. |
| koreksi_gamma | float | Koreksi gamma. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Lapisan Penyesuaian Eksposur yang dibuat |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

Menambahkan lapisan Penyesuaian GradientMap.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | Instansi GradientMap. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Menambahkan lapisan penyesuaian hue/saturasi.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Lapisan hue/saturasi yang baru dibuat. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Menambahkan lapisan penyesuaian invert.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | Lapisan invert yang dibuat |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Menambahkan lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Menambahkan grup lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| group_name | string | Nama grup. |
| index | int | Indeks lapisan yang akan disisipkan setelahnya. |
| start_behaviour | bool | jika diatur ke <c>true</c> [start behaviour] maka grup akan berada dalam keadaan terbuka saat memulai, jika tidak dalam keadaan diminimalkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Membuka lapisan grup |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Menambahkan lapisan penyesuaian Levels.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Lapisan Levels yang baru dibuat |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

Menambahkan lapisan PhotoFilter.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Warna. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Lapisan PhotoFilter yang dibuat |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Menambahkan lapisan Penyesuaian Posterize.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | Instansi PosterizeLayer. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Menambahkan lapisan reguler baru.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan reguler yang dibuat. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Menambahkan lapisan penyesuaian warna selektif.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | Lapisan penyesuaian warna selektif yang dibuat. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Tambahkan lapisan Bentuk kosong.<br/>            Tanpa jalur. Mereka harus ditambahkan ke lapisan bentuk sebelum disimpan.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Instansi ShapeLayer. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Menambahkan lapisan Teks baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | string | Teks lapisan. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Lapisan teks yang dibuat. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Menambahkan lapisan penyesuaian Threshold.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | Lapisan penyesuaian Threshold yang dibuat. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Menambahkan lapisan penyesuaian Vibrance.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Lapisan Vibrance yang baru dibuat. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Penyesuaian kecerahan untuk gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kecerahan | int | Nilai kecerahan. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Kontras gambar

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kontras | float | Nilai kontras (dalam rentang [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Koreksi gamma pada gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| gamma | float | Koefisien gamma untuk saluran merah, hijau, dan biru |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Koreksi gamma pada gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| gamma_red | float | Koefisien gamma untuk saluran merah |
| gamma_green | float | Koefisien gamma untuk saluran hijau |
| gamma_blue | float | Koefisien gamma untuk saluran biru |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brightness_difference | double | Selisih kecerahan antara piksel dan rata-rata jendela s x s piksel yang berpusat di sekitar piksel ini. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brightness_difference | double | Selisih kecerahan antara piksel dan rata-rata jendela s x s piksel yang berpusat di sekitar piksel ini. |
| window_size | int | Ukuran jendela s x s piksel yang berpusat di sekitar piksel ini |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Binarisasi gambar dengan ambang batas yang telah ditentukan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| threshold | byte | Nilai ambang. Jika nilai abu-abu yang bersesuaian dari sebuah piksel lebih besar dari ambang, nilai 255 akan diberikan padanya, jika tidak 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


```
 can_load(file_path) 
```

Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika gambar dapat dimuat dari berkas yang ditentukan; sebaliknya, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


```
 can_load(file_path, load_options) 
```

Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan opsi buka yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika gambar dapat dimuat dari berkas yang ditentukan; sebaliknya, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_30}


```
 can_load(stream) 
```

Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk dimuat dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika gambar dapat dimuat dari aliran yang ditentukan; sebaliknya, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


```
 can_load(stream, load_options) 
```

Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan <paramref name="loadOptions" /> yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk dimuat dari. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika gambar dapat dimuat dari aliran yang ditentukan; sebaliknya, <c>false</c>. |


### Method: can_save(options) {#can_save_options_32}


```
 can_save(options) 
```

Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi simpan yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi penyimpanan yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika gambar dapat disimpan ke format berkas yang ditentukan yang diwakili oleh opsi penyimpanan yang diberikan; sebaliknya, <c>false</c>. |


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Mengonversi format gambar ini ke format yang ditentukan dalam opsi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | Opsi baru. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


```
 create(image_options, width, height) 
```

Membuat gambar baru menggunakan opsi pembuatan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi gambar. |
| width | int | Lebar. |
| tinggi | int | Tinggi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Gambar yang baru dibuat. |


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Memotong gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Melakukan dithering pada gambar saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Metode dithering. |
| bits_count | int | Jumlah bit akhir untuk dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Melakukan dithering pada gambar saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Metode dithering. |
| bits_count | int | Jumlah bit akhir untuk dithering. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet khusus untuk dithering. |

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Menyaring persegi panjang yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | Opsi. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


```
 get_argb_32_pixel(x, y) 
```

Mendapatkan piksel ARGB 32-bit gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Piksel ARGB 32-bit untuk lokasi yang ditentukan. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


```
 get_default_argb_32_pixels(rectangle) 
```

Mendapatkan array piksel ARGB 32-bit default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Array piksel default. |


### Method: get_default_options(args) {#get_default_options_args_41}


```
 get_default_options(args) 
```

Mendapatkan opsi default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| args | object | Argumen. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi default |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Mendapatkan array piksel default menggunakan pemuat piksel parsial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Pemuat piksel parsial. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Mendapatkan array data mentah default menggunakan pemuat piksel parsial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Pemuat data mentah parsial. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Pengaturan data mentah. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Mendapatkan array data mentah default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan data mentah. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Pengaturan data mentah. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Array data mentah default. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


```
 get_file_format(file_path) 
```

Mendapatkan format file.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Format file yang ditentukan. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


```
 get_file_format(stream) 
```

Mendapatkan format file.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Format file yang ditentukan. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Mendapatkan persegi panjang yang sesuai dengan gambar saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan persegi panjang yang cocok. |
| pixels | int | Piksel ARGB 32-bit. |
| width | int | Lebar objek. |
| tinggi | int | Tinggi objek. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang yang cocok atau pengecualian jika tidak dapat menemukan persegi panjang yang cocok. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Mendapatkan persegi panjang yang sesuai dengan gambar saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan persegi panjang yang cocok. |
| width | int | Lebar objek. |
| tinggi | int | Tinggi objek. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang yang cocok atau pengecualian jika tidak dapat menemukan persegi panjang yang cocok. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

Mendapatkan tanggal dan waktu gambar sumber terakhir dimodifikasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| use_default | bool | jika disetel ke <c>true</c> menggunakan informasi dari FileInfo sebagai nilai default. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| datetime | Tanggal dan waktu gambar sumber terakhir dimodifikasi. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Mendapatkan opsi berdasarkan pengaturan file asli.<br/>            Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah.<br/>            Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metode, gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan.<br/>            Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metode sebagai parameter kedua.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi berdasarkan pengaturan file asli. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


```
 get_pixel(x, y) 
```

Mendapatkan satu piksel gambar.<br/>            Peringatan Kinerja: Hindari menggunakan metode ini untuk mengiterasi semua piksel gambar karena dapat menyebabkan masalah kinerja yang signifikan.<br/>            Untuk manipulasi piksel yang lebih efisien, gunakan metode `LoadArgb32Pixels` untuk mengambil seluruh array piksel sekaligus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Warna piksel untuk lokasi yang ditentukan. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


```
 get_proportional_height(width, height, new_width) 
```

Mendapatkan tinggi proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Lebar. |
| tinggi | int | Tinggi. |
| new_width | int | Lebar baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Tinggi proporsional. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


```
 get_proportional_width(width, height, new_height) 
```

Mendapatkan lebar proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | int | Lebar. |
| tinggi | int | Tinggi. |
| new_height | int | Tinggi baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Lebar proporsional. |


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

Memuat gambar baru dari file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk memuat gambar dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Gambar yang dimuat. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

Memuat gambar baru dari file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk memuat gambar dari. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Gambar yang dimuat. |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Stream untuk memuat gambar dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Gambar yang dimuat. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

Memuat gambar baru dari aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Stream untuk memuat gambar dari. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Opsi pemuatan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Gambar yang dimuat. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

Memuat piksel ARGB 32-bit.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Array piksel ARGB 32-bit yang dimuat. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

Memuat piksel ARGB 64-bit.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| long | Array piksel ARGB 64-bit yang dimuat. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

Memuat piksel dalam format CMYK.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Piksel CMYK yang dimuat disajikan sebagai nilai integer 32-bit. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

Memuat piksel dalam format CMYK.<br/>            Metode ini sudah usang. Silakan gunakan metode yang lebih efektif yaitu [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Array piksel CMYK yang dimuat. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Memuat piksel ARGB 32-bit secara parsial (per blok).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Pemuat piksel parsial. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Memuat piksel secara parsial per paket.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang yang diinginkan. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Pemuat piksel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


```
 load_pixels(rectangle) 
```

Memuat piksel.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Array piksel yang dimuat. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Memuat data mentah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat data mentah dari. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Batas gambar tujuan. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Pengaturan data mentah yang akan digunakan untuk data yang dimuat. Catatan: jika data tidak dalam format yang ditentukan maka konversi data akan dilakukan. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Pemuat data mentah. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Memuat data mentah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk memuat data mentah dari. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Pengaturan data mentah yang akan digunakan untuk data yang dimuat. Catatan: jika data tidak dalam format yang ditentukan maka konversi data akan dilakukan. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Pemuat data mentah. |

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Menggabungkan lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan bawah. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan atas. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan bawah setelah penggabungan |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


```
 read_argb_32_scan_line(scan_line_index) 
```

Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scan_line_index | int | Indeks berbasis nol dari baris pemindaian. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Array nilai warna ARGB 32-bit baris pemindaian. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


```
 read_scan_line(scan_line_index) 
```

Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scan_line_index | int | Indeks berbasis nol dari baris pemindaian. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Array nilai warna piksel baris pemindaian. |


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | Perbedaan yang diizinkan pada warna lama untuk dapat memperlebar nada warna yang diganti. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Mengganti satu warna dengan warna lain dengan perbedaan yang diizinkan dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| old_color_argb | int | Nilai ARGB warna lama yang akan diganti. |
| old_color_diff | byte | Perbedaan yang diizinkan pada warna lama untuk dapat memperlebar nada warna yang diganti. |
| new_color_argb | int | Nilai ARGB warna baru untuk menggantikan warna lama. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.<br/>            Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Mengganti semua warna non-transparan dengan warna baru dan mempertahankan nilai alfa asli untuk menyimpan tepi yang halus.<br/>            Catatan: jika Anda menggunakannya pada gambar tanpa transparansi, semua warna akan diganti dengan satu warna saja.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_argb | int | Nilai ARGB warna baru untuk menggantikan warna non-transparan. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Mengubah ukuran gambar. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| new_height | int | Tinggi baru. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


```
 resize(new_width, new_height, resize_type) 
```

Mengubah ukuran gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| new_height | int | Tinggi baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


```
 resize(new_width, new_height, settings) 
```

Mengubah ukuran gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| new_height | int | Tinggi baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran gambar. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Mengubah ukuran lebar secara proporsional. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Mengubah ukuran lebar secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Mengubah ukuran lebar secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran gambar. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Memutar gambar di sekitar pusat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi dalam derajat. Nilai positif akan memutar searah jarum jam. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


```
 rotate(angle, resize_proportionally, background_color) 
```

Memutar gambar di sekitar pusat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi dalam derajat. Nilai positif akan memutar searah jarum jam. |
| resize_proportionally | bool | jika disetel ke <c>true</c> ukuran gambar Anda akan berubah sesuai proyeksi persegi panjang yang diputar (titik sudut); dalam kasus lain dimensi tetap tidak berubah dan hanya konten internal gambar yang diputar. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Warna latar belakang. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Memutar, membalik, atau memutar dan membalik gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Jenis putar balik. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Segi empat batas gambar tujuan. Atur segi empat kosong untuk menggunakan batas sumber. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |
| over_write | bool | jika disetel ke <c>true</c> menimpa isi file, jika tidak akan menambahkan. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data objek. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data gambar. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi penyimpanan. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


```
 save(stream, options_base, bounds_rectangle) 
```

Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data gambar. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi penyimpanan. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang batas gambar tujuan. Atur persegi panjang kosong untuk menggunakan batas sumber. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Menyimpan piksel ARGB 32-bit.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| pixels | int | Array piksel ARGB 32-bit. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Menyimpan piksel (metode khusus format).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Array piksel ARGB 32-bit. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Menyimpan data mentah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| data | byte | Data mentah. |
| data_offset | int | Offset data mentah awal. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang data mentah. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Pengaturan data mentah tempat data berada. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Menetapkan piksel ARGB 32-bit gambar untuk posisi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |
| argb_32_color | int | Piksel ARGB 32-bit untuk posisi yang ditentukan. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Menetapkan palet gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet yang akan diatur. |
| update_colors | bool | jika disetel ke <c>true</c> warna akan diperbarui sesuai palet baru; sebaliknya indeks warna tetap tidak berubah. Perhatikan bahwa indeks yang tidak berubah dapat menyebabkan gambar crash saat dimuat jika beberapa indeks tidak memiliki entri palet yang sesuai. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


```
 set_pixel(x, y, color) 
```

Menetapkan piksel gambar untuk posisi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Lokasi x piksel. |
| y | int | Lokasi y piksel. |
| color | [Color](/psd/python-net/aspose.psd/color) | Warna piksel untuk posisi yang ditentukan. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Mengatur resolusi untuk [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dpi_x | double | Resolusi horizontal, dalam titik per inci, dari [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | Resolusi vertikal, dalam titik per inci, dari [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scan_line_index | int | Indeks berbasis nol dari baris pemindaian. |
| argb_32_pixels | int | Array warna ARGB 32-bit untuk ditulis. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scan_line_index | int | Indeks berbasis nol dari baris pemindaian. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Array warna piksel untuk ditulis. |

