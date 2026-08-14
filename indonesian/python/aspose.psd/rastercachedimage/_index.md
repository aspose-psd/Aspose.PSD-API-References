---
title: "Kelas RasterCachedImage"
type: docs
weight: 3730
url: /id/python-net/aspose.psd/rastercachedimage/
---

**Summary:** Represents a raster image supporting raster graphics operations. This image caches pixel data when required.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterCachedImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterImage

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| bits_per_pixel | int | r | Mendapatkan jumlah bit per piksel gambar. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Mendapatkan batas objek. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Mendapatkan kontainer [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Mendapatkan aliran data objek. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan nilai format file |
| memiliki_alpha | bool | r | Mendapatkan nilai yang menunjukkan apakah instansi ini memiliki alfa. |
| memiliki_warna_latar | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| memiliki_warna_transparan | bool | r/w | Mendapatkan nilai yang menunjukkan apakah gambar memiliki warna transparan. |
| tinggi | int | r | Mendapatkan tinggi objek. |
| horizontal_resolution | double | r/w | Mendapatkan atau mengatur resolusi horizontal, dalam piksel per inci, dari [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| opasitas_gambar | float | r | Mendapatkan opasitas gambar ini. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Mendapatkan atau mengatur monitor interupsi. |
| tersimpan_di_cache | bool | r | Mendapatkan nilai yang menunjukkan apakah data gambar saat ini di-cache. |
| data_mentah_tersedia | bool | r | Mendapatkan nilai yang menunjukkan apakah pemuatan data mentah tersedia. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| komponen_premultiplikasi | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen gambar harus dipremultiplikasi. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Mendapatkan atau mengatur konverter warna khusus |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Mendapatkan format data mentah. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Mendapatkan pengaturan data mentah saat ini. Catatan: saat menggunakan pengaturan ini, data dimuat tanpa konversi. |
| indeks_fallback_mentah | int | r/w | Mendapatkan atau mengatur indeks cadangan yang digunakan ketika indeks palet di luar batas |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Mendapatkan atau mengatur konverter warna terindeks |
| ukuran_garis_mentah | int | r | Mendapatkan ukuran baris mentah dalam byte. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Mendapatkan ukuran objek. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan warna transparan gambar. |
| update_xmp_data | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah metadata XMP harus diperbarui. |
| use_palette | bool | r | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| use_raw_data | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah harus menggunakan pemuatan data mentah ketika pemuatan data mentah tersedia. |
| vertical_resolution | double | r/w | Mendapatkan atau mengatur resolusi vertikal, dalam piksel per inci, dari [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Mendapatkan lebar objek. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur metadata XMP. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Penyesuaian kecerahan untuk gambar. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Kontras gambar |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Koreksi gamma pada gambar. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Koreksi gamma pada gambar. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_5) | Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_6) | Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_7) | Binarisasi gambar dengan ambang batas yang telah ditentukan |
| binarize_otsu() | Binarisasi gambar dengan thresholding Otsu |
| cache_data() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) yang mendasari. |
| [can_load(file_path)](#can_load_file_path_8) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_9) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan opsi buka yang ditentukan. |
| [can_load(stream)](#can_load_stream_10) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan. |
| [can_load(stream, load_options)](#can_load_stream_load_options_11) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan <paramref name="loadOptions" /> yang ditentukan. |
| [can_save(options)](#can_save_options_12) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi simpan yang diberikan. |
| [create(image_options, width, height)](#create_image_options_width_height_13) | Membuat gambar baru menggunakan opsi pembuatan yang ditentukan. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_14) | Memotong gambar. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_15) | Melakukan dithering pada gambar saat ini. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_16) | Melakukan dithering pada gambar saat ini. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_17) | Mendapatkan piksel ARGB 32-bit gambar. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_18) | Mendapatkan array piksel ARGB 32-bit default. |
| [get_default_options(args)](#get_default_options_args_19) | Mendapatkan opsi default. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_20) | Mendapatkan array piksel default menggunakan pemuat piksel parsial. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21) | Mendapatkan array data mentah default menggunakan pemuat piksel parsial. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_22) | Mendapatkan array data mentah default. |
| [get_file_format(file_path)](#get_file_format_file_path_23) | Mendapatkan format file. |
| [get_file_format(stream)](#get_file_format_stream_24) | Mendapatkan format file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_25) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_26) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [get_modify_date(use_default)](#get_modify_date_use_default_27) | Mendapatkan tanggal dan waktu gambar sumber terakhir dimodifikasi. |
| [get_original_options()](#get_original_options__28) | Mendapatkan opsi berdasarkan pengaturan file asli.<br/>            Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah.<br/>            Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metode, gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan.<br/>            Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metode sebagai parameter kedua. |
| [get_pixel(x, y)](#get_pixel_x_y_29) | Mendapatkan satu piksel gambar.<br/>            Peringatan Kinerja: Hindari menggunakan metode ini untuk mengiterasi semua piksel gambar karena dapat menyebabkan masalah kinerja yang signifikan.<br/>            Untuk manipulasi piksel yang lebih efisien, gunakan metode `LoadArgb32Pixels` untuk mengambil seluruh array piksel sekaligus. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | Mendapatkan tinggi proporsional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | Mendapatkan lebar proporsional. |
| [get_skew_angle()](#get_skew_angle__32) |    |
| grayscale() | Transformasi gambar menjadi representasi skala abu-abu |
| [load(file_path)](#load_file_path_33) | Memuat gambar baru dari file yang ditentukan. |
| [load(file_path, load_options)](#load_file_path_load_options_34) | Memuat gambar baru dari file yang ditentukan. |
| [load(stream)](#load_stream_35) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(stream, load_options)](#load_stream_load_options_36) | Memuat gambar baru dari aliran yang ditentukan. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_37) | Memuat piksel ARGB 32-bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_38) | Memuat piksel ARGB 64-bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_39) | Memuat piksel dalam format CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_40) | Memuat piksel dalam format CMYK.<br/>            Metode ini sudah usang. Silakan gunakan metode yang lebih efektif yaitu [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41) | Memuat piksel ARGB 32-bit secara parsial per paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_42) | Memuat piksel secara parsial per paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_43) | Memuat piksel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44) | Memuat data mentah. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45) | Memuat data mentah. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_46) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_47) | Membaca seluruh baris pemindaian berdasarkan indeks baris pemindaian yang ditentukan. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_48) | Mengubah ukuran gambar. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_49) | Mengubah ukuran gambar. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_50) | Mengubah ukuran gambar. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_51) | Mengubah ukuran tinggi secara proporsional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_52) | Mengubah ukuran tinggi secara proporsional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_53) | Mengubah ukuran tinggi secara proporsional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_54) | Mengubah ukuran lebar secara proporsional. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_55) | Mengubah ukuran lebar secara proporsional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_56) | Mengubah ukuran lebar secara proporsional. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_57) | Memutar gambar di sekitar pusat. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_58) | Memutar, membalik, atau memutar dan membalik gambar. |
| save() | Menyimpan data gambar ke aliran dasar. |
| [save(file_path)](#save_file_path_59) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(file_path, options)](#save_file_path_options_60) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_61) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(file_path, over_write)](#save_file_path_over_write_62) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(stream)](#save_stream_63) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(stream, options_base)](#save_stream_options_base_64) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_65) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_66) | Menyimpan piksel ARGB 32-bit. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_67) | Menyimpan piksel (metode khusus format). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_68) | Menyimpan data mentah. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_69) | Menetapkan piksel ARGB 32-bit gambar untuk posisi yang ditentukan. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_70) | Menetapkan palet gambar. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_71) | Menetapkan piksel gambar untuk posisi yang ditentukan. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__72) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_74) | Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Penyesuaian kecerahan untuk gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kecerahan | int | Nilai kecerahan. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Kontras gambar

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| kontras | float | Nilai kontras (dalam rentang [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Koreksi gamma pada gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| gamma | float | Koefisien gamma untuk saluran merah, hijau, dan biru |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_5}


```
 binarize_bradley(brightness_difference) 
```

Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brightness_difference | double | Selisih kecerahan antara piksel dan rata-rata jendela s x s piksel yang berpusat di sekitar piksel ini. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_6}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisasi gambar menggunakan algoritma threshold adaptif Bradley dengan thresholding citra integral

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| brightness_difference | double | Selisih kecerahan antara piksel dan rata-rata jendela s x s piksel yang berpusat di sekitar piksel ini. |
| window_size | int | Ukuran jendela s x s piksel yang berpusat di sekitar piksel ini |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_7}


```
 binarize_fixed(threshold) 
```

Binarisasi gambar dengan ambang batas yang telah ditentukan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| threshold | byte | Nilai ambang. Jika nilai abu-abu yang bersesuaian dari sebuah piksel lebih besar dari ambang, nilai 255 akan diberikan padanya, jika tidak 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_8}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_9}


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


### Method: can_load(stream)  [static] {#can_load_stream_10}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_11}


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


### Method: can_save(options) {#can_save_options_12}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_13}


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


### Method: crop(rectangle) {#crop_rectangle_14}


```
 crop(rectangle) 
```

Memotong gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_15}


```
 dither(dithering_method, bits_count) 
```

Melakukan dithering pada gambar saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Metode dithering. |
| bits_count | int | Jumlah bit akhir untuk dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_16}


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

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_17}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_18}


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


### Method: get_default_options(args) {#get_default_options_args_19}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_20}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Mendapatkan array piksel default menggunakan pemuat piksel parsial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk mendapatkan piksel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Pemuat piksel parsial. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_22}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_25}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_26}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_27}


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


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Mendapatkan opsi berdasarkan pengaturan file asli.<br/>            Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah.<br/>            Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metode, gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan.<br/>            Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metode sebagai parameter kedua.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi berdasarkan pengaturan file asli. |


### Method: get_pixel(x, y) {#get_pixel_x_y_29}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


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


### Method: get_skew_angle() {#get_skew_angle__32}


```
 get_skew_angle() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_33}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


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


### Method: load(stream)  [static] {#load_stream_35}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_37}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_38}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_39}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_40}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Memuat piksel ARGB 32-bit secara parsial per paket.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang yang diinginkan. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Pemuat piksel ARGB 32-bit. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_42}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Memuat piksel secara parsial per paket.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang yang diinginkan. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Pemuat piksel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_43}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_46}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_47}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_48}


```
 resize(new_width, new_height) 
```

Mengubah ukuran gambar. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| new_height | int | Tinggi baru. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_49}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_50}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_51}


```
 resize_height_proportionally(new_height) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_52}


```
 resize_height_proportionally(new_height, resize_type) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_53}


```
 resize_height_proportionally(new_height, settings) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran gambar. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_54}


```
 resize_width_proportionally(new_width) 
```

Mengubah ukuran lebar secara proporsional. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_55}


```
 resize_width_proportionally(new_width, resize_type) 
```

Mengubah ukuran lebar secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_56}


```
 resize_width_proportionally(new_width, settings) 
```

Mengubah ukuran lebar secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran gambar. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_57}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_58}


```
 rotate_flip(rotate_flip_type) 
```

Memutar, membalik, atau memutar dan membalik gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Jenis putar balik. |

### Method: save(file_path) {#save_file_path_59}


```
 save(file_path) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |

### Method: save(file_path, options) {#save_file_path_options_60}


```
 save(file_path, options) 
```

Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_61}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_62}


```
 save(file_path, over_write) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |
| over_write | bool | jika disetel ke <c>true</c> menimpa isi file, jika tidak akan menambahkan. |

### Method: save(stream) {#save_stream_63}


```
 save(stream) 
```

Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data objek. |

### Method: save(stream, options_base) {#save_stream_options_base_64}


```
 save(stream, options_base) 
```

Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data gambar. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi penyimpanan. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_65}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_66}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Menyimpan piksel ARGB 32-bit.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| pixels | int | Array piksel ARGB 32-bit. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_67}


```
 save_pixels(rectangle, pixels) 
```

Menyimpan piksel (metode khusus format).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang untuk menyimpan piksel. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Array piksel ARGB 32-bit. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_68}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_69}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_70}


```
 set_palette(palette, update_colors) 
```

Menetapkan palet gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet yang akan diatur. |
| update_colors | bool | jika disetel ke <c>true</c> warna akan diperbarui sesuai palet baru; sebaliknya indeks warna tetap tidak berubah. Perhatikan bahwa indeks yang tidak berubah dapat menyebabkan gambar crash saat dimuat jika beberapa indeks tidak memiliki entri palet yang sesuai. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_71}


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

### Method: to_bitmap() {#to_bitmap__72}


```
 to_bitmap() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scan_line_index | int | Indeks berbasis nol dari baris pemindaian. |
| argb_32_pixels | int | Array warna ARGB 32-bit untuk ditulis. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_74}


```
 write_scan_line(scan_line_index, pixels) 
```

Menulis seluruh baris pemindaian ke indeks baris pemindaian yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scan_line_index | int | Indeks berbasis nol dari baris pemindaian. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Array warna piksel untuk ditulis. |

