---
title: "ExifData-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ExifData()](#ExifData__1) | Initierar en ny instans av klassen [ExifData](/psd/python-net/aspose.psd.exif/exifdata/). |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Initierar en ny instans av klassen [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) med data från en array. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Initierar en ny instans av klassen [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) med data från en array. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger bländarvärdet. |
| body_serial_number | string | r/w | Hämtar eller anger kamerakroppens serienummer. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Hämtar eller anger ljusstyrkevärdet. |
| camera_owner_name | string | r/w | Hämtar eller anger kamerans ägarnamn |
| cfa_pattern | byte | r/w | Hämtar eller anger CFA-mönstret. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Hämtar eller anger färgrymden. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggar som tillhör den gemensamma sektionen. Detta gäller endast för jpeg‑bilder, i tiff‑format används tiffOptions istället. |
| components_configuration | byte | r/w | Hämtar eller anger komponenternas konfiguration. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger komprimerade bitar per pixel. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Hämtar eller anger kontrasten. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Hämtar eller anger den anpassade rendering. |
| date_time_digitized | string | r/w | Hämtar eller anger datum och tid för digitalisering. |
| date_time_original | string | r/w | Hämtar eller anger originalets datum och tid. |
| device_setting_description | byte | r/w | Hämtar eller anger beskrivning av enhetsinställningar |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger förhållandet för digital zoom. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggar som endast tillhör EXIF‑avsnittet. |
| exif_version | byte | r/w | Hämtar eller anger EXIF‑versionen. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Hämtar eller anger exponeringskompensationsvärdet. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger exponeringsindex. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Hämtar eller anger exponeringsläge. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Hämtar eller anger exponeringsprogram. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger exponeringstid. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger bländartalet. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Hämtar eller anger filkällans typ. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Hämtar eller anger blixten. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger blixtenergi. |
| flashpix_version | byte | r/w | Hämtar eller anger flash‑pix‑versionen. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger brännvidden. |
| focal_length_in_35_mm_film | ushort | r/w | Hämtar eller anger brännvidden i 35 mm‑film. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Hämtar eller anger upplösningsenheten för fokalplanet. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger fokalplanets X‑upplösning. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger fokalplanets y‑upplösning. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Hämtar eller anger graden av total bildförstärkningsjustering. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑höjden. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Hämtar eller anger GPS‑höjden som används som referenshöjd. |
| gps_area_information | byte | r/w | Hämtar eller anger GPS‑områdesinformationen. |
| gps_date_stamp | string | r/w | Hämtar eller anger GPS‑teckenkedjans datum‑ och tidsinformation i förhållande till UTC (Coordinated Universal Time). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑riktningen till destinationspunkten. |
| gps_dest_bearing_ref | string | r/w | Hämtar eller anger GPS‑referensen som används för att ange riktningen till destinationspunkten. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑avståndet till destinationspunkten. |
| gps_dest_distance_ref | string | r/w | Hämtar eller anger GPS‑enheten som används för att uttrycka avståndet till destinationspunkten. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑latituden för destinationspunkten. |
| gps_dest_latitude_ref | string | r/w | Hämtar eller anger GPS‑värdet som indikerar om latituden för destinationspunkten är norra eller södra latituden. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑longituden för destinationspunkten. |
| gps_dest_longitude_ref | string | r/w | Hämtar eller anger GPS‑värdet som indikerar om longituden för destinationspunkten är östra eller västra longituden. |
| gps_differential | ushort | r/w | Hämtar eller anger ett GPS‑värde som indikerar om differentialkorrigering tillämpas på GPS‑mottagaren. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS‑riktningen för bilden när den togs. |
| gps_img_direction_ref | string | r/w | Hämtar eller anger GPS‑referensen för att ange bildens riktning när den tas. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-latitud. |
| gps_latitude_ref | string | r/w | Hämtar eller anger om GPS-latituden är norr eller söder. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-longitud. |
| gps_longitude_ref | string | r/w | Hämtar eller anger om GPS-longituden är öst eller väst. |
| gps_map_datum | string | r/w | Hämtar eller anger de GPS-geodetiska undersökningsdata som används av GPS-mottagaren. |
| gps_measure_mode | string | r/w | Hämtar eller anger GPS-mätningsläget. |
| gps_processing_method | byte | r/w | Hämtar eller anger GPS-teckensnöret som registrerar namnet på metoden som används för positionsbestämning. |
| gps_satellites | string | r/w | Hämtar eller anger de GPS-satelliter som används för mätningar. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger hastigheten för GPS-mottagarens rörelse. |
| gps_speed_ref | string | r/w | Hämtar eller anger enheten som används för att uttrycka GPS-mottagarens rörelsehastighet. |
| gps_status | string | r/w | Hämtar eller anger statusen för GPS-mottagaren när bilden tas. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggar som endast tillhör GPS-avsnittet. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS-tiden som UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Hämtar eller anger riktningen för GPS-mottagarens rörelse. |
| gps_track_ref | string | r/w | Hämtar eller anger referensen för att ange riktningen för GPS-mottagarens rörelse. |
| gps_version_id | byte | r/w | Hämtar eller anger GPS‑versionsidentifieraren. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger GPS DOP (dataprecisionsgrad). |
| image_unique_id | string | r/w | Hämtar eller anger bildens unika identifierare. |
| is_big_endian | bool | r/w | Hämtar eller anger ett värde som indikerar om EXIF‑datastreamen som skapats från är big endian. |
| iso_speed | uint | r/w | Hämtar eller anger ISO‑hastighet |
| iso_speed_latitude_yyy | uint | r/w | Hämtar eller anger ISO‑hastighetslatitud yyy‑värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Hämtar eller anger ISO‑hastighetslatitud zzz‑värdet för en kamera eller inmatningsenhet som definieras i ISO 12232. |
| lens_make | string | r/w | Hämtar eller anger linsens tillverkare. |
| lens_model | string | r/w | Hämtar eller anger linsmodellen. |
| lens_serial_number | string | r/w | Hämtar eller anger linsens serienummer. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger linsens specifikation |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Hämtar eller anger ljuskällan. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Hämtar tillverkarens noteringsdata. |
| maker_note_raw_data | byte | r/w | Hämtar eller anger tillverkarens rådata för notering. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger maximalt bländarvärde. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Hämtar eller anger mätarläget. |
| oecf | byte | r/w | Hämtar eller anger den optoelektriska konverteringsfunktionen (OECF) som specificeras i ISO 14524. |
| photographic_sensitivity | uint | r/w | Hämtar eller anger den fotografiska känsligheten. |
| pixel_x_dimension | uint | r/w | Hämtar eller anger pixelns x-dimension. |
| pixel_y_dimension | uint | r/w | Hämtar eller anger pixelns y-dimension. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger alla EXIF-taggar (inklusive vanliga och GPS-taggar). |
| recommended_exposure_index | uint | r/w | Hämtar eller anger det rekommenderade exponeringsindexet. |
| related_sound_file | string | r/w | Hämtar eller anger den relaterade ljudfilen. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Hämtar eller anger mättnaden. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Hämtar eller anger sceninspelningstypen. |
| scene_type | byte | r/w | Hämtar eller anger scen-typen. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Hämtar eller anger avkänningsmetoden. |
| sensitivity_type | ushort | r/w | Hämtar eller anger känslighetstypen. |
| sharpness | ushort | r/w | Hämtar eller anger skärpan. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Hämtar eller anger slutartidsvärdet. |
| spatial_frequency_response | byte | r/w | Hämtar eller anger svar på rumslig frekvens. |
| spectral_sensitivity | string | r/w | Hämtar eller anger den spektrala känsligheten. |
| standard_output_sensitivity | uint | r/w | Hämtar eller anger standardutgångskänsligheten |
| subject_area | ushort | r/w | Hämtar eller anger ämnesområdet. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger avståndet till motivet. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Hämtar eller anger avståndsområdet för motivet. |
| subject_location | ushort | r/w | Hämtar eller anger motivets plats. |
| subsec_time | string | r/w | Hämtar eller anger bråkdelen av sekunder för DateTime-taggen. |
| subsec_time_digitized | string | r/w | Hämtar eller anger bråkdelen av sekunder för DateTimeDigitized-taggen. |
| subsec_time_original | string | r/w | Hämtar eller anger bråkdelen av sekunder för DateTimeOriginal-taggen. |
| user_comment | string | r/w | Hämtar eller anger användarkommentaren. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Hämtar eller anger vitbalansen. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger kromatiken för bildens vita punkt. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Ta bort tagg från behållaren |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Ta bort tagg från behållaren |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Initierar en ny instans av klassen [ExifData](/psd/python-net/aspose.psd.exif/exifdata/).

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Initierar en ny instans av klassen [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) med data från en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De vanliga taggarna. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | EXIF-taggarna. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | GPS-taggarna. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Initierar en ny instans av klassen [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) med data från en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Array av EXIF-taggar tillsammans med vanliga och GPS-taggar. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Ta bort tagg från behållaren

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Taggen att ta bort |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Ta bort tagg från behållaren

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | ushort | Taggidentifieraren att ta bort. |

