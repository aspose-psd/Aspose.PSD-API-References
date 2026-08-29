---
title: "TiffOptions Sınıfı"
type: docs
weight: 130
url: /tr/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır. |
| [TiffOptions(options)](#TiffOptions_options_3) | Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Alfa depolama seçeneğini alır veya ayarlar. [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            3'ten fazla [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) tanımlandığında kullanılır. |
| sanatçı | string | r/w | Sanatçıyı alır veya ayarlar. |
| bits_per_pixel | int | r | Piksel başına bit sayısını alır. |
| bits_per_sample | ushort | r/w | Örnek başına bit sayısını alır veya ayarlar. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Tiff bayt sırasını gösteren bir değeri alır veya ayarlar. |
| color_map | ushort | r/w | Renk haritasını alır veya ayarlar. |
| compressed_quality | int | r/w | Sıkıştırılmış görüntü kalitesini alır veya ayarlar.<br/>            Jpeg sıkıştırmasıyla birlikte kullanılır. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Sıkıştırmayı alır veya ayarlar. |
| copyright | string | r/w | Telif hakkını alır veya ayarlar. |
| date_time | string | r/w | Tarih ve saati alır veya ayarlar. |
| default_memory_allocation_limit | int | r/w | varsayılan bellek tahsis sınırını alır veya ayarlar. |
| default_replacement_font | string | r/w | Varsayılan değiştirme yazı tipini alır veya ayarlar (rastera dışa aktarırken metin çizmeye kullanılacak yazı tipi, eğer PSD dosyasındaki mevcut katman yazı tipi sistemde bulunmuyorsa).<br/>            Varsayılan yazı tipinin doğru adını almak için aşağıdaki kod parçacığı kullanılabilir:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| document_name | string | r/w | Belgenin adını alır veya ayarlar. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | EXIF IFD'ye işaretçiyi alır veya ayarlar. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Faks t4 seçeneklerini alır veya ayarlar. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | TIFF dosya standardını alır veya ayarlar. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Byte bit doldurma sırasını alır veya ayarlar. |
| full_frame | bool | r/w | Tam çerçeve olup olduğunu gösteren bir değeri alır veya ayarlar. |
| half_tone_hints | ushort | r/w | Yarı ton ipuçlarını alır veya ayarlar. |
| image_description | string | r/w | Görüntü açıklamasını alır veya ayarlar. |
| image_length | uint | r/w | Görüntü uzunluğunu alır veya ayarlar. |
| image_width | uint | r/w | Görüntü genişliğini alır veya ayarlar. |
| ink_names | string | r/w | Mürekkep adlarını alır veya ayarlar. |
| is_extra_samples_present | bool | r | Ek örneklerin mevcut olup olmadığını gösteren bir değeri alır. |
| is_tiled | bool | r | Görüntünün döşenip döşenmediğini gösteren bir değer alır. |
| is_valid | bool | r | TiffOptions'in doğru yapılandırılıp yapılandırıldığını gösteren bir değer alır. Hata nedenini bulmak için Validate yöntemini kullanın. |
| max_sample_value | ushort | r/w | Maksimum örnek değerini alır veya ayarlar. |
| min_sample_value | ushort | r/w | Minimum örnek değerini alır veya ayarlar. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Çok sayfalı seçenekler |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Yönü alır veya ayarlar. |
| page_name | string | r/w | Sayfa adını alır veya ayarlar. |
| page_number | ushort | r/w | Sayfa numarası etiketini alır veya ayarlar. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Fotometrik değeri alır veya ayarlar. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Planar yapılandırmayı alır veya ayarlar. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | LZW sıkıştırması için tahmin ediciyi alır veya ayarlar. |
| bileşenleri_ön_çarp | bool | r/w | Bileşenlerin önceden çarpılması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Çözünürlük ayarlarını alır veya ayarlar. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | çözünürlük birimini alır veya ayarlar. |
| rows_per_strip | uint | r/w | Şerit başına satır sayısını alır veya ayarlar. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Örnek formatını alır veya ayarlar. |
| samples_per_pixel | ushort | r | Piksel başına örnekleri alır. Bu özellik değerini değiştirmek için [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) özelliği ayarlayıcısını kullanın. |
| scanner_manufacturer | string | r/w | Tarayıcı üreticisini alır veya ayarlar. |
| scanner_model | string | r/w | Tarayıcı modelini alır veya ayarlar. |
| smax_sample_value | uint | r/w | Maksimum örnek değerini alır veya ayarlar. Değer, örnek verileriyle en iyi eşleşen bir alan tipine sahiptir (Byte, Short veya Long tipi). |
| smin_sample_value | uint | r/w | Minimum örnek değerini alır veya ayarlar. Değer, örnek veriye en uygun alan tipine sahiptir (Byte, Short veya Long tipi). |
| software_type | string | r/w | Yazılım tipini alır veya ayarlar. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Görüntünün oluşturulacağı kaynağı alır veya ayarlar. |
| strip_byte_counts | uint | r/w | Şerit bayt sayılarını alır veya ayarlar. |
| strip_offsets | uint | r/w | Şerit ofsetlerini alır veya ayarlar. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Bu alt dosyada bulunan veri türünün genel bir göstergesini alır veya ayarlar. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Etiketleri alır veya ayarlar. |
| target_printer | string | r/w | Hedef yazıcıyı alır veya ayarlar. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Eşikleme değerini alır veya ayarlar. |
| tile_byte_counts | uint | r/w | Döşeme bayt sayılarını alır veya ayarlar. |
| tile_length | uint | r/w | Döşeme uzunluğunu alır veya ayarlar. |
| tile_offsets | uint | r/w | Döşeme ofsetlerini alır veya ayarlar. |
| tile_width | uint | r/w | Döşeme genişliğini alır veya ayarlar. |
| total_pages | ushort | r | Toplam sayfaları alır. |
| valid_tag_count | int | r | Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiketlerin sayısıdır. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP meta veri konteynerini alır veya ayarlar. |
| xp_author | string | r/w | Windows Gezgini tarafından kullanılan görüntü yazarını alır veya ayarlar. |
| xp_comment | string | r/w | Windows Gezgini tarafından kullanılan görüntü üzerindeki yorumu alır veya ayarlar. |
| xp_keywords | string | r/w | Windows Gezgini tarafından kullanılan görüntü konusunu alır veya ayarlar. |
| xp_subject | string | r/w | Windows Gezgini tarafından kullanılan görüntü hakkında bilgiyi alır veya ayarlar. |
| xp_title | string | r/w | Windows Gezgini tarafından kullanılan görüntü hakkında bilgiyi alır veya ayarlar. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x konumunu alır veya ayarlar. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x çözünürlüğünü alır veya ayarlar. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | YCbCrCoefficients değerini alır veya ayarlar. |
| y_cb_cr_subsampling | ushort | r/w | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y konumunu alır veya ayarlar. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y çözünürlüğünü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Yeni bir etiket ekler. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Etiketleri ekler. |
| [clone()](#clone__3) | Bu örneği klonlar. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Etiketin türüne göre örneğini alır. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Geçerli etiket sayısını alır. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Etiketin seçeneklerde bulunup bulunmadığını belirler. |
| [remove_tag(tag)](#remove_tag_tag_7) | Etiketi kaldırır. |
| validate() | Seçeneklerin geçerli bir etiket kombinasyonuna sahip olup olmadığını doğrular. |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır. Varsayılan olarak küçük endian kuralı kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Beklenen tiff dosya formatı. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Beklenen tiff dosya formatı. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | Kullanılacak TIFF dosya formatı bayt sırası. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Kopyalanacak seçenekler. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Yeni bir [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Seçenekleri başlatmak için etiketler. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Yeni bir etiket ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Eklenecek etiket. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Etiketleri ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Eklenecek etiketler. |

### Method: clone() {#clone__3}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bu örneğin yüzeysel bir kopyasını döndürür. |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Etiketin türüne göre örneğini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Etiket anahtarı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Etiketin var olması durumunda örneği, aksi takdirde null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Geçerli etiket sayısını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Doğrulanacak etiketler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Geçerli etiket sayısı. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Etiketin seçeneklerde bulunup bulunmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Kontrol edilecek etiket kimliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer etiket mevcutsa; aksi takdirde <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Etiketi kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Kaldırılacak etiket. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | true eğer başarıyla kaldırıldıysa. |


