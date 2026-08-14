---
title: "Kelas JpegExifData"
type: docs
weight: 20
url: /id/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Menginisialisasi sebuah instance baru dari kelas [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Menginisialisasi sebuah instance baru dari kelas [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) dengan data dari array. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Menginisialisasi sebuah instance baru dari kelas [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) dengan data dari array. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | Ukuran segmen EXIF maksimum dalam byte yang diizinkan. |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur nilai aperture. |
| seniman | string | r/w | Mendapatkan atau mengatur seniman. |
| bits_per_sample | ushort | r/w | Mendapatkan atau mengatur bit per sampel. |
| body_serial_number | string | r/w | Mendapatkan atau mengatur nomor seri bodi kamera. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Mendapatkan atau mengatur nilai kecerahan. |
| camera_owner_name | string | r/w | Mendapatkan atau mengatur nama pemilik kamera |
| cfa_pattern | byte | r/w | Mendapatkan atau mengatur pola CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Mendapatkan atau mengatur ruang warna. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Mendapatkan atau mengatur tag, yang termasuk dalam bagian umum. Ini hanya berlaku untuk gambar jpeg, dalam format tiff opsi tiffOptions digunakan sebagai gantinya |
| components_configuration | byte | r/w | Mendapatkan atau mengatur konfigurasi komponen. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur bit terkompresi per piksel. |
| compression | ushort | r/w | Mendapatkan atau mengatur kompresi. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Mendapatkan atau mengatur kontras. |
| hak cipta | string | r/w | Mendapatkan atau mengatur hak cipta. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Mendapatkan atau mengatur hasil render khusus. |
| date_time | string | r/w | Mendapatkan atau mengatur tanggal dan waktu. |
| date_time_digitized | string | r/w | Mendapatkan atau mengatur tanggal dan waktu digitalisasi. |
| date_time_original | string | r/w | Mendapatkan atau mengatur tanggal dan waktu asli. |
| device_setting_description | byte | r/w | Mendapatkan atau mengatur deskripsi pengaturan perangkat |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur rasio zoom digital. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Mendapatkan atau mengatur tag yang hanya termasuk dalam bagian EXIF. |
| exif_version | byte | r/w | Mendapatkan atau mengatur versi EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Mendapatkan atau mengatur nilai bias eksposur. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur indeks eksposur. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Mendapatkan atau mengatur mode eksposur. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Mendapatkan atau mengatur program eksposur. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur waktu paparan. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur nomor F. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Mendapatkan atau mengatur tipe sumber file. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Mendapatkan atau mengatur lampu kilat. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur energi lampu kilat. |
| flashpix_version | byte | r/w | Mendapatkan atau mengatur versi flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur panjang fokus. |
| focal_length_in_35_mm_film | ushort | r/w | Mendapatkan atau mengatur panjang fokus dalam film 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Mendapatkan atau mengatur satuan resolusi bidang fokus. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur resolusi x bidang fokus. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur resolusi y bidang fokus. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Mendapatkan atau mengatur tingkat penyesuaian gain gambar secara keseluruhan. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur ketinggian GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Mendapatkan atau mengatur ketinggian GPS yang digunakan sebagai ketinggian referensi. |
| gps_area_information | byte | r/w | Mendapatkan atau mengatur informasi area GPS. |
| gps_date_stamp | string | r/w | Mendapatkan atau mengatur string karakter GPS yang merekam informasi tanggal dan waktu relatif terhadap UTC (Coordinated Universal Time). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur arah GPS ke titik tujuan. |
| gps_dest_bearing_ref | string | r/w | Mendapatkan atau mengatur referensi GPS yang digunakan untuk memberikan arah ke titik tujuan. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur jarak GPS ke titik tujuan. |
| gps_dest_distance_ref | string | r/w | Mendapatkan atau mengatur unit GPS yang digunakan untuk menyatakan jarak ke titik tujuan. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur lintang GPS dari titik tujuan. |
| gps_dest_latitude_ref | string | r/w | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah lintang titik tujuan berada di lintang utara atau selatan. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur bujur GPS dari titik tujuan. |
| gps_dest_longitude_ref | string | r/w | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah bujur titik tujuan berada di bujur timur atau barat. |
| gps_differential | ushort | r/w | Mendapatkan atau mengatur nilai GPS yang menunjukkan apakah koreksi diferensial diterapkan pada penerima GPS. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur arah GPS gambar saat diambil. |
| gps_img_direction_ref | string | r/w | Mendapatkan atau mengatur referensi GPS untuk memberikan arah gambar saat diambil. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur lintang GPS. |
| gps_latitude_ref | string | r/w | Mendapatkan atau mengatur apakah lintang GPS berada di lintang utara atau selatan. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur bujur GPS. |
| gps_longitude_ref | string | r/w | Mendapatkan atau mengatur apakah bujur GPS berada di bujur timur atau barat. |
| gps_map_datum | string | r/w | Mendapatkan atau mengatur data survei geodetik GPS yang digunakan oleh penerima GPS. |
| gps_measure_mode | string | r/w | Mendapatkan atau mengatur mode pengukuran GPS. |
| gps_processing_method | byte | r/w | Mendapatkan atau mengatur string karakter GPS yang merekam nama metode yang digunakan untuk menemukan lokasi. |
| gps_satellites | string | r/w | Mendapatkan atau mengatur satelit GPS yang digunakan untuk pengukuran. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur kecepatan pergerakan penerima GPS. |
| gps_speed_ref | string | r/w | Mendapatkan atau mengatur satuan yang digunakan untuk menyatakan kecepatan pergerakan penerima GPS. |
| gps_status | string | r/w | Mendapatkan atau mengatur status penerima GPS saat gambar direkam. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Mendapatkan atau mengatur tag, yang hanya termasuk dalam bagian GPS. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur waktu GPS sebagai UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Mendapatkan atau mengatur arah pergerakan penerima GPS. |
| gps_track_ref | string | r/w | Mendapatkan atau mengatur referensi untuk memberikan arah pergerakan penerima GPS. |
| gps_version_id | byte | r/w | Mendapatkan atau mengatur pengidentifikasi versi GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur GPS DOP (data degree of precision). |
| image_description | string | r/w | Mendapatkan atau mengatur deskripsi gambar. |
| image_length | uint | r/w | Mendapatkan atau mengatur panjang gambar. |
| image_unique_id | string | r/w | Mendapatkan atau mengatur pengidentifikasi unik gambar. |
| image_width | uint | r/w | Mendapatkan atau mengatur lebar gambar. |
| is_big_endian | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah data aliran EXIF yang dibuat darinya menggunakan urutan byte besar (big endian). |
| iso_speed | uint | r/w | Mendapatkan atau mengatur kecepatan ISO |
| iso_speed_latitude_yyy | uint | r/w | Mendapatkan atau mengatur nilai latitude yyy kecepatan ISO dari kamera atau perangkat input yang didefinisikan dalam ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Mendapatkan atau mengatur nilai latitude zzz kecepatan ISO dari kamera atau perangkat input yang didefinisikan dalam ISO 12232. |
| lens_make | string | r/w | Mendapatkan atau mengatur pembuat lensa. |
| lens_model | string | r/w | Mendapatkan atau mengatur model lensa. |
| lens_serial_number | string | r/w | Mendapatkan atau mengatur nomor seri lensa. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur spesifikasi lensa |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Mendapatkan atau mengatur sumber cahaya. |
| make | string | r/w | Mendapatkan atau mengatur produsen peralatan perekaman. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Mendapatkan data catatan pembuat. |
| maker_note_raw_data | byte | r/w | Mendapatkan atau mengatur data mentah catatan pembuat. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur nilai apertur maksimum. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Mendapatkan atau mengatur mode pengukuran. |
| model | string | r/w | Mendapatkan atau mengatur model. |
| oecf | byte | r/w | Mendapatkan atau mengatur Fungsi Konversi Opto-Listrik (OECF) yang ditentukan dalam ISO 14524. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | Mendapatkan atau mengatur orientasi. |
| photographic_sensitivity | uint | r/w | Mendapatkan atau mengatur sensitivitas fotografi. |
| photometric_interpretation | ushort | r/w | Mendapatkan atau mengatur interpretasi fotometrik. |
| pixel_x_dimension | uint | r/w | Mendapatkan atau mengatur dimensi x piksel. |
| pixel_y_dimension | uint | r/w | Mendapatkan atau mengatur dimensi y piksel. |
| planar_configuration | ushort | r/w | Mendapatkan atau mengatur konfigurasi planar. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur kromatisitas tiga warna primer pada gambar. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Mendapatkan atau mengatur semua tag EXIF (termasuk tag umum dan GPS). |
| recommended_exposure_index | uint | r/w | Mendapatkan atau mengatur indeks eksposur yang direkomendasikan. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur referensi hitam putih. |
| related_sound_file | string | r/w | Mendapatkan atau mengatur file suara terkait. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Mendapatkan atau mengatur satuan resolusi. |
| samples_per_pixel | ushort | r/w | Mendapatkan atau mengatur sampel per piksel. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Mendapatkan atau mengatur saturasi. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Mendapatkan atau mengatur tipe penangkapan adegan. |
| scene_type | byte | r/w | Mendapatkan atau mengatur tipe adegan. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Mendapatkan atau mengatur metode penginderaan. |
| sensitivity_type | ushort | r/w | Mendapatkan atau mengatur tipe sensitivitas. |
| sharpness | ushort | r/w | Mendapatkan atau mengatur ketajaman. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Mendapatkan atau mengatur nilai kecepatan rana. |
| software | string | r/w | Mendapatkan atau mengatur perangkat lunak. |
| spatial_frequency_response | byte | r/w | Mendapatkan atau mengatur respons frekuensi spasial. |
| spectral_sensitivity | string | r/w | Mendapatkan atau mengatur sensitivitas spektral. |
| standard_output_sensitivity | uint | r/w | Mendapatkan atau mengatur sensitivitas output standar |
| subject_area | ushort | r/w | Mendapatkan atau mengatur area subjek. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur jarak subjek. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Mendapatkan atau mengatur rentang jarak subjek. |
| subject_location | ushort | r/w | Mendapatkan atau mengatur lokasi subjek. |
| subsec_time | string | r/w | Mendapatkan atau mengatur fraksi detik untuk tag DateTime. |
| subsec_time_digitized | string | r/w | Mendapatkan atau mengatur pecahan detik untuk tag DateTimeDigitized. |
| subsec_time_original | string | r/w | Mendapatkan atau mengatur pecahan detik untuk tag DateTimeOriginal. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | Mendapatkan atau mengatur gambar miniatur. |
| transfer_function | ushort | r/w | Mendapatkan atau mengatur fungsi transfer. |
| user_comment | string | r/w | Mendapatkan atau mengatur komentar pengguna. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Mendapatkan atau mengatur keseimbangan putih. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur kromatisitas titik putih gambar. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur resolusi x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur koefisien matriks untuk transformasi data gambar dari RGB ke YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | Mendapatkan atau mengatur posisi komponen krominansi relatif terhadap komponen luminansi. |
| y_cb_cr_sub_sampling | ushort | r/w | Mendapatkan atau mengatur rasio sampling komponen krominansi relatif terhadap komponen luminansi. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Mendapatkan atau mengatur resolusi y. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Hapus tag dari kontainer |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Hapus tag dari kontainer |
| [serialize_exif_data()](#serialize_exif_data__3) | Menyerialkan data EXIF. Menulis nilai tag dan isinya. Tag ukuran yang paling berpengaruh adalah isi tag Thumbnail. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Menginisialisasi sebuah instance baru dari kelas [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Menginisialisasi sebuah instance baru dari kelas [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) dengan data dari array.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag umum. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tag GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Menginisialisasi sebuah instance baru dari kelas [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) dengan data dari array.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Array tag EXIF bersama dengan tag umum dan GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Hapus tag dari kontainer

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Tag yang akan dihapus |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Hapus tag dari kontainer

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tag_id | ushort | Pengidentifikasi tag yang akan dihapus. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

Menyerialkan data EXIF. Menulis nilai tag dan isinya. Tag ukuran yang paling berpengaruh adalah isi tag Thumbnail.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| byte | Data EXIF yang diserialkan. |


