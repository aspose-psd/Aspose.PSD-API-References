---
title: "JpegExifData Classe"
type: docs
weight: 20
url: /it/python-net/aspose.psd.exif/jpegexifdata/
---

**Summary:** EXIF data container for jpeg files.

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.JpegExifData

**Inheritance:** ExifData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegExifData()](#JpegExifData__1) | Inizializza una nuova istanza della classe [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/). |
| [JpegExifData(common_tags, exif_tags, gps_tags)](#JpegExifData_common_tags_exif_tags_gps_tags_2) | Inizializza una nuova istanza della classe [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con dati da un array. |
| [JpegExifData(exifdata)](#JpegExifData_exifdata_3) | Inizializza una nuova istanza della classe [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con dati da un array. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| MAX_EXIF_SEGMENT_SIZE [static] | int | r | La dimensione massima del segmento EXIF in byte consentita. |
| aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il valore dell'apertura. |
| artista | string | r/w | Ottiene o imposta l'artista. |
| bits_per_sample | ushort | r/w | Ottiene o imposta i bit per campione. |
| body_serial_number | string | r/w | Ottiene o imposta il numero di serie del corpo della fotocamera. |
| brightness_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta il valore della luminosità. |
| camera_owner_name | string | r/w | Ottiene o imposta il nome del proprietario della fotocamera |
| cfa_pattern | byte | r/w | Ottiene o imposta il modello CFA. |
| color_space | [ExifColorSpace](/psd/python-net/aspose.psd.exif.enums/exifcolorspace/) | r/w | Ottiene o imposta lo spazio colore. |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag, che appartengono alla sezione comune. Questo si applica solo alle immagini jpeg; nel formato tiff vengono invece utilizzate tiffOptions. |
| components_configuration | byte | r/w | Ottiene o imposta la configurazione dei componenti. |
| compressed_bits_per_pixel | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta i bit compressi per pixel. |
| compression | ushort | r/w | Ottiene o imposta la compressione. |
| contrast | [ExifContrast](/psd/python-net/aspose.psd.exif.enums/exifcontrast/) | r/w | Ottiene o imposta il contrasto. |
| copyright | string | r/w | Ottiene o imposta il copyright. |
| custom_rendered | [ExifCustomRendered](/psd/python-net/aspose.psd.exif.enums/exifcustomrendered/) | r/w | Ottiene o imposta il rendering personalizzato. |
| date_time | string | r/w | Ottiene o imposta la data e ora. |
| date_time_digitized | string | r/w | Ottiene o imposta la data e ora di digitalizzazione. |
| date_time_original | string | r/w | Ottiene o imposta la data e ora originali. |
| device_setting_description | byte | r/w | Ottiene o imposta la descrizione delle impostazioni del dispositivo |
| digital_zoom_ratio | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il rapporto di zoom digitale. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag che appartengono solo alla sezione EXIF. |
| exif_version | byte | r/w | Ottiene o imposta la versione EXIF. |
| exposure_bias_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta il valore del bias di esposizione. |
| exposure_index | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'indice di esposizione. |
| exposure_mode | [ExifExposureMode](/psd/python-net/aspose.psd.exif.enums/exifexposuremode/) | r/w | Ottiene o imposta la modalità di esposizione. |
| exposure_program | [ExifExposureProgram](/psd/python-net/aspose.psd.exif.enums/exifexposureprogram/) | r/w | Ottiene o imposta il programma di esposizione. |
| exposure_time | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il tempo di esposizione. |
| f_number | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il numero F. |
| file_source | [ExifFileSource](/psd/python-net/aspose.psd.exif.enums/exiffilesource/) | r/w | Ottiene o imposta il tipo di origine del file. |
| flash | [ExifFlash](/psd/python-net/aspose.psd.exif.enums/exifflash/) | r/w | Ottiene o imposta il flash. |
| flash_energy | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'energia del flash. |
| flashpix_version | byte | r/w | Ottiene o imposta la versione flash pix. |
| focal_length | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la lunghezza focale. |
| focal_length_in_35_mm_film | ushort | r/w | Ottiene o imposta la lunghezza focale in pellicola da 35 mm. |
| focal_plane_resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Ottiene o imposta l'unità di risoluzione del piano focale. |
| focal_plane_x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione X del piano focale. |
| focal_plane_y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione Y del piano focale. |
| gain_control | [ExifGainControl](/psd/python-net/aspose.psd.exif.enums/exifgaincontrol/) | r/w | Ottiene o imposta il grado di regolazione complessiva del guadagno dell'immagine. |
| gamma | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la gamma. |
| gps_altitude | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'altitudine GPS. |
| gps_altitude_ref | [ExifGPSAltitudeRef](/psd/python-net/aspose.psd.exif.enums/exifgpsaltituderef/) | r/w | Ottiene o imposta l'altitudine GPS utilizzata come altitudine di riferimento. |
| gps_area_information | byte | r/w | Ottiene o imposta le informazioni dell'area GPS. |
| gps_date_stamp | string | r/w | Ottiene o imposta la stringa di caratteri GPS che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| gps_dest_bearing | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'azimut GPS verso il punto di destinazione. |
| gps_dest_bearing_ref | string | r/w | Ottiene o imposta il riferimento GPS utilizzato per fornire l'azimut verso il punto di destinazione. |
| gps_dest_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la distanza GPS verso il punto di destinazione. |
| gps_dest_distance_ref | string | r/w | Ottiene o imposta l'unità GPS utilizzata per esprimere la distanza dal punto di destinazione. |
| gps_dest_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la latitudine GPS del punto di destinazione. |
| gps_dest_latitude_ref | string | r/w | Ottiene o imposta il valore GPS che indica se la latitudine del punto di destinazione è nord o sud. |
| gps_dest_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la longitudine GPS del punto di destinazione. |
| gps_dest_longitude_ref | string | r/w | Ottiene o imposta il valore GPS che indica se la longitudine del punto di destinazione è est o ovest. |
| gps_differential | ushort | r/w | Ottiene o imposta un valore GPS che indica se la correzione differenziale è applicata al ricevitore GPS. |
| gps_img_direction | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la direzione GPS dell'immagine al momento della cattura. |
| gps_img_direction_ref | string | r/w | Ottiene o imposta il riferimento GPS per fornire la direzione dell'immagine al momento della cattura. |
| gps_latitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la latitudine GPS. |
| gps_latitude_ref | string | r/w | Ottiene o imposta se la latitudine GPS è nord o sud. |
| gps_longitude | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la longitudine GPS. |
| gps_longitude_ref | string | r/w | Ottiene o imposta se la longitudine GPS è est o ovest. |
| gps_map_datum | string | r/w | Ottiene o imposta i dati di rilevamento geodetico GPS utilizzati dal ricevitore GPS. |
| gps_measure_mode | string | r/w | Ottiene o imposta la modalità di misurazione GPS. |
| gps_processing_method | byte | r/w | Ottiene o imposta la stringa di caratteri GPS che registra il nome del metodo utilizzato per la localizzazione. |
| gps_satellites | string | r/w | Ottiene o imposta i satelliti GPS utilizzati per le misurazioni. |
| gps_speed | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la velocità del movimento del ricevitore GPS. |
| gps_speed_ref | string | r/w | Ottiene o imposta l'unità usata per esprimere la velocità di movimento del ricevitore GPS. |
| gps_status | string | r/w | Ottiene o imposta lo stato del ricevitore GPS quando l'immagine viene registrata. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag, che appartengono solo alla sezione GPS. |
| gps_timestamp | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta l'ora GPS come UTC (Coordinated Universal Time). |
| gps_track | string | r/w | Ottiene o imposta la direzione del movimento del ricevitore GPS. |
| gps_track_ref | string | r/w | Ottiene o imposta il riferimento per fornire la direzione del movimento del ricevitore GPS. |
| gps_version_id | byte | r/w | Ottiene o imposta l'identificatore della versione GPS. |
| gpsdop | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il GPS DOP (data degree of precision). |
| image_description | string | r/w | Ottiene o imposta la descrizione dell'immagine. |
| image_length | uint | r/w | Ottiene o imposta la lunghezza dell'immagine. |
| image_unique_id | string | r/w | Ottiene o imposta l'identificatore unico dell'immagine. |
| image_width | uint | r/w | Ottiene o imposta la larghezza dell'immagine. |
| is_big_endian | bool | r/w | Ottiene o imposta un valore che indica se il flusso di dati EXIF da cui è stato creato è big endian. |
| iso_speed | uint | r/w | Ottiene o imposta la velocità ISO |
| iso_speed_latitude_yyy | uint | r/w | Ottiene o imposta il valore della latitudine yyy della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| iso_speed_latitude_zzz | uint | r/w | Ottiene o imposta il valore della latitudine zzz della velocità ISO di una fotocamera o dispositivo di input definito nella ISO 12232. |
| lens_make | string | r/w | Ottiene o imposta il produttore dell'obiettivo. |
| lens_model | string | r/w | Ottiene o imposta il modello dell'obiettivo. |
| lens_serial_number | string | r/w | Ottiene o imposta il numero di serie dell'obiettivo. |
| lens_specification | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la specifica dell'obiettivo |
| light_source | [ExifLightSource](/psd/python-net/aspose.psd.exif.enums/exiflightsource/) | r/w | Ottiene o imposta la sorgente luminosa. |
| make | string | r/w | Ottiene o imposta il produttore dell'attrezzatura di registrazione. |
| maker_note_data | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r | Ottiene i dati della nota del produttore. |
| maker_note_raw_data | byte | r/w | Ottiene o imposta i dati grezzi della nota del produttore. |
| max_aperture_value | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il valore dell'apertura massima. |
| metering_mode | [ExifMeteringMode](/psd/python-net/aspose.psd.exif.enums/exifmeteringmode/) | r/w | Ottiene o imposta la modalità di misurazione. |
| model | string | r/w | Ottiene o imposta il modello. |
| oecf | byte | r/w | Ottiene o imposta la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| orientation | [ExifOrientation](/psd/python-net/aspose.psd.exif.enums/exiforientation/) | r/w | Ottiene o imposta l'orientamento. |
| photographic_sensitivity | uint | r/w | Ottiene o imposta la sensibilità fotografica. |
| photometric_interpretation | ushort | r/w | Ottiene o imposta l'interpretazione fotometrica. |
| pixel_x_dimension | uint | r/w | Ottiene o imposta la dimensione x del pixel. |
| pixel_y_dimension | uint | r/w | Ottiene o imposta la dimensione y del pixel. |
| planar_configuration | ushort | r/w | Ottiene o imposta la configurazione planare. |
| primary_chromaticities | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la cromaticità dei tre colori primari dell'immagine. |
| properties | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta tutti i tag EXIF (inclusi i tag comuni e GPS). |
| recommended_exposure_index | uint | r/w | Ottiene o imposta l'indice di esposizione consigliato. |
| reference_black_white | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta il riferimento bianco e nero. |
| related_sound_file | string | r/w | Ottiene o imposta il file audio correlato. |
| resolution_unit | [ExifUnit](/psd/python-net/aspose.psd.exif.enums/exifunit/) | r/w | Ottiene o imposta l'unità di risoluzione. |
| samples_per_pixel | ushort | r/w | Ottiene o imposta i campioni per pixel. |
| saturation | [ExifSaturation](/psd/python-net/aspose.psd.exif.enums/exifsaturation/) | r/w | Ottiene o imposta la saturazione. |
| scene_capture_type | [ExifSceneCaptureType](/psd/python-net/aspose.psd.exif.enums/exifscenecapturetype/) | r/w | Ottiene o imposta il tipo di acquisizione della scena. |
| scene_type | byte | r/w | Ottiene o imposta il tipo di scena. |
| sensing_method | [ExifSensingMethod](/psd/python-net/aspose.psd.exif.enums/exifsensingmethod/) | r/w | Ottiene o imposta il metodo di rilevamento. |
| sensitivity_type | ushort | r/w | Ottiene o imposta il tipo di sensibilità. |
| sharpness | ushort | r/w | Ottiene o imposta la nitidezza. |
| shutter_speed_value | [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) | r/w | Ottiene o imposta il valore della velocità dell'otturatore. |
| software | string | r/w | Ottiene o imposta il software. |
| spatial_frequency_response | byte | r/w | Ottiene o imposta la risposta in frequenza spaziale. |
| spectral_sensitivity | string | r/w | Ottiene o imposta la sensibilità spettrale. |
| standard_output_sensitivity | uint | r/w | Ottiene o imposta la sensibilità di uscita standard |
| subject_area | ushort | r/w | Ottiene o imposta l'area del soggetto. |
| subject_distance | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la distanza del soggetto. |
| subject_distance_range | [ExifSubjectDistanceRange](/psd/python-net/aspose.psd.exif.enums/exifsubjectdistancerange/) | r/w | Ottiene o imposta l'intervallo di distanza del soggetto. |
| subject_location | ushort | r/w | Ottiene o imposta la posizione del soggetto. |
| subsec_time | string | r/w | Ottiene o imposta le frazioni di secondo per il tag DateTime. |
| subsec_time_digitized | string | r/w | Ottiene o imposta le frazioni di secondo per il tag DateTimeDigitized. |
| subsec_time_original | string | r/w | Ottiene o imposta le frazioni di secondo per il tag DateTimeOriginal. |
| thumbnail | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | r/w | Ottiene o imposta l'immagine miniatura. |
| transfer_function | ushort | r/w | Ottiene o imposta la funzione di trasferimento. |
| user_comment | string | r/w | Ottiene o imposta il commento dell'utente. |
| white_balance | [ExifWhiteBalance](/psd/python-net/aspose.psd.exif.enums/exifwhitebalance/) | r/w | Ottiene o imposta il bilanciamento del bianco. |
| white_point | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la cromaticità del punto bianco dell'immagine. |
| x_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta i coefficienti della matrice per la trasformazione dei dati immagine da RGB a YCbCr. |
| y_cb_cr_positioning | [ExifYCbCrPositioning](/psd/python-net/aspose.psd.exif.enums/exifycbcrpositioning/) | r/w | Ottiene o imposta la posizione dei componenti di crominanza rispetto al componente di luminanza. |
| y_cb_cr_sub_sampling | ushort | r/w | Ottiene o imposta il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| y_resolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [remove_tag(tag)](#remove_tag_tag_1) | Rimuovi il tag dal contenitore |
| [remove_tag(tag_id)](#remove_tag_tag_id_2) | Rimuovi il tag dal contenitore |
| [serialize_exif_data()](#serialize_exif_data__3) | Serializza i dati EXIF. Scrive i valori e i contenuti dei tag. Il tag di dimensione più influente è il contenuto del tag Miniatura. |


### Constructor: JpegExifData() {#JpegExifData__1}


```
 JpegExifData() 
```

Inizializza una nuova istanza della classe [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/).

### Constructor: JpegExifData(common_tags, exif_tags, gps_tags) {#JpegExifData_common_tags_exif_tags_gps_tags_2}


```
 JpegExifData(common_tags, exif_tags, gps_tags) 
```

Inizializza una nuova istanza della classe [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con dati da un array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| common_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | I tag comuni. |
| exif_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | I tag EXIF. |
| gps_tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | I tag GPS. |

### Constructor: JpegExifData(exifdata) {#JpegExifData_exifdata_3}


```
 JpegExifData(exifdata) 
```

Inizializza una nuova istanza della classe [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) con dati da un array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| exifdata | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Array di tag EXIF insieme a tag comuni e GPS. |

### Method: remove_tag(tag) {#remove_tag_tag_1}


```
 remove_tag(tag) 
```

Rimuovi il tag dal contenitore

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag | [ExifProperties](/psd/python-net/aspose.psd.exif/exifproperties) | Il tag da rimuovere |

### Method: remove_tag(tag_id) {#remove_tag_tag_id_2}


```
 remove_tag(tag_id) 
```

Rimuovi il tag dal contenitore

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_id | ushort | L'identificatore del tag da rimuovere. |

### Method: serialize_exif_data() {#serialize_exif_data__3}


```
 serialize_exif_data() 
```

Serializza i dati EXIF. Scrive i valori e i contenuti dei tag. Il tag di dimensione più influente è il contenuto del tag Miniatura.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | I dati EXIF serializzati. |


