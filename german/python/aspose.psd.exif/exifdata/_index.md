---
title: "ExifData Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.exif/exifdata/
---

**Summary:** EXIF data container.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifData

**Inheritance:** TiffDataTypeController

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ExifData()](#ExifData__1) | Initialisiert eine neue Instanz der [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) Klasse. |
| [ExifData(common_tags, exif_tags, gps_tags)](#ExifData_common_tags_exif_tags_gps_tags_2) | Initialisiert eine neue Instanz der [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) Klasse mit Daten aus einem Array. |
| [ExifData(exifdata)](#ExifData_exifdata_3) | Initialisiert eine neue Instanz der [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) Klasse mit Daten aus einem Array. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den Blendenwert. |
| body_serial_number | string | r/w | Liest oder setzt die Seriennummer des Kameragehäuses. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Liest oder setzt den Helligkeitswert. |
| camera_owner_name | string | r/w | Liest oder setzt den Namen des Kamerabesitzers |
| cfa_pattern | byte | r/w | Liest oder setzt das CFA-Muster. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Liest oder setzt den Farbraum. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt Tags, die zum gemeinsamen Abschnitt gehören. Dies gilt nur für JPEG‑Bilder; im TIFF‑Format werden stattdessen tiffOptions verwendet. |
| components_configuration | byte | r/w | Liest oder setzt die Komponenten‑Konfiguration. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die komprimierten Bits pro Pixel. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Liest oder setzt den Kontrast. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Liest oder setzt die benutzerdefinierte Darstellung. |
| date_time_digitized | string | r/w | Liest oder setzt das digitalisierte Datum und die Uhrzeit. |
| date_time_original | string | r/w | Liest oder setzt das ursprüngliche Datum und die Uhrzeit. |
| device_setting_description | byte | r/w | Liest oder setzt die Beschreibung der Geräteeinstellungen |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt das digitale Zoom‑Verhältnis. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt Tags, die ausschließlich zum EXIF‑Abschnitt gehören. |
| exif_version | byte | r/w | Liest oder setzt die EXIF-Version. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Liest oder setzt den Belichtungswert. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den Belichtungsindex. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Liest oder setzt den Belichtungsmodus. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Liest oder setzt das Belichtungsprogramm. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Belichtungszeit. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Blendenzahl. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Liest oder setzt den Dateiquellentyp. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Liest oder setzt den Blitz. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Blitzenergie. |
| flashpix_version | byte | r/w | Liest oder setzt die Blitz-Pix-Version. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Brennweite. |
| focal_length_in_35_mm_film | ushort | r/w | Liest oder setzt die Brennweite in 35‑mm-Film. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Liest oder setzt die Auflösungseinheit der Bildebene. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die X-Auflösung der Bildebene. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Y-Auflösung der Bildebene. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Liest oder setzt den Grad der Gesamtbildverstärkungsanpassung. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt das Gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Höhe. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Liest oder setzt die GPS-Höhe, die als Referenzhöhe verwendet wird. |
| gps_area_information | byte | r/w | Liest oder setzt die GPS-Areainformation. |
| gps_date_stamp | string | r/w | Liest oder setzt die GPS-Zeichenkette, die Datum- und Zeitinformationen relativ zu UTC (Koordinierte Weltzeit) aufzeichnet. |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Peilung zum Zielpunkt. |
| gps_dest_bearing_ref | string | r/w | Liest oder setzt die GPS-Referenz, die zur Angabe der Peilung zum Zielpunkt verwendet wird. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Entfernung zum Zielpunkt. |
| gps_dest_distance_ref | string | r/w | Liest oder setzt die GPS-Einheit, die zur Angabe der Entfernung zum Zielpunkt verwendet wird. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Breitengrad des Zielpunkts. |
| gps_dest_latitude_ref | string | r/w | Liest oder setzt den GPS-Wert, der angibt, ob der Breitengrad des Zielpunkts nördlich oder südlich liegt. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Längengrad des Zielpunkts. |
| gps_dest_longitude_ref | string | r/w | Liest oder setzt den GPS-Wert, der angibt, ob der Längengrad des Zielpunkts östlich oder westlich liegt. |
| gps_differential | ushort | r/w | Liest oder setzt einen GPS-Wert, der angibt, ob eine Differentialkorrektur auf den GPS-Empfänger angewendet wird. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Richtung des Bildes zum Zeitpunkt der Aufnahme. |
| gps_img_direction_ref | string | r/w | Liest oder setzt die GPS-Referenz zur Angabe der Bildrichtung bei der Aufnahme. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Breitengrad. |
| gps_latitude_ref | string | r/w | Liest oder setzt, ob die GPS-Breitengrad nördlich oder südlich ist. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS-Längengrad. |
| gps_longitude_ref | string | r/w | Liest oder setzt, ob die GPS-Längengrad östlich oder westlich ist. |
| gps_map_datum | string | r/w | Liest oder setzt die GPS-geodätischen Vermessungsdaten, die vom GPS-Empfänger verwendet werden. |
| gps_measure_mode | string | r/w | Liest oder setzt den GPS-Messmodus. |
| gps_processing_method | byte | r/w | Liest oder setzt die GPS-Zeichenkette, die den Namen der für die Positionsbestimmung verwendeten Methode aufzeichnet. |
| gps_satellites | string | r/w | Liest oder setzt die für Messungen verwendeten GPS‑Satelliten. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Geschwindigkeit der GPS‑Empfängerbewegung. |
| gps_speed_ref | string | r/w | Liest oder setzt die Einheit, die zur Angabe der Geschwindigkeit der GPS‑Empfängerbewegung verwendet wird. |
| gps_status | string | r/w | Liest oder setzt den Status des GPS‑Empfängers, wenn das Bild aufgenommen wird. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt Tags, die ausschließlich zum GPS‑Abschnitt gehören. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die GPS‑Zeit als UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Liest oder setzt die Richtung der GPS‑Empfängerbewegung. |
| gps_track_ref | string | r/w | Liest oder setzt die Referenz zur Angabe der Richtung der GPS‑Empfängerbewegung. |
| gps_version_id | byte | r/w | Liest oder setzt die GPS‑Versionskennung. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den GPS‑DOP (Data Degree of Precision). |
| image_unique_id | string | r/w | Liest oder setzt die eindeutige Bildkennung. |
| is_big_endian | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die aus dem Stream erstellten EXIF‑Daten big endian sind. |
| iso_speed | uint | r/w | Liest oder setzt ISO speed |
| iso_speed_latitude_yyy | uint | r/w | Liest oder setzt den ISO speed latitude yyy-Wert einer Kamera oder eines Eingabegeräts, das in ISO 12232 definiert ist. |
| iso_speed_latitude_zzz | uint | r/w | Liest oder setzt den ISO speed latitude zzz-Wert einer Kamera oder eines Eingabegeräts, das in ISO 12232 definiert ist. |
| lens_make | string | r/w | Liest oder setzt den Hersteller des Objektivs. |
| lens_model | string | r/w | Liest oder setzt das Objektivmodell. |
| lens_serial_number | string | r/w | Liest oder setzt die Seriennummer des Objektivs. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Objektivspezifikation |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Liest oder setzt die Lichtquelle. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Liest die Maker-Notizdaten. |
| maker_note_raw_data | byte | r/w | Liest oder setzt die rohen Maker-Notizdaten. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt den maximalen Blendenwert. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Liest oder setzt den Messmodus. |
| oecf | byte | r/w | Liest oder setzt die Opto-Electric Conversion Function (OECF), die in ISO 14524 angegeben ist. |
| photographic_sensitivity | uint | r/w | Liest oder setzt die fotografische Empfindlichkeit. |
| pixel_x_dimension | uint | r/w | Liest oder setzt die Pixel‑X‑Dimension. |
| pixel_y_dimension | uint | r/w | Liest oder setzt die Pixel‑Y‑Dimension. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt alle EXIF‑Tags (einschließlich gängiger und GPS‑Tags). |
| recommended_exposure_index | uint | r/w | Liest oder setzt den empfohlenen Belichtungsindex. |
| related_sound_file | string | r/w | Liest oder setzt die zugehörige Audiodatei. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Liest oder setzt die Sättigung. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Liest oder setzt den Aufnahmetyp der Szene. |
| scene_type | byte | r/w | Liest oder setzt den Szenentyp. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Liest oder setzt die Erfassungsmethode. |
| sensitivity_type | ushort | r/w | Liest oder setzt den Empfindlichkeitstyp. |
| sharpness | ushort | r/w | Liest oder setzt die Schärfe. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Liest oder setzt den Verschlusszeitwert. |
| spatial_frequency_response | byte | r/w | Liest oder setzt die räumliche Frequenzantwort. |
| spectral_sensitivity | string | r/w | Liest oder setzt die spektrale Empfindlichkeit. |
| standard_output_sensitivity | uint | r/w | Liest oder setzt die standardmäßige Ausgangsempfindlichkeit |
| subject_area | ushort | r/w | Liest oder setzt den Motivbereich. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Motiventfernung. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Liest oder setzt den Motiventfernungsbereich. |
| subject_location | ushort | r/w | Liest oder setzt den subject location. |
| subsec_time | string | r/w | Liest oder setzt die Sekundenbruchteile für das DateTime-Tag. |
| subsec_time_digitized | string | r/w | Liest oder setzt die Sekundenbruchteile für das DateTimeDigitized-Tag. |
| subsec_time_original | string | r/w | Liest oder setzt die Sekundenbruchteile für das DateTimeOriginal-Tag. |
| user_comment | string | r/w | Liest oder setzt den user comment. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Liest oder setzt den Weißabgleich. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die Chromatik des Weißpunkts des Bildes. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Tag aus dem Container entfernen |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Tag aus dem Container entfernen |


### Constructor: ExifData() {#ExifData__1}


```
 ExifData() 
```

Initialisiert eine neue Instanz der [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) Klasse.

### Constructor: ExifData(common_tags, exif_tags, gps_tags) {#ExifData_common_tags_exif_tags_gps_tags_2}


```
 ExifData(common_tags, exif_tags, gps_tags) 
```

Initialisiert eine neue Instanz der [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) Klasse mit Daten aus einem Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Die gemeinsamen Tags. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Die EXIF-Tags. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Die GPS-Tags. |

### Constructor: ExifData(exifdata) {#ExifData_exifdata_3}


```
 ExifData(exifdata) 
```

Initialisiert eine neue Instanz der [ExifData](/psd/python-net/aspose.psd.exif/exifdata/) Klasse mit Daten aus einem Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Array von EXIF-Tags zusammen mit gemeinsamen und GPS-Tags. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Tag aus dem Container entfernen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Der zu entfernende Tag |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Tag aus dem Container entfernen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | ushort | Der Tag-Identifikator zum Entfernen. |

