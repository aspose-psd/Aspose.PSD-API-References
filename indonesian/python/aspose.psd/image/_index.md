---
title: "Kelas Image"
type: docs
weight: 2170
url: /id/python-net/aspose.psd/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Image

**Inheritance:** IObjectWithBounds, DataStreamSupporter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah palet disesuaikan secara otomatis. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Mendapatkan atau mengatur nilai untuk warna latar belakang. |
| bits_per_pixel | int | r | Mendapatkan jumlah bit per piksel gambar. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Mendapatkan batas gambar. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Mendapatkan kontainer [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Mendapatkan aliran data objek. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Mendapatkan nilai format file |
| memiliki_warna_latar | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah gambar memiliki warna latar belakang. |
| tinggi | int | r | Mendapatkan tinggi gambar. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Mendapatkan atau mengatur monitor interupsi. |
| tersimpan_di_cache | bool | r | Mendapatkan nilai yang menunjukkan apakah data objek saat ini di-cache dan tidak diperlukan pembacaan data. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. Palet warna tidak digunakan ketika piksel direpresentasikan secara langsung. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Mendapatkan ukuran gambar. |
| use_palette | bool | r | Mendapatkan nilai yang menunjukkan apakah palet gambar digunakan. |
| width | int | r | Mendapatkan lebar gambar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| cache_data() | Menyimpan data dalam cache dan memastikan tidak ada pemuatan data tambahan yang akan dilakukan dari [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) yang mendasari. |
| [can_load(file_path)](#can_load_file_path_1) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Menentukan apakah gambar dapat dimuat dari jalur file yang ditentukan dan secara opsional menggunakan opsi buka yang ditentukan. |
| [can_load(stream)](#can_load_stream_3) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Menentukan apakah gambar dapat dimuat dari aliran yang ditentukan dan secara opsional menggunakan <paramref name="loadOptions" /> yang ditentukan. |
| [can_save(options)](#can_save_options_5) | Menentukan apakah gambar dapat disimpan ke format file yang ditentukan yang diwakili oleh opsi simpan yang diberikan. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Membuat gambar baru menggunakan opsi pembuatan yang ditentukan. |
| [get_default_options(args)](#get_default_options_args_7) | Mendapatkan opsi default. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | Mendapatkan format file. |
| [get_file_format(stream)](#get_file_format_stream_9) | Mendapatkan format file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | Mendapatkan persegi panjang yang sesuai dengan gambar saat ini. |
| [get_original_options()](#get_original_options__12) | Mendapatkan opsi berdasarkan pengaturan file asli.<br/>            Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah.<br/>            Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metode, gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan.<br/>            Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metode sebagai parameter kedua. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | Mendapatkan tinggi proporsional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | Mendapatkan lebar proporsional. |
| [load(file_path)](#load_file_path_15) | Memuat gambar baru dari file yang ditentukan. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | Memuat gambar baru dari file yang ditentukan. |
| [load(stream)](#load_stream_17) | Memuat gambar baru dari aliran yang ditentukan. |
| [load(stream, load_options)](#load_stream_load_options_18) | Memuat gambar baru dari aliran yang ditentukan. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | Mengubah ukuran gambar. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | Mengubah ukuran gambar. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | Mengubah ukuran gambar. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | Mengubah ukuran tinggi secara proporsional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | Mengubah ukuran tinggi secara proporsional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | Mengubah ukuran tinggi secara proporsional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | Mengubah ukuran lebar secara proporsional. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | Mengubah ukuran lebar secara proporsional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | Mengubah ukuran lebar secara proporsional. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | Memutar, membalik, atau memutar dan membalik gambar. |
| save() | Menyimpan data gambar ke aliran dasar. |
| [save(file_path)](#save_file_path_29) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(file_path, options)](#save_file_path_options_30) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | Menyimpan data objek ke lokasi file yang ditentukan. |
| [save(stream)](#save_stream_33) | Menyimpan data objek ke aliran yang ditentukan. |
| [save(stream, options_base)](#save_stream_options_base_34) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | Menetapkan palet gambar. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_save(options) {#can_save_options_5}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


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


### Method: get_default_options(args) {#get_default_options_args_7}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


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


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

Mendapatkan opsi berdasarkan pengaturan file asli.<br/>            Ini dapat membantu menjaga kedalaman bit dan parameter lain dari gambar asli tetap tidak berubah.<br/>            Misalnya, jika kita memuat gambar PNG hitam-putih dengan 1 bit per piksel dan kemudian menyimpannya menggunakan<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metode, gambar PNG keluaran dengan 8-bit per piksel akan dihasilkan.<br/>            Untuk menghindarinya dan menyimpan gambar PNG dengan 1-bit per piksel, gunakan metode ini untuk mendapatkan opsi penyimpanan yang sesuai dan berikan ke<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metode sebagai parameter kedua.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi berdasarkan pengaturan file asli. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


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


### Method: load(file_path)  [static] {#load_file_path_15}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


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


### Method: load(stream)  [static] {#load_stream_17}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

Mengubah ukuran gambar. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| new_height | int | Tinggi baru. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

Mengubah ukuran tinggi secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_height | int | Tinggi baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran gambar. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

Mengubah ukuran lebar secara proporsional. Default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

Mengubah ukuran lebar secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Jenis pengubahan ukuran. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

Mengubah ukuran lebar secara proporsional.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_width | int | Lebar baru. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Pengaturan pengubahan ukuran gambar. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

Memutar, membalik, atau memutar dan membalik gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Tipe rotasi balik. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

Menyimpan data objek ke lokasi file yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur berkas. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

Menyimpan data objek ke lokasi file yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | string | Jalur file untuk menyimpan data objek. |
| over_write | bool | jika disetel ke <c>true</c> menimpa isi file, jika tidak akan menambahkan. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

Menyimpan data objek ke aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data objek. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

Menyimpan data gambar ke aliran yang ditentukan dalam format file yang ditentukan sesuai opsi penyimpanan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| aliran | _io.BufferedRandom | Aliran untuk menyimpan data gambar. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opsi penyimpanan. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

Menetapkan palet gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Palet yang akan diatur. |
| update_colors | bool | jika disetel ke <c>true</c> warna akan diperbarui sesuai palet baru; sebaliknya indeks warna tetap tidak berubah. Perhatikan bahwa indeks yang tidak berubah dapat menyebabkan gambar crash saat dimuat jika beberapa indeks tidak memiliki entri palet yang sesuai. |

