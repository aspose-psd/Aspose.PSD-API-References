---
title: "Clase JpegExifData"
type: docs
weight: 20
url: /es/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Inicializa una nueva instancia de la clase [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Inicializa una nueva instancia de la clase [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con datos del array. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Inicializa una nueva instancia de la clase [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con datos del array. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | El tamaño máximo del segmento EXIF en bytes permitido. |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el valor de la apertura. |
| artist | string | r/w | Obtiene o establece el artista. |
| bits_per_sample | ushort | r/w | Obtiene o establece los bits por muestra. |
| body_serial_number | string | r/w | Obtiene o establece el número de serie del cuerpo de la cámara. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Obtiene o establece el valor de brillo. |
| camera_owner_name | string | r/w | Obtiene o establece el nombre del propietario de la cámara |
| cfa_pattern | byte | r/w | Obtiene o establece el patrón CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Obtiene o establece el espacio de color. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece etiquetas, que pertenecen a la sección común. Esto se aplica solo a imágenes jpeg, en formato tiff tiffOptions se están usando en su lugar |
| components_configuration | byte | r/w | Obtiene o establece la configuración de componentes. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece los bits comprimidos por píxel. |
| compression | ushort | r/w | Obtiene o establece la compresión. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Obtiene o establece el contraste. |
| copyright | string | r/w | Obtiene o establece el copyright. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Obtiene o establece el renderizado personalizado. |
| date_time | string | r/w | Obtiene o establece la fecha y hora. |
| date_time_digitized | string | r/w | Obtiene o establece la fecha y hora digitalizadas. |
| date_time_original | string | r/w | Obtiene o establece la fecha y hora original. |
| device_setting_description | byte | r/w | Obtiene o establece la descripción de la configuración del dispositivo |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la relación de zoom digital. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece etiquetas que pertenecen solo a la sección EXIF. |
| exif_version | byte | r/w | Obtiene o establece la versión EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Obtiene o establece el valor de sesgo de exposición. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el índice de exposición. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Obtiene o establece el modo de exposición. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Obtiene o establece el programa de exposición. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el tiempo de exposición. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el número F. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Obtiene o establece el tipo de origen del archivo. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Obtiene o establece el flash. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la energía del flash. |
| flashpix_version | byte | r/w | Obtiene o establece la versión flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la distancia focal. |
| focal_length_in_35_mm_film | ushort | r/w | Obtiene o establece la distancia focal en película de 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Obtiene o establece la unidad de resolución del plano focal. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución x del plano focal. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución y del plano focal. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Obtiene o establece el grado de ajuste general de ganancia de la imagen. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la altitud GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Obtiene o establece la altitud GPS utilizada como altitud de referencia. |
| gps_area_information | byte | r/w | Obtiene o establece la información de área GPS. |
| gps_date_stamp | string | r/w | Obtiene o establece la cadena de caracteres GPS que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la dirección GPS al punto de destino. |
| gps_dest_bearing_ref | string | r/w | Obtiene o establece la referencia GPS utilizada para indicar la dirección al punto de destino. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la distancia GPS al punto de destino. |
| gps_dest_distance_ref | string | r/w | Obtiene o establece la unidad GPS utilizada para expresar la distancia al punto de destino. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la latitud GPS del punto de destino. |
| gps_dest_latitude_ref | string | r/w | Obtiene o establece el valor GPS que indica si la latitud del punto de destino es norte o sur. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la longitud GPS del punto de destino. |
| gps_dest_longitude_ref | string | r/w | Obtiene o establece el valor GPS que indica si la longitud del punto de destino es este u oeste. |
| gps_differential | ushort | r/w | Obtiene o establece un valor GPS que indica si se aplica corrección diferencial al receptor GPS. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la dirección GPS de la imagen cuando fue capturada. |
| gps_img_direction_ref | string | r/w | Obtiene o establece la referencia GPS para indicar la dirección de la imagen cuando se captura. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la latitud GPS. |
| gps_latitude_ref | string | r/w | Obtiene o establece si la latitud GPS es norte o sur. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la longitud GPS. |
| gps_longitude_ref | string | r/w | Obtiene o establece si la longitud GPS es este u oeste. |
| gps_map_datum | string | r/w | Obtiene o establece los datos de levantamiento geodésico GPS utilizados por el receptor GPS. |
| gps_measure_mode | string | r/w | Obtiene o establece el modo de medición GPS. |
| gps_processing_method | byte | r/w | Obtiene o establece la cadena de caracteres GPS que registra el nombre del método utilizado para la localización. |
| gps_satellites | string | r/w | Obtiene o establece los satélites GPS utilizados para las mediciones. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la velocidad del movimiento del receptor GPS. |
| gps_speed_ref | string | r/w | Obtiene o establece la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. |
| gps_status | string | r/w | Obtiene o establece el estado del receptor GPS cuando se registra la imagen. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece etiquetas, que pertenecen solo a la sección GPS. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la hora GPS como UTC (Tiempo Universal Coordinado). |
| gps_track | string | r/w | Obtiene o establece la dirección del movimiento del receptor GPS. |
| gps_track_ref | string | r/w | Obtiene o establece la referencia para indicar la dirección del movimiento del receptor GPS. |
| gps_version_id | byte | r/w | Obtiene o establece el identificador de versión GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el DOP GPS (grado de precisión de los datos). |
| image_description | string | r/w | Obtiene o establece la descripción de la imagen. |
| image_length | uint | r/w | Obtiene o establece la longitud de la imagen. |
| image_unique_id | string | r/w | Obtiene o establece el identificador único de la imagen. |
| image_width | uint | r/w | Obtiene o establece el ancho de la imagen. |
| is_big_endian | bool | r/w | Obtiene o establece un valor que indica si los datos EXIF del flujo creados son big endian. |
| iso_speed | uint | r/w | Obtiene o establece la velocidad ISO |
| iso_speed_latitude_yyy | uint | r/w | Obtiene o establece el valor de latitud yyy de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Obtiene o establece el valor de latitud zzz de velocidad ISO de una cámara o dispositivo de entrada definido en ISO 12232. |
| lens_make | string | r/w | Obtiene o establece el fabricante del objetivo. |
| lens_model | string | r/w | Obtiene o establece el modelo del objetivo. |
| lens_serial_number | string | r/w | Obtiene o establece el número de serie del objetivo. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la especificación del objetivo |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Obtiene o establece la fuente de luz. |
| make | string | r/w | Obtiene o establece el fabricante del equipo de grabación. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Obtiene los datos de la nota del fabricante. |
| maker_note_raw_data | byte | r/w | Obtiene o establece los datos sin procesar de la nota del fabricante. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el valor de apertura máxima. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Obtiene o establece el modo de medición. |
| model | string | r/w | Obtiene o establece el modelo. |
| oecf | byte | r/w | Obtiene o establece la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | Obtiene o establece la orientación. |
| photographic_sensitivity | uint | r/w | Obtiene o establece la sensibilidad fotográfica. |
| photometric_interpretation | ushort | r/w | Obtiene o establece la interpretación fotométrica. |
| pixel_x_dimension | uint | r/w | Obtiene o establece la dimensión x del píxel. |
| pixel_y_dimension | uint | r/w | Obtiene o establece la dimensión y del píxel. |
| planar_configuration | ushort | r/w | Obtiene o establece la configuración planar. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la cromaticidad de los tres colores primarios de la imagen. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece todas las etiquetas EXIF (incluyendo etiquetas comunes y GPS). |
| recommended_exposure_index | uint | r/w | Obtiene o establece el índice de exposición recomendado. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece el negro y blanco de referencia. |
| related_sound_file | string | r/w | Obtiene o establece el archivo de sonido relacionado. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Obtiene o establece la unidad de resolución. |
| samples_per_pixel | ushort | r/w | Obtiene o establece las muestras por píxel. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Obtiene o establece la saturación. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Obtiene o establece el tipo de captura de escena. |
| scene_type | byte | r/w | Obtiene o establece el tipo de escena. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Obtiene o establece el método de detección. |
| sensitivity_type | ushort | r/w | Obtiene o establece el tipo de sensibilidad. |
| sharpness | ushort | r/w | Obtiene o establece la nitidez. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Obtiene o establece el valor de la velocidad de obturación. |
| software | string | r/w | Obtiene o establece el software. |
| spatial_frequency_response | byte | r/w | Obtiene o establece la respuesta de frecuencia espacial. |
| spectral_sensitivity | string | r/w | Obtiene o establece la sensibilidad espectral. |
| standard_output_sensitivity | uint | r/w | Obtiene o establece la sensibilidad de salida estándar |
| subject_area | ushort | r/w | Obtiene o establece el área del sujeto. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la distancia del sujeto. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Obtiene o establece el rango de distancia del sujeto. |
| subject_location | ushort | r/w | Obtiene o establece la ubicación del sujeto. |
| subsec_time | string | r/w | Obtiene o establece las fracciones de segundo para la etiqueta DateTime. |
| subsec_time_digitized | string | r/w | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeDigitized. |
| subsec_time_original | string | r/w | Obtiene o establece las fracciones de segundo para la etiqueta DateTimeOriginal. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | Obtiene o establece la imagen en miniatura. |
| transfer_function | ushort | r/w | Obtiene o establece la función de transferencia. |
| user_comment | string | r/w | Obtiene o establece el comentario del usuario. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Obtiene o establece el balance de blancos. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la cromaticidad del punto blanco de la imagen. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece los coeficientes de la matriz para la transformación de datos de imagen de RGB a YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | Obtiene o establece la posición de los componentes de crominancia en relación con el componente de luminancia. |
| y_cb_cr_sub_sampling | ushort | r/w | Obtiene o establece la proporción de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Eliminar etiqueta del contenedor |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Eliminar etiqueta del contenedor |
| [serialize_exif_data()](#serialize_exif_data__3) | Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño más influyente es el contenido de la etiqueta Miniatura. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Inicializa una nueva instancia de la clase [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Inicializa una nueva instancia de la clase [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con datos del array.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Las etiquetas comunes. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Las etiquetas EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Las etiquetas GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Inicializa una nueva instancia de la clase [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con datos del array.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Matriz de etiquetas EXIF junto con etiquetas comunes y GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Eliminar etiqueta del contenedor

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | La etiqueta a eliminar |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Eliminar etiqueta del contenedor

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_id | ushort | El identificador de la etiqueta a eliminar. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño más influyente es el contenido de la etiqueta Miniatura.

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Los datos EXIF serializados. |


