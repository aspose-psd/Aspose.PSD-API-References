---
title: "ImageAttributes Sınıfı"
type: docs
weight: 2180
url: /tr/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | ImageAttributes sınıfının yeni bir örneğini başlatır |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| clear_brush_remap_table() | Bu [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) nesnesinin fırça renk yeniden eşleme tablosunu temizler. |
| clear_color_key() | Varsayılan kategori için renk anahtarını (şeffaflık aralığını) temizler. |
| [clear_color_key(type)](#clear_color_key_type_1) | Belirtilen kategori için renk anahtarını (şeffaflık aralığını) temizler. |
| clear_color_matrix() | Varsayılan kategori için renk ayarlama matrisini temizler. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Belirtilen kategori için renk ayarlama matrisini temizler. |
| clear_gamma() | Varsayılan kategori için gama düzeltmesini devre dışı bırakır. |
| [clear_gamma(type)](#clear_gamma_type_3) | Belirtilen kategori için gama düzeltmesini devre dışı bırakır. |
| clear_no_op() | Varsayılan kategori için NoOp ayarını temizler. |
| [clear_no_op(type)](#clear_no_op_type_4) | Belirtilen kategori için NoOp ayarını temizler. |
| clear_output_channel() | Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Belirtilen kategori için (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler. |
| clear_output_channel_color_profile() | Varsayılan kategori için çıkış kanalı renk profili ayarını temizler. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Belirtilen kategori için çıkış kanalı renk profili ayarını temizler. |
| clear_remap_table() | Varsayılan kategori için renk yeniden eşleme tablosunu temizler. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Belirtilen kategori için renk yeniden eşleme tablosunu temizler. |
| clear_threshold() | Varsayılan kategori için eşik değerini temizler. |
| [clear_threshold(type)](#clear_threshold_type_8) | Belirtilen kategori için eşik değerini temizler. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Varsayılan kategori için color key ayarlar. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Belirtilen kategori için color key (transparency range) ayarlar. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Varsayılan kategori için color-adjustment matrix ve grayscale-adjustment matrix ayarlar. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Varsayılan kategori için color-adjustment matrix ve grayscale-adjustment matrix ayarlar. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Belirtilen kategori için color-adjustment matrix ve grayscale-adjustment matrix ayarlar. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Varsayılan kategori için color-adjustment matrix ayarlar. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Varsayılan kategori için color-adjustment matrix ayarlar. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Belirtilen kategori için color-adjustment matrix ayarlar. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Varsayılan kategori için gamma değerini ayarlar. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Belirtilen kategori için gamma değerini ayarlar. |
| set_no_op() | Varsayılan kategori için color adjustment kapatır. |
| [set_no_op(type)](#set_no_op_type_20) | Belirtilen kategori için color adjustment kapatır. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Belirtilen kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Belirtilen kategori için çıkış kanalı renk profili dosyasını ayarlar. |
| [set_remap_table(map)](#set_remap_table_map_25) | Varsayılan kategori için color-remap tablosunu ayarlar. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Belirtilen kategori için color-remap tablosunu ayarlar. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Varsayılan kategori için eşik (transparency range) ayarlar. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Belirtilen kategori için eşik (transparency range) ayarlar. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Bir şekil boyunca veya şekil sınırlarında dokunun nasıl döşeneceğine karar vermek için kullanılan wrap mode'u ayarlar. Dokunun, dolduracağı şekilden daha küçük olduğunda şekli doldurmak için dokunun şekil boyunca döşenmesi sağlanır. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Bir şekil boyunca veya şekil sınırlarında dokunun nasıl döşeneceğine karar vermek için kullanılan wrap mode ve rengi ayarlar. Dokunun, dolduracağı şekilden daha küçük olduğunda şekli doldurmak için dokunun şekil boyunca döşenmesi sağlanır. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Bir şekil boyunca veya şekil sınırlarında dokunun nasıl döşeneceğine karar vermek için kullanılan wrap mode ve rengi ayarlar. Dokunun, dolduracağı şekilden daha küçük olduğunda şekli doldurmak için dokunun şekil boyunca döşenmesi sağlanır. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

ImageAttributes sınıfının yeni bir örneğini başlatır

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Belirtilen kategori için renk anahtarını (şeffaflık aralığını) temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | color key'in temizlendiği kategoriyi belirten bir [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Belirtilen kategori için renk ayarlama matrisini temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | color-adjustment matrix'in temizlendiği kategoriyi belirten bir [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Belirtilen kategori için gama düzeltmesini devre dışı bırakır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | gamma correction'ın devre dışı bırakıldığı kategoriyi belirten bir [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Belirtilen kategori için NoOp ayarını temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | NoOp ayarının temizlendiği kategoriyi belirten bir [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Belirtilen kategori için (cyan-magenta-yellow-black) çıkış kanalı ayarını temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Çıktı kanal ayarının temizlendiği kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Belirtilen kategori için çıkış kanalı renk profili ayarını temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Çıktı kanal profili ayarının temizlendiği kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Belirtilen kategori için renk yeniden eşleme tablosunu temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Yeniden eşleme tablosunun temizlendiği kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Belirtilen kategori için eşik değerini temizler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Eşik değerinin temizlendiği kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Fırça kategorisi için renk yeniden eşleme tablosunu ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) nesnelerinin bir dizisi. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Varsayılan kategori için color key ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Düşük renk anahtarı değeri. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Yüksek renk anahtarı değeri. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Belirtilen kategori için color key (transparency range) ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Düşük renk anahtarı değeri. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Yüksek renk anahtarı değeri. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Renk anahtarının ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Varsayılan kategori için color-adjustment matrix ve grayscale-adjustment matrix ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Gri tonlama ayarlama matrisi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Varsayılan kategori için color-adjustment matrix ve grayscale-adjustment matrix ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Gri tonlama ayarlama matrisi. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Renk ayarlama ve gri tonlama ayarlama matrislerinden etkilenecek görüntü ve renk türünü belirten [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) öğesi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Belirtilen kategori için color-adjustment matrix ve grayscale-adjustment matrix ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Gri tonlama ayarlama matrisi. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Renk ayarlama ve gri tonlama ayarlama matrislerinden etkilenecek görüntü ve renk türünü belirten [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) öğesi. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Renk ayarlama ve gri tonlama ayarlama matrislerinin ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Varsayılan kategori için color-adjustment matrix ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Renk ayarlama matrisi. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Varsayılan kategori için color-adjustment matrix ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Renk ayarlama matrisinden etkilenecek görüntü ve renk türünü belirten [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) öğesi. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Belirtilen kategori için color-adjustment matrix ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Renk ayarlama matrisi. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Renk ayarlama matrisinden etkilenecek görüntü ve renk türünü belirten [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) öğesi. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Renk ayarlama matrisinin ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Varsayılan kategori için gamma değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Gama düzeltme değeri. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Belirtilen kategori için gamma değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Gama düzeltme değeri. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Gama değerinin ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) enum öğesi. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Belirtilen kategori için color adjustment kapatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Renk düzeltmesinin kapatıldığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Varsayılan kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Çıktı kanalını belirten [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) öğesi. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Belirtilen kategori için CMYK (cyan-magenta-yellow-black) çıkış kanalını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Çıktı kanalını belirten [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) öğesi. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Çıktı kanalının ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Varsayılan kategori için çıkış kanalı renk profili dosyasını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_profile_filename | string | Bir renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise bu parametre dosya adı olabilir. Aksi takdirde bu parametre tam nitelikli yol adı olmalıdır. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Belirtilen kategori için çıkış kanalı renk profili dosyasını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color_profile_filename | string | Bir renk profili dosyasının yol adı. Renk profili dosyası %SystemRoot%\\System32\\Spool\\Drivers\\Color dizininde ise bu parametre dosya adı olabilir. Aksi takdirde bu parametre tam nitelikli yol adı olmalıdır. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Çıktı kanal renk profili dosyasının ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Varsayılan kategori için color-remap tablosunu ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) tipinde renk çiftlerinin bir dizisi. Her renk çifti mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Belirtilen kategori için color-remap tablosunu ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) tipinde renk çiftlerinin bir dizisi. Her renk çifti mevcut bir rengi (ilk değer) ve ona eşlenecek rengi (ikinci değer) içerir. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Renk yeniden eşleme tablosunun ayarlandığı kategoriyi belirten [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Varsayılan kategori için eşik (transparency range) ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| threshold | float | Eşik değerini belirten gerçek bir sayı. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Belirtilen kategori için eşik (transparency range) ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| threshold | float | 0.0 ile 1.0 arasında bir eşik değeri, renkleri maksimum ya da minimum bir değere eşlenecek şekilde sıralamak için bir kesme noktası olarak kullanılır. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) öğesi, renk eşiğinin ayarlandığı kategoriyi belirtir. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Bir şekil boyunca veya şekil sınırlarında dokunun nasıl döşeneceğine karar vermek için kullanılan wrap mode'u ayarlar. Dokunun, dolduracağı şekilden daha küçük olduğunda şekli doldurmak için dokunun şekil boyunca döşenmesi sağlanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) öğesi, bir görüntünün tekrar eden kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Bir şekil boyunca veya şekil sınırlarında dokunun nasıl döşeneceğine karar vermek için kullanılan wrap mode ve rengi ayarlar. Dokunun, dolduracağı şekilden daha küçük olduğunda şekli doldurmak için dokunun şekil boyunca döşenmesi sağlanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) öğesi, bir görüntünün tekrar eden kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |
| color | [Color](/psd/python-net/aspose.psd/color) | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) nesnesi, işlenmiş bir görüntünün dışındaki piksellerin rengini belirtir. Bu renk, mod parametresi [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgeni görüntünün kendisinden daha büyük olduğunda görünür. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Bir şekil boyunca veya şekil sınırlarında dokunun nasıl döşeneceğine karar vermek için kullanılan wrap mode ve rengi ayarlar. Dokunun, dolduracağı şekilden daha küçük olduğunda şekli doldurmak için dokunun şekil boyunca döşenmesi sağlanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) öğesi, bir görüntünün tekrar eden kopyalarının bir alanı döşemek için nasıl kullanıldığını belirtir. |
| color | [Color](/psd/python-net/aspose.psd/color) | İşlenmiş bir görüntünün dışındaki piksellerin rengini belirten bir renk nesnesi. Bu renk, mod parametresi [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgeni görüntünün kendisinden daha büyük olduğunda görünür. |
| kısma | bool | Bu parametrenin hiçbir etkisi yoktur. False olarak ayarlayın. |

