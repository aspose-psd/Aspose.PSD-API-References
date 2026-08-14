---
title: "Kelas ImageAttributes"
type: docs
weight: 2180
url: /id/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Menginisialisasi instance baru dari kelas ImageAttributes |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| clear_brush_remap_table() | Menghapus tabel remap warna kuas dari objek [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ini. |
| clear_color_key() | Menghapus kunci warna (rentang transparansi) untuk kategori default. |
| [clear_color_key(type)](#clear_color_key_type_1) | Menghapus kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| clear_color_matrix() | Menghapus matriks penyesuaian warna untuk kategori default. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Menghapus matriks penyesuaian warna untuk kategori yang ditentukan. |
| clear_gamma() | Menonaktifkan koreksi gamma untuk kategori default. |
| [clear_gamma(type)](#clear_gamma_type_3) | Menonaktifkan koreksi gamma untuk kategori yang ditentukan. |
| clear_no_op() | Menghapus pengaturan NoOp untuk kategori default. |
| [clear_no_op(type)](#clear_no_op_type_4) | Menghapus pengaturan NoOp untuk kategori yang ditentukan. |
| clear_output_channel() | Menghapus pengaturan saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Menghapus pengaturan saluran output (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| clear_output_channel_color_profile() | Menghapus pengaturan profil warna saluran output untuk kategori default. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Menghapus pengaturan profil warna saluran output untuk kategori yang ditentukan. |
| clear_remap_table() | Menghapus tabel pemetaan ulang warna untuk kategori default. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Menghapus tabel pemetaan ulang warna untuk kategori yang ditentukan. |
| clear_threshold() | Menghapus nilai ambang untuk kategori default. |
| [clear_threshold(type)](#clear_threshold_type_8) | Menghapus nilai ambang untuk kategori yang ditentukan. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Menetapkan tabel pemetaan ulang warna untuk kategori kuas. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Mengatur kunci warna untuk kategori default. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Mengatur kunci warna (rentang transparansi) untuk kategori yang ditentukan. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Mengatur matriks penyesuaian warna untuk kategori default. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Mengatur matriks penyesuaian warna untuk kategori yang ditentukan. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Mengatur nilai gamma untuk kategori default. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Mengatur nilai gamma untuk kategori yang ditentukan. |
| set_no_op() | Menonaktifkan penyesuaian warna untuk kategori default. |
| [set_no_op(type)](#set_no_op_type_20) | Menonaktifkan penyesuaian warna untuk kategori yang ditentukan. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Mengatur file profil warna saluran output untuk kategori default. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Mengatur file profil warna saluran output untuk kategori yang ditentukan. |
| [set_remap_table(map)](#set_remap_table_map_25) | Mengatur tabel pemetaan ulang warna untuk kategori default. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Mengatur tabel pemetaan ulang warna untuk kategori yang ditentukan. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Mengatur ambang (rentang transparansi) untuk kategori default. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Mengatur ambang (rentang transparansi) untuk kategori yang ditentukan. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Mengatur mode pembungkus yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas-batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas-batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas-batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Menginisialisasi instance baru dari kelas ImageAttributes

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Menghapus kunci warna (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori di mana kunci warna dibersihkan. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Menghapus matriks penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori di mana matriks penyesuaian warna dibersihkan. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Menonaktifkan koreksi gamma untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori di mana koreksi gamma dinonaktifkan. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Menghapus pengaturan NoOp untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori di mana pengaturan NoOp dibersihkan. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Menghapus pengaturan saluran output (cyan-magenta-yellow-black) untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana pengaturan saluran keluaran dibersihkan. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Menghapus pengaturan profil warna saluran output untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana pengaturan profil saluran keluaran dibersihkan. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Menghapus tabel pemetaan ulang warna untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana tabel remap dibersihkan. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Menghapus nilai ambang untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana ambang dibersihkan. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Menetapkan tabel pemetaan ulang warna untuk kategori kuas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Array dari objek [ColorMap](/psd/python-net/aspose.psd/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Mengatur kunci warna untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Nilai kunci-warna rendah. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Nilai kunci-warna tinggi. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Mengatur kunci warna (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Nilai kunci-warna rendah. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Nilai kunci-warna tinggi. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana kunci warna diatur. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-warna. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-grayscale. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-warna. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-grayscale. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Elemen dari [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian-warna dan penyesuaian-grayscale. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Mengatur matriks penyesuaian warna dan matriks penyesuaian skala abu-abu untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-warna. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-grayscale. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Elemen dari [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian-warna dan penyesuaian-grayscale. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana matriks penyesuaian-warna dan penyesuaian-grayscale diatur. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Mengatur matriks penyesuaian warna untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-warna. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Mengatur matriks penyesuaian warna untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-warna. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Elemen dari [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian-warna. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Mengatur matriks penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Matriks penyesuaian-warna. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Elemen dari [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) yang menentukan jenis gambar dan warna yang akan dipengaruhi oleh matriks penyesuaian-warna. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana matriks penyesuaian-warna diatur. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Mengatur nilai gamma untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| gamma | float | Nilai koreksi gamma. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Mengatur nilai gamma untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| gamma | float | Nilai koreksi gamma. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari enumerasi [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana nilai gamma diatur. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Menonaktifkan penyesuaian warna untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana koreksi warna dimatikan. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Elemen dari [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) yang menentukan saluran keluaran. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Mengatur saluran output CMYK (cyan-magenta-yellow-black) untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Elemen dari [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) yang menentukan saluran keluaran. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana saluran keluaran diatur. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Mengatur file profil warna saluran output untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_profile_filename | string | Nama jalur berkas profil-warna. Jika berkas profil-warna berada di direktori %SystemRoot%\System32\Spool\Drivers\Color, parameter ini dapat berupa nama berkas. Jika tidak, parameter ini harus berupa nama jalur lengkap. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Mengatur file profil warna saluran output untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| color_profile_filename | string | Nama jalur berkas profil-warna. Jika berkas profil-warna berada di direktori %SystemRoot%\System32\Spool\Drivers\Color, parameter ini dapat berupa nama berkas. Jika tidak, parameter ini harus berupa nama jalur lengkap. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana berkas profil-warna saluran keluaran diatur. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Mengatur tabel pemetaan ulang warna untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Array pasangan warna berjenis [ColorMap](/psd/python-net/aspose.psd/colormap/). Setiap pasangan warna berisi warna yang ada (nilai pertama) dan warna yang akan dipetakan kepadanya (nilai kedua). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Mengatur tabel pemetaan ulang warna untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Array pasangan warna berjenis [ColorMap](/psd/python-net/aspose.psd/colormap/). Setiap pasangan warna berisi warna yang ada (nilai pertama) dan warna yang akan dipetakan kepadanya (nilai kedua). |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori untuk mana tabel warna-remap diatur. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Mengatur ambang (rentang transparansi) untuk kategori default.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| threshold | float | Bilangan riil yang menentukan nilai ambang. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Mengatur ambang (rentang transparansi) untuk kategori yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| threshold | float | Nilai ambang dari 0.0 hingga 1.0 yang digunakan sebagai titik pemisah untuk mengurutkan warna yang akan dipetakan ke nilai maksimum atau minimum. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Elemen dari [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) yang menentukan kategori di mana ambang warna diatur. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Mengatur mode pembungkus yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas-batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Elemen dari [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana salinan berulang dari sebuah gambar digunakan untuk menutupi area. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas-batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Elemen dari [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana salinan berulang dari sebuah gambar digunakan untuk menutupi area. |
| color | [Color](/psd/python-net/aspose.psd/color) | Objek [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) yang menentukan warna piksel di luar gambar yang dirender. Warna ini terlihat jika parameter mode diatur ke [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) dan persegi panjang sumber yang diberikan ke DrawImage lebih besar daripada gambar itu sendiri. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Mengatur mode pembungkus dan warna yang digunakan untuk menentukan cara menempelkan tekstur pada sebuah bentuk, atau pada batas-batas bentuk. Tekstur ditempelkan pada bentuk untuk mengisinya ketika tekstur lebih kecil daripada bentuk yang diisi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Elemen dari [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana salinan berulang dari sebuah gambar digunakan untuk menutupi area. |
| color | [Color](/psd/python-net/aspose.psd/color) | Objek warna yang menentukan warna piksel di luar gambar yang dirender. Warna ini terlihat jika parameter mode diatur ke [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) dan persegi panjang sumber yang diberikan ke DrawImage lebih besar daripada gambar itu sendiri. |
| clamp | bool | Parameter ini tidak berpengaruh. Atur ke false. |

