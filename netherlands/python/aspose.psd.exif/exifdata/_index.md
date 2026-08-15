---
title: "ExifData Class"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ExifData()](#ExifData__1) | Initialiseert een nieuw exemplaar van de [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) klasse. |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Initialiseert een nieuw exemplaar van de [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) klasse met gegevens uit een array. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Initialiseert een nieuw exemplaar van de [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) klasse met gegevens uit een array. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de diafragmawaarde in. |
| body_serial_number | string | r/w | Haalt of stelt het serienummer van de camerabehuizing in. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Haalt de helderheidswaarde op of stelt deze in. |
| camera_owner_name | string | r/w | Haalt de naam van de camerabeheerder op of stelt deze in |
| cfa_pattern | byte | r/w | Haalt het CFA-patroon op of stelt dit in. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Haalt de kleurenruimte op of stelt deze in. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Haalt tags op of stelt ze in, die tot de algemene sectie behoren. Dit is alleen van toepassing op jpeg-afbeeldingen; bij TIFF-indeling worden tiffOptions in plaats daarvan gebruikt. |
| components_configuration | byte | r/w | Haalt de componentconfiguratie op of stelt deze in. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt het aantal gecomprimeerde bits per pixel op of stelt dit in. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Haalt het contrast op of stelt dit in. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Haalt de aangepaste weergave op of stelt deze in. |
| date_time_digitized | string | r/w | Haalt de gedigitaliseerde datum en tijd op of stelt deze in. |
| date_time_original | string | r/w | Haalt de oorspronkelijke datum en tijd op of stelt deze in. |
| device_setting_description | byte | r/w | Haalt de beschrijving van apparaatinstellingen op of stelt deze in. |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt de digitale zoomverhouding op of stelt deze in. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Haalt tags op of stelt ze in die uitsluitend tot de EXIF-sectie behoren. |
| exif_version | byte | r/w | Haalt de EXIF-versie op of stelt deze in. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Haalt de belichtingsbiaswaarde op of stelt deze in. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt de belichtingsindex op of stelt deze in. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Haalt de belichtingsmodus op of stelt deze in. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Haalt het belichtingsprogramma op of stelt dit in. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de belichtingstijd in. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt het F-getal in. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Haalt of stelt het bestandbrontype in. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Haalt of stelt de flits in. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de flitsenergie in. |
| flashpix_version | byte | r/w | Haalt of stelt de flash-pix-versie in. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de brandpuntsafstand in. |
| focal_length_in_35_mm_film | ushort | r/w | Haalt of stelt de brandpuntsafstand in 35 mm film in. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Haalt of stelt de resolutie-eenheid van het brandpuntvlak in. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de x-resolutie van het brandpuntvlak in. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de y-resolutie van het brandpuntvlak in. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Haalt of stelt de graad van algemene beeldversterkingsaanpassing in. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt de gamma op of stelt deze in. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de GPS-hoogte in. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Haalt of stelt de GPS-hoogte die als referentiehoogte wordt gebruikt in. |
| gps_area_information | byte | r/w | Haalt of stelt de GPS-gebiedsinformatie in. |
| gps_date_stamp | string | r/w | Haalt of stelt de GPS-tekenreeks die datum- en tijdinformatie registreert ten opzichte van UTC (gecoördineerde wereldtijd) in. |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de GPS-richting naar het bestemmingspunt in. |
| gps_dest_bearing_ref | string | r/w | Haalt of stelt de GPS-referentie die wordt gebruikt om de richting naar het bestemmingspunt te geven in. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de GPS-afstand naar het bestemmingspunt in. |
| gps_dest_distance_ref | string | r/w | Haalt op of stelt de GPS-eenheid in die wordt gebruikt om de afstand tot het bestemmingspunt uit te drukken. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS-breedtegraad van het bestemmingspunt in. |
| gps_dest_latitude_ref | string | r/w | Haalt op of stelt de GPS-waarde in die aangeeft of de breedtegraad van het bestemmingspunt noordelijk of zuidelijk is. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS-lengtegraad van het bestemmingspunt in. |
| gps_dest_longitude_ref | string | r/w | Haalt op of stelt de GPS-waarde in die aangeeft of de lengtegraad van het bestemmingspunt oostelijk of westelijk is. |
| gps_differential | ushort | r/w | Haalt op of stelt een GPS-waarde in die aangeeft of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS-richting van de afbeelding in op het moment dat deze werd vastgelegd. |
| gps_img_direction_ref | string | r/w | Haalt op of stelt de GPS-referentie in voor het geven van de richting van de afbeelding wanneer deze wordt vastgelegd. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS-breedtegraad in. |
| gps_latitude_ref | string | r/w | Haalt op of stelt de GPS-breedtegraad in als noordelijk of zuidelijk. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS-lengtegraad in. |
| gps_longitude_ref | string | r/w | Haalt op of stelt de GPS-lengtegraad in als oostelijk of westelijk. |
| gps_map_datum | string | r/w | Haalt op of stelt de GPS-geodetische surveygegevens in die door de GPS-ontvanger worden gebruikt. |
| gps_measure_mode | string | r/w | Haalt op of stelt de GPS-meetmodus in. |
| gps_processing_method | byte | r/w | Haalt op of stelt de GPS-tekenreeks in die de naam van de gebruikte methode voor locatiebepaling registreert. |
| gps_satellites | string | r/w | Haalt op of stelt de GPS-satellieten in die voor metingen worden gebruikt. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de snelheid van de beweging van de GPS-ontvanger in. |
| gps_speed_ref | string | r/w | Haalt op of stelt de eenheid in die wordt gebruikt om de snelheid van de beweging van de GPS-ontvanger uit te drukken. |
| gps_status | string | r/w | Haalt op of stelt de status van de GPS-ontvanger in op het moment dat de afbeelding wordt vastgelegd. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Haalt op of stelt tags in die uitsluitend tot de GPS-sectie behoren. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS-tijd in als UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Haalt op of stelt de richting van de GPS-ontvangerbeweging in. |
| gps_track_ref | string | r/w | Haalt op of stelt de referentie in voor het aangeven van de richting van de GPS-ontvangerbeweging. |
| gps_version_id | byte | r/w | Haalt op of stelt de GPS-versie-identificatie in. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de GPS DOP (data degree of precision) in. |
| image_unique_id | string | r/w | Haalt op of stelt de unieke identifier van de afbeelding in. |
| is_big_endian | bool | r/w | Haalt op of stelt een waarde in die aangeeft of de EXIF-gegevensstroom die ervan is gemaakt big endian is. |
| iso_speed | uint | r/w | Haalt op of stelt de ISO-snelheid in. |
| iso_speed_latitude_yyy | uint | r/w | Haalt op of stelt de ISO-snelheid latitude yyy-waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Haalt op of stelt de ISO-snelheid latitude zzz-waarde van een camera of invoerapparaat in die is gedefinieerd in ISO 12232. |
| lens_make | string | r/w | Krijgt of stelt de fabrikant van de lens in. |
| lens_model | string | r/w | Krijgt of stelt het lensmodel in. |
| lens_serial_number | string | r/w | Krijgt of stelt het serienummer van de lens in. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Krijgt of stelt de lensspecificatie in. |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Krijgt of stelt de lichtbron in. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Krijgt de makeropmerkingsgegevens op. |
| maker_note_raw_data | byte | r/w | Krijgt of stelt de ruwe makeropmerkingsgegevens in. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Krijgt of stelt de maximale diafragmawaarde in. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Krijgt of stelt de meetmodus in. |
| oecf | byte | r/w | Krijgt of stelt de Opto-Electrische Conversiefunctie (OECF) gespecificeerd in ISO 14524 in. |
| photographic_sensitivity | uint | r/w | Krijgt of stelt de fotografische gevoeligheid in. |
| pixel_x_dimension | uint | r/w | Krijgt of stelt de pixel x-dimensie in. |
| pixel_y_dimension | uint | r/w | Krijgt of stelt de pixel y-dimensie in. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Krijgt of stelt alle EXIF-tags in (inclusief algemene en GPS-tags). |
| recommended_exposure_index | uint | r/w | Krijgt of stelt de aanbevolen belichtingsindex in. |
| related_sound_file | string | r/w | Haalt of stelt het gerelateerde geluidsbestand in. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Haalt of stelt de verzadiging in. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Haalt of stelt het type scène-opname in. |
| scene_type | byte | r/w | Haalt of stelt het type scène in. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Haalt of stelt de detectiemethode in. |
| sensitivity_type | ushort | r/w | Haalt of stelt het type gevoeligheid in. |
| sharpness | ushort | r/w | Haalt of stelt de scherpte in. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Haalt of stelt de sluitertijdwaarde in. |
| spatial_frequency_response | byte | r/w | Haalt of stelt de ruimtelijke frequentierespons in. |
| spectral_sensitivity | string | r/w | Haalt of stelt de spectrale gevoeligheid in. |
| standard_output_sensitivity | uint | r/w | Haalt of stelt de standaard uitgangsgevoeligheid in |
| subject_area | ushort | r/w | Haalt of stelt het onderwerpgebied in. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt of stelt de onderwerpafstand in. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Haalt of stelt het bereik van de onderwerpafstand in. |
| subject_location | ushort | r/w | Haalt of stelt de locatie van het onderwerp in. |
| subsec_time | string | r/w | Haalt of stelt de fracties van seconden voor de DateTime-tag in. |
| subsec_time_digitized | string | r/w | Haalt op of stelt de fracties van seconden in voor de DateTimeDigitized-tag. |
| subsec_time_original | string | r/w | Haalt op of stelt de fracties van seconden in voor de DateTimeOriginal-tag. |
| user_comment | string | r/w | Haalt op of stelt de gebruikersopmerking in. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Haalt op of stelt de witbalans in. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de chromaticiteit van het witte punt van de afbeelding in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Tag verwijderen uit container |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Tag verwijderen uit container |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Initialiseert een nieuw exemplaar van de [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) klasse.

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Initialiseert een nieuw exemplaar van de [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) klasse met gegevens uit een array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De algemene tags. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De EXIF-tags. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De GPS-tags. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Initialiseert een nieuw exemplaar van de [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) klasse met gegevens uit een array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Array van EXIF-tags samen met algemene en GPS-tags. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Tag verwijderen uit container

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | De te verwijderen tag |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Tag verwijderen uit container

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tag_id | ushort | De tag‑identificatie om te verwijderen. |

