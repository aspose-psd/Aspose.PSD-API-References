---
title: "FontSettings Kelas"
type: docs
weight: 1370
url: /id/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Mendapatkan atau mengatur nama default font. |
| get_system_alternative_font [static] | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [get alternative font]. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| clear_font_replacements() | Menghapus semua penggantian font |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Mendapatkan nama font Adobe berdasarkan nama keluarga font. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Mendapatkan folder font default. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Mendapatkan array penggantian font berdasarkan nama font |
| [get_fonts_folders()](#get_fonts_folders__4) | Mendapatkan salinan array yang berisi daftar folder tempat Aspose.Words mencari font TrueType. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Mendapatkan font pengganti yang paling cocok.<br/>            Jika semua pengganti tidak diizinkan maka akan mengembalikan font pertama yang diizinkan dan tersedia.<br/>            Jika tidak ada font yang tersedia maka akan mengembalikan font dari argumen |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Menentukan apakah [is font allowed] [nama font yang ditentukan]. |
| remove_font_cache_file() | Menghapus file cache font. |
| reset() | Mengatur ulang folder font dan nama font default ke default sistem. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Membatasi penggunaan font dengan daftar font. Harap periksa nama font yang sebenarnya sebelum pembatasan<br/>            Atur daftar font yang diizinkan ke Null untuk menghapus pembatasan. |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Mengatur daftar pengganti font. Jika font tidak diizinkan maka akan dicari pengganti.<br/>            Font pertama dalam daftar akan digunakan pertama kali. Jika juga dibatasi, maka font berikutnya dalam daftar akan dipilih.<br/>            Jika font tidak memiliki pengganti atau semua pengganti tidak diizinkan, maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan.<br/>            Jika tidak ada font yang diizinkan dan tersedia, maka perpustakaan akan mencoba menggunakan font default sistem meskipun tidak diizinkan. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Ini adalah pintasan ke [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) untuk mengatur hanya satu direktori font.<br/>            Tidak ada pemeriksaan yang dilakukan pada folder font. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Mengatur folder tempat font TrueType dimuat dan menghapus semua font yang dimuat.<br/>            Tidak ada pemeriksaan yang dilakukan pada folder font. |
| update_fonts() | Memperbarui cache font untuk file PSD yang berisi lapisan teks. Metode ini menjamin bahwa font dari folder fontsFolder yang menggunakan<br/>            metode FontSettings.SetFontsFolder(fontsFolder) atau setelah mereset font menggunakan FontSettings.Reset() akan dipertimbangkan saat memproses file PSD. Harap gunakan metode ini setiap kali <br/>            FontSettings.SetFontsFolder(fontsFolder) atau FontSettings.Reset() dipanggil untuk gambar PSD. Tanpa memanggil Metode ini tidak ada jaminan bahwa font akan diperbarui. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Mendapatkan nama font Adobe berdasarkan nama keluarga font.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_family_name | string | Nama keluarga font. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Nama font Adobe berdasarkan nama keluarga font. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Mendapatkan folder font default.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Mengembalikan folder sistem |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Mendapatkan array penggantian font berdasarkan nama font

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Nama font. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Array nama pengganti untuk font yang disediakan |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Mendapatkan salinan array yang berisi daftar folder tempat Aspose.Words mencari font TrueType.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Salinan lokasi font saat ini. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Mendapatkan font pengganti yang paling cocok.<br/>            Jika semua pengganti tidak diizinkan maka akan mengembalikan font pertama yang diizinkan dan tersedia.<br/>            Jika tidak ada font yang tersedia maka akan mengembalikan font dari argumen

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Nama font. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Nama font yang diganti |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Menentukan apakah [is font allowed] [nama font yang ditentukan].

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Nama font. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika [is font allowed] [nama font yang ditentukan]; jika tidak, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Membatasi penggunaan font dengan daftar font. Harap periksa nama font yang sebenarnya sebelum pembatasan<br/>            Atur daftar font yang diizinkan ke Null untuk menghapus pembatasan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_list | string | Daftar font. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Mengatur daftar pengganti font. Jika font tidak diizinkan maka akan dicari pengganti.<br/>            Font pertama dalam daftar akan digunakan pertama kali. Jika juga dibatasi, maka font berikutnya dalam daftar akan dipilih.<br/>            Jika font tidak memiliki pengganti atau semua pengganti tidak diizinkan, maka akan digunakan font pertama yang diizinkan dari daftar font yang diizinkan.<br/>            Jika tidak ada font yang diizinkan dan tersedia, maka perpustakaan akan mencoba menggunakan font default sistem meskipun tidak diizinkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_to_replace | string | Font yang akan diganti. |
| font_names | string | Nama font pengganti dalam urutan kesamaan. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Ini adalah pintasan ke [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) untuk mengatur hanya satu direktori font.<br/>            Tidak ada pemeriksaan yang dilakukan pada folder font.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_folder | string | Folder font. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Mengatur folder tempat font TrueType dimuat dan menghapus semua font yang dimuat.<br/>            Tidak ada pemeriksaan yang dilakukan pada folder font.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fonts_folders | string | Folder font. |
| rekursif | bool | jika diatur ke <c>true</c> [recursive]. |

