---
title: "Classe ExifData"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ExifData()](#ExifData__1) | Initialise une nouvelle instance de la classe [ExifData](/psd/python-net/aspose.psd.exif/exifdata/). |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Initialise une nouvelle instance de la classe [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) avec des données provenant d'un tableau. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Initialise une nouvelle instance de la classe [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) avec des données provenant d'un tableau. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la valeur d'ouverture. |
| body_serial_number | chaîne | r/w | Obtient ou définit le numéro de série du boîtier de l'appareil photo. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Obtient ou définit la valeur de luminosité. |
| camera_owner_name | chaîne | r/w | Obtient ou définit le nom du propriétaire de la caméra |
| cfa_pattern | byte | r/w | Obtient ou définit le motif CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Obtient ou définit l'espace colorimétrique. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises, qui appartiennent à la section commune. Cela s'applique uniquement aux images jpeg, au format tiff les tiffOptions sont utilisées à la place |
| components_configuration | byte | r/w | Obtient ou définit la configuration des composants. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit les bits compressés par pixel. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Obtient ou définit le contraste. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Obtient ou définit le rendu personnalisé. |
| date_time_digitized | chaîne | r/w | Obtient ou définit la date et l'heure de numérisation. |
| date_time_original | chaîne | r/w | Obtient ou définit la date et l'heure d'origine. |
| device_setting_description | byte | r/w | Obtient ou définit la description des paramètres de l'appareil |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le rapport de zoom numérique. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises qui appartiennent uniquement à la section EXIF. |
| exif_version | byte | r/w | Obtient ou définit la version EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Obtient ou définit la valeur du biais d'exposition. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'indice d'exposition. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Obtient ou définit le mode d'exposition. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Obtient ou définit le programme d'exposition. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le temps d'exposition. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le nombre F. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Obtient ou définit le type de source du fichier. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Obtient ou définit le flash. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'énergie du flash. |
| flashpix_version | byte | r/w | Obtient ou définit la version flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la distance focale. |
| focal_length_in_35_mm_film | ushort | r/w | Obtient ou définit la distance focale en film 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Obtient ou définit l'unité de résolution du plan focal. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution x du plan focal. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution y du plan focal. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Obtient ou définit le degré d'ajustement global du gain de l'image. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'altitude GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Obtient ou définit l'altitude GPS utilisée comme altitude de référence. |
| gps_area_information | byte | r/w | Obtient ou définit les informations de zone GPS. |
| gps_date_stamp | chaîne | r/w | Obtient ou définit la chaîne de caractères GPS enregistrant les informations de date et d'heure relatives à UTC (Temps Universel Coordonné). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'azimut GPS vers le point de destination. |
| gps_dest_bearing_ref | chaîne | r/w | Obtient ou définit la référence GPS utilisée pour fournir l'azimut vers le point de destination. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la distance GPS au point de destination. |
| gps_dest_distance_ref | chaîne | r/w | Obtient ou définit l'unité GPS utilisée pour exprimer la distance jusqu'au point de destination. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la latitude GPS du point de destination. |
| gps_dest_latitude_ref | chaîne | r/w | Obtient ou définit la valeur GPS indiquant si la latitude du point de destination est nord ou sud. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la longitude GPS du point de destination. |
| gps_dest_longitude_ref | chaîne | r/w | Obtient ou définit la valeur GPS indiquant si la longitude du point de destination est est ou ouest. |
| gps_differential | ushort | r/w | Obtient ou définit une valeur GPS indiquant si une correction différentielle est appliquée au récepteur GPS. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la direction GPS de l'image lorsqu'elle a été capturée. |
| gps_img_direction_ref | chaîne | r/w | Obtient ou définit la référence GPS indiquant la direction de l'image lors de la capture. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la latitude GPS. |
| gps_latitude_ref | chaîne | r/w | Obtient ou définit si la latitude GPS est nord ou sud. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la longitude GPS. |
| gps_longitude_ref | chaîne | r/w | Obtient ou définit si la longitude GPS est est ou ouest. |
| gps_map_datum | chaîne | r/w | Obtient ou définit les données d'enquête géodésique GPS utilisées par le récepteur GPS. |
| gps_measure_mode | chaîne | r/w | Obtient ou définit le mode de mesure GPS. |
| gps_processing_method | byte | r/w | Obtient ou définit la chaîne de caractères GPS enregistrant le nom de la méthode utilisée pour la localisation. |
| gps_satellites | chaîne | r/w | Obtient ou définit les satellites GPS utilisés pour les mesures. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la vitesse du mouvement du récepteur GPS. |
| gps_speed_ref | chaîne | r/w | Obtient ou définit l'unité utilisée pour exprimer la vitesse du mouvement du récepteur GPS. |
| gps_status | chaîne | r/w | Obtient ou définit l'état du récepteur GPS lors de l'enregistrement de l'image. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises, qui appartiennent uniquement à la section GPS. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit l'heure GPS en UTC (Temps Universel Coordonné). |
| gps_track | chaîne | r/w | Obtient ou définit la direction du mouvement du récepteur GPS. |
| gps_track_ref | chaîne | r/w | Obtient ou définit la référence pour indiquer la direction du mouvement du récepteur GPS. |
| gps_version_id | byte | r/w | Obtient ou définit l'identifiant de version GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit le DOP GPS (degré de précision des données). |
| image_unique_id | chaîne | r/w | Obtient ou définit l'identifiant unique de l'image. |
| is_big_endian | bool | r/w | Obtient ou définit une valeur indiquant si le flux de données EXIF créé est en big endian. |
| iso_speed | uint | r/w | Obtient ou définit la vitesse ISO |
| iso_speed_latitude_yyy | uint | r/w | Obtient ou définit la valeur de latitude yyy de la vitesse ISO d'un appareil photo ou d'un dispositif d'entrée tel que défini dans la norme ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Obtient ou définit la valeur de latitude zzz de la vitesse ISO d'un appareil photo ou d'un dispositif d'entrée tel que défini dans la norme ISO 12232. |
| lens_make | chaîne | r/w | Obtient ou définit le fabricant de l'objectif. |
| lens_model | chaîne | r/w | Obtient ou définit le modèle de l'objectif. |
| lens_serial_number | chaîne | r/w | Obtient ou définit le numéro de série de l'objectif. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la spécification de l'objectif |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Obtient ou définit la source de lumière. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Obtient les données de la note du fabricant. |
| maker_note_raw_data | byte | r/w | Obtient ou définit les données brutes de la note du fabricant. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la valeur maximale d'ouverture. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Obtient ou définit le mode de mesure. |
| oecf | byte | r/w | Obtient ou définit la fonction de conversion opto-électrique (OECF) spécifiée dans la norme ISO 14524. |
| photographic_sensitivity | uint | r/w | Obtient ou définit la sensibilité photographique. |
| pixel_x_dimension | uint | r/w | Obtient ou définit la dimension x du pixel. |
| pixel_y_dimension | uint | r/w | Obtient ou définit la dimension y du pixel. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit toutes les balises EXIF (y compris les balises communes et GPS). |
| recommended_exposure_index | uint | r/w | Obtient ou définit l'indice d'exposition recommandé. |
| related_sound_file | chaîne | r/w | Obtient ou définit le fichier son associé. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Obtient ou définit la saturation. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Obtient ou définit le type de capture de la scène. |
| scene_type | byte | r/w | Obtient ou définit le type de scène. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Obtient ou définit la méthode de détection. |
| sensitivity_type | ushort | r/w | Obtient ou définit le type de sensibilité. |
| sharpness | ushort | r/w | Obtient ou définit la netteté. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Obtient ou définit la valeur de la vitesse d’obturation. |
| spatial_frequency_response | byte | r/w | Obtient ou définit la réponse en fréquence spatiale. |
| spectral_sensitivity | chaîne | r/w | Obtient ou définit la sensibilité spectrale. |
| standard_output_sensitivity | uint | r/w | Obtient ou définit la sensibilité de sortie standard |
| subject_area | ushort | r/w | Obtient ou définit la zone du sujet. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la distance du sujet. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Obtient ou définit la plage de distance du sujet. |
| subject_location | ushort | r/w | Obtient ou définit l’emplacement du sujet. |
| subsec_time | chaîne | r/w | Obtient ou définit les fractions de seconde pour le tag DateTime. |
| subsec_time_digitized | chaîne | r/w | Obtient ou définit les fractions de seconde pour le tag DateTimeDigitized. |
| subsec_time_original | chaîne | r/w | Obtient ou définit les fractions de seconde pour le tag DateTimeOriginal. |
| user_comment | chaîne | r/w | Obtient ou définit le commentaire de l'utilisateur. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Obtient ou définit la balance des blancs. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la chromaticité du point blanc de l'image. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Supprimer le tag du conteneur |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Supprimer le tag du conteneur |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Initialise une nouvelle instance de la classe [ExifData](/psd/python-net/aspose.psd.exif/exifdata/).

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Initialise une nouvelle instance de la classe [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) avec des données provenant d'un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Les tags communs. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Les tags EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Les tags GPS. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Initialise une nouvelle instance de la classe [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) avec des données provenant d'un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Tableau de tags EXIF avec les tags communs et GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Supprimer le tag du conteneur

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Le tag à supprimer |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Supprimer le tag du conteneur

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_id | ushort | L'identifiant du tag à supprimer. |

