---
title: "Kelas TiffOptions"
type: docs
weight: 130
url: /id/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Secara default konvensi little endian digunakan. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Mendapatkan atau mengatur opsi penyimpanan alfa. Opsi selain [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            digunakan ketika ada lebih dari 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) yang didefinisikan. |
| seniman | string | r/w | Mendapatkan atau mengatur seniman. |
| bits_per_pixel | int | r | Mendapatkan bit per piksel. |
| bits_per_sample | ushort | r/w | Mendapatkan atau mengatur bit per sampel. |
| buffer_size_hint | int | r/w | Mendapatkan atau mengatur petunjuk ukuran buffer yang didefinisikan sebagai ukuran maksimum yang diizinkan untuk semua buffer internal. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Mendapatkan atau mengatur nilai yang menunjukkan urutan byte tiff. |
| color_map | ushort | r/w | Mendapatkan atau mengatur peta warna. |
| compressed_quality | int | r/w | Mendapatkan atau mengatur kualitas gambar terkompresi.<br/>            Digunakan dengan kompresi Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Mendapatkan atau mengatur kompresi. |
| hak cipta | string | r/w | Mendapatkan atau mengatur hak cipta. |
| date_time | string | r/w | Mendapatkan atau mengatur tanggal dan waktu. |
| default_memory_allocation_limit | int | r/w | Mendapatkan atau mengatur batas alokasi memori default. |
| default_replacement_font | string | r/w | Mendapatkan atau mengatur font pengganti default (font yang akan digunakan untuk menggambar teks saat mengekspor ke raster, jika font lapisan yang ada dalam file PSD tidak tersedia di sistem).<br/>            Untuk mengambil nama font default yang tepat dapat digunakan cuplikan kode berikut:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| document_name | string | r/w | Mendapatkan atau mengatur nama dokumen. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Mendapatkan atau mengatur penunjuk ke EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Mendapatkan atau mengatur opsi fax t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Mendapatkan atau mengatur standar file TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Mendapatkan atau mengatur urutan pengisian bit byte. |
| full_frame | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah [full frame]. |
| half_tone_hints | ushort | r/w | Mendapatkan atau mengatur petunjuk halftone. |
| image_description | string | r/w | Mendapatkan atau mengatur deskripsi gambar. |
| image_length | uint | r/w | Mendapatkan atau mengatur panjang gambar. |
| image_width | uint | r/w | Mendapatkan atau mengatur lebar gambar. |
| ink_names | string | r/w | Mendapatkan atau mengatur nama tinta. |
| is_extra_samples_present | bool | r | Mendapatkan nilai yang menunjukkan apakah sampel ekstra hadir. |
| is_tiled | bool | r | Mendapatkan nilai yang menunjukkan apakah gambar ditata ubin. |
| is_valid | bool | r | Mendapatkan nilai yang menunjukkan apakah [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) telah dikonfigurasi dengan benar. Gunakan metode Validate untuk menemukan alasan kegagalan. |
| max_sample_value | ushort | r/w | Mendapatkan atau mengatur nilai sampel maksimum. |
| min_sample_value | ushort | r/w | Mendapatkan atau mengatur nilai sampel minimum. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Opsi multipage |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Mendapatkan atau mengatur orientasi. |
| page_name | string | r/w | Mendapatkan atau mengatur nama halaman. |
| page_number | ushort | r/w | Mendapatkan atau mengatur tag nomor halaman. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Mendapatkan atau mengatur palet warna. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Mendapatkan atau mengatur fotometrik. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Mendapatkan atau mengatur konfigurasi planar. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Mendapatkan atau mengatur prediktor untuk kompresi LZW. |
| komponen_premultiplikasi | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah komponen harus dipremultiplikasi. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Mendapatkan atau mengatur pengaturan resolusi. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Mendapatkan atau mengatur satuan resolusi. |
| rows_per_strip | uint | r/w | Mendapatkan atau mengatur baris per strip. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Mendapatkan atau mengatur format sampel. |
| samples_per_pixel | ushort | r | Mendapatkan sampel per piksel. Untuk mengubah nilai properti ini, gunakan pengatur properti [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Mendapatkan atau mengatur produsen pemindai. |
| scanner_model | string | r/w | Mendapatkan atau mengatur model pemindai. |
| smax_sample_value | uint | r/w | Mendapatkan atau mengatur nilai sampel maksimum. Nilai tersebut memiliki tipe bidang yang paling cocok dengan data sampel (tipe Byte, Short, atau Long). |
| smin_sample_value | uint | r/w | Mendapatkan atau mengatur nilai sampel minimum. Nilai tersebut memiliki tipe bidang yang paling cocok dengan data sampel (Byte, Short or Long type). |
| software_type | string | r/w | Mendapatkan atau mengatur tipe perangkat lunak. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Mendapatkan atau mengatur sumber untuk membuat gambar di. |
| strip_byte_counts | uint | r/w | Mendapatkan atau mengatur jumlah byte strip. |
| strip_offsets | uint | r/w | Mendapatkan atau mengatur offset strip. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Mendapatkan atau mengatur indikasi umum tentang jenis data yang terdapat dalam subfile ini. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Mendapatkan atau mengatur tag. |
| target_printer | string | r/w | Mendapatkan atau mengatur printer target. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Mendapatkan atau mengatur threshholding. |
| tile_byte_counts | uint | r/w | Mendapatkan atau mengatur jumlah byte ubin. |
| tile_length | uint | r/w | Mendapatkan ot mengatur panjang ubin. |
| tile_offsets | uint | r/w | Mendapatkan atau mengatur offset ubin. |
| tile_width | uint | r/w | Mendapatkan ot mengatur lebar ubin. |
| total_pages | ushort | r | Mendapatkan total halaman. |
| valid_tag_count | int | r | Mendapatkan jumlah tag yang valid. Ini bukan jumlah total tag melainkan jumlah tag yang dapat dipertahankan. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Mendapatkan atau mengatur opsi rasterisasi vektor. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Mendapatkan atau mengatur kontainer metadata XMP. |
| xp_author | string | r/w | Mendapatkan atau mengatur penulis gambar, yang digunakan oleh Windows Explorer. |
| xp_comment | string | r/w | Mendapatkan atau mengatur komentar pada gambar, yang digunakan oleh Windows Explorer. |
| xp_keywords | string | r/w | Mendapatkan atau mengatur subjek gambar, yang digunakan oleh Windows Explorer. |
| xp_subject | string | r/w | Mendapatkan atau mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| xp_title | string | r/w | Mendapatkan atau mengatur informasi tentang gambar, yang digunakan oleh Windows Explorer. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur posisi x. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur resolusi x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur YCbCrCoefficients. |
| y_cb_cr_subsampling | ushort | r/w | Mendapatkan atau mengatur faktor subsampling untuk fotometrik YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur posisi y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur resolusi y. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Menambahkan tag baru. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Menambahkan tag-tag tersebut. |
| [clone()](#clone__3) | Mengkloning instance ini. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Mendapatkan instance tag berdasarkan tipe. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Mendapatkan jumlah tag yang valid. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Menentukan apakah tag ada dalam opsi atau tidak. |
| [remove_tag(tag)](#remove_tag_tag_7) | Menghapus tag. |
| validate() | Memvalidasi apakah opsi memiliki kombinasi tag yang valid |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Secara default konvensi little endian digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Format file tiff yang diharapkan. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Format file tiff yang diharapkan. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | Urutan byte format file tiff yang akan digunakan. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Opsi untuk menyalin dari. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Menginisialisasi instance baru dari kelas [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag-tag untuk menginisialisasi opsi. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Menambahkan tag baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag untuk ditambahkan. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Menambahkan tag-tag tersebut.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag-tag untuk ditambahkan. |

### Method: clone() {#clone__3}


```
 clone() 
```

Mengkloning instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Mengembalikan salinan dangkal dari instance ini |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Mendapatkan instance tag berdasarkan tipe.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Kunci tag. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instansi tag jika ada atau null jika tidak. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Mendapatkan jumlah tag yang valid.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag yang akan divalidasi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Jumlah tag yang valid. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Menentukan apakah tag ada dalam opsi atau tidak.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | ID tag untuk diperiksa. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <c>true</c> jika tag ada; jika tidak, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Menghapus tag.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Tag untuk dihapus. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true jika berhasil dihapus |


