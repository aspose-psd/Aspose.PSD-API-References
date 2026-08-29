---
title: "JpegExifData Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Yeni bir [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) sınıf örneği başlatır. |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Diziden veri ile yeni bir [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) sınıf örneği başlatır. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Diziden veri ile yeni bir [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | İzin verilen maksimum EXIF segment boyutu (bayt olarak). |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Diyafram değerini alır veya ayarlar. |
| sanatçı | string | r/w | Sanatçıyı alır veya ayarlar. |
| bits_per_sample | ushort | r/w | Örnek başına bit sayısını alır veya ayarlar. |
| body_serial_number | string | r/w | Kamera gövdesi seri numarasını alır veya ayarlar. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Parlaklık değerini alır veya ayarlar. |
| camera_owner_name | string | r/w | Kamera sahibi adını alır veya ayarlar |
| cfa_pattern | byte | r/w | CFA desenini alır veya ayarlar. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Renk uzayını alır veya ayarlar. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Ortak bölüme ait etiketleri alır veya ayarlar. Bu yalnızca jpeg görüntüler için geçerlidir, tiff formatında ise tiffOptions kullanılmaktadır. |
| components_configuration | byte | r/w | Bileşen yapılandırmasını alır veya ayarlar. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar. |
| compression | ushort | r/w | Sıkıştırmayı alır veya ayarlar. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Kontrasti alır veya ayarlar. |
| copyright | string | r/w | Telif hakkını alır veya ayarlar. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Özel işlenmiş değeri alır veya ayarlar. |
| date_time | string | r/w | Tarih ve zamanı alır veya ayarlar. |
| date_time_digitized | string | r/w | Dijitalleştirilmiş tarih ve saati alır veya ayarlar. |
| date_time_original | string | r/w | Orijinal tarih ve saati alır veya ayarlar. |
| device_setting_description | byte | r/w | Cihaz ayarları açıklamasını alır veya ayarlar |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Dijital yakınlaştırma oranını alır veya ayarlar. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar. |
| exif_version | byte | r/w | EXIF sürümünü alır veya ayarlar. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Pozlama sapma değerini alır veya ayarlar. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Pozlama indeksini alır veya ayarlar. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Pozlama modunu alır veya ayarlar. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Pozlama programını alır veya ayarlar. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Pozlama süresini alır veya ayarlar. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | F-numarasını alır veya ayarlar. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Dosya kaynağı türünü alır veya ayarlar. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Flaş'ı alır veya ayarlar. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Flaş enerjisini alır veya ayarlar. |
| flashpix_version | byte | r/w | Flaş piksel sürümünü alır veya ayarlar. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Odak uzaklığını alır veya ayarlar. |
| focal_length_in_35_mm_film | ushort | r/w | 35 mm filmde odak uzaklığını alır veya ayarlar. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Odak düzlemi çözünürlük birimini alır veya ayarlar. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Odak düzlemi x çözünürlüğünü alır veya ayarlar. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Odak düzlemi y çözünürlüğünü alır veya ayarlar. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Genel görüntü kazancı ayarlamasının derecesini alır veya ayarlar. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gamayı alır veya ayarlar. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS yüksekliğini alır veya ayarlar. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar. |
| gps_area_information | byte | r/w | GPS bölge bilgilerini alır veya ayarlar. |
| gps_date_stamp | string | r/w | UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgisini kaydeden GPS karakter dizisini alır veya ayarlar. |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hedef noktaya olan GPS yönünü alır veya ayarlar. |
| gps_dest_bearing_ref | string | r/w | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hedef noktaya olan GPS mesafesini alır veya ayarlar. |
| gps_dest_distance_ref | string | r/w | Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hedef noktanın GPS enlemini alır veya ayarlar. |
| gps_dest_latitude_ref | string | r/w | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hedef noktanın GPS boylamını alır veya ayarlar. |
| gps_dest_longitude_ref | string | r/w | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar. |
| gps_differential | ushort | r/w | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Görüntünün çekildiği zaman GPS yönünü alır veya ayarlar. |
| gps_img_direction_ref | string | r/w | Görüntünün çekildiği zaman yönünü vermek için GPS referansını alır veya ayarlar. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS enlemini alır veya ayarlar. |
| gps_latitude_ref | string | r/w | GPS enleminin kuzey mi yoksa güney mi olduğunu alır veya ayarlar. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS boylamını alır veya ayarlar. |
| gps_longitude_ref | string | r/w | GPS boylamının doğu mu yoksa batı mı olduğunu alır veya ayarlar. |
| gps_map_datum | string | r/w | GPS alıcısı tarafından kullanılan GPS jeodezik ölçüm verilerini alır veya ayarlar. |
| gps_measure_mode | string | r/w | GPS ölçüm modunu alır veya ayarlar. |
| gps_processing_method | byte | r/w | Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizisini alır veya ayarlar. |
| gps_satellites | string | r/w | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS alıcısının hareket hızını alır veya ayarlar. |
| gps_speed_ref | string | r/w | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. |
| gps_status | string | r/w | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar. |
| gps_track | string | r/w | GPS alıcısının hareket yönünü alır veya ayarlar. |
| gps_track_ref | string | r/w | GPS alıcısının hareket yönünü vermek için referansı alır veya ayarlar. |
| gps_version_id | byte | r/w | GPS sürüm tanımlayıcısını alır veya ayarlar. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar. |
| image_description | string | r/w | Görüntü açıklamasını alır veya ayarlar. |
| image_length | uint | r/w | Görüntü uzunluğunu alır veya ayarlar. |
| image_unique_id | string | r/w | Görüntünün benzersiz tanımlayıcısını alır veya ayarlar. |
| image_width | uint | r/w | Görüntü genişliğini alır veya ayarlar. |
| is_big_endian | bool | r/w | Oluşturulan akış EXIF verisinin büyük endian olup olmadığını belirten bir değeri alır veya ayarlar. |
| iso_speed | uint | r/w | ISO hızını alır veya ayarlar. |
| iso_speed_latitude_yyy | uint | r/w | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar. |
| iso_speed_latitude_zzz | uint | r/w | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar. |
| lens_make | string | r/w | Lensin üreticisini alır veya ayarlar. |
| lens_model | string | r/w | Lens modelini alır veya ayarlar. |
| lens_serial_number | string | r/w | Lens seri numarasını alır veya ayarlar. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Lens özelliklerini alır veya ayarlar. |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Işık kaynağını alır veya ayarlar. |
| make | string | r/w | Kayıt ekipmanının üreticisini alır veya ayarlar. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Üretici not verisini alır. |
| maker_note_raw_data | byte | r/w | Üretici not ham verisini alır veya ayarlar. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Maksimum diyafram değerini alır veya ayarlar. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Ölçüm modunu alır veya ayarlar. |
| model | string | r/w | Modeli alır veya ayarlar. |
| oecf | byte | r/w | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | Yönü alır veya ayarlar. |
| photographic_sensitivity | uint | r/w | Fotoğrafik duyarlılığı alır veya ayarlar. |
| photometric_interpretation | ushort | r/w | Fotometrik yorumu alır veya ayarlar. |
| pixel_x_dimension | uint | r/w | Piksel x boyutunu alır veya ayarlar. |
| pixel_y_dimension | uint | r/w | Piksel y boyutunu alır veya ayarlar. |
| planar_configuration | ushort | r/w | Planar yapılandırmayı alır veya ayarlar. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Görüntünün üç ana renginin kromatikliğini alır veya ayarlar. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar. |
| recommended_exposure_index | uint | r/w | Önerilen pozlama indeksini alır veya ayarlar. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Referans siyah beyazı alır veya ayarlar. |
| related_sound_file | string | r/w | İlgili ses dosyasını alır veya ayarlar. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | çözünürlük birimini alır veya ayarlar. |
| samples_per_pixel | ushort | r/w | Piksel başına örnekleri alır veya ayarlar. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Doygunluğu alır veya ayarlar. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Sahne yakalama türünü alır veya ayarlar. |
| scene_type | byte | r/w | Sahne türünü alır veya ayarlar. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Algılama yöntemini alır veya ayarlar. |
| sensitivity_type | ushort | r/w | Duyarlılık türünü alır veya ayarlar. |
| sharpness | ushort | r/w | Keskinliği alır veya ayarlar. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Deklanşör hızı değerini alır veya ayarlar. |
| software | string | r/w | Yazılımı alır veya ayarlar. |
| spatial_frequency_response | byte | r/w | Uzamsal frekans yanıtını alır veya ayarlar. |
| spectral_sensitivity | string | r/w | Spektral duyarlılığı alır veya ayarlar. |
| standard_output_sensitivity | uint | r/w | Standart çıktı duyarlılığını alır veya ayarlar |
| subject_area | ushort | r/w | Konu alanını alır veya ayarlar. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Konu mesafesini alır veya ayarlar. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Konu mesafe aralığını alır veya ayarlar. |
| subject_location | ushort | r/w | Konu konumunu alır veya ayarlar. |
| subsec_time | string | r/w | DateTime etiketi için saniyenin kesirlerini alır veya ayarlar. |
| subsec_time_digitized | string | r/w | DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar. |
| subsec_time_original | string | r/w | DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | Küçük resim görüntüsünü alır veya ayarlar. |
| transfer_function | ushort | r/w | Transfer fonksiyonunu alır veya ayarlar. |
| user_comment | string | r/w | Kullanıcı yorumunu alır veya ayarlar. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Beyaz dengesini alır veya ayarlar. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Görüntünün beyaz noktasının kromatikliğini alır veya ayarlar. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x çözünürlüğünü alır veya ayarlar. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayılarını alır veya ayarlar. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | Krominans bileşenlerinin parlaklık bileşenine göre konumunu alır veya ayarlar. |
| y_cb_cr_sub_sampling | ushort | r/w | Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranını alır veya ayarlar. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y çözünürlüğünü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Etiketi konteynerden kaldır |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Etiketi konteynerden kaldır |
| [serialize_exif_data()](#serialize_exif_data__3) | EXIF verilerini serileştirir. Etiket değerlerini ve içeriklerini yazar. En çok boyutu etkileyen etiket Küçük Resim etiketinin içeriğidir. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Yeni bir [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) sınıf örneği başlatır.

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Diziden veri ile yeni bir [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Ortak etiketler. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | EXIF etiketleri. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | GPS etiketleri. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Diziden veri ile yeni bir [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Etiketi konteynerden kaldır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Kaldırılacak etiket |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Etiketi konteynerden kaldır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| tag_id | ushort | Kaldırılacak etiket tanımlayıcısı. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

EXIF verilerini serileştirir. Etiket değerlerini ve içeriklerini yazar. En çok boyutu etkileyen etiket Küçük Resim etiketinin içeriğidir.

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Serileştirilmiş EXIF verileri. |


