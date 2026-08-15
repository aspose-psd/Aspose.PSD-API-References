---
title: "Класс ExifData"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ExifData()](#ExifData__1) | Создаёт новый экземпляр класса [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) . |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Создаёт новый экземпляр класса [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) с данными из массива. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Создаёт новый экземпляр класса [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) с данными из массива. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задаёт значение диафрагмы. |
| body_serial_number | string | r/w | Получает или задаёт серийный номер корпуса камеры. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значение яркости. |
| camera_owner_name | string | r/w | Получает или задает имя владельца камеры |
| cfa_pattern | байт | r/w | Получает или задает шаблон CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Получает или задает цветовое пространство. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги, которые относятся к общей секции. Это применяется только к jpeg‑изображениям, в формате tiff вместо этого используются tiffOptions. |
| components_configuration | байт | r/w | Получает или задает конфигурацию компонентов. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает сжатые биты на пиксель. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Получает или задает контраст. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Получает или задает пользовательскую отрисовку. |
| date_time_digitized | string | r/w | Получает или задает дату и время оцифровки. |
| date_time_original | string | r/w | Получает или задает оригинальную дату и время. |
| device_setting_description | байт | r/w | Получает или задает описание настроек устройства |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает коэффициент цифрового зума. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги, которые относятся только к секции EXIF. |
| exif_version | байт | r/w | Получает или задает версию EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значение смещения экспозиции. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает индекс экспозиции. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Получает или задает режим экспозиции. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Получает или задает программу экспозиции. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает время экспозиции. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает значение F-number. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Получает или задает тип источника файла. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Получает или задает вспышку. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает энергию вспышки. |
| flashpix_version | байт | r/w | Получает или задает версию flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает фокусное расстояние. |
| focal_length_in_35_mm_film | ushort | r/w | Получает или задает фокусное расстояние в пленке 35 мм. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Получает или задает единицу разрешения фокальной плоскости. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси X фокальной плоскости. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси Y фокальной плоскости. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Получает или задает степень общей регулировки усиления изображения. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает гамму. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает высоту GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Получает или задает высоту GPS, используемую в качестве эталонной высоты. |
| gps_area_information | байт | r/w | Получает или задает информацию о области GPS. |
| gps_date_stamp | string | r/w | Получает или задает строку GPS, записывающую дату и время относительно UTC (координированного всемирного времени). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает азимут GPS к целевой точке. |
| gps_dest_bearing_ref | string | r/w | Получает или задает ссылку GPS, используемую для указания азимута к целевой точке. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает расстояние GPS до целевой точки. |
| gps_dest_distance_ref | string | r/w | Получает или задает единицу GPS, используемую для выражения расстояния до целевой точки. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает широту GPS целевой точки. |
| gps_dest_latitude_ref | string | r/w | Получает или задает значение GPS, указывающее, является ли широта целевой точки северной или южной. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает долготу GPS целевой точки. |
| gps_dest_longitude_ref | string | r/w | Получает или задает значение GPS, указывающее, является ли долгота целевой точки восточной или западной. |
| gps_differential | ushort | r/w | Получает или задает значение GPS, указывающее, применяется ли дифференциальная коррекция к GPS-приемнику. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает направление GPS изображения при его захвате. |
| gps_img_direction_ref | string | r/w | Получает или задает ссылку GPS, указывающую направление изображения при его захвате. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает широту GPS. |
| gps_latitude_ref | string | r/w | Получает или задает, является ли широта GPS северной или южной. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает долготу GPS. |
| gps_longitude_ref | string | r/w | Получает или задает, является ли долгота GPS восточной или западной. |
| gps_map_datum | string | r/w | Получает или задает геодезические данные GPS, используемые GPS-приемником. |
| gps_measure_mode | string | r/w | Получает или задает режим измерения GPS. |
| gps_processing_method | байт | r/w | Получает или задает строку GPS, содержащую название метода, используемого для определения местоположения. |
| gps_satellites | string | r/w | Получает или задает спутники GPS, используемые для измерений. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает скорость перемещения приемника GPS. |
| gps_speed_ref | string | r/w | Получает или задает единицу измерения скорости перемещения приемника GPS. |
| gps_status | string | r/w | Получает или задает статус приемника GPS при записи изображения. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги, относящиеся только к разделу GPS. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает время GPS в формате UTC (координированное всемирное время). |
| gps_track | string | r/w | Получает или задает направление перемещения приемника GPS. |
| gps_track_ref | string | r/w | Получает или задает ссылку, определяющую направление перемещения приемника GPS. |
| gps_version_id | байт | r/w | Получает или задает идентификатор версии GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает GPS DOP (степень точности данных). |
| image_unique_id | string | r/w | Получает или задает уникальный идентификатор изображения. |
| is_big_endian | bool | r/w | Получает или задает значение, указывающее, является ли поток данных EXIF, созданный из него, big endian. |
| iso_speed | uint | r/w | Получает или задает ISO‑скорость |
| iso_speed_latitude_yyy | uint | r/w | Получает или задает значение ISO‑скорости latitude yyy камеры или входного устройства, определённое в ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Получает или задает значение ISO‑скорости latitude zzz камеры или входного устройства, определённое в ISO 12232. |
| lens_make | string | r/w | Получает или задает производителя объектива. |
| lens_model | string | r/w | Получает или задает модель объектива. |
| lens_serial_number | string | r/w | Получает или задает серийный номер объектива. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает спецификацию объектива |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Получает или задает источник света. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Получает данные примечания производителя. |
| maker_note_raw_data | байт | r/w | Получает или задает необработанные данные примечания производителя. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает значение максимальной диафрагмы. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Получает или задает режим измерения экспозиции. |
| oecf | байт | r/w | Получает или задает опто-электрическую функцию преобразования (OECF), указанную в ISO 14524. |
| photographic_sensitivity | uint | r/w | Получает или задает фоточувствительность. |
| pixel_x_dimension | uint | r/w | Получает или задает размерность пикселя по оси X. |
| pixel_y_dimension | uint | r/w | Получает или задает размерность пикселя по оси Y. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает все теги EXIF (включая общие и GPS-теги). |
| recommended_exposure_index | uint | r/w | Получает или задает рекомендуемый индекс экспозиции. |
| related_sound_file | string | r/w | Получает или задает связанный звуковой файл. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Получает или задает насыщенность. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Получает или задает тип захвата сцены. |
| scene_type | байт | r/w | Получает или задает тип сцены. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Получает или задает метод измерения. |
| sensitivity_type | ushort | r/w | Получает или задает тип чувствительности. |
| sharpness | ushort | r/w | Получает или задает резкость. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Получает или задает значение скорости затвора. |
| spatial_frequency_response | байт | r/w | Получает или задает пространственную частотную характеристику. |
| spectral_sensitivity | string | r/w | Получает или задает спектральную чувствительность. |
| standard_output_sensitivity | uint | r/w | Получает или задает стандартную чувствительность вывода |
| subject_area | ushort | r/w | Получает или задает область объекта. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает расстояние до объекта. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Получает или задает диапазон расстояний до объекта. |
| subject_location | ushort | r/w | Получает или задает местоположение объекта. |
| subsec_time | string | r/w | Получает или задает доли секунды для тега DateTime. |
| subsec_time_digitized | string | r/w | Получает или задает доли секунды для тега DateTimeDigitized. |
| subsec_time_original | string | r/w | Получает или задает доли секунды для тега DateTimeOriginal. |
| user_comment | string | r/w | Получает или задает пользовательский комментарий. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Получает или задает баланс белого. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает хроматичность белой точки изображения. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Удалить тег из контейнера |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Удалить тег из контейнера |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Создаёт новый экземпляр класса [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) .

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Создаёт новый экземпляр класса [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) с данными из массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Общие теги. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Теги EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Теги GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Создаёт новый экземпляр класса [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) с данными из массива.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Массив тегов EXIF вместе с общими и тегами GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Удалить тег из контейнера

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Тег для удаления |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Удалить тег из контейнера

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_id | ushort | Идентификатор тега для удаления. |

